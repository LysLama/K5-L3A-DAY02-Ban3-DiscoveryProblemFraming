# Báo cáo cá nhân — Tô Minh Thành

> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Báo cáo cá nhân trên repo nhóm; điền bằng trải nghiệm thật của bạn, không ghi thay người khác.

## 1. Thông tin học viên

* Họ tên: Tô Minh Thành

* MSSV: 2A202603439

* Email trường (không bắt buộc, repo có thể để public): 

* Tên nhóm: Ban3

* Link repo nhóm: https://github.com/LysLama/K5-L3A-DAY02-Ban3-DiscoveryProblemFraming

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.


| \# | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) | 
| ----- | ----- | ----- | ----- | ----- | 
| 1 | Tốn thời gian | Khi chuẩn bị mở PR, tôi muốn giải thích rõ lý do thay đổi và cách kiểm thử, để reviewer hiểu mục đích mà không phải hỏi lại. | Junior Dev, Senior Dev | Quy trình được ước lượng khoảng 25 phút tổng cộng, trong đó khoảng 20 phút đọc lại ngữ cảnh và soạn mô tả; tần suất 4-5 PR/tuần. Chưa ghi nhật ký thời gian hoặc nguồn cho nhận xét của Senior. | 
| 2 | Lặp lại | Khi hoàn thành một API CRUD cơ bản, tôi muốn bao phủ các nhánh quan trọng bằng unit test mà không phải lặp lại nhiều thao tác viết mã, để giảm nguy cơ hồi quy. | Dev | Ước lượng 30-45 phút để viết test cho luồng cơ bản; chưa ghi loại API, số lần quan sát hoặc cách bấm giờ. | 
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi điều tra lỗi được báo trong Sentry/Kibana, tôi muốn xác định được đoạn log và bước tiếp theo cần kiểm tra, để rút ngắn thời gian chẩn đoán. | Dev, QA | Ước lượng 20-30 phút/lần và 2-3 lần/ngày trong lúc test; cần ghi khoảng thời gian và mẫu lỗi đã quan sát. | 
| 4 | Pain từ người khác | Khi QA báo một bug, tôi muốn nhận đủ bước tái hiện và dữ liệu liên quan, để có thể kiểm tra lỗi mà không phải hỏi lại nhiều lần. | Dev, QA | Con số 30% chưa có mẫu số, khoảng thời gian hay nguồn ticket đi kèm; cần bổ sung các thông tin đó hoặc bỏ tỷ lệ. | 
| 5 | Lặp lại | Khi chuẩn bị Daily Standup, tôi muốn nhớ chính xác các việc đã làm hôm trước, để cập nhật tiến độ rõ ràng. | Dev | Ước lượng 5-10 phút mỗi sáng để xem lại Git/Jira; chưa ghi nhật ký thời gian. | 
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi phải sửa một phần trong project cũ, tôi muốn hiểu các luồng liên quan trước khi thay đổi, để tránh làm hỏng hành vi hiện có. | Junior Dev | Ước lượng 3-4 giờ cho một lần tìm hiểu; cần nêu trường hợp cụ thể và phân biệt thời gian đọc với thời gian chờ/hỏi người khác. | 
| 7 | Lặp lại | Khi API thay đổi, tôi muốn frontend có thông tin endpoint, tham số và hành vi chính xác, để tích hợp mà không phải chờ hoặc sửa do tài liệu sai. | Backend Dev, Frontend Dev | Chưa có số lần thiếu tham số hoặc ví dụ ticket/comment; cần bổ sung bằng chứng cụ thể nếu giữ pain này. | 
| 8 | Tốn thời gian | Khi bắt đầu làm việc trên một dự án mới, tôi muốn hoàn tất cài đặt môi trường trong thời gian dự đoán được, để có thể bắt đầu xử lý task mà không mắc kẹt vì xung đột phiên bản. | Junior Dev mới onboarding | Ước lượng mất 1-2 ngày đầu; chưa tách thời gian thao tác thực tế khỏi thời gian chờ hoặc thời gian xử lý việc khác. | 

**Nếu có dùng AI để gợi ý thêm:** Tôi đưa bối cảnh "Tôi là Junior Software Engineer mới ra trường, làm việc theo mô hình Agile/Scrum" và nhờ AI gợi ý.

