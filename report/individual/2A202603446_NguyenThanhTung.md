# Báo cáo cá nhân — 2A202603446_NguyenThanhTung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Thanh Tùng
- MSSV: 2A202603446
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Ban3
- Link repo nhóm: https://github.com/LysLama/K5-L3A-DAY02-Ban3-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi kiểm tra chất lượng tư vấn của 10 saler mỗi ngày trên Pancake, tôi muốn nhanh chóng phát hiện các lỗi sai về tư vấn liều lượng, chống chỉ định và thiếu ưu đãi, để kịp thời chấn chỉnh trước khi đơn hàng xuất kho. | Quản lý chất lượng (QA), Khách hàng, 10 saler | Mất 90–120 phút/ngày rà soát 20–25 đoạn chat (chỉ đạt ~8% trong 300 cuộc chat/ngày trên Pancake). Bằng chứng: Bảng chấm điểm audit QA hàng ngày. |
| 2 | Tốn thời gian | Khi lead mới đổ về từ quảng cáo vào đầu ca sáng, tôi muốn lọc trùng số điện thoại và phân bổ ngay cho đúng telesale đang trực, để khách được gọi trong vòng 15 phút đầu. | Quản lý vận hành, 8 Telesaler, Khách để lại SĐT | Mất 45 phút mỗi sáng tải file Excel từ Ads/Fanpage, rà trùng 150 số điện thoại với dữ liệu 30 ngày qua trên CRM. Bằng chứng: Lịch sử tải lead lúc 8h30 và giờ gọi đầu tiên 9h15. |
| 3 | Cần đọc, tổng hợp | Khi kiểm tra chất lượng telesale hàng tuần, tôi muốn tổng hợp toàn bộ lý do khách từ chối mua thuốc và phản hồi về giá, để báo cáo lại cho bộ phận marketing điều chỉnh nội dung quảng cáo. | Đội ngũ Marketing, Quản lý vận hành, 8 Telesaler | Mất 3 tiếng mỗi chiều thứ Sáu nghe lại 40 cuộc gọi thất bại và đọc ghi chú rải rác. Bằng chứng: Báo cáo tổng kết tuần trễ hạn gửi ban giám đốc 2 lần trong tháng qua. |
| 4 | Lặp lại | Khi đến giờ check-in và check-out mỗi ngày, tôi muốn đối soát nhanh giữa dữ liệu máy chấm công và tin nhắn xin phép nghỉ/đi muộn, để báo cáo chấm công chính xác mà không phải tra cứu thủ công từng người. | Quản lý nhân sự/vận hành, 25 nhân viên | Mất 30 phút/ngày (15 phút sáng, 15 phút chiều) đối chiếu 25 nhân sự giữa vân tay và nhóm Zalo báo phép. Bằng chứng: Bảng công Excel có 12 trường hợp phải sửa tay mỗi tháng. |
| 5 | Pain từ người khác | Khi khách hàng nhận thuốc và phản ánh qua hotline/tin nhắn về việc nhân viên tư vấn sai công dụng hoặc thiếu quà tặng kèm, tôi muốn truy vết ngay lịch sử tư vấn và mã đơn trên Pancake, để xử lý khiếu nại dưới 10 phút. | Nhân viên CSKH, Khách hàng khiếu nại, Quản lý | Mỗi tuần có 3–5 ca khiếu nại, mỗi ca mất 25–40 phút lội lại lịch sử chat Pancake vì saler quên gắn tag phân loại bệnh. Bằng chứng: Ticket khiếu nại trên Zalo CSKH. |
| 6 | Cần đọc, tổng hợp | Khi soạn thảo bài viết chuyên môn và kịch bản 1 video ngắn mỗi tuần, tôi muốn tổng hợp nhanh các nghiên cứu dược lý và quy định quảng cáo thuốc của Bộ Y Tế, để nội dung vừa chuẩn y khoa vừa thu hút người xem. | Nhân viên nội dung/Marketing, Dược sĩ chuyên môn | Mất 4–5 tiếng/bài viết để tra cứu tài liệu dược thư và rà soát từ ngữ nhạy cảm tránh vi phạm chính sách. Bằng chứng: Bài viết từng bị kiểm duyệt nội bộ trả lại 3 lần vì dùng sai thuật ngữ chỉ định. |
| 7 | Lặp lại | Khi có đơn hàng xuất bán mỗi buổi chiều, tôi muốn đối soát số lượng thực xuất từ kho với phiếu xuất kho trên phần mềm, để phát hiện ngay chênh lệch tồn kho thực tế và số lô thuốc. | Thủ kho, Kế toán kho | Mất 45 phút mỗi cuối ngày kiểm đếm 60–80 kiện hàng và gõ lại số lô thuốc vào phần mềm bán hàng. Bằng chứng: Biên bản lệch kho 2 lần/tháng do nhân viên xuất nhầm lô thuốc cận date. |
| 8 | Pain từ người khác | Khi telesale gọi điện cho danh sách khách hàng mới, tôi muốn lọc trước các số điện thoại rác hoặc thuê bao không có thực trước khi bấm gọi, để telesale không lãng phí thời gian chờ máy vô ích. | 8 Telesaler, Quản lý vận hành | Mỗi telesale bấm 60–80 cuộc/ngày thì có 20–25 cuộc là số ảo hoặc thuê bao, tốn 40 phút/người/ngày. Bằng chứng: Thống kê tỷ lệ cước cuộc gọi dưới 5 giây trên tổng đài đạt 32%. |
| 9 | Tốn thời gian | Khi kiểm kê kho hàng định kỳ ngày 25 hàng tháng, tôi muốn lọc ra toàn bộ sản phẩm còn hạn dùng dưới 6 tháng trên kệ kho, để lên kế hoạch xả hàng hoặc đổi trả nhà cung cấp kịp thời. | Quản lý kho, Bộ phận kinh doanh | Mất 6 tiếng đối chiếu danh mục 85 mã thuốc giữa thực tế trên kệ và file Excel date; tháng trước phát hiện trễ 1 lô trị giá 18 triệu đồng hết hạn phải hủy. Bằng chứng: Biên bản hủy dược phẩm quá hạn ngày 15 tháng trước. |
| 10 | Lặp lại | Khi saler kết thúc một phiên tư vấn thành công trên Pancake, tôi muốn kiểm tra xem nhân viên đã gắn đủ thẻ (tags) hành trình khách hàng hay chưa, để dữ liệu remarketing không bị sót. | Trưởng nhóm Sales, Bộ phận Marketing | Mỗi ngày có 15–20% cuộc hội thoại bị bỏ quên không gắn tag, khiến marketing chạy lại quảng cáo vào chính khách đã mua. Bằng chứng: 12 phản hồi từ khách hàng cũ phàn nàn vì liên tục bị gọi lại tư vấn lại từ đầu. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý AI gợi ý mà tôi giữ lại:** Gợi ý về việc *"Lọc số điện thoại ảo và phát hiện tỷ lệ cước dưới 5 giây"* (Problem #8) vì đây là pain point thực tế của đội telesale mà tôi chưa định lượng thành phút cụ thể trước đó.
- **Ý AI gợi ý mà tôi bỏ và vì sao:** AI gợi ý *"Tự động hóa hoàn toàn việc kê đơn thuốc cho bệnh nhân"*. Tôi loại bỏ ngay vì trong ngành dược, việc kê đơn thuốc bắt buộc phải có Dược sĩ/Bác sĩ chịu trách nhiệm pháp lý, rủi ro Viability & Feasibility quá cao và không khả thi cho một bài lab định lượng.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Kiểm tra chất lượng tư vấn (QA) của nhân viên sales dược (Problem #1) | Tác động trực tiếp đến an toàn dùng thuốc của khách và doanh thu; quy trình audit hiện tại rất rõ ràng nhưng nghẽn nặng ở khâu đọc/nghe thủ công; impact đo lường được ngay. | Chưa chắc về khả năng nhận diện ngữ cảnh tiếng Việt chuyên ngành y dược khi có tiếng lóng hoặc lỗi chính tả của khách. |
| 2 | Rà soát trùng lặp và phân bổ lead khách hàng cho Telesale (Problem #2) | Bottleneck đo được chính xác theo phút (chậm trễ thời gian vàng liên hệ lead); quy trình có dữ liệu input/output chuẩn hóa rõ ràng. | Chưa chắc liệu giải pháp Rule đơn giản trên Google Sheets/AppSheet đã đủ xử lý chưa, hay cần đến quy trình nâng cao. |
| 3 | Cảnh báo và kiểm soát thuốc cận hạn dùng (date) trong kho (Problem #9) | Rủi ro tài chính trực tiếp (hủy thuốc mất tiền); quy trình nhập/xuất kho hiện tại có sẵn số lô và date trên hóa đơn. | Phụ thuộc nhiều vào tính kỷ luật của thủ kho khi nhập liệu ban đầu (nếu nhập sai thì hệ thống kiểm soát cũng sai). |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi kiểm tra chất lượng tư vấn của 10 saler mỗi ngày, tôi muốn nhanh chóng phát hiện các lỗi sai về tư vấn liều lượng và chống chỉ định thuốc, để kịp thời chấn chỉnh trước khi đơn hàng xuất kho. |
| Actor | Trưởng nhóm QA / Quản trị vận hành bán hàng |
| Thời điểm / bối cảnh | Diễn ra trực tiếp trong ca làm việc của 10 saler (chia thành các khung giờ cao điểm sáng và chiều). Saler liên tục tiếp nhận và chat tư vấn cho khách từ nhiều Fanpage Facebook thông qua phần mềm chat đa kênh bên thứ ba (như Pancake / POS). |
| Quy trình hiện tại (3–7 bước) | 1. Mở giao diện Pancake, chọn từng Fanpage và lọc danh sách hội thoại đang phát sinh của 10 saler trong ca (10 phút).<br>2. Chọn ngẫu nhiên các hội thoại có phát sinh báo giá hoặc chuẩn bị chốt đơn (5 phút).<br>3. Đọc từng luồng tin nhắn (thread) trên Pancake, đối chiếu checklist dược (hỏi bệnh nền, liều lượng, chống chỉ định, dặn dò tương tác thuốc) (90 phút - chia làm 3 lần/ca - Bottleneck).<br>4. Khi phát hiện saler tư vấn sai hoặc thiếu thông tin y khoa, QA nhắn tin riêng qua Zalo nội bộ yêu cầu saler nhắn tin đính chính lại với khách trước khi bấm tạo đơn (15 phút).<br>5. Ghi mã hội thoại Pancake và lỗi vi phạm vào file Excel theo dõi KPI chất lượng của saler (10 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Đọc lướt và đối chiếu checklist thủ công trên giao diện Pancake, mất **90 phút/ngày** trong ca trực. Do tin nhắn từ khách đổ về liên tục trên nhiều Fanpage, QA bị ngợp và chỉ rà soát được khoảng 20–25 hội thoại/ngày (chỉ chiếm ~8% trong tổng số gần 300 hội thoại/ngày của 10 saler). |
| Impact (nếu không giải thì sao) | Trong lúc QA đang đọc 1 hội thoại thì hàng chục hội thoại khác đã chốt đơn xong và được đẩy tự động sang bộ phận kho/in bill vận chuyển. Saler tư vấn sai liều hoặc bỏ qua chống chỉ định (ví dụ: bán thuốc dạ dày/khớp cho người có tiền sử suy thận, phụ nữ có thai) không được phát hiện kịp thời; đơn hàng bị gửi đi dẫn đến nguy cơ khách dùng sai thuốc gây biến chứng, khiếu nại, trả hàng và phạt vi phạm pháp lý ngành dược. |
| Success metric (baseline → target) | • **Baseline:** Kiểm tra ngẫu nhiên được ~20 hội thoại/ngày (~8%), mất 90 phút/ca của QA; độ trễ phát hiện lỗi từ 30–60 phút (nhiều ca in đơn xong mới phát hiện).<br>• **Target:** 100% hội thoại có chốt đơn được quét kiểm tra ngay trong ca; thời gian cảnh báo lỗi dưới 3 phút (trước khi saler bấm tạo đơn trên Pancake); QA chỉ mất 20 phút/ca để xử lý các ca bị gắn cờ đỏ.<br>• **Cách đo:** Tỷ lệ % hội thoại chốt đơn được quét rà soát trước khi tạo mã vận đơn; thời gian trung bình từ khi saler nhắn sai đến khi nhận cảnh báo sửa đổi. |
| Phương án không dùng AI | 1. Tận dụng tính năng Rule/Phím tắt của Pancake: Bắt buộc saler sử dụng bộ tin nhắn mẫu (Quick Reply) đã được dược sĩ soạn sẵn, nghiêm cấm gõ tay tự do.<br>2. Cài đặt Rule tự động: Nếu saler chưa gắn tag "Đã hỏi bệnh nền" mà đã gắn tag "Đã chốt đơn" thì phần mềm chặn không cho tạo đơn hàng sang bên vận chuyển. |
| Giả thuyết về AI (nếu có) | Sử dụng Webhook kết nối từ Pancake/Facebook Graph API đẩy tin nhắn về mô hình LLM. Mô hình đóng vai trò trợ lý QA rà soát theo thời gian thực (real-time): đọc hội thoại, so khớp với bảng chỉ định/chống chỉ định của từng loại thuốc. Nếu phát hiện saler bỏ sót câu hỏi bệnh nền hoặc tư vấn sai liều, hệ thống tự động bắn cảnh báo vào nhóm Zalo/Telegram nội bộ của ca trực để QA can thiệp ngay lập tức. |
| Cảm nhận nhanh | **Workflow** (Hệ thống chạy luồng định sẵn: Bắt tin nhắn Pancake → AI đối soát checklist dược → Cảnh báo ca rủi ro → Con người kiểm tra và xử lý). |

Quy trình nháp hiện tại:

```text
[Mở giao diện Pancake / POS của các Fanpage] (10')
  ──> [Lọc lấy ngẫu nhiên 20-25 hội thoại đang chat trong ca] (5')
  ──> [*NGHẼN* Đọc từng đoạn chat trên Pancake + Soi checklist y dược + Kiểm tra gắn tag] (90' rải rác trong ca)
  ──> [Nhắn tin Zalo nội bộ giục Saler sửa tin nhắn trước khi tạo đơn] (15')
  ──> [Ghi nhận mã hội thoại và lỗi vi phạm vào file Excel KPI] (10')

Tổng thời gian QA: 130 phút/ca làm việc
Tỷ lệ bao phủ kiểm tra: Chỉ đạt ~8% tổng số hội thoại trong ngày
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi lead khách hàng mới đổ về từ quảng cáo, tôi muốn lọc trùng số điện thoại và phân bổ ngay cho đúng telesale chuyên trách bệnh lý đó, để khách được liên hệ trong vòng 15 phút đầu. |
| Actor | Điều phối viên Telesales |
| Thời điểm / bối cảnh | Đầu mỗi ca sáng (8h30) và đầu ca chiều (13h30), khi các chiến dịch quảng cáo Facebook/Google đổ data về form đăng ký và tin nhắn. |
| Quy trình hiện tại (3–7 bước) | 1. Tải danh sách lead từ Ads Manager về file Excel (10 phút).<br>2. **Tra cứu đối soát SĐT với danh mục khách hàng cũ trên CRM để lọc trùng (30 phút - Bottleneck)**.<br>3. Chia danh sách theo khu vực và bệnh lý (15 phút).<br>4. Gửi SĐT vào nhóm Zalo riêng của từng telesale (10 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2: Rà soát thủ công số điện thoại cũ và lịch sử mua thuốc trong vòng 30 ngày trên CRM/Excel, mất **30 phút/lần** (60 phút/ngày). |
| Impact (nếu không giải thì sao) | Tốc độ liên hệ khách hàng bị chậm trễ hơn 45–60 phút; tỷ lệ bắt máy giảm từ 75% xuống 52% vì khách đã rời khỏi điện thoại hoặc mua từ nhà thuốc khác. |
| Success metric (baseline → target) | • **Baseline:** Thời gian từ lúc khách để lại SĐT đến khi telesale nhận được là 55 phút.<br>• **Target:** Giảm xuống dưới 5 phút.<br>• **Cách đo:** So sánh timestamp khách điền form và timestamp telesale bấm cuộc gọi đầu tiên trên tổng đài. |
| Phương án không dùng AI | Dùng Google Apps Script hoặc Webhook (Zapier/Make) kết nối Form về Google Sheet, dùng hàm `VLOOKUP`/`COUNTIF` để lọc trùng tự động và chia đều theo vòng tròn (Round Robin). |
| Giả thuyết về AI (nếu có) | Chưa cần thiết phải dùng AI; phương án Rule và Tự động hóa luồng dữ liệu (Workflow tự động không AI) đã giải quyết triệt để 90% bài toán. |
| Cảm nhận nhanh | **Rule** (Không cần dùng AI). |

Quy trình nháp hiện tại:

```text
[Tải file lead từ Ads] (10') 
  ──> [*NGHẼN* Tra cứu đối soát SĐT cũ trên CRM/Excel] (30') 
  ──> [Phân loại bệnh lý + chia ca trực] (15') 
  ──> [Gửi danh sách vào nhóm Zalo từng telesale] (10')

Tổng thời gian: 65 phút/ca
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi kiểm kê kho hàng định kỳ, tôi muốn nhanh chóng lọc ra toàn bộ các mặt hàng thuốc còn hạn dùng dưới 6 tháng trên toàn bộ kệ hàng, để lên kế hoạch kích cầu xả hàng hoặc đổi trả kịp thời. |
| Actor | Quản lý kho dược |
| Thời điểm / bối cảnh | Ngày 25 hàng tháng hoặc khi chuẩn bị nhập đợt hàng lớn từ nhà máy sản xuất. |
| Quy trình hiện tại (3–7 bước) | 1. In bảng danh mục 85 mã thuốc từ phần mềm (10 phút).<br>2. Cầm bảng giấy đi kiểm tra từng kệ, đọc số lô và date (120 phút).<br>3. **Gõ số liệu thực tế vào Excel và đối chiếu chênh lệch số lượng/date (90 phút - Bottleneck)**.<br>4. Lọc danh sách hàng date < 6 tháng (15 phút).<br>5. Lập biên bản đề xuất xử lý gửi Giám đốc (20 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Nhập liệu thủ công từ giấy vào máy và dò tìm xem lô thuốc nào bị lệch date giữa thực tế và phần mềm, mất **90 phút**. |
| Impact (nếu không giải thì sao) | Hàng cận date bị tồn đọng không phát hiện kịp; mỗi quý trung bình công ty phải tiêu hủy 15–20 triệu đồng tiền thuốc hết hạn sử dụng. |
| Success metric (baseline → target) | • **Baseline:** Tốn 255 phút/lần kiểm kê, độ trễ cảnh báo 30 ngày (chỉ phát hiện vào ngày 25 hàng tháng).<br>• **Target:** Thời gian đối chiếu giảm còn 30 phút; cảnh báo cận date tự động theo thời gian thực (real-time).<br>• **Cách đo:** Giá trị thuốc hủy do hết date giảm về 0 đồng/quý. |
| Phương án không dùng AI | Áp dụng chuẩn hóa quản lý kho FEFO (First Expired, First Out), dán mã QR/BarCode cho từng lô thuốc khi nhập hàng, cài đặt công thức điều kiện trên phần mềm tự tô đỏ các mã thuốc có date < 180 ngày. |
| Giả thuyết về AI (nếu có) | Chụp ảnh phiếu nhập kho/hóa đơn viết tay bằng mô hình OCR trích xuất tự động số lô, hạn dùng vào hệ thống. |
| Cảm nhận nhanh | **Rule** kết hợp mã vạch (Barcode/QR code). |

Quy trình nháp hiện tại:

```text
[In bảng tồn kho giấy] (10') 
  ──> [Đi rà từng kệ thuốc đọc số lô & date] (120') 
  ──> [*NGHẼN* Gõ tay vào Excel + Dò lệch hạn dùng với phần mềm] (90') 
  ──> [Lọc hàng date < 6 tháng] (15') 
  ──> [Làm báo cáo trình sếp] (20')

Tổng thời gian: 255 phút/kỳ kiểm kê
```

### Card muốn pitch nhất

- Card số: **Card #1** (Rà soát chất lượng tư vấn y dược của 10 saler trên phần mềm chat Pancake ngay trong ca làm việc)
- Vì sao:
  1. Đây là bài toán có **rủi ro lớn nhất** trong vận hành công ty dược: Sai sót về liều lượng hay bỏ qua chống chỉ định (bệnh nền tim mạch, huyết áp, phụ nữ mang thai) sẽ gây nguy hiểm trực tiếp đến sức khỏe khách hàng và vi phạm pháp lý y tế.
  2. **Bottleneck cực kỳ nặng và có thật**: QA bị ngợp vì tin nhắn đổ về liên tục trên Pancake từ nhiều Fanpage, mất tới 90 phút/ngày mà chỉ soi ngẫu nhiên được ~8% hội thoại, trong khi đơn hàng vẫn được chốt và in bill đẩy đi kho đều đặn mà không được kiểm soát hết.
  3. **Phù hợp nhất với đề bài Lab**: Ranh giới rất rõ để so sánh giữa Rule (từ khóa cấm/tin nhắn mẫu) và Workflow AI (hiểu ngữ cảnh tư vấn và sàng lọc bệnh nền), giúp nhóm dễ dàng đào sâu ở các checkpoint sau.
- Câu hỏi muốn nhóm phản biện:
  *"Khách hàng mua thuốc trên Facebook thường nhắn tin ngắt quãng, gõ tắt và dùng từ ngữ dân gian/tiếng lóng vùng miền (ví dụ: 'đau bao tử', 'nóng trong', 'dạo này người cấn cấn'). Liệu AI có thể hiểu đúng ngữ cảnh để bắt lỗi saler hay sẽ liên tục 'báo nhầm' (false alarm) làm loạn nhóm chat nội bộ của ca trực? Và giải pháp kỹ thuật kết nối vào Pancake/Facebook sẽ là gì để đảm bảo độ trễ dưới 3 phút?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| AI chỉ ra rằng việc rà soát theo thời gian thực (real-time) cho toàn bộ câu chat sẽ rất dễ làm phiền saler và gây quá tải hệ thống nếu AI liên tục cảnh báo sai. | Đồng ý | Tôi đã thu hẹp phạm vi can thiệp: Không bắt lỗi mọi câu chat vụn vặt, mà chỉ kích hoạt rà soát tại thời điểm mấu chốt: khi khách báo triệu chứng/tiền sử bệnh và khi saler gửi thông tin báo giá/chốt đơn. |
| AI chất vấn: "Tại sao không dùng tính năng tin nhắn mẫu (Quick Reply) và Rule bắt buộc có sẵn trên Pancake để giải quyết, cần gì AI?" | Đồng ý một phần | Tôi đã bổ sung phân tích vào phần phương án không dùng AI: Rule từ khóa trên Pancake không thể hiểu được ngữ cảnh khi khách hỏi kết hợp nhiều triệu chứng phức tạp hoặc gõ sai chính tả, nhưng tôi vẫn giữ Rule làm tầng lọc thô số 1 trước khi cần AI can thiệp. |
| AI cảnh báo: Success metric ban đầu ghi "giúp saler tư vấn tốt hơn" là định tính, không chấm điểm được theo rubric của lab. | Đồng ý | Tôi đã sửa lại Success Metric thành định lượng cụ thể: **Baseline: Soát 20 cuộc/ngày (8%), tốn 90 phút → Target: Quét 100% cuộc chốt đơn, độ trễ cảnh báo dưới 3 phút, QA chỉ mất 20 phút/ngày** kèm cách đo rõ ràng. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| **Pitch Problem Card** | Trình bày 3 card cá nhân: Rà soát chất lượng tư vấn y dược 10 saler trên Pancake (#10), Lọc trùng và phân bổ lead telesale (#11), Kiểm kê thuốc cận date trong kho dược (#12). Nhấn mạnh nỗi đau rà soát Pancake mất 90–120 phút/ngày ngay trong ca trực. | Card #10 được đưa vào shortlist thảo luận ở Cluster C (Vận hành & Auditing). Tuy nhiên, nhóm nhận thấy bài dược có rào cản pháp lý y tế và độ sẵn sàng dữ liệu quá khó để kiểm chứng trong một buổi lab so với đề tài gọi xe Xanh SM. |
| **Phản biện bài của bạn khác** | Câu hỏi tôi đã đặt:<br>• Cho Lâm (Card #1 - Ngâm cuốc Xanh SM): *'Làm sao hệ thống phân biệt được tài xế cố tình ngâm cuốc với tài xế bị kẹt cứng tại nút giao thông ngã tư Cổ Linh hoặc xe mất sóng GPS trong hầm chung cư?'*<br>• Cho Thành (Card #5 - Unit test API): *'Unit test CRUD cơ bản hiện đã có nhiều thư viện boilerplate hoặc plugin IDE sinh tự động bằng rule/template, việc đưa AI vào có thực sự tạo ra đột phá về độ bao phủ logic nghiệp vụ phức tạp không?'* | Hai câu hỏi được ghi trong bảng pitch mục 2.1 của `group_report.md`. Câu hỏi cho Lâm đã trực tiếp dẫn đến việc nhóm bổ sung cờ trạng thái giao thông (Traffic status) và chốt chặn con người (HITL) để không phạt oan tài xế. |
| **Nhận phản biện** | Câu hỏi tôi nhận được:<br>• Từ Kiên (về bài #10 QA Pancake): *'Ngành dược có rủi ro sức khỏe rất cao, nếu AI bỏ sót lỗi sai liều lượng của saler dẫn đến đơn hàng xuất đi thì hậu quả pháp lý thế nào?'*<br>• Từ Lâm (về bài #10): *'Hệ thống chat Pancake thuộc nền tảng bên thứ ba đóng gói kín, nhóm sinh viên bên ngoài lấy webhook thời gian thực ở đâu để tích hợp AI quét real-time?'* | Tôi đã sửa: Thừa nhận bài toán y dược có rào cản pháp lý và kỹ thuật kết nối bên thứ 3 quá lớn trong phạm vi bài lab; đồng ý rút lui bài dược để ủng hộ Candidate #1 (Xanh SM) của Lâm và Kiên vì cả nhóm đều là người dùng thật, dễ tiếp cận dữ liệu kiểm chứng tại chỗ. |
| **Gom cluster / cây OST** | Cùng nhóm phân loại 15 candidate vào 4 cụm A, B, C, D. Xếp bài của mình (#10, #11, #12) vào Cluster C. Nhắc nhở nhóm trên cây OST: tập trung vào outcome giảm thời gian chờ đợi thụ động cho khách; kiên quyết gạch bỏ các giải pháp đội lốt như "Chatbot tự động chat thay saler" hay "AI tự động khóa tài khoản tài xế". | Cụm A (Mobility & Ride-hailing) được chọn. Cây OST giữ đúng bản chất Opportunity (pain), loại bỏ hoàn toàn các ý tưởng giải pháp viển vông. |
| **Chọn candidate problem** | Bỏ phiếu đồng thuận 5/5 chọn Candidate #1 (Tài xế Xanh SM ngâm cuốc + hỗ trợ phân loại khiếu nại hủy chuyến) vì có bằng chứng thực tế tại Ocean Park, có thể kiểm chứng phỏng vấn ngay với sinh viên và tài xế xung quanh trường. | Candidate #1 trở thành đề tài chính thức của nhóm; kinh nghiệm xây dựng quy trình kiểm soát QA từ bài dược của tôi được áp dụng sang thiết kế luồng kiểm soát đối soát tài xế. |
| **Kiểm chứng / research** | Cùng nhóm phân tích 5 Interview Snapshots do Long và Kiên thực hiện. Đọc kỹ Snapshot 3 (bác tài VF e34 phản ánh kẹt ngã tư Cổ Linh bị trừ điểm oan) để đưa vào thiết kế điều kiện ràng buộc của quy trình. Thảo luận rút ra bài học từ Uber RADAR: bắt buộc phải có chốt chặn con người (HITL). | Xác nhận giả định: Không được dùng Rule thời gian cứng để phạt tài xế; AI chỉ hỗ trợ hậu kiểm, còn giải cứu khách hàng thì dùng Rule tức thì. |
| **Quy trình nhóm (Phụ trách chính)** | **Trực tiếp phụ trách thiết kế và vẽ sơ đồ Mermaid** Quy trình hiện tại (6 bước, 2 bottleneck lớn) và Quy trình tương lai (Mục 4.1 và 4.2 `group_report.md`). Đưa ra kiến trúc 2 tầng: Tầng 1 Rule-based giải cứu khách sau 3 phút + Tầng 2 AI Workflow phân tích ngữ cảnh chat/GPS cho CSKH duyệt + Fallback khi timeout/lỗi API. Lập bảng Before / After (Mục 4.3). | Hoàn thành sơ đồ Mermaid chuẩn xác, trực quan, phân định rõ Rule vs AI vs Con người (HITL); bảng Before/After chứng minh rút ngắn thời gian từ 33 phút xuống < 4 phút, bảo lưu 100% voucher. |
| **Problem Statement** | Cùng Lâm và Long rà soát Problem Statement v0 và v1; đóng góp ý kiến siết chặt trường **Boundary**: AI tuyệt đối không tự động trừ tiền ví hoặc khóa tài khoản tài xế; bổ sung metric đo lường hiệu suất thẩm định cho CSKH (< 30 giây/ticket). | Problem Statement v1 hoàn chỉnh, đầy đủ 8 trường, tách bạch rõ ràng giữa điểm can thiệp của Rule (frontend) và AI (backend hậu kiểm). |
| **Mức can thiệp AI** | Cùng Thành (phụ trách CP6) thảo luận điền AI Canvas và phân tích ma trận: chọn **Workflow**, kiên quyết phản đối Agent tự trị vì rủi ro tranh chấp pháp lý và báo nhầm (False Positive). Đóng góp phân tích hai câu hỏi thiết kế của Google PAIR. | Hoàn thành mục 6 trong báo cáo nhóm: bảo vệ vững chắc lý do vì sao không chọn mức Agent (tránh over-engineering) và vì sao Rule đơn thuần không đủ cho khâu xử phạt. |
| **Quyết định** | Thống nhất với Lâm và cả nhóm đưa ra quyết định **Not Yet** (pilot 4 tuần trên Staging Sandbox) vì rào cản dữ liệu viễn thông nội bộ GSM và yêu cầu tuân thủ Nghị định 13/2023/NĐ-CP về bảo vệ dữ liệu cá nhân; thống nhất ngưỡng dừng đo lường được (False Positive > 5%). | Quyết định Not Yet được lập luận chặt chẽ, thể hiện tư duy trung thực về ranh giới doanh nghiệp, có ngưỡng dừng định lượng rõ ràng tại Mục 8 `group_report.md`. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **CP1 Scan** | Hỏi gợi ý thêm góc nhìn vận hành kho và telesale ngành dược từ trải nghiệm công việc thực tế. | Gợi ý cách đo lường cụ thể về tỷ lệ cước cuộc gọi dưới 5 giây để định lượng số điện thoại ảo của telesale. | Gợi ý giải pháp viễn vông: *"Hệ thống AI tự động kê đơn thuốc thay bác sĩ"*. | Loại bỏ hoàn toàn ý tưởng kê đơn tự động vì vi phạm nghiêm trọng quy chuẩn y tế và pháp lý; chỉ giữ lại các pain point có dấu hiệu thật đo được về kiểm soát chất lượng và xử lý lead. |
| **CP2 Problem Card** | Nhờ AI đóng vai "PM hoài nghi" để phản biện điểm yếu của Card #1 (Rà soát chất lượng tư vấn trên Pancake). | Chỉ ra rằng việc bắt AI quét liên tục theo thời gian thực (real-time) cho toàn bộ tin nhắn sẽ gây quá tải hệ thống và làm phiền saler. | Gợi ý hời hợt rằng chỉ cần dùng bộ tin nhắn mẫu (Quick Reply) là giải quyết triệt để 100% bài toán, không cần phân tích gì thêm. | Tiếp thu điểm yếu để thu hẹp phạm vi kích hoạt AI vào thời điểm chốt đơn/báo giá; đồng thời phản biện lại AI rằng Quick Reply không xử lý được khi khách hàng gõ sai chính tả hoặc mô tả triệu chứng phức tạp. |
| **CP4 Research** | Tìm kiếm tài liệu kỹ thuật về cách các ứng dụng gọi xe lớn (Uber, Grab) phát hiện gian lận và xử lý hủy chuyến. | Tóm tắt nhanh kiến trúc Project RADAR của Uber và nền tảng Graph Anomaly của Grab. | Đưa link blog cũ đã lỗi thời và đánh đồng bài toán gian lận cước/thanh toán (payment fraud) với bài toán vi mô về tài xế ngâm cuốc cục bộ. | Tự mở lại từng link blog kỹ thuật chính thức; chắt lọc đúng phần xử lý bất thường hành trình và nguyên tắc giữ con người trong luồng (HITL) để đưa vào bảng research nhóm. |
| **CP5 Quy trình** | Nhờ AI hỗ trợ sinh cú pháp sơ đồ Mermaid từ bản nháp quy trình 2 tầng mà tôi đã phác thảo trên giấy. | Chuyển đổi nhanh cấu trúc các bước thành khối flowchart Mermaid trực quan, căn chỉnh các nhánh điều kiện rẽ nhánh. | AI tự động nối mũi tên từ khối AI phân loại thẳng sang hành động *"Tự động khóa tài khoản và trừ tiền tài xế"* mà không có bước con người kiểm duyệt. | Chỉnh sửa lại toàn bộ sơ đồ: ngắt liên kết tự động phạt của AI, chèn khối chốt chặn con người `[HUMAN-IN-THE-LOOP]` bắt buộc chuyên viên CSKH duyệt; bổ sung thêm nhánh `[FALLBACK]` khi pipeline AI gặp sự cố timeout > 3 giây. |
| **CP5–6 Problem Statement** | Nhờ AI rà soát lỗ hổng logic trong bản thảo Problem Statement v0 xem có bị lỗi solution-first không. | Nhắc nhở rằng bản v0 đang dồn hết sự tập trung vào hành khách mà bỏ quên actor nội bộ là chuyên viên CSKH – người trực tiếp chịu áp lực xử lý khiếu nại. | Đề xuất bổ sung các chỉ số định tính chung chung như *"tăng cường sự hài lòng của khách hàng"*, *"tối ưu hóa quy trình"*. | Bác bỏ các chỉ số định tính của AI; giữ vững các metric định lượng chuẩn mực: thời gian thoát cuốc kẹt < 5 phút, 100% voucher được bảo lưu, thời gian thẩm định của CSKH < 30 giây. |
| **CP6 Mức can thiệp / quyết định** | Nhờ AI đối chiếu 4 mức No AI / Rule / Workflow / Agent theo ma trận độ phức tạp và độ mơ hồ. | Phân tích rõ ràng sự khác biệt giữa hỗ trợ con người (Augment) và tự động hóa hoàn toàn (Automate) theo hướng dẫn Google PAIR. | AI có xu hướng xúi giục chọn mức "Agent" tự trị hoặc kết luận "Go ngay" để giải pháp trông hiện đại, hoành tráng hơn. | Giữ vững lập trường của nhóm: kiên quyết chọn **Workflow** (kết hợp Rule tầng 1 và AI tầng 2) và chốt quyết định **Not Yet** vì rào cản sống còn về dữ liệu viễn thông GSM theo Nghị định 13/2023/NĐ-CP. |

---

## 6. Reflection (CP7)

Trắc nghiệm và tự soi rọi bằng trải nghiệm thật qua quá trình làm việc nhóm, tối thiểu 200 từ cho các câu 6.1–6.6. **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi lắng nghe phần trình bày của các thành viên trong nhóm Bàn 3, bài học lớn nhất tôi rút ra được là sự khác biệt giữa một "bài toán cá nhân" và một "đề tài phù hợp cho cả nhóm cùng đào sâu". Bản thân tôi xuất phát điểm với 6 tháng kinh nghiệm làm vận hành dược, mang đến buổi lab những bài toán rất thật về kiểm tra chất lượng tư vấn trên Pancake hay kiểm kê date thuốc. Tuy nhiên, khi nghe Lâm pitch về trải nghiệm bị tài xế Xanh SM "ngâm cuốc" tại Ocean Park, tôi lập tức nhận thấy đây là một đề tài vượt trội về tính cộng hưởng: tất cả thành viên trong nhóm đều là sinh viên/cư dân di chuyển hàng ngày quanh khu đô thị này, ai cũng từng nếm trải cảm giác ức chế khi đứng dưới mưa nhìn xe đứng im một chỗ trên bản đồ. Trong khi đó, bài toán của Thành về viết mô tả PR hay điều tra log dù rất thực tế với dân lập trình nhưng lại chỉ gói gọn trong nội bộ kỹ thuật; bài toán của Long về chọn thực phẩm siêu thị thì ranh giới can thiệp AI còn khá mơ hồ. Đặc biệt, sự kết hợp giữa card ngâm cuốc của Lâm và card phân loại lý do hủy chuyến của Kiên đã tạo nên một chuỗi quy trình khép kín: giải quyết nỗi đau của khách trước chuyến đi và giải quyết bài toán vận hành sau chuyến đi. Điều này giúp tôi hiểu rằng một đề tài tốt ở giai đoạn Discovery không chỉ cần có số liệu thật, mà còn phải tạo điều kiện để cả nhóm có thể tiếp cận người dùng và kiểm chứng giả định ngay lập tức trong buổi học.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm tôi đã bị rơi vào cái bẫy "solution-first" rất nặng ngay ở những phút đầu tiên của Checkpoint 3, ngay khi vừa thống nhất chọn chủ đề tài xế Xanh SM ngâm cuốc. Với tâm lý hào hứng của sinh viên công nghệ, phản xạ đầu tiên của cả nhóm là lập tức bàn về giải pháp: *"Hay là mình xây dựng một con AI Agent tự động phát hiện xe đứng im rồi tự gọi điện thoại cho tài xế, tự hủy chuyến và tự trừ 50k trong ví tài xế luôn?"*. Lúc đó, chúng tôi gần như bị cuốn vào việc vẽ ra một hệ thống tự trị cực kỳ phức tạp và hiện đại. Rất may mắn là Thành và Kiên đã kịp thời "kéo phanh" cả nhóm lại bằng câu hỏi phản biện: *"Nếu hệ thống cứ thấy xe đứng im 3 phút là tự động phạt tiền tài xế, thì lỡ họ bị kẹt cứng ở ngã tư Cổ Linh giờ cao điểm hoặc mất sóng GPS dưới hầm thì sao? Chúng ta đang trừng phạt cả những tài xế vô tội à?"*. Câu hỏi này như một gáo nước lạnh làm cả nhóm bừng tỉnh. Chúng tôi lập tức quay lại cây Opportunity Solution Tree (OST) ở mục 2.3, dùng bút đỏ gạch bỏ toàn bộ các nhánh giải pháp đội lốt như "chatbot tự động phạt", "agent tự hoàn tiền". Nhóm nhận ra rằng người dùng lúc đó chỉ có một nhu cầu duy nhất là **được thoát khỏi cuốc xe kẹt để đi tiếp mà không mất mã giảm giá**, hoàn toàn không đòi hỏi AI phải can thiệp tức thì. Từ đó, chúng tôi thống nhất chia đôi bài toán: Tầng 1 cứu khách thuần túy bằng tập luật Rule-based đơn giản, còn Tầng 2 mới đưa AI Workflow vào khâu hậu kiểm có con người phê duyệt.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Lần đổi ý lớn nhất và có tính bước ngoặt đối với tôi chính là việc **từ bỏ việc bảo vệ đề tài kiểm soát chất lượng tư vấn y dược (Card #10) để toàn tâm toàn ý cùng nhóm phát triển đề tài Xanh SM**. Ban đầu, với lợi thế 6 tháng làm việc thực tế tại công ty dược, tôi đã chuẩn bị Card #10 rất chi tiết với số phút nghẽn 90 phút/ngày và các kịch bản đối soát checklist rất chặt chẽ. Tôi rất tự tin muốn đưa bài này thành đề tài chung của nhóm. Tuy nhiên, trong phần phản biện ở CP3, Kiên đã đặt câu hỏi chất vấn: *"Ngành dược liên quan trực tiếp đến tính mạng con người, nếu AI của Tùng bỏ sót một lỗi tư vấn sai liều lượng hoặc chống chỉ định dẫn đến bệnh nhân gặp biến chứng thì ai chịu trách nhiệm pháp lý?"*, đồng thời Lâm chất vấn thêm: *"Phần mềm Pancake là hệ thống đóng của bên thứ ba, nhóm mình làm thế nào lấy được API webhook real-time để đưa AI vào quét?"*. Hai câu hỏi này đánh trúng vào hai tử huyệt: tính khả thi kỹ thuật (Feasibility) và rủi ro pháp lý/vận hành (Viability). Tôi nhận thức rõ ràng rằng trong phạm vi một bài lab 4 tiếng, nhóm không thể nào tiếp cận được dữ liệu chat y tế thật hay giải quyết được bài toán đạo đức dược phẩm. Tôi đã chủ động rút lui đề tài cá nhân của mình, chấm điểm khách quan và đồng thuận 100% chọn bài toán Xanh SM. Sự đổi ý này giúp tôi nhận ra tư duy làm sản phẩm đòi hỏi sự thực tế và dũng cảm từ bỏ ý tưởng riêng khi nó không phù hợp với nguồn lực kiểm chứng của tập thể.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điều khiến tôi bất ngờ nhất trong giai đoạn kiểm chứng CP4 chính là **tín hiệu phản bác cực kỳ mạnh mẽ từ phía các bác tài xế**. Trước khi đi phỏng vấn, góc nhìn của tôi (cũng như đa số khách hàng) khá một chiều và đầy định kiến: cứ thấy xe nhận cuốc mà đứng im ở quán nước hoặc đi chậm là quy kết ngay tài xế vô ý thức, cố tình ngâm cuốc để ép khách tự hủy. Tuy nhiên, khi đọc biên bản phỏng vấn (Snapshot 3) của bác tài lái xe VF e34 tại ngã tư Cổ Linh và Snapshot 4 của bạn tài xế Bike bị trôi GPS ở cụm tòa S1 Ocean Park, tôi thực sự bị giật mình. Hóa ra có rất nhiều tình huống bất khả kháng: tắc đường dài 4 nhịp đèn đỏ, công trình rào chắn đường gom, hay hiện tượng dội sóng GPS (Urban Canyon) giữa các khối nhà cao tầng khiến bản đồ hiển thị xe đứng im dù tài xế đang cố gắng di chuyển. Nếu nhóm chúng tôi giữ nguyên tư duy ban đầu dùng AI tự động xử phạt, chúng tôi sẽ biến hệ thống thành một cỗ máy áp bức đối tác lái xe. Kết quả kiểm chứng này đã làm thay đổi hoàn toàn cách tôi thiết kế sơ đồ quy trình ở CP5: tôi bắt buộc phải đưa thêm lớp dữ liệu mật độ giao thông vào điều kiện Rule, và ở tầng AI hậu kiểm bắt buộc phải có chốt chặn con người (Human-in-the-loop) để cho phép tài xế giải trình.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Trải nghiệm trực tiếp cùng nhóm xây dựng Problem Statement từ bản v0 lên v1 giúp tôi nhận thấy điều khó nhất không phải là câu chữ, mà là **việc kiềm chế thói quen nhét giải pháp vào bài toán và việc xác định ranh giới (Boundary) cho AI**. Khi viết bản v0, chúng tôi rất dễ bị cám dỗ viết những câu như: *"Vấn đề là thiếu một hệ thống AI để phát hiện tài xế ngâm cuốc"*. Chúng tôi phải liên tục nhắc nhau sửa lại theo chuẩn Lean UX: chỉ mô tả actor, các bước trong quy trình, thời gian nghẽn (12 phút chờ đợi + 8 phút chụp màn hình) và hệ quả thiệt hại. Sang bản v1, cái khó nhất là phân định điểm can thiệp (AI Intervention Point) và ranh giới. Rất khó để dũng cảm thừa nhận rằng: ở bước tiếp xúc trực tiếp với khách hàng, AI hoàn toàn không có chỗ đứng vì độ trễ và nguy cơ ảo giác (hallucination); chỗ của AI chỉ nằm khiêm tốn ở khâu backend hậu kiểm nhằm giúp chuyên viên CSKH đọc tóm tắt tin nhắn chat. Việc viết một Boundary cấm AI tự động trừ tiền và cấm AI tự ý khóa tài khoản đòi hỏi một sự thấu hiểu sâu sắc về quản trị rủi ro chứ không đơn thuần là áp dụng công nghệ.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu có cơ hội làm lại buổi lab này từ đầu, điều tôi muốn thay đổi nhất là **chủ động tham gia trực tiếp vào ít nhất 2 cuộc phỏng vấn tài xế ngoài thực địa**, thay vì chỉ ngồi nghe và đọc lại biên bản tổng hợp của các bạn trong nhóm. Trực tiếp nhìn thấy vẻ mặt bức xúc của bác tài khi bị trừ điểm oan sẽ giúp tôi có thêm nhiều dữ liệu cảm xúc và trực giác thực tế hơn để tinh chỉnh các tham số thời gian trong quy trình. Về góc độ phản biện nhóm, tôi sẽ phản biện mạnh mẽ hơn ngay từ khâu lập Assumption Map ở CP4 về **tính khả thi của việc truy cập dữ liệu viễn thông GSM**. Ban đầu nhóm dành quá nhiều thời gian tranh luận về thuật toán AI phân tích ngôn ngữ chat, trong khi rủi ro lớn nhất khiến dự án phải dừng ở mức "Not Yet" lại là tính pháp lý của dữ liệu hành trình theo Nghị định 13/2023/NĐ-CP. Nếu tôi quyết liệt chất vấn nhóm sớm hơn về quyền hạn truy cập database nội bộ của GSM, nhóm sẽ tiết kiệm được rất nhiều thời gian và có thể tập trung thiết kế sâu hơn môi trường giả lập (Mock Telemetry Sandbox) ngay trong buổi lab.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

1. **Problem:** Hành khách đặt xe Xanh SM bị tài xế nhận cuốc nhưng cố tình đứng im hoặc đi ngược hướng để ép khách tự hủy, khiến khách mất 25–35 phút chờ đợi trong bức xúc và bị mất mã giảm giá; đồng thời chuyên viên CSKH phải tốn 3–4 phút/ticket đọc dò thủ công tin nhắn chat và vết GPS để giải quyết khiếu nại.
2. **Quy trình:** Nhóm tái cấu trúc quy trình thành 2 tầng rõ rệt: Tầng 1 sử dụng Rule-based kiểm tra sau 3 phút nếu xe đứng im và không kẹt xe thì kích hoạt ngay nút cho khách đổi xe mới hoặc hủy miễn phí; Tầng 2 sử dụng AI Workflow tổng hợp log GPS và tin nhắn chat để trích xuất bằng chứng dự thảo nhãn vi phạm cho CSKH phê duyệt.
3. **Success Metric:** Giảm thời gian giải cứu khách hàng từ 25–35 phút xuống dưới 5 phút, bảo lưu 100% voucher ưu đãi cho khách; giảm thời gian thẩm định khiếu nại của CSKH từ 3–4 phút xuống dưới 30 giây/ca với tỷ lệ phạt nhầm tài xế (False Positive) dưới 5%.
4. **Boundary:** AI tuyệt đối không được tự ý can thiệp vào tài khoản thanh toán/ví tiền của khách hàng và không được tự động ban hành quyết định xử phạt tài xế nếu chưa có sự phê duyệt của con người (Human-in-the-loop); đồng thời toàn bộ dữ liệu cá nhân (tên, SĐT, địa chỉ) phải được che mờ (masking) trước khi xử lý.
5. **Mức can thiệp AI:** Nhóm lựa chọn mức **Workflow** (kết hợp Rule Engine ở tầng giao diện và AI Analysis Pipeline ở tầng backend quản trị), kiên quyết nói không với Autonomous Agent để tránh rủi ro tự trị mất kiểm soát.
6. **Quyết định:** Nhóm đưa ra kết luận **NOT YET** — đề xuất triển khai chương trình thử nghiệm Pilot 4 tuần trên môi trường Staging Sandbox mô phỏng dữ liệu, xuất phát từ sự trung thực về rào cản pháp lý bảo vệ dữ liệu cá nhân (Nghị định 13/2023/NĐ-CP) và việc nhóm chưa có quyền truy cập cơ sở dữ liệu viễn thông nội bộ của GSM.
7. **Ngưỡng dừng:** Nếu sau 4 tuần thử nghiệm trên môi trường Staging mà tỷ lệ phạt nhầm (False Positive) của AI vẫn vượt quá 5% hoặc không giải quyết được cơ chế ẩn danh hóa dữ liệu định vị, nhóm sẽ dừng toàn bộ module AI và chỉ giữ lại tính năng Rule-based giải cứu khách hàng trên ứng dụng.

---

## 7. Tài liệu tham khảo

1. **Báo cáo nhóm Ban3:** [report/team/group_report.md](../team/group_report.md) — Chi tiết kết quả hội tụ từ CP3 đến CP6 của nhóm Bàn 3.
2. **Bảng phân công nhiệm vụ và nhật ký đóng góp:** [TEAM.md](../../TEAM.md).
3. **Bộ dữ liệu kiểm thử 10 cặp Input/Output (Bonus B3):** [report/assets/cp6-eval-set-10-pairs.md](../assets/cp6-eval-set-10-pairs.md).
4. **Uber Engineering (2019):** *Project RADAR: Intelligent Early Fraud Detection System with Humans in the Loop*. URL: [https://www.uber.com/blog/project-radar-intelligent-early-fraud-detection/](https://www.uber.com/blog/project-radar-intelligent-early-fraud-detection/)
5. **Grab Tech Blog (2021):** *Graph-based Prediction Platform for Fraud Detection*. URL: [https://engineering.grab.com/graph-based-prediction-platform](https://engineering.grab.com/graph-based-prediction-platform)
6. **Zendesk AI (2023):** *Intelligent Triage & Intent Detection for Customer Experience*. URL: [https://www.zendesk.com/service/ai/](https://www.zendesk.com/service/ai/)
7. **Google PAIR (People + AI Research):** *People + AI Guidebook — Chapters on Mental Models, Errors & Graceful Failure*. URL: [https://pair.withgoogle.com/](https://pair.withgoogle.com/)
8. **Anthropic Research (2024):** *Building Effective Agents — Workflows versus Autonomous Agents*. URL: [https://www.anthropic.com/research/building-effective-agents](https://www.anthropic.com/research/building-effective-agents)
9. **Chính phủ Việt Nam (2023):** *Nghị định số 13/2023/NĐ-CP về Bảo vệ dữ liệu cá nhân*.
10. **Marty Cagan (Silicon Valley Product Group):** *Inspired: How to Create Tech Products Customers Love — Assessing Product Risks (Value, Usability, Feasibility, Viability)*.
11. **Rob Fitzpatrick:** *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you*.
12. **Teresa Torres:** *Continuous Discovery Habits: Discover Products that Create Customer Value and Business Value — Opportunity Solution Trees*.
