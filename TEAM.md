# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Ban3
- Candidate problem nhóm chọn (1 câu): Hệ thống phát hiện tài xế ngâm cuốc và tự động phân loại khiếu nại hủy chuyến cho ứng dụng gọi xe Xanh SM.
- Quyết định cuối (Go / Not Yet / No-Go): Not Yet (Chạy pilot 4 tuần trên môi trường Staging/Mock Sandbox trước khi xem xét tích hợp)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Lý Thanh Lâm | 2A202603475 | | https://github.com/LysLama |
| 2 | Tô Minh Thành | 2A202603439 | | https://github.com/thanh211124 |
| 3 | Phạm Trung Kiên | 2A202603479| |https://github.com/trungkienpham0607 |
| 4 | Nguyễn Thanh Tùng | 2A202603446 | | https://github.com/hunter2996 |
| 5 | Đoàn Gia Long | 2A202603443 | | https://github.com/DoanGiaLong |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Lý Thanh Lâm | Tô Minh Thành, Phạm Trung Kiên | Bảng pitch, Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Đoàn Gia Long | Tô Minh Thành | Assumption map, 5 interview snapshots (Bonus B2) |
| CP4 — Research | Phạm Trung Kiên | Lý Thanh Lâm | Bảng research 3 giải pháp có link đã kiểm chứng |
| CP5 — Quy trình trước/sau | Nguyễn Thanh Tùng | Phạm Trung Kiên | Sơ đồ Mermaid Trước/Sau + bảng before/after có HITL & Fallback |
| CP5 — Problem Statement v0 | Lý Thanh Lâm | Đoàn Gia Long | Problem Statement v0 (6 trường chuẩn) |
| CP6 — Mức can thiệp + Problem Statement v1 | Tô Minh Thành | Nguyễn Thanh Tùng | Ma trận, AI Canvas, PAIR, eval 10 pairs (Bonus B3), Problem Statement v1 |
| CP6 — Quyết định | Lý Thanh Lâm | Tô Minh Thành | Đánh giá 4 rủi ro + Quyết định Not Yet + Ngưỡng dừng đo được |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### LyThanhLam-2A202603475

**Phần việc phụ trách:**

- Nhóm trưởng điều phối tiến độ, quản trị repo GitHub chung của nhóm Bàn 3.
- Phụ trách chính CP3 (Hội tụ nhóm & Dựng cây Opportunity Solution Tree).
- Phụ trách CP5 (Problem Statement v0) và CP6 (Đánh giá 4 rủi ro, phân tích rào cản dữ liệu & đề xuất Quyết định Not Yet kèm ngưỡng dừng).
- Hỗ trợ CP4 (Research giải pháp Uber/Grab) và rà soát chất lượng tổng thể `group_report.md`.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Quản trị repo, phân công vai trò và checkpoint cho 5 thành viên trong `TEAM.md`.
- Đóng góp Card #1 về "Tài xế Xanh SM ngâm cuốc ép khách tự hủy", làm tiền đề then chốt kết hợp với bài gắn nhãn hủy chuyến của Kiên để nhóm hội tụ thành đề tài chung.
- Trực tiếp xây dựng cây Opportunity Solution Tree (OST) tách bạch giữa Outcome đo được, Opportunity (pain) và gạch bỏ các giải pháp đội lốt ở CP3.
- Soạn thảo Problem Statement v0 và v1, thiết lập Boundary nghiêm ngặt (không cho AI tự động phạt tài xế hoặc tự ý trừ/hoàn tiền ví hành khách).
- Phân tích 4 rủi ro lớn (Value, Usability, Feasibility, Viability) dưới góc độ bảo mật dữ liệu theo Nghị định 13/2023/NĐ-CP và ranh giới dữ liệu GSM, chốt quyết định Not Yet trung thực và khả thi.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Mục 1, Mục 2.3 (Cây OST), Mục 2.4 (Bảng chấm điểm & lý do chọn), Mục 5 (Problem Statement v0), Mục 7 (Problem Statement v1), Mục 8 (4 rủi ro & Quyết định Not Yet).
- `TEAM.md`: Bảng thành viên, phân công checkpoint và mục cá nhân.
- Commits trên branch `main` và `2A202603475-LyThanhLam`.