* Giữ lại: Ý #4 (Ticket bug từ QA thiếu thông tin) và #6 (Đọc legacy code). Rất đúng thực tế khi mới đi làm.

* Bỏ: Ý "AI tự động fix bug giùm Dev". Vì nó quá rủi ro (Feasibility/Viability thấp), chưa phù hợp với năng lực kiểm soát của junior dev.

## 3. Top 3 Problem Cards + quy trình nháp (CP2)


| Rank | Problem | Vì sao chọn | Điều còn chưa chắc | 
| ----- | ----- | ----- | ----- | 
| 1 | Viết mô tả Pull Request (#1) | Quy trình chuẩn bị PR có thể mô tả rõ và có đầu vào cụ thể (Git diff, Jira ticket). Tần suất và thời gian hiện mới là ước lượng, cần kiểm tra lại. | Liệu thông tin trong diff và Jira có đủ để giải thích lý do nghiệp vụ, hay chỉ tạo ra bản diễn giải thay đổi code? | 
| 2 | Sinh khung Unit Test (#2) | Có tính lặp lại cao, tiết kiệm nhiều thời gian cho Dev. | AI có sinh ra test case ảo tưởng (hallucinate) sai logic nghiệp vụ không? | 
| 3 | Tóm tắt lỗi từ Log (#3) | Giảm thời gian debug đáng kể. | Việc đẩy log (có thể chứa dữ liệu nhạy cảm của khách) lên AI có vi phạm bảo mật không? | 

### Problem Card #1: Viết mô tả Pull Request (PR Description)

| Trường | Nội dung | 
| ----- | ----- | 
| Job Story | Khi chuẩn bị gửi thay đổi để review, tôi muốn trình bày lý do, phạm vi và cách kiểm thử rõ ràng, để reviewer đánh giá được thay đổi mà không phải hỏi lại thông tin cơ bản. | 
| Actor | Junior Software Engineer | 
| Thời điểm / bối cảnh | Ngay sau khi push code lên branch và chuẩn bị tạo PR trên GitHub/GitLab. | 
| Quy trình hiện tại (5 bước) | 1\. Push branch · 2. Tạo Draft PR · 3. Đọc lại Jira và Git diff để nhớ bối cảnh · 4. Viết description theo template (Context, Changes, How to test) · 5. Kiểm tra description, chuyển PR sang trạng thái sẵn sàng review và gửi reviewer. | 
| Bottleneck | Theo ước lượng trong quy trình nháp, bước 3 (đọc lại Jira và diff) mất 8 phút, bước 4 (soạn mô tả) mất 12 phút; tổng 20 phút. Cần đo lại để xác nhận đây thực sự là phần tốn thời gian nhất. | 
| Impact | Với 4-5 PR/tuần và khoảng 20 phút đọc ngữ cảnh + soạn mô tả mỗi PR, phần việc này tương đương khoảng 80-100 phút/tuần (phép tính từ các ước lượng hiện có, chưa phải số đo độc lập). Thời gian chờ review 1-2 ngày chưa được chứng minh là do mô tả thiếu context, nên không dùng làm impact đã xác nhận. | 
| Success metric | Mục tiêu thử nghiệm: giảm thời gian đọc ngữ cảnh + soạn mô tả từ baseline ước lượng khoảng 20 phút xuống dưới 5 phút/PR. Ghi thời gian từng PR trước/sau; đồng thời đếm PR bị yêu cầu bổ sung context trên tổng PR được review. Tỷ lệ dưới 10% là target tạm thời; cần đo baseline và xác nhận target phù hợp. | 
| Phương án không dùng AI | Dùng PR template có các mục Context, Changes, How to test cùng checklist reviewer. Template có thể cải thiện độ đầy đủ nhưng người viết vẫn phải cung cấp nội dung; cần so sánh với quy trình hiện tại trước khi kết luận mức giảm thời gian. | 
| Giả thuyết về AI | Nếu được phép theo chính sách dữ liệu, AI có thể dùng diff và nội dung ticket đã được kiểm tra để soạn bản nháp. AI không được tự suy diễn business context không có trong input; Dev xác minh và chịu trách nhiệm nội dung cuối. | 
| Cảm nhận nhanh | Workflow (AI làm 1 bước tổng hợp text, người phải duyệt). | 

Quy trình nháp hiện tại:

```
HIỆN TẠI — 25 phút

[1 Push code lên nhánh: 1'] → [2 Tạo Draft PR trên GitHub: 1'] 
→ [3 Đọc lại Jira + Git diff: 8'] ← BOTTLENECK
→ [4 Soạn mô tả PR: 12'] ← BOTTLENECK
→ [5 Kiểm tra mô tả, chuyển sang sẵn sàng review: 3']

```

### Problem Card #2: Gen khung Unit Test

| Trường | Nội dung | 
| ----- | ----- | 
| Job Story | Khi hoàn thành một API CRUD cơ bản, tôi muốn kiểm tra được các nhánh quan trọng mà không phải lặp lại nhiều thao tác viết mã, để giảm nguy cơ hồi quy. | 
| Actor | Backend Developer | 
| Thời điểm / bối cảnh | Khi viết xong logic của hàm/API, chuẩn bị commit code. | 
| Quy trình hiện tại (4 bước) | 1\. Đọc lại hàm vừa viết · 2. Nghĩ ra các test cases (Happy case, Bad case, Edge case) · 3. Gõ code setup mock data và assert · 4. Chạy thử và fix lỗi test. | 
| Bottleneck | Bước 3 (Gõ boilerplate code để setup mock và assert): mất 20-30 phút/hàm. | 
| Impact | Dev lười viết test vì tốn thời gian rập khuôn, dẫn đến code coverage thấp, dễ lọt bug ra production. | 
| Success metric | Quy trình nháp hiện cộng thành 35' cho cả 4 bước, còn 20-30' là ước lượng riêng cho bước viết boilerplate. Cần đo cùng một phạm vi trước/sau; chưa chốt target thời gian cho toàn quy trình. Theo dõi coverage riêng bằng công cụ dự án, chưa đặt target coverage khi chưa có baseline. | 
| Phương án không dùng AI | Dùng test template, snippet hoặc helper của dự án để giảm phần boilerplate; vẫn cần người viết chọn case, viết assertion và xác minh test. | 
| Giả thuyết về AI | AI đọc code của hàm, tự suy luận các nhánh logic (if/else) và tự sinh ra các test case sử dụng thư viện test chuẩn của project. | 
| Cảm nhận nhanh | Workflow (AI như một trợ lý viết nháp code). | 

Quy trình nháp hiện tại:

```
HIỆN TẠI — 35 phút

[1 Đọc lại hàm: 5'] → [2 Xác định test case: 5'] 
→ [3 Viết code Unit Test + Mock: 20'] ← BOTTLENECK
→ [4 Chạy thử và sửa lỗi: 5']

```

### Problem Card #3: Phân tích Log lỗi (Error Log Analysis)

| Trường | Nội dung | 
| ----- | ----- | 
| Job Story | Khi nhận báo cáo lỗi, tôi muốn xác định được dấu vết liên quan và hướng điều tra tiếp theo, để giảm thời gian tìm nguyên nhân có thể kiểm chứng. | 
| Actor | Developer / On-call Engineer | 
| Thời điểm / bối cảnh | Khi có alert từ hệ thống hoặc QA báo bug kèm link log Kibana/Sentry. | 
| Quy trình hiện tại (4 bước) | 1\. Mở tool log · 2. Filter theo Request ID · 3. Đọc stack trace từ dưới lên trên để tìm file code bị lỗi · 4. Xác định nguyên nhân. | 
| Bottleneck | Bước 3 (Đọc stack trace hàng ngàn dòng chứa toàn thư viện không liên quan): mất 15-20 phút. | 
| Impact | Bug rò rỉ lâu, tốn thời gian debug, áp lực khi on-call. | 
| Success metric | Đo thời gian từ lúc bắt đầu điều tra đến khi xác nhận được nguyên nhân cho một tập lỗi tương đương; sau khi có baseline mới đặt target giảm 50%. Không dùng MTTR thay cho thời gian chẩn đoán nếu chưa đo thời gian khắc phục/khôi phục đầy đủ. | 
| Phương án không dùng AI | Gắn thêm nhiều log rõ ràng hơn trong code (phụ thuộc vào ý thức lúc code). | 
| Giả thuyết về AI | Chỉ khi chính sách dữ liệu cho phép, AI có thể hỗ trợ tóm tắt log đã lọc/ẩn dữ liệu nhạy cảm, nêu dấu vết liên quan và giả thuyết điều tra kèm căn cứ. Kết quả không được xem là nguyên nhân đã xác nhận nếu chưa được Dev kiểm tra. | 
| Cảm nhận nhanh | Rule (Filter log) + AI Workflow (giải thích). | 

Quy trình nháp hiện tại:

```
HIỆN TẠI — 25 phút

[1 Mở Sentry/Kibana: 2'] → [2 Lọc đúng Request ID: 3'] 
→ [3 Đọc và trace log: 15'] ← BOTTLENECK
→ [4 Xác định file lỗi: 5']

```

### Card muốn pitch nhất

* Card số: **#1 (Viết mô tả Pull Request)**

* Vì sao: Quy trình có đầu vào có thể xác định (Git diff và nội dung ticket) và đầu ra là bản mô tả để người viết kiểm tra. Tuy nhiên, đầu vào có thể chứa mã nguồn hoặc thông tin nội bộ; dạng đầu ra là văn bản không tự làm cho việc gửi dữ liệu ra dịch vụ AI trở nên an toàn. Chỉ thử với công cụ và dữ liệu được tổ chức cho phép.

* Câu hỏi muốn nhóm phản biện: Có cách nào để AI tự fetch dữ liệu từ Jira và Github mà Dev không phải copy-paste thủ công vào prompt không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì | 
| ----- | ----- | ----- | 
| Diff lớn hoặc nhiều file có thể khiến bản tóm tắt thiếu trọng tâm; chưa kiểm tra được một ngưỡng dòng cụ thể. | Đồng ý | Chưa đặt ngưỡng 500 dòng khi chưa thử nghiệm. Pilot cần ghi nhận kích thước diff và lỗi đầu ra; PR vượt phạm vi pilot sẽ được viết thủ công. | 
| AI có thể tạo mô tả nghe hợp lý nhưng sai mục đích nghiệp vụ. | Đồng ý | Người viết phải đối chiếu bản nháp với ticket và diff trước khi cập nhật mô tả PR. TODO trong nội dung không bảo đảm người dùng đã kiểm tra, nên cần checklist review và không coi đây là biện pháp kỹ thuật ngăn gửi sai. | 


## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm | 
| ----- | ----- | ----- | 
| Pitch Problem Card | Đưa candidate viết mô tả Pull Request, sinh unit test và phân tích log lỗi; candidate nhóm tôi muốn pitch nhất là viết PR description. | Ba candidate được ghi trong bảng pitch CP3 của báo cáo nhóm; nhóm chọn ý tưởng tài xế nhận chuyến nhưng xe không tiến về điểm đón của Lý Thanh Lâm. |
| Phản biện bài của bạn khác | Hỏi Lý Thanh Lâm: nếu xe đứng im 3 phút thì làm sao phân biệt tài xế cố tình “ngâm cuốc” với kẹt xe hoặc mất sóng trong hầm? | Nêu rủi ro báo nhầm và ảnh hưởng tới tài xế; câu hỏi được ghi trong `group_report.md`, mục 2.1. |
| Nhận phản biện | Phạm Trung Kiên hỏi liệu thời gian chờ review PR 1–2 ngày có thực sự do thiếu mô tả hay do Senior bận; Lý Thanh Lâm hỏi ai chịu trách nhiệm kiểm tra unit test do AI sinh. | Trong candidate PR, không quy kết thời gian chờ review là do mô tả thiếu context; với unit test, cần xác định người chịu trách nhiệm duyệt nội dung AI gợi ý. Xem `group_report.md`, mục 2.1. |
| Gom cluster / cây OST | Được phân công hỗ trợ CP3 cùng Lý Thanh Lâm và Phạm Trung Kiên. | Báo cáo nhóm ghi các cluster về điều phối chuyến, chất lượng vận hành và tổng hợp thông tin; phần đóng góp cá nhân cụ thể trong buổi cần tôi xác nhận. |
| Chọn candidate problem | Tham gia thảo luận và ủng hộ candidate của Lý Thanh Lâm theo kết quả nhóm ghi trong báo cáo. | Candidate được chốt là tình huống hành khách không biết xử lý thế nào khi chuyến đã ghép nhưng xe không tiến về điểm đón; xem `group_report.md`, mục 1–2. |
| Kiểm chứng / research | Theo `TEAM.md`, tôi được phân công hỗ trợ Đoàn Gia Long ở CP4; hồ sơ nhóm hiện có interview snapshots và bảng tổng hợp. | `group_report.md`, mục 3.2. Báo cáo chưa ghi rõ phần snapshot/phỏng vấn nào do cá nhân tôi thực hiện. Ngoài ra, bảng tổng hợp ghi 3 hành khách và 2 tài xế nhưng Snapshot 5 mô tả chuyên viên vận hành; cần nhóm xác minh lại trước khi nộp. |
| Quy trình nhóm | Theo phân công trong `TEAM.md`, tôi không phải người chính vẽ quy trình CP5. Tôi góp ý rủi ro tài xế bị kết luận nhầm từ dấu hiệu GPS. | Báo cáo nhóm mô tả Rule cho khâu hỗ trợ khách và Workflow AI cho hậu kiểm; xem `group_report.md`, mục 4. |
| Problem Statement | Được phân công phụ trách CP6 Problem Statement v1 cùng với các deliverable khác. | Bản v1 tách actor hành khách và CSKH, đặt AI ở khâu hậu kiểm, kèm boundary; xem `group_report.md`, mục 7. |
| Mức can thiệp AI | Theo `TEAM.md`, phụ trách ma trận, AI Canvas, PAIR và bộ eval 10 cặp. | Bằng chứng trong `group_report.md`, mục 6–7 và [`cp6-eval-set-10-pairs.md`](../assets/cp6-eval-set-10-pairs.md). Các nội dung là sản phẩm nhóm; xác nhận phần nào do tôi trực tiếp soạn trước khi nộp. |
| Quyết định | Theo phân công, hỗ trợ Lý Thanh Lâm đánh giá rủi ro và ngưỡng dừng. | Quyết định cuối là Not Yet, pilot Staging/Mock 4 tuần; xem `group_report.md`, mục 8 và `TEAM.md`. |

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ----- | ----- | ----- | ----- | ----- |
| CP1 Scan | Nhờ gợi ý nỗi đau của lập trình viên mới. | Gợi ý đúng các pain point về docs, log, setup môi trường. | Gợi ý AI tự động fix bug. | Gạt bỏ vì hiểu rằng AI tự fix bug rất nguy hiểm và ngoài tầm kiểm soát của junior. |
| CP2 Problem Card | Đóng vai Senior Dev chỉ trích bài toán viết PR. | Cảnh báo về việc AI có thể làm Dev phụ thuộc, mất khả năng giao tiếp kỹ thuật. | Đề xuất giải pháp là cấm dùng AI. | Tôi không cấm, mà coi AI như công cụ "dự thảo", sửa lại quy trình để con người làm chủ văn bản cuối. |
| CP4 Research | Theo ghi chú cá nhân, dùng AI tìm công cụ liên quan đến PR description. | Gợi ý `pr-agent` và `openai-pr-reviewer`. | Các nhận định về tính năng chưa được xác minh trong ghi chú này. | Cần mở tài liệu chính thức và chỉ giữ thông tin đã kiểm tra; phần research này thuộc candidate cá nhân, không phải bằng chứng cho candidate Xanh SM. |
| CP5 Quy trình | Ghi chú hiện có nói AI được dùng để tạo sơ đồ Mermaid cho quy trình PR. | Giúp tạo nhanh cấu trúc sơ đồ. | Đã gộp bước lấy Git diff và Jira thành một. | Yêu cầu tách hai nguồn dữ liệu. Đây là quy trình của candidate cá nhân; CP5 nhóm về chuyến xe cần ghi đúng việc AI bạn thực sự đã làm. |
| CP5–6 Problem Statement | Ghi chú hiện có nói AI hỗ trợ rút gọn phần Impact cho candidate PR. | Giúp câu chữ ngắn và rõ hơn. | Làm mất bối cảnh của reviewer. | Bổ sung lại bối cảnh theo nhận định cá nhân. Với bài nhóm, chỉ ghi việc sử dụng AI nếu thực sự đã dùng. |
| CP6 Mức can thiệp / quyết định | Ghi chú hiện có nói AI hỗ trợ so sánh các mức can thiệp cho candidate PR. | Giúp liệt kê ưu/nhược điểm. | Có xu hướng đề cao Agent. | Đối chiếu với quy trình thật và chọn mức có căn cứ. Cập nhật nhật ký riêng cho bài nhóm nếu bạn đã dùng AI ở CP6. |

## 6. Reflection (CP7)

6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?
Tôi nhận ra rào cản lớn nhất khi giải quyết vấn đề bằng AI trong thực tế không chỉ nằm ở kỹ thuật, mà nằm ở quyền truy cập dữ liệu và quy định ngành. Ví dụ, bài toán y tế (EMR) của Tùng hay bài review OTA Vinpearl của Kiên rất có giá trị, nhưng sinh viên từ bên ngoài không thể lấy được dữ liệu thật để kiểm chứng (rủi ro Viability). Trong khi đó, bài toán gọi xe Xanh SM của Lâm lại cực kỳ sát sườn, nhóm dễ dàng đóng vai hành khách trải nghiệm hoặc ra ngã tư phỏng vấn trực tiếp tài xế. Một problem tốt phải là problem mà nhóm có khả năng tiếp cận và kiểm chứng.

6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?
Có. Lúc mới chọn đề tài Xanh SM, ý định ban đầu của nhóm là nhắm thẳng vào giải pháp trừng phạt: "Làm một mô hình AI dự đoán tài xế nào hay ngâm cuốc để khóa tài khoản tự động". Lúc đó, nhóm chỉ đứng dưới góc độ bức xúc của hành khách. Tuy nhiên, tôi và Long đã kịp thời đặt câu hỏi: "Nếu dựa vào GPS đứng im 3 phút để tự động phạt, lỡ tài xế kẹt đèn đỏ thì sao?". Nhóm chợt nhận ra mình đang quy chụp vấn đề nên đã dừng ngay việc nghĩ thuật toán để tiến hành phỏng vấn tài xế, từ đó mới tìm ra được bản chất thật của sự việc.

6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.
Có, tôi đã thay đổi hoàn toàn kỳ vọng về metric khi pitch bài toán cá nhân (AI viết PR). Ban đầu, tôi dùng thời gian chờ review (1-2 ngày) làm pain point và kỳ vọng AI viết PR tốt sẽ giảm con số này. Tuy nhiên, Kiên đã phản biện cực kỳ thực tế: "Thời gian chờ lâu thường do Senior bận fix bug hoặc họp, chứ không hẳn do PR thiếu mô tả. Ông đo lường tác động đó kiểu gì?". Tôi nhận ra mình đã mắc lỗi quy kết nhân quả sai (correlation vs causation). Do đó, tôi đổi ý, sửa lại Impact và chỉ tập trung đo lường đúng phạm vi hẹp: "giảm thời gian soạn thảo của Junior" và "giảm số comment yêu cầu bổ sung context".

6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?
Điều làm tôi bất ngờ nhất là buổi phỏng vấn bác tài xế Xanh SM. Ban đầu cả nhóm đinh ninh rằng việc xe đứng im là 100% do tài xế gian lận (chờ khách hủy để khỏi bị trừ điểm). Nhưng bác tài đã cung cấp một góc nhìn trái ngược hoàn toàn: có những nút giao như Cổ Linh kẹt cứng 4 nhịp đèn đỏ, hoặc định vị bị dội sóng (drift) quanh các tòa nhà cao tầng. Tài xế cũng là nạn nhân và họ mất tới 20 phút gọi tổng đài giải trình để xin không bị phạt oan. Tín hiệu này đã thay đổi hoàn toàn cục diện kiến trúc của nhóm: tuyệt đối không dùng AI/Rule để tự phạt tiền mà bắt buộc phải có bước con người hậu kiểm (HITL).

6.5. Điều khó nhất khi viết Problem Statement là gì?
Điều khó nhất là bóc tách các Actor và định hình đúng Boundary (ranh giới). Ban đầu, Problem Statement v0 của nhóm ôm đồm cả việc cứu khách hàng lẫn xử phạt tài xế vào chung một quy trình. Sau nhiều lần chỉnh sửa, chúng tôi mới tìm ra cấu trúc đúng: tách làm 2 tầng. Tầng 1 chỉ dùng Rule-based (nút bấm) để cứu khách ngay lập tức sau 3 phút. Tầng 2 mới là sân chơi của AI (AI Workflow) để đọc tin nhắn chat hỗ trợ CSKH phân loại nguyên nhân. Việc kiềm chế không đưa AI vào khâu phản ứng tức thời thời gian thực là một quyết định kiến trúc rất khó.

6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?
Nếu làm lại, tôi sẽ phản biện mạnh hơn ở bước CP4 (Kiểm chứng rủi ro Viability). Bài toán lấy log định vị GPS và nội dung tin nhắn chat của hành khách vướng rào cản cực kỳ lớn về Nghị định 13/2023/NĐ-CP bảo vệ dữ liệu cá nhân. Nhóm chỉ thực sự nhận diện rõ rào cản này ở khâu quyết định (CP6), dẫn đến kết quả Not Yet. Tôi nên thúc đẩy nhóm tìm hiểu phương án ẩn danh dữ liệu (PII Masking) hoặc lên kế hoạch dùng dữ liệu giả lập (mock data) ngay từ bước research ban đầu.

**6.7. Hiểu bài:** Nhóm tập trung vào tình huống hành khách bị kẹt khi tài xế đã nhận chuyến nhưng không tiến về điểm đón, đồng thời tránh kết luận tài xế vi phạm chỉ từ GPS đứng im vì nguyên nhân có thể là kẹt xe hoặc lỗi định vị. Sau 3 phút không tiến lại gần và không có cảnh báo tắc đường nghiêm trọng, Rule sẽ cho khách chọn đổi tài xế, giữ giá và voucher; AI không tham gia quyết định giải cứu tức thời. Nếu chuyến bị hủy, AI Workflow tổng hợp chat và dữ liệu hành trình để dự thảo nguyên nhân cùng bằng chứng cho CSKH hậu kiểm. Mục tiêu của nhóm là đưa thời gian thoát cuốc từ 25–35 phút xuống dưới 5 phút, giảm thời gian CSKH xử lý mỗi ticket từ 3–4 phút xuống dưới 30 giây, và giữ tỷ lệ phạt nhầm dưới 5%. AI không được tự phạt tài xế hoặc tự xử lý tiền; CSKH phải duyệt, còn dữ liệu chat và vị trí cần được che thông tin định danh trước khi xử lý. Vì vậy nhóm chọn Workflow kết hợp Rule-based, nhưng quyết định hiện tại là Not Yet: chỉ thử nghiệm 4 tuần trong Staging/Mock Sandbox, rồi mới cân nhắc tích hợp thật.

## 7. Tài liệu tham khảo

* Ghi chú phỏng vấn cá nhân trực tiếp với 3 Senior Software Engineers tại công ty (dữ liệu đã ẩn danh thành Dev A, Dev B, Dev C). Đây là phỏng vấn sâu 1-1, không phải khảo sát. Thời điểm thực hiện: 04/10/2026 - 05/10/2026 thông qua Google Meet. Mục đích phỏng vấn: tìm hiểu kỳ vọng của reviewer khi đọc Pull Request.

Tài liệu chính thức của công cụ CodiumAI PR-Agent. URL: https://github.com/Codium-ai/pr-agent (Ngày truy cập: 08/11/2026).

Tài liệu chính thức của GitHub Copilot for Pull Requests. URL: https://docs.github.com/en/copilot/using-github-copilot/using-github-copilot-for-pull-requests (Ngày truy cập: 08/11/2026).

Hướng dẫn "How to write the perfect pull request" - GitHub Blog (Quy chuẩn viết Pull Request tốt của cộng đồng mã nguồn mở). URL: https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/ (Ngày truy cập: 07/11/2026).