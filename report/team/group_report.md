# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Ban3
- Thành viên: xem `TEAM.md` (Lý Thanh Lâm, Tô Minh Thành, Phạm Trung Kiên, Nguyễn Thanh Tùng, Đoàn Gia Long)
- Candidate problem được chọn (1 câu): Hệ thống phát hiện tài xế ngâm cuốc và tự động phân loại khiếu nại hủy chuyến cho ứng dụng gọi xe Xanh SM.
- Quyết định cuối: Not Yet (Chạy pilot 4 tuần trên môi trường Staging/Mock Sandbox trước khi xem xét tích hợp)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Lý Thanh Lâm | Khi đặt xe Xanh SM mà tài xế nhận cuốc nhưng đứng im/đi ngược hướng "ngâm cuốc", tôi muốn hệ thống ghi nhận trạng thái bất thường để hỗ trợ đổi tài xế hoặc hủy không mất phí ngay, để không mất 30–60 phút chờ đợi và trễ việc. | Hành khách đặt xe Xanh SM (tuyến Ocean Park – nội thành) | Bước 2 (chờ 12 phút nhìn map xe đứng im) và Bước 4 (8 phút chụp màn hình làm bằng chứng hủy) | |
| 2 | Lý Thanh Lâm | Khi gom dữ liệu bản vẽ/tài liệu scan để kiểm thử OCR, tôi muốn lọc nhanh ảnh mờ và xoay phẳng các ảnh bị chụp nghiêng/ngược trước khi đưa vào pipeline, để tiết kiệm hàng giờ căn chỉnh thủ công từng file. | Kỹ sư / Sinh viên xây dựng pipeline OCR | Bước 3 (75 phút ngồi duyệt mắt từng ảnh lọc mờ và xoay tay 90°/180° cho 50–60 ảnh) | |
| 3 | Lý Thanh Lâm | Khi khách đặt xe tại các khu đô thị nhiều tòa nhà (S1, S2 Ocean Park) bị lệch ghim hoặc vướng phân luồng, người tài xế muốn xác nhận ngay sảnh đón chính xác và gửi vị trí thực tế, để đón khách nhanh và không bị hủy chuyến oan. | Tài xế xe công nghệ (Xanh SM, Grab, Be) | Bước 3 (8 phút tài xế chạy vòng quanh giữa các tòa S1–S2 nhìn biển tìm sảnh đón) | |
| 4 | Tô Minh Thành | Khi chuẩn bị gửi thay đổi để review, tôi muốn trình bày lý do, phạm vi và cách kiểm thử rõ ràng, để reviewer đánh giá được thay đổi mà không phải hỏi lại thông tin cơ bản. | Junior Software Engineer | Bước 3 (8 phút đọc lại Jira/diff) và Bước 4 (12 phút soạn mô tả PR theo template) | |
| 5 | Tô Minh Thành | Khi hoàn thành một API CRUD cơ bản, tôi muốn bao phủ các nhánh quan trọng bằng unit test mà không phải lặp lại nhiều thao tác viết mã, để giảm nguy cơ hồi quy. | Backend Developer | Bước 3 (20–30 phút nghĩ và viết test case cho các luồng ngoại lệ) | |
| 6 | Tô Minh Thành | Khi điều tra lỗi được báo trong Sentry/Kibana, tôi muốn xác định được đoạn log và bước tiếp theo cần kiểm tra, để rút ngắn thời gian chẩn đoán. | Developer, QA | Bước 2–3 (15–20 phút đọc và lọc hàng trăm dòng log phân tán để tìm stack trace) | |
| 7 | Phạm Trung Kiên | Khi inbox đầy review 1–3 sao trên Booking, Agoda và Google, tôi muốn hiểu khách đang phàn nàn gì rồi viết thư trả lời đúng giọng khách sạn, để kịp hạn 24 giờ và các ca không viết mỗi người một kiểu. | Nhân viên CSKH property Vinpearl | Bước soạn thư trả lời đúng chuẩn SOP và giọng điệu khách sạn (12–15 phút/review) | |
| 8 | Phạm Trung Kiên | Khi đóng ca, tôi muốn gắn một nguyên nhân gốc cho từng chuyến hủy (tài xế muộn / khách hủy / app lỗi), để sáng hôm sau khỏi đọc lại đống ghi chú khi làm báo cáo tuần. | Nhân viên chất lượng Xanh SM | Đối chiếu ghi chú của khách và tài xế với GPS để gắn nhãn thủ công (1–2 phút/note, dồn ca mất cả tiếng) | |
| 9 | Phạm Trung Kiên | Khi bệnh nhân sắp vào phòng, tôi muốn gom tiền sử, dị ứng và thuốc đang dùng từ vài lần khám cũ thành một trang, để bác sĩ không hỏi lại từ đầu. | Điều dưỡng tiền khám Vinmec | Lướt hệ thống EMR và ghi tay bản tóm tắt tiền sử (8–10 phút/ca) | |
| 10 | Nguyễn Thanh Tùng | Khi kiểm tra chất lượng tư vấn của 10 saler mỗi ngày trên Pancake, tôi muốn nhanh chóng phát hiện các lỗi sai về tư vấn liều lượng, chống chỉ định và thiếu ưu đãi, để kịp thời chấn chỉnh trước khi đơn hàng xuất kho. | Quản lý chất lượng (QA), Saler | Đọc lội từng đoạn chat dài 20–30 tin nhắn trên Pancake để tìm lỗi sai (90–120 phút/ngày) | |
| 11 | Nguyễn Thanh Tùng | Khi lead mới đổ về từ quảng cáo vào đầu ca sáng, tôi muốn lọc trùng số điện thoại và phân bổ ngay cho đúng telesale đang trực, để khách được gọi trong vòng 15 phút đầu. | Quản lý vận hành telesale | Tải file Excel, rà trùng 150 số điện thoại thủ công trên CRM (45 phút/sáng) | |
| 12 | Nguyễn Thanh Tùng | Khi kiểm kê kho hàng định kỳ ngày 25 hàng tháng, tôi muốn lọc ra toàn bộ sản phẩm còn hạn dùng dưới 6 tháng trên kệ kho, để lên kế hoạch xả hàng hoặc đổi trả nhà cung cấp kịp thời. | Quản lý kho dược, Kế toán kho | Đối chiếu danh mục 85 mã thuốc giữa thực tế trên kệ và file Excel date (mất 6 tiếng) | |
| 13 | Đoàn Gia Long | Khi tìm được đồ cần mua ở siêu thị, tôi muốn đọc và so sánh nhanh thông tin các sản phẩm, để chọn được sản phẩm phù hợp mà không mất nhiều thời gian. | Người mua sắm cho gia đình | Bước 2–4 (đọc nhãn chữ nhỏ, nhiều thành phần lạ, phải tự so sánh mất ~1–2 phút/sản phẩm) | |
| 14 | Đoàn Gia Long | Khi đã chọn sản phẩm để nấu ăn, tôi muốn biết chắc sản phẩm không có chất bố mẹ bị dị ứng, để cả nhà ăn an toàn. | Người mua sắm cho gia đình | Bước 2–3 (thành phần dài, đối chiếu từng chất với danh sách dị ứng mất 1–2 phút/sản phẩm) | |
| 15 | Đoàn Gia Long | Khi đang trên đường từ công ty đến siêu thị, tôi muốn nhanh chóng có món ăn phù hợp khẩu vị cả nhà và khác bữa trước, để mua đúng nguyên liệu. | Người nấu cơm tối gia đình | Bước 2–3 (nghĩ món ăn mới vừa hợp khẩu vị từng người trong nhà mất 10–15 phút) | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| **A — Vận hành di chuyển & Ứng dụng gọi xe (Mobility & Ride-hailing)** | #1, #3, #8 | Sự lệch pha thông tin vị trí và trạng thái di chuyển thời gian thực giữa tài xế và hành khách dẫn đến thời gian chờ đợi thụ động, hủy chuyến và tranh chấp cước/điểm thưởng khiếu nại. |
| **B — Kỹ thuật phần mềm & Xử lý dữ liệu (Software Engineering & Data Ops)** | #2, #4, #5, #6 | Lập trình viên và kỹ sư AI mất nhiều thời gian đọc lại ngữ cảnh, lặp lại các thao tác viết/kiểm thử mã nguồn thủ công và rà soát lỗi trên các tệp log/dữ liệu phân tán. |
| **C — Vận hành thương mại, CSKH & Quản lý nghiệp vụ (Operations, CS & Auditing)** | #7, #9, #10, #11, #12 | Nhân viên nghiệp vụ/CSKH phải đọc duyệt thủ công khối lượng lớn văn bản, hội thoại và bảng biểu rời rạc để đối chiếu quy chuẩn dịch vụ hoặc phát hiện sai sót trước khi phê duyệt. |
| **D — Đời sống tiêu dùng & Hỗ trợ sinh hoạt cá nhân (Consumer Lifestyle & Nutrition)** | #13, #14, #15 | Người tiêu dùng mất thời gian đọc lướt các nhãn thành phần chữ nhỏ và cân nhắc khẩu vị/dị ứng thủ công trong điều kiện thời gian mua sắm gấp gáp hàng ngày. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