**Điều mình học được từ phần nhóm:**

- Chuyển từ tư duy "Solution-first" sang "Problem-first": ở bước cứu khách hàng đang đứng chờ xe, chỉ cần tập luật Rule-based đơn giản là đã giải quyết được 80% bức xúc mà không cần mô hình AI phức tạp.
- Nhận thức sâu sắc về ranh giới dữ liệu và pháp lý doanh nghiệp: một nhóm học viên làm lab bên ngoài không thể tự tiện tuyên bố có quyền can thiệp vào cơ sở dữ liệu nội bộ của GSM hay tự động ra lệnh bồi hoàn tiền; một quyết định "Not Yet" có cơ sở dữ liệu và lộ trình pilot staging 4 tuần giá trị và đáng tin cậy hơn nhiều so với một quyết định "Go" viển vông.

---

### LyThanhLam-2A202603475

**Phần việc phụ trách:**

- Nhóm trưởng điều phối tiến độ, quản trị repo GitHub chung của nhóm Bàn 3.
- Phụ trách chính CP3 (Hội tụ nhóm & Dựng cây Opportunity Solution Tree).
- Phụ trách CP5 (Problem Statement v0) và CP6 (Đánh giá 4 rủi ro, phân tích rào cản dữ liệu & đề xuất Quyết định Not Yet kèm ngưỡng dừng).
- Hỗ trợ CP4 (Research giải pháp Uber/Grab) và rà soát chất lượng tổng thể `group_report.md`.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Quản trị repo, phân công vai trò và checkpoint cho 5 thành viên trong `TEAM.md`.
- Đóng góp Card #1 về "Tài xế Xanh SM ngâm cuốc ép khách tự hủy", làm tiền đề then chốt kết hợp với bài gắn nhãn hủy chuyến của Kiên để nhóm hội tụ thành đề tài chung.
- Trực tiếp xây dựng cây Opportunity Solution Tree (OST) tách bạch giữa Outcome đo được, Opportunity (pain) và gạch bỏ các giải pháp đội lốt ở CP3.
- Soạn thảo Problem Statement v0 và v1, thiết lập Boundary nghiêm ngặt (không cho AI tự động phạt tài xế hoặc tự ý trừ/hoàn tiền ví hành khách).
- Phân tích 4 rủi ro lớn (Value, Usability, Feasibility, Viability) dưới góc độ bảo mật dữ liệu theo Nghị định 13/2023/NĐ-CP và ranh giới dữ liệu GSM, chốt quyết định Not Yet trung thực và khả thi.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Mục 1, Mục 2.3 (Cây OST), Mục 2.4 (Bảng chấm điểm & lý do chọn), Mục 5 (Problem Statement v0), Mục 7 (Problem Statement v1), Mục 8 (4 rủi ro & Quyết định Not Yet).
- `TEAM.md`: Bảng thành viên, phân công checkpoint và mục cá nhân.
- Commits trên branch `main` và `2A202603475-LyThanhLam`.

**Điều mình học được từ phần nhóm:**

- Chuyển từ tư duy "Solution-first" sang "Problem-first": ở bước cứu khách hàng đang đứng chờ xe, chỉ cần tập luật Rule-based đơn giản là đã giải quyết được 80% bức xúc mà không cần mô hình AI phức tạp.
- Nhận thức sâu sắc về ranh giới dữ liệu và pháp lý doanh nghiệp: một nhóm học viên làm lab bên ngoài không thể tự tiện tuyên bố có quyền can thiệp vào cơ sở dữ liệu nội bộ của GSM hay tự động ra lệnh bồi hoàn tiền; một quyết định "Not Yet" có cơ sở dữ liệu và lộ trình pilot staging 4 tuần giá trị và đáng tin cậy hơn nhiều so với một quyết định "Go" viển vông.

---

### ToMinhThanh-2A202603439

**Phần việc phụ trách:**

