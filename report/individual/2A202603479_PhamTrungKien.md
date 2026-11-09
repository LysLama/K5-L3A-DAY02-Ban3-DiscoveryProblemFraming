# Báo cáo cá nhân — 2A202603479_PhamTrungKien

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phạm Trung Kiên
- MSSV: 2A202603479
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Ban3
- Link repo nhóm: https://github.com/LysLama/K5-L3A-DAY02-Ban3-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

Mình quét lại các pain từng ghi ở bài Day02 cũ (Vinpearl / VinFast / Xanh SM / Vinhomes / Vinmec), rồi bổ sung actor khác trong cùng chuỗi — mỗi dòng một việc, không tách một quy trình thành 3 bài.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi inbox đầy review 1–3 sao từ Booking, Agoda và Google cùng lúc, tôi muốn soạn xong từng phản hồi đúng giọng khách sạn trước khi hết ca, để không vỡ hạn 24 giờ | CSKH property Vinpearl (người gõ thư) | Một review thường mất khoảng 12–15 phút. Cuối tuần mình ước ~35–40 review/người/ca. Có hôm hai ca viết khác giọng hẳn dù cùng một SOP |
| 2 | Lặp lại | Khi khách đứng cạnh hỏi “xe này + pin này hết bao nhiêu sau ưu đãi”, tôi muốn lấy đúng giá khu vực và chương trình tháng đang chạy, để gửi Zalo luôn mà không phải cộng Excel lại từ đầu | Tư vấn showroom VinFast | Khoảng 15–20 phút/khách. Ngày đông làm cả chục bảng. Tháng đổi ưu đãi là hay lệch vài dòng so với bảng giá in |
| 3 | Lặp lại | Khi đóng ca, tôi muốn gắn một nguyên nhân gốc cho từng chuyến hủy (tài xế muộn / khách hủy / app lỗi), để sáng hôm sau khỏi đọc lại đống ghi chú khi làm báo cáo tuần | Nhân viên chất lượng Xanh SM | Mỗi ca cả trăm note ngắn của khách và tài xế. Gắn tay khoảng 1–2 phút/note. Để dồn cuối tuần thì ngồi cả tiếng đồng hồ |
| 4 | Tốn thời gian | Khi giờ cao điểm sảnh đông, tôi muốn biết căn hộ có cho khách vào không trước khi mở cửa, để hàng không dài và mình khỏi gọi đi gọi lại | Bảo vệ / lễ tân tòa Vinhomes | Mỗi lượt hay mất 10–15 phút vì phải gọi cư dân. Buổi tối sau 18h hàng dài rõ; khách gắt vì đứng chờ |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi bệnh nhân sắp vào phòng, tôi muốn gom tiền sử, dị ứng và thuốc đang dùng từ vài lần khám cũ thành một trang, để bác sĩ không hỏi lại từ đầu | Điều dưỡng tiền khám Vinmec | Lướt EMR + ghi tay khoảng 8–10 phút/ca. Hồ sơ dài thì dễ sót dòng dị ứng |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận ca sáng, tôi muốn biết ca đêm còn bao nhiêu review chưa trả và cái nào gần vỡ SLA, để phân việc trước khi mở từng ticket | Trưởng ca / Guest Experience property | Handover hay chỉ là tin nhắn rời. Mình từng thấy mở lại 3 tab OTA mất gần 20 phút chỉ để đếm việc tồn |
| 7 | Pain từ người khác | Khi bị trừ điểm chuyến hủy mà mình không muộn, tôi muốn lý do trên hệ thống khớp việc thật, để khỏi phải khiếu nại nội bộ mất cả buổi | Tài xế Xanh SM | Tài xế hay nhắn group chất lượng nhờ xem lại nhãn. Một case làm rõ thường 30–45 phút (đối chiếu GPS + note) |
| 8 | Pain từ người khác | Khi đang họp mà lễ tân gọi “có khách bên dưới”, tôi muốn xác nhận cho vào trong một thao tác ngắn, để khỏi ngắt họp và khách khỏi đứng sảnh | Cư dân Vinhomes; khách thăm; lễ tân | Cư dân bị gọi 1–2 lần/lượt khách. Giờ cao điểm có người tắt máy → lễ tân gọi lại → khách chờ thêm |
| 9 | Pain từ người khác | Khi vừa gọi tên bệnh nhân, tôi muốn nhìn một bản tóm tắt dị ứng/thuốc trước mặt, để khỏi lật EMR giữa buổi và khỏi hỏi lại người nhà những câu đã hỏi ở quầy | Bác sĩ khám ngoại trú Vinmec | Mất khoảng 8–10 phút đầu ca nếu tờ tóm tắt chưa có. Người nhà phàn nàn bị hỏi trùng |
| 10 | Lặp lại | Khi hết ngày, tôi muốn đối chiếu các báo giá đã gửi khách với bảng giá chính thức trong ngày, để bắt lệch ưu đãi trước khi khách chốt cọc | Trưởng showroom / salesteam lead VinFast | Cuối ngày soi 10–20 file PDF/sheet. Lệch một dòng phụ kiện là phải gọi lại khách; ước 30–40 phút/ngày |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Năm ý gốc (Vinpearl review, VinFast báo giá, Xanh SM gắn nhãn, Vinhomes khách thăm, Vinmec tóm tắt EMR) mình giữ vì đã đào ở bài trước, có số phút.
- AI gợi ý tách review Vinpearl thành “đọc”, “tra SOP”, “soạn thư” — mình **bỏ**, trùng một quy trình.
- AI gợi ý “chatbot tự trả lời OTA” — **bỏ**, đó là giải pháp; bài trước từng bị AI dụ tự đăng / tự hoàn tiền.
- **Giữ** thêm #6–#10 vì đổi actor thật (trưởng ca, tài xế, cư dân, bác sĩ, trưởng showroom), không phải viết lại cùng một pain.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Phản hồi đánh giá OTA Vinpearl (#1) | Có số phút thật từ bài trước; quy trình 5 bước rõ; so được No AI / Rule / Workflow | Property có chịu dùng bản nháp máy soạn không? Giọng “đủ Vinpearl” đo sao? |
| 2 | Gắn nhãn hủy chuyến Xanh SM (#3) | Lặp mỗi ca; nối được pain tài xế (#7); metric đếm được | Taxonomy đã chuẩn chưa? Note ngắn có gắn đúng được không? |
| 3 | Tóm tắt tiền sử Vinmec (#5, nối #9) | Có phút đo; bác sĩ/người nhà cùng đau; quy trình ngắn | EMR có cho lab đụng không; “không sót dị ứng” khó chứng trong buổi |

### Problem Card #1 — Phản hồi đánh giá OTA (Vinpearl)

| Trường | Nội dung |
|---|---|
| Job Story | Khi inbox đầy review một đến ba sao trên Booking, Agoda và Google, tôi muốn hiểu khách đang phàn nàn gì rồi viết thư trả lời đúng giọng khách sạn, để kịp hạn hai mươi bốn giờ và các ca không viết mỗi người một kiểu |
| Actor | Nhân viên CSKH ở property Vinpearl, kèm quản lý Guest Experience duyệt trước khi đăng |
| Thời điểm / bối cảnh | Trong ca trực, nặng nhất cuối tuần và mùa cao điểm, vì review đổ về cả ba kênh cùng lúc |
| Quy trình hiện tại (3–7 bước) | Lấy review mới vào inbox. Đọc rồi phân loại khiếu nại. Tra SOP, voucher và hạn mức xin lỗi. Soạn thư tiếng Việt hoặc tiếng Anh rồi nhờ quản lý duyệt. Đăng lên OTA và ghi log nội bộ. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Chỗ nặng nhất là bước soạn thư, thường khoảng năm phút, vì dễ lệch giọng giữa các ca và lúc viết gấp hay hứa ngoài SOP. Đọc phân loại với tra SOP cũng mỗi bước khoảng bốn phút, cộng lại đoạn giữa khá mệt. |
| Impact (nếu không giải thì sao) | Cuối tuần một người có thể cầm khoảng ba mươi lăm đến bốn mươi review một ca, dễ mất cả buổi chỉ để trả lời. Property đông khách thì cả tuần vài chục giờ CSKH. Trễ hạn hai mươi bốn giờ thì điểm review và hạng OTA tụt. |
| Success metric (baseline → target) | Hiện khoảng mười lăm phút một review, muốn xuống dưới ba phút. Ít nhất chín mươi lăm phần trăm review được trả lời trong hai mươi bốn giờ. Mọi thư gửi đi vẫn phải có người duyệt, không tự đăng. |
| Phương án không dùng AI | Có sẵn mẫu xin lỗi theo chủ đề, checklist SOP, gom inbox ba kênh. Cách này đỡ loạn format nhưng vẫn mất thời gian đọc review cảm xúc và chọn đúng chính sách. |
| Giả thuyết về AI | Máy gợi ý chủ đề và mức nghiêm trọng rồi viết bản nháp đúng giọng. Phần SOP và voucher vẫn theo rule có sẵn. CSKH sửa và bấm duyệt rồi mới đăng. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Hiện tại: khoảng 12 đến 15 phút một review
Cuối tuần ước 35 đến 40 review mỗi người mỗi ca

1. Lấy review từ OTA vào inbox (khoảng 1 phút)
2. Đọc và phân loại khiếu nại (khoảng 4 phút) — chỗ nghẽn vì nhiều ý, viết cảm xúc
3. Tra SOP, voucher, hạn mức xin lỗi (khoảng 4 phút) — SOP nằm rải nhiều file
4. Soạn thư tiếng Việt hoặc Anh rồi xin duyệt (khoảng 5 phút) — BOTTLENECK, dễ lệch giọng
5. Đăng lên OTA và ghi log (khoảng 1 phút)
```

### Problem Card #2 — Gắn nhãn nguyên nhân hủy chuyến (Xanh SM)

| Trường | Nội dung |
|---|---|
| Job Story | Khi hết ca, tôi muốn gắn đúng lý do gốc cho từng chuyến hủy (tài xế muộn, khách đổi ý, lỗi app), để làm báo cáo tuần khỏi phải đọc lại cả đống ghi chú từ đầu |
| Actor | Nhân viên chất lượng Xanh SM; quản lý vận hành là người đọc báo cáo tuần |
| Thời điểm / bối cảnh | Cuối mỗi ca, rồi dồn sang cuối tuần khi tổng hợp chất lượng |
| Quy trình hiện tại (3–7 bước) | Xuất danh sách chuyến hủy trong ca. Mở từng ghi chú của khách và tài xế. Đọc rồi gắn nhãn nguyên nhân theo danh mục. Ghi vào sheet tổng hợp. Cuối tuần cộng theo nhãn rồi viết báo cáo. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Nặng ở đoạn đọc ghi chú rồi gắn nhãn, thường một đến hai phút mỗi note. Một ca cả trăm note thì chỉ việc gắn nhãn cũng mất hai đến ba giờ. |
| Impact (nếu không giải thì sao) | Báo cáo tuần chậm hoặc gắn sai lý do. Quản lý không biết nên ưu tiên sửa tài xế, app hay quy trình đón. Để dồn cuối tuần thì phải ngồi đọc lại note thô. |
| Success metric (baseline → target) | Hiện gắn tay khoảng hai phút một ghi chú, muốn người chỉ còn duyệt dưới hai mươi giây. Trên mẫu kiểm, nhãn đúng từ chín mươi phần trăm trở lên. Báo cáo tuần ra đúng hạn, không phải đọc lại thô. |
| Phương án không dùng AI | Danh mục nguyên nhân cố định, bắt chọn dropdown khi đóng ticket hủy, báo cáo lấy từ sheet. Đỡ phải nghĩ nhãn, nhưng note dài hoặc mơ hồ vẫn đọc mệt. |
| Giả thuyết về AI | Máy đề xuất một hai nhãn từ nội dung ghi chú. Người chất lượng xác nhận. Rule chặn nhãn ngoài danh mục. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Hiện tại: khoảng 1 đến 2 phút một ghi chú, mỗi ca cả trăm ghi chú

1. Xuất danh sách chuyến hủy (khoảng 5 phút mỗi ca)
2. Mở và đọc ghi chú khách hoặc tài xế (khoảng 1 phút mỗi ghi chú) — chỗ nghẽn
3. Gắn nhãn nguyên nhân gốc (khoảng 1 phút mỗi ghi chú) — BOTTLENECK
4. Ghi vào sheet tổng hợp (khoảng 15 giây mỗi ghi chú)
5. Cuối tuần cộng số và viết báo cáo (khoảng 45 đến 60 phút)
```

### Problem Card #3 — Tóm tắt tiền sử trước khám (Vinmec)

| Trường | Nội dung |
|---|---|
| Job Story | Khi bệnh nhân sắp vào phòng khám, tôi muốn có sẵn tiền sử, dị ứng và thuốc đang dùng lấy từ các lần khám cũ, để bác sĩ khỏi mất tám đến mười phút đầu buổi vì hồ sơ chưa sẵn |
| Actor | Điều dưỡng tiền khám và bác sĩ khám ngoại trú ở Vinmec |
| Thời điểm / bối cảnh | Ngay trước giờ bác sĩ gọi tên, với bệnh nhân đã khám nhiều lần trên EMR |
| Quy trình hiện tại (3–7 bước) | Mở EMR và lướt các lần khám cũ. Ghi tay tiền sử, dị ứng, thuốc đang dùng. Hỏi lại bệnh nhân cho đủ. Đưa tờ tóm tắt cho bác sĩ trước giờ khám. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Nặng ở đoạn lướt EMR rồi ghi tay, cả thảy khoảng tám đến mười phút một ca. Làm gấp thì dễ sót dòng dị ứng. |
| Impact (nếu không giải thì sao) | Bác sĩ mất gần mười phút đầu ca. Sót dị ứng thì rủi ro cao. Giờ đông thì hàng chờ dài thêm, người nhà cũng bị hỏi trùng. |
| Success metric (baseline → target) | Hiện chuẩn bị hồ sơ khoảng mười phút, muốn xuống dưới hai phút. Trên bộ case kiểm không bỏ sót dị ứng hoặc thuốc đang dùng. Máy không được tự kê đơn hay chẩn đoán. |
| Phương án không dùng AI | Checklist tiền khám cố định và một trang mẫu trong EMR. Đỡ sót trường, nhưng vẫn mất thời gian đọc nhiều lần khám dài. |
| Giả thuyết về AI | Máy đọc EMR rồi viết bản tóm tắt có mục rõ. Điều dưỡng duyệt trước khi đưa bác sĩ. Case lạ thì chuyển lên xử lý tay. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Hiện tại: khoảng 8 đến 10 phút mỗi ca trước giờ khám

1. Lướt EMR nhiều lần khám cũ (khoảng 5 phút) — BOTTLENECK
2. Ghi tay tiền sử, dị ứng, thuốc (khoảng 3 phút) — chỗ nghẽn, dễ sót
3. Hỏi lại bệnh nhân cho đủ (khoảng 1 đến 2 phút)
4. Đưa tờ tóm tắt cho bác sĩ (khoảng 1 phút)
```

### Card muốn pitch nhất

- Card số: 1 (phản hồi đánh giá OTA Vinpearl) — *đây là lựa chọn lúc làm CP2 cá nhân*
- Vì sao (lúc đó): Đã đào sâu ở Day02 trước, có số phút và năm bước rõ; dễ nói boundary người duyệt.
- Câu hỏi muốn nhóm phản biện: Nếu chỉ dùng mẫu SOP theo chủ đề, không dùng AI, liệu có kéo từ khoảng mười lăm phút xuống dưới năm phút không?
- Sau CP3: Nhóm chọn bài ngâm cuốc Xanh SM của Lâm. Card #2 (gắn nhãn hủy) của mình được ghép vào tầng hậu kiểm. Vinpearl bị loại vì không có quyền OTA trong lab.

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Mốc mười lăm phút có thể chỉ nhớ miệng, chưa bấm giờ từng bước | Đồng ý một phần | Giữ khoảng mười hai đến mười lăm phút như bài trước, nhưng tách phút từng bước và ghi là ước lượng, CP4 sẽ hỏi lại người thật |
| Đang nói nghẽn ở cả bước 2, 3 và 4, chưa chốt một bước chính | Đồng ý | Chốt nghẽn chính là bước soạn thư khoảng năm phút; đọc và tra SOP là nghẽn phụ |
| Gợi ý cho máy tự đăng OTA hoặc tự gửi voucher | Không đồng ý | Giữ ranh giới: chỉ soạn nháp, CSKH duyệt; không tự đăng, không hứa bồi thường ngoài SOP |
| Metric mới đo tốc độ, chưa nói chất lượng giọng và đúng SOP | Đồng ý | Thêm điều kiện mọi bản gửi đều có người duyệt; sau này ở Problem Statement sẽ ghi rõ không được hứa ngoài SOP |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| **Pitch Problem Card** | Trình bày 3 card: Vinpearl trả lời review OTA (#7), gắn nhãn nguyên nhân hủy chuyến Xanh SM (#8), tóm tắt tiền sử Vinmec (#9). Lúc đầu muốn đẩy Vinpearl vì đã có khung từ bài Day02 trước. | Card #8 được Long nối với bài ngâm cuốc của Lâm thành luồng trước–sau chuyến. Vinpearl vào shortlist rồi bị loại vì nhóm không có quyền OTA. |
| **Phản biện bài của bạn khác** | Câu hỏi tôi đã đặt:<br>• Cho Thành (#4 PR): *'Thời gian chờ review kéo dài 1–2 ngày chủ yếu do Senior bận chứ không hẳn do thiếu mô tả PR, đo lường tác động thực tế thế nào?'*<br>• Cho Tùng (#10 QA Pancake): *'Ngành dược có rủi ro sức khỏe rất cao, nếu AI bỏ sót lỗi sai liều lượng của saler dẫn đến đơn hàng xuất đi thì hậu quả pháp lý thế nào?'* | Hai câu được ghi trong bảng pitch mục 2.1. Nhóm thận trọng hơn với bài thuần kỹ thuật nội bộ và bài dược nặng pháp lý. |
| **Nhận phản biện** | Câu hỏi tôi nhận được:<br>• Từ Lâm (bài Vinpearl): *'Nhóm sinh viên bên ngoài không có quyền truy cập hệ thống quản trị OTA của Vinpearl, tiêu chuẩn giọng văn Vinpearl lấy thước đo nào để định lượng?'*<br>• Từ Long (bài #8): *'Bài toán này gắn rất chặt với bài toán ngâm cuốc của Lâm, hai bài có thể kết hợp thành luồng trước chuyến và sau chuyến không?'*<br>• Từ Thành (bài Vinmec): *'Dữ liệu EMR thuộc nhóm bảo mật y tế nhạy cảm cao nhất, nhóm lấy dữ liệu thật để kiểm thử trong lab kiểu gì?'* | Tôi đã sửa: bỏ bảo lưu Vinpearl làm candidate chính; đồng ý ghép card gắn nhãn vào nửa sau của Candidate #1; không đẩy Vinmec tiếp vì rào cản dữ liệu. |
| **Gom cluster / cây OST** | Cùng Lâm và Thành xếp #1, #3, #8 vào cluster A (Mobility). Nhắc Opportunity C trên cây OST: bộ phận vận hành cần đối soát GPS và chat để phân loại đúng nguyên nhân hủy, không lội log thủ công; gạch ý chatbot tự phạt tài xế. | Cluster A thắng. Opportunity C giữ đúng pain gắn nhãn của mình, không đội lốt thành giải pháp. |
| **Chọn candidate problem** | Ban đầu nghiêng Vinpearl. Sau phản biện về quyền truy cập, mình chấm lại và ủng hộ Candidate #1. Nhóm đồng thuận 5/5. | Candidate #7 Vinpearl đạt 24/35 và bị loại. Đóng góp của mình vào đề tài chung nằm ở tầng hậu kiểm gắn nhãn. |
| **Kiểm chứng / research** | Phụ trách chính bảng research CP4: Uber Project RADAR, Grab Graph-based Anomaly Detection, Zendesk AI Dispute Routing. Tự mở từng link, ghi rõ giải bước nào trong quy trình và khoảng trống còn lại. | Mục 3.3 `group_report.md` dùng 3 nguồn này. Bài học chung: Rule cứu khách tức thì, AI chỉ hậu kiểm, con người duyệt phạt (HITL). |
| **Quy trình nhóm** | Hỗ trợ Tùng vẽ quy trình trước/sau. Góp ý tầng 2: AI gom GPS + chat rồi đưa CSKH duyệt; khi AI lỗi thì fallback giữ quyền lợi khách và đẩy ticket thô. | Sơ đồ Mermaid mục 4.2 có HITL và Fallback. Boundary: AI không tự phạt, không tự hoàn tiền. |
| **Problem Statement** | Không viết chính (Lâm / Long phụ trách). Đọc v0 và góp ý: tách rõ Rule cứu khách với AI hậu kiểm; bổ sung metric thời gian thẩm định CSKH. | v1 thêm actor CSKH và metric vận hành, khớp insight research và snapshot chuyên viên vận hành. |
| **Mức can thiệp AI** | Thảo luận với Thành: ủng hộ **Workflow**, phản đối Agent. Dẫn research Uber/Grab đều giữ người trong vòng xử lý đối tác lái xe. | Nhóm chọn Workflow (Rule tầng 1 + AI Workflow tầng 2). |
| **Quyết định** | Đồng ý **Not Yet** vì Viability cao (Nghị định 13/2023/NĐ-CP, không có API GSM). Góp ngưỡng dừng: nếu false positive phạt oan > 5% hoặc không che được PII thì dừng module AI, chỉ giữ Rule. | Quyết định Not Yet + pilot Staging 4 tuần được ghi ở mục 8. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **CP1 Scan** | Hỏi gợi ý thêm actor quanh các pain Vingroup đã tự scan. | Gợi ý các góc trưởng ca, tài xế, cư dân, trưởng showroom — đỡ trùng một quy trình. | Tách Vinpearl thành nhiều dòng; đẩy chatbot tự trả lời OTA. | Gộp lại một quy trình một dòng; bỏ solution trá hình; chỉ giữ ý có người thật chịu pain. |
| **CP2 Problem Card** | Đưa card Vinpearl cho AI đóng vai PM hoài nghi phản biện. | Chỉ ra bottleneck đang ôm nhiều bước và metric thiếu chất lượng. | Gợi ý tự đăng OTA hoặc tự gửi voucher hoàn tiền. | Chốt nghẽn chính ở bước soạn thư khoảng 5 phút; giữ boundary người duyệt trước khi gửi. |
| **CP4 Research** | Tìm case tương tự phát hiện gian lận gọi xe / định tuyến khiếu nại. | Gợi ý từ khóa Uber Project RADAR, Grab graph anomaly, Zendesk AI. | Đưa link cũ hoặc gom sai phạm vi (payment fraud khác bài ngâm cuốc cục bộ). | Tự mở từng link engineering blog; viết lại cột “giải bước nào” cho đúng quy trình Xanh SM của nhóm; không copy nguyên đoạn marketing. |
| **CP5 Quy trình** | Nhờ chuyển mô tả hai tầng Rule + AI sang cú pháp Mermaid. | Sinh nhanh khung flowchart. | Hay gộp “đổi xe cho khách” với “phạt tài xế” thành một bước AI duy nhất. | Tách lại tầng 1 Rule và tầng 2 HITL; bổ sung nhánh Fallback khi AI lỗi. |
| **CP5–6 Problem Statement** | Nhờ chỉ ra lỗ hổng v0, không để AI viết lại thay. | Nhắc v0 đang ôm cả hành khách và trách nhiệm tài xế vào một mối. | Đôi khi đề xuất Agent tự hoàn tiền ví. | Giữ góp ý tách AI intervention về khâu hậu kiểm; boundary không tự phạt / không tự trừ tiền. |
| **CP6 Mức can thiệp / quyết định** | Hỏi nhanh vì sao không chọn Rule thuần hoặc Agent. | So được rủi ro phạt oan với rủi ro over-automation. | Hay nghiêng “Go ngay” nếu chỉ nhìn Value. | Giữ kết luận **Not Yet** vì nhóm sinh viên không có quyền dữ liệu GSM. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe Lâm pitch bài tài xế Xanh SM ngâm cuốc, mình thấy ngay độ “sờ được”: Ocean Park, chờ map, mất voucher — đúng chuyện cả nhóm từng gặp khi đi học. So với card Vinpearl mình mang lên, bài của Lâm dễ hỏi người thật trong buổi lab hơn nhiều. Nghe Thành nói về viết PR và đọc log thì đúng pain kỹ thuật, nhưng impact nằm nội bộ team dev nên khó thành bài chung. Bài QA Pancake của Tùng có số phút rõ nhưng ngành dược nặng pháp lý. Bài siêu thị của Long gần đời sống nhưng baseline và độ sẵn sàng dùng AI còn mỏng. Điểm mình ấn tượng nhất là chính card gắn nhãn hủy chuyến của mình (#8) được Long chỉ ra có thể ghép với bài ngâm cuốc: trước chuyến cứu khách, sau chuyến hỗ trợ vận hành phân loại. Mình học được một tiêu chí thực dụng: candidate thắng không phải bài mình chuẩn bị kỹ nhất từ trước, mà bài nhóm tiếp cận được bằng chứng và có thể hội tụ trong buổi học.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, và bị khá rõ ngay đầu CP3 khi vừa chọn hướng Xanh SM. Lâm vừa nêu pain ngâm cuốc, gần như ngay lập tức cả nhóm (kể cả mình) buột miệng bàn giải pháp: *'Hay mình làm AI phát hiện xe đứng im rồi tự hủy chuyến, tự khóa tài xế, tự hoàn voucher?'*. Mình lúc đó còn nghĩ tầng gắn nhãn của mình sẽ thành “AI tự gắn nhãn và tự phạt”. Không khí đang nghiêng về một con Agent thật ngầu. May là Thành phản biện ngay trên bảng pitch: *'Nếu chỉ dựa vào GPS đứng im 3 phút thì làm sao phân biệt tài xế cố tình ngâm với tài xế kẹt đèn đỏ hoặc hầm mất sóng?'*. Câu đó kéo cả nhóm dừng lại. Chúng tôi mở lại cây OST và gạch bỏ các ý solution đội lốt: chatbot tự hủy–hoàn tiền, model tự khóa tài khoản, bản đồ 3D tự tìm đường. Nhóm nhận ra nhu cầu cốt lõi của khách lúc đó chỉ là **đổi xe nhanh và không mất mã giảm giá**, còn việc xử lý trách nhiệm tài xế phải để người duyệt. Cách xử lý cụ thể: tách đôi bài toán — Tầng 1 dùng Rule cứu khách; Tầng 2 mới dùng AI Workflow tóm tắt GPS/chat cho CSKH. Mình cũng sửa lại kỳ vọng về card #8: không còn là AI tự kết luận, mà là hỗ trợ người gắn nhãn hậu kiểm.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có, và lần đổi ý lớn nhất của mình không phải về kỹ thuật Rule/AI mà về **candidate mình muốn bảo vệ**. Ở CP2 mình chọn pitch Vinpearl vì đã deep-dive ở bài trước, có sẵn số phút và boundary HITL. Sang CP3, Lâm hỏi thẳng: nhóm sinh viên lấy quyền hệ thống OTA ở đâu, và “giọng văn Vinpearl” đo bằng gì? Thành hỏi thêm card Vinmec thì EMR lấy data thật kiểu gì trong lab? Mình trả lời không được. Cùng lúc Long hỏi bài gắn nhãn hủy (#8) của mình có ghép được với ngâm cuốc của Lâm không. Lúc đầu mình vẫn muốn giữ Vinpearl vì “đã làm nhiều”. Nhưng nhìn bảng chấm điểm và rào cản dữ liệu, mình chấp nhận Candidate #7 chỉ được 24/35 và bị loại là đúng. Mình đổi từ tư thế “bảo vệ bài cũ” sang “đóng góp nửa sau của đề tài nhóm”: card gắn nhãn trở thành Opportunity C và tầng AI hậu kiểm trong quy trình chung. Nếu không bị phản biện về quyền truy cập, mình có lẽ vẫn kéo nhóm vào một bài không kiểm chứng nổi trong lab.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Bất ngờ nhất là **tín hiệu phản bác từ phía tài xế**. Trước CP4, góc nhìn của mình (và của khá nhiều khách trong nhóm) là xe đứng im trên map gần như đồng nghĩa gian lận. Snapshot bác tài VF e34 nói về kẹt Cổ Linh và cảnh bị trừ điểm oan làm mình giật mình: nếu tầng gắn nhãn/phạt chỉ nhìn GPS thì đúng là đang tái tạo pain mình từng ghi ở scan cá nhân (tài xế bị trừ điểm sai). Research Uber RADAR và Grab cũng bất ngờ theo hướng khác: họ không “AI tự phạt”, mà giữ Rule/ML phát hiện bất thường rồi **con người trong vòng quyết định**. Zendesk thì mạnh ở intent routing nhưng tách khỏi telemetry GPS — đúng khoảng trống nhóm cần tự thiết kế pipeline gọn. Mình bất ngờ vì phần AI mình phụ trách research hóa ra giá trị nhất ở hậu kiểm đọc chat, không phải ở nút cứu khách thời gian thực.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Dù không cầm bút chính, phần khó nhất khi góp ý Problem Statement là **không nhét giải pháp vào câu problem** và **không gộp hai actor khác nhu cầu vào một metric**. Bản v0 nghiêng về hành khách. Sau kiểm chứng phải thêm CSKH và metric phạt nhầm dưới 5%. Mỗi lần góp ý mình vẫn hay buột “dùng AI để phân loại…”, rồi phải tự xóa và chỉ giữ việc đang đau: chờ quá lâu, mất voucher, đọc chat thủ công 3–4 phút/ticket. Khó ở chỗ phải chấp nhận AI intervention point nằm ở hậu kiểm — chỗ ít “ngầu” hơn nút đổi xe — nhưng mới đúng chỗ AI đọc ngữ cảnh tốt, còn chỗ cứu khách để Rule làm.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, mình sẽ **không bám Vinpearl quá lâu ở CP3**. Card pitch chính ngay từ đầu nên là gắn nhãn hủy Xanh SM (#8), vì cùng domain với Lâm và dễ hội tụ. Thứ hai, mình sẽ phản biện mạnh hơn ngay từ Assumption Map về **Viability dữ liệu**: hỏi sớm ai có quyền GPS/chat production, thay vì research xong mới nhận ra nhóm không có API GSM rồi mới Not Yet. Thứ ba, ngoài desk research mình sẽ xin tham gia ít nhất một cuộc phỏng vấn tài xế trực tiếp, để không chỉ dựa vào snapshot của bạn khác khi bảo vệ boundary HITL.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

1. **Problem:** Hành khách Xanh SM bị tài xế nhận cuốc rồi đứng im hoặc đi ngược hướng, phải chờ lâu, tự hủy và dễ mất voucher; phía vận hành thì mất nhiều phút đọc chat/GPS để phân loại khiếu nại hủy chuyến.
2. **Quy trình:** Hiện tại khoảng 25–35 phút (chờ map, gọi nhắn, chụp màn hình, hủy, gửi ticket). Tương lai tách 2 tầng: Rule phát hiện xe không tiến lại gần sau khoảng 3 phút rồi cho khách đổi xe giữ voucher; AI Workflow gom GPS/chat tạo dự thảo nhãn cho CSKH duyệt.
3. **Metric:** Thời gian thoát cuốc xuống dưới 5 phút; 100% mã ưu đãi được bảo lưu; thời gian thẩm định CSKH xuống dưới 30 giây; tỷ lệ phạt nhầm tài xế dưới 5%.
4. **Boundary:** AI không tự phạt tài xế, không tự trừ/hoàn tiền ví; dữ liệu định danh phải được che mờ trước khi đưa vào pipeline.
5. **Mức can thiệp AI:** **Workflow** (Rule ở tầng cứu khách + AI phân tích ở tầng hậu kiểm), không dùng Autonomous Agent.
6. **Quyết định:** **Not Yet** — pilot 4 tuần trên Staging/Mock Sandbox vì Viability cao (Nghị định 13/2023/NĐ-CP, chưa có quyền DB GSM); nếu false positive vẫn trên 5% hoặc không che được PII thì dừng AI và chỉ giữ Rule.

---

## 7. Tài liệu tham khảo

1. Báo cáo nhóm Ban3: [report/team/group_report.md](../team/group_report.md)
2. Phân công vai trò: [TEAM.md](../../TEAM.md)
3. Uber Engineering (2019), *Project RADAR: Intelligent Early Fraud Detection System with Humans in the Loop*, [https://www.uber.com/blog/project-radar-intelligent-early-fraud-detection/](https://www.uber.com/blog/project-radar-intelligent-early-fraud-detection/)
4. Grab Tech Blog (2021), *Graph-based Prediction Platform for Fraud Detection*, [https://engineering.grab.com/graph-based-prediction-platform](https://engineering.grab.com/graph-based-prediction-platform)
5. Zendesk, *AI for customer service*, [https://www.zendesk.com/service/ai/](https://www.zendesk.com/service/ai/)
6. Chính phủ Việt Nam (2023), *Nghị định số 13/2023/NĐ-CP về Bảo vệ dữ liệu cá nhân*.
7. Google PAIR, *People + AI Guidebook*, [https://pair.withgoogle.com/](https://pair.withgoogle.com/)
8. Anthropic Research (2024), *Building Effective Agents*, [https://www.anthropic.com/research/building-effective-agents](https://www.anthropic.com/research/building-effective-agents)
9. Marty Cagan (SVPG), *The Four Big Risks*.
10. Rob Fitzpatrick, *The Mom Test*.
11. Teresa Torres, *Continuous Discovery Habits — Opportunity Solution Trees*.
12. Bài scan cá nhân Day02 cũ (nhánh PHẠM-TRUNG-KIÊN-03479): [https://github.com/NguyenDucTrung999/VinUni_Codelab_Day02/tree/PH%E1%BA%A0M-TRUNG-KI%C3%8AN-03479](https://github.com/NguyenDucTrung999/VinUni_Codelab_Day02/tree/PH%E1%BA%A0M-TRUNG-KI%C3%8AN-03479)