- CP3: hỗ trợ Lý Thanh Lâm và Phạm Trung Kiên trong hội tụ nhóm.
- CP4: hỗ trợ Đoàn Gia Long kiểm chứng.
- CP6: phụ trách ma trận, AI Canvas, PAIR, bộ eval 10 cặp và Problem Statement v1; hỗ trợ Lý Thanh Lâm đánh giá rủi ro và quyết định.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Nêu phản biện rằng chỉ dựa vào GPS đứng im không đủ phân biệt tài xế cố tình ngâm cuốc với kẹt xe hoặc lỗi định vị; phản biện này được ghi trong bảng pitch CP3.
- Theo phân công CP6, phụ trách các đầu ra được trình bày trong báo cáo nhóm: ma trận mức can thiệp, AI Canvas, PAIR và Problem Statement v1; bộ 10 cặp eval có file riêng.
- Báo cáo nhóm ghi quyết định Not Yet, pilot 4 tuần trên Staging/Mock Sandbox. Phần nào trong quyết định tôi trực tiếp thực hiện cần được tôi xác nhận trước khi nộp.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: mục 2.1 (phản biện CP3), mục 6 (ma trận và AI Canvas), mục 7 (PAIR và Problem Statement v1), mục 8 (quyết định).
- `report/assets/cp6-eval-set-10-pairs.md`: bộ eval 10 cặp.
- `TEAM.md`: bảng phân công CP3, CP4 và CP6.

**Điều mình học được từ phần nhóm:**

- Tự bổ sung một điều học được từ trải nghiệm thực tế của mình; không suy ra reflection chỉ từ phân công hoặc nội dung báo cáo nhóm.

---

### PhamTrungKien-2A202603479

**Phần việc phụ trách:**

- CP3: hỗ trợ Lý Thanh Lâm và Tô Minh Thành hội tụ nhóm (pitch, cluster, chấm điểm).
- CP4 Research: phụ trách chính bảng research giải pháp đã có (Uber RADAR, Grab, Zendesk); Lý Thanh Lâm hỗ trợ.
- CP5: hỗ trợ Nguyễn Thanh Tùng vẽ quy trình trước/sau, HITL và fallback.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 candidate: Vinpearl trả lời review OTA, gắn nhãn hủy chuyến Xanh SM, tóm tắt tiền sử Vinmec (bảng pitch #7–#9).
- Đặt câu hỏi phản biện cho bài PR của Thành và bài QA Pancake của Tùng; nhận phản biện về quyền OTA/EMR và gợi ý ghép card gắn nhãn với bài ngâm cuốc.
- Đổi hướng: bỏ bảo lưu Vinpearl làm đề tài chính; đóng góp card gắn nhãn hủy vào tầng hậu kiểm của candidate #1.
- Làm bảng research 3 nguồn có link đã tự mở; rút bài học Rule cứu khách + AI hậu kiểm + người duyệt.
- Góp ý sơ đồ tương lai tách tầng Rule và AI Workflow, boundary không tự phạt/tự hoàn tiền; ủng hộ quyết định Not Yet.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: mục 2.1 (pitch #7–#9 và câu hỏi phản biện), mục 2.2–2.4 (cluster A, lý do loại Vinpearl, xử lý bất đồng), mục 3.3 (research), mục 4.2 (quy trình tương lai / boundary).
- `report/individual/2A202603479_PhamTrungKien.md`: CP1–CP2 và nhật ký tham gia mục 4–6.
- `TEAM.md`: dòng phân công CP3, CP4 Research, CP5 quy trình.

**Điều mình học được từ phần nhóm:**

- Candidate có deep-dive sẵn chưa chắc thắng nếu nhóm không đụng được dữ liệu thật trong lab.
- Card “gắn nhãn hủy chuyến” của mình không bị bỏ: nó trở thành nửa sau của bài ngâm cuốc (AI hỗ trợ CSKH hậu kiểm), còn nửa trước cứu khách chỉ cần Rule.

---

### NguyenThanhTung-2A202603446

**Phần việc phụ trách:**

- CP3: Trình bày 3 candidate cá nhân về ngành dược (QA Pancake, chia lead telesale, kiểm kê thuốc cận date); phản biện bài toán ngâm cuốc của Lâm và unit test của Thành.
- CP5: **Phụ trách chính thiết kế và vẽ sơ đồ Quy trình Trước/Sau** (sơ đồ Mermaid Mục 4.1 và 4.2 trong `group_report.md`), thiết lập cơ chế Human-in-the-loop (HITL), nhánh Fallback an toàn, và xây dựng bảng Before/After so sánh hiệu quả.
- CP6: Hỗ trợ Tô Minh Thành phân tích ma trận mức can thiệp, hoàn thiện AI Canvas và trả lời hai câu hỏi thiết kế theo hướng dẫn Google PAIR; đóng góp ý kiến về Boundary an toàn và tiêu chí eval.
- CP6: Thống nhất với nhóm về việc ra quyết định Not Yet và ngưỡng dừng đo lường được (False Positive > 5%).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đặt câu hỏi phản biện then chốt cho Lâm tại CP3 về việc phân biệt xe đứng im do ngâm cuốc vs kẹt xe Cổ Linh, giúp nhóm định hình lại việc không được dùng Rule cứng để phạt tài xế.
- Trực tiếp chuyển hóa ý tưởng của nhóm thành **2 sơ đồ Mermaid chuẩn chỉnh trong Mục 4 `group_report.md`**: Sơ đồ hiện tại (33 phút, 2 bottleneck) và Sơ đồ tương lai (phân định rõ ràng giữa Tầng 1 Rule cứu khách sau 3 phút, Tầng 2 AI Workflow phân tích ngữ cảnh chat/GPS, Chốt chặn con người CSKH duyệt, và nhánh Fallback khi timeout > 3s).
- Lập bảng so sánh Before/After (Mục 4.3): Chứng minh định lượng việc cắt giảm thời gian giải cứu khách hàng từ 33 phút xuống < 4 phút và tự động hoàn lại 100% voucher.
- Cùng Thành hoàn thành AI Canvas rút gọn, kiên quyết phản đối mức Autonomous Agent để bảo vệ nhóm khỏi rủi ro over-engineering và tranh chấp pháp lý.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: Mục 2.1 (Bảng pitch dòng #10 và câu hỏi phản biện cho Lâm), Mục 4.1 (Sơ đồ Mermaid hiện tại + bảng phân rã bước), Mục 4.2 (Sơ đồ Mermaid tương lai phân tầng + HITL + Fallback), Mục 4.3 (Bảng Before/After), Mục 6 (AI Canvas & câu hỏi PAIR).
- `report/individual/2A202603446_NguyenThanhTung.md`: Báo cáo cá nhân hoàn thiện đầy đủ từ mục 1 đến mục 7.
- `TEAM.md`: Bảng phân công người chính CP5 (Quy trình trước/sau) và người hỗ trợ CP6.

**Điều mình học được từ phần nhóm:**

- Tư duy "Problem-first" và "Đơn giản nhất đủ dùng": Khách hàng cần được giải cứu bằng Rule tức thì trong 3 phút chứ không cần chờ một mô hình AI suy luận phức tạp; AI chỉ phát huy giá trị cao nhất khi đặt đúng vị trí backend hậu kiểm để đọc hiểu văn bản phi cấu trúc (tin nhắn chat).
- Trải nghiệm dũng cảm từ bỏ đề tài cá nhân (bài dược) khi bị phản biện về rào cản pháp lý và quyền truy cập API bên thứ ba, để tập trung nguồn lực cùng nhóm giải quyết một bài toán có thể kiểm chứng người dùng thực tế ngay tại khu đô thị Ocean Park.

**Điều mình học được từ phần nhóm:**

- Candidate có deep-dive sẵn chưa chắc thắng nếu nhóm không đụng được dữ liệu thật trong lab.
- Card “gắn nhãn hủy chuyến” của mình không bị bỏ: nó trở thành nửa sau của bài ngâm cuốc (AI hỗ trợ CSKH hậu kiểm), còn nửa trước cứu khách chỉ cần Rule.
