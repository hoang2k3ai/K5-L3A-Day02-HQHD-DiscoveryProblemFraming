# Báo cáo cá nhân — 2A202603469_BuiQuangHuy

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Bùi Quang Huy
- MSSV: 2A202603469     
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: HQHD
- Link repo nhóm: https://github.com/hoang2k3ai/K5-L3A-Day02-HQHD-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại, Pain từ người khác |Khi ứng viên hoặc học viên của chương trình AI Thực chiến VinUni nhắn tin đến Facebook Page hoặc bình luận hỏi về lịch học, nội dung, học phí, đăng ký và hỗ trợ trong quá trình học, tôi muốn hệ thống tập hợp câu hỏi và gợi ý câu trả lời dựa trên thông tin chính thức, để đội ngũ phụ trách phản hồi nhanh, nhất quán và không bỏ sót câu hỏi |Đội tuyển sinh, quản trị Fanpage, điều phối chương trình, ứng viên và học viên |Cần kiểm chứng: xuất số tin nhắn và bình luận hỏi đáp trong 2 tuần; phân nhóm câu hỏi lặp lại; đo thời gian phản hồi trung vị, tỷ lệ bỏ sót và số lần nhân viên phải tra cứu tài liệu. Lấy mẫu 30–50 hội thoại, ẩn dữ liệu cá nhân |
| 2 |Lặp lại, Pain từ ng khác |Khi sắp đến buổi học của chương trình AI thực chiến hoặc có thay đổi lịch học tôi muốn được nhắc tự động về thời gian, hình thức học, địa điểm hoặc link tham gia và nội dung cần chuẩn bị, để không quên lịch, vào lớp muộn hoặc bỏ lỡ thông báo quan trọng |Học viên, điều phối lớp học, giảng viên |Cần kiểm chứng: đối chiếu lịch học và thông báo trong 2–4 tuần; khảo sát số học viên từng quên lịch hoặc vào muộn; đếm số tin nhắn hỏi lại lịch/link học và thời gian điều phối viên dùng để gửi nhắc thủ công |
| 3 |Pain từ người khác,Tốn thời gian |Khi khách hàng là chủ xe viinfast báo lỗi qua nhiều kênh như email, chat và hotline, tôi muốn xem được lịch sử tương tác và trạng thái xử lý trong một nơi, để không yêu cầu khách hàng lặp lại thông tin và không tạo ticket trùng |Nhân viên CSKH, kỹ thuật hỗ trợ, khách hàng |Cần kiểm chứng: lấy mẫu 30 ticket; đếm ticket trùng, số lần khách hàng phải cung cấp lại thông tin và thời gian chuyển giao giữa CSKH và kỹ thuật |
| 4 |Tốn thời gian, Cần đọc, tổng hợp nhiều thông tin |Khi nhận một bug report từ khách hàng hoặc QA, tôi muốn có bản tóm tắt lỗi kèm log, bước tái hiện và thay đổi code liên quan, để xác định nguyên nhân và ưu tiên xử lý nhanh hơn |Backend developer, QA, tech lead, khách hàng |Cần kiểm chứng: chọn 20 ticket lỗi gần nhất; đo thời gian từ lúc nhận ticket đến lúc tái hiện được lỗi; đếm số lượt hỏi bổ sung thông tin và số nguồn log phải mở |
| 5 |Lặp lại, cần tổng hợp nhiều thông tin|Khi bắt đầu ngày làm việc hoặc buổi standup, tôi muốn có bản tổng hợp các task đang làm, pull request đang chờ và blocker từ công cụ quản lý dự án, để cập nhật tiến độ chính xác mà không phải mở nhiều trang |Developer, scrum master, project manage |Cần kiểm chứng: đo thời gian chuẩn bị standup trong 5 ngày; đếm số công cụ phải mở và số blocker bị phát hiện muộn |

**AI gợi ý thêm:** sau khi tự scan 5 ý, Minh hỏi AI và giữ lại ý #1 và #2, và #3. Bỏ ý còn lại vì chưa thấy bài toán cụ thể.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|  
| 1 |Gợi ý trả lời câu hỏi trên Facebook chương trình AI Thực chiến VinUni |Phạm vi cụ thể, câu hỏi có thể lặp lại, dễ thử nghiệm với bộ FAQ và người duyệt, và quen thuộc với bản thân |Số lượng câu hỏi thực tế; quyền truy cập Page/API; mức độ cập nhật của thông tin chính sách, quy định, lịch học, tuyển sinh; tỷ lệ câu hỏi cần người xử lý |
| 2 |Hợp nhất lịch sử hỗ trợ khách hàng đa kênh, tránh ticket trùng |Ảnh hưởng trực tiếp tới trải nghiệm khách hàng và năng suất CSKH; có thể đo tỷ lệ ticket trùng và thời gian tra cứu |Có mã định danh chung giữa email/chat/hotline không; mức độ tích hợp CRM/ticket; quyền truy cập dữ liệu |
| 3 |Nhắc nhở lịch học |Quy trình lặp lại, có lịch và đối tượng nhận rõ, có thể bắt đầu bằng rule/workflow đơn giản |đối tượng nhận rõ; có thể bắt đầu bằng rule/workflow đơn giản	Học viên muốn nhận qua kênh nào; tỷ lệ quên lịch thực tế; dữ liệu lịch có cập nhật kịp thời không |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi ứng viên hoặc học viên đặt câu hỏi qua Messenger hoặc bình luận trên Fanpage chương trình AI Thực chiến VinUni, tôi muốn nhận được câu trả lời gợi ý dựa trên thông tin chương trình đã xác thực, để phản hồi nhanh, nhất quán và không phải tra cứu lại các câu hỏi lặp lạ |
| Actor |Nhân viên trực Fanpage/tư vấn tuyển sinh và hỗ trợ học viên; người hỏi là ứng viên hoặc học viên đã tham gia |
| Thời điểm / bối cảnh |Khi có tin nhắn hoặc bình luận mới hỏi về lịch học, điều kiện tham gia, học phí, nội dung khóa học, thông tin về phụ cấp |
| Quy trình hiện tại (3–7 bước) |1. Kiểm tra Messenger và bình luận  2. Đọc, phân loại và xác định ngữ cảnh câu hỏi  3. Tìm thông tin trong FAQ, tài liệu, bài đăng hoặc hỏi điều phối viên 4. Soạn câu trả lời  5. Kiểm tra tính chính xác, cá nhân hóa và gửi 6. Ghi nhận câu hỏi cần theo dõi |
| Bottleneck (bước nào, mất bao nhiêu phút) |Ở bước thứ 3, việc đối chiếu thông tin, tổng hợp lại nhiều thông tin, khoảng 5p/1 câu  khi chính sách thay đổi|
| Impact (nếu không giải thì sao) |Thời gian phản hồi kéo dài, câu hỏi lặp lại chiếm nhiều thời gian tư vấn |
| Success metric (baseline → target) |Giả định thử nghiệm: thời gian xử lý trung bình 15 -> <= 7m/câu , tỷ lệ trả lời đúng theo tài liệu chính thức >= 95%, 100% câu trả lời liên quan tới học phí/chính sách/phụ câps,....  được người phụ trách duyệt trước khi trả lời |
| Phương án không dùng AI |Lập trình tường minh trả lời dựa trên việc xây dựng FAQ chuẩn, mẫu trả lời theo chủ đề gán nhãn hội thoại |
| Giả thuyết về AI (nếu có) |Ai có thể nhận diện được ý định của câu hỏi, tìm tại liêụ liên quan trong kho tài liệu và đề xuất câu trả lời và kèm nguồn, nhân sự phụ trách sẽ kiểm tra và sửa nếu có sai sót và gửi câu trả lời |
| Cảm nhận nhanh | Worflow: có Ai hỗ trợ gợi ý câu trả lời, người ra quyết định là người phụ trách. Chưa cần tới Agent tự phản hồi |

Quy trình nháp hiện tại:

HIỆN TẠI — 15 phút/câu (ước tính)

[1 Kiểm tra Messenger/comment: 2']
  → [2 Đọc và phân loại: 2']
  → [3 Tra cứu FAQ/tài liệu/hỏi điều phối: 5'] ← 🔴 BOTTLENECK
  → [4 Soạn câu trả lời: 3']
  → [5 Kiểm tra và gửi: 2']
  → [6 Ghi nhận để theo dõi: 1']

🔄 Handoff: Facebook → nhân sự trực Page → nguồn thông tin/điều phối viên → người hỏi

### Problem Card #2


| Trường | Nội dung |
|---|---|
| Job Story | Khi có lịch học sắp đến hoặc có sự thay đổi thông tin về địa điểm, thời gian, nội dung cần chuẩn tôi muốn có thông báo nhắc nhở , để có thể tham gia buổi học một cách tốt nhất |
| Actor |Học viên chương trình Ai thực chiến , điều phối viên lớp học |
| Thời điểm / bối cảnh |Trước mỗi buổi học . ví dụ trước 24h và 1h, hoặc ngay khi có sự thay đổi về thông tin buổi |
| Quy trình hiện tại (3–7 bước) |1. Điều phối viên kiểm tra lịch học chính thức 2.Đối chiếu thay đổi 3. Lấy danh lớp, kênh thông báo 4.Gửi tin nhắn nhắc lịch thủ công tới kênh thông báo của lớp|
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3,4 dễ bỏ sót lớp học khi thay đổi lịch nhiều lớp, hoặc là khi thay đổi sát giờ |
| Impact (nếu không giải thì sao) |Học viên không nhận được thông tin kịp thời , điều phối viên phải nhắc lặp lại. Giả sử 4 buổi/tuần × 20 phút = 80 phút/tuần cho một đầu mối điều phối; chưa tính thời gian học viên bị ảnh hưởng |
| Success metric (baseline → target) |Giả định kiểm thử: Thời gian điều phối nhắc lịch 20->5p/buổi. Tỷ lệ học viên nhận thong báo đúng hạn >= 95%. Tỷ lệ quên lịch, không nhận được thông tin mới nhất giamr >=30% |
| Phương án không dùng AI |Google Calendar/Google Sheets làm lịch chuẩn + thông báo tự động theo mốc giờ bằng công cụ lập lịch hoặc workflow; mẫu tin nhắn cố định và quy tắc gửi lại khi đổi lịch |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | Rule. Chưa cần thiết phải dùng tới AI |

Quy trình nháp hiện tại:
HIỆN TẠI — 20 phút/buổi (ước tính)

[1 Kiểm tra lịch chính thức: 3']
  → [2 Đối chiếu thay đổi, soạn nội dung: 4']
  → [3 Lấy danh sách lớp/kênh nhận: 3']
  → [4 Gửi nhắc thủ công: 5'] ← 🔴 BOTTLENECK
  → [5 Trả lời hỏi lại/xử lý bỏ sót: 5'] ← 🔴 BOTTLENECK

🔄 Handoff: Giảng viên/điều phối → lịch học → nhóm thông báo → học viên


### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:
| Trường | Nội dung |
|---|---|
| Job Story | Khi chủ xe vinfsat muốn báo lỗi qua các kênh email, hotline, ứng dụng tôi muốn xem toàn bộ lịch sử tương tác và trạng thái xử lý trên một giao diện, để không yêu cầu khách hàng cung cấp lại thông tin tránh tạo ticket hỗ trợ trùng lặp |
| Actor |Nhân viên CSKH VinFast, bộ phận kỹ thuật, cố vấn dịch vụ tại xưởng  |
| Thời điểm / bối cảnh |Khi khách hàng phản ánh lỗi xe hoặc liên hệ lại để hỏi tiến độ xử lý qua một kênh khá|
| Quy trình hiện tại (3–7 bước) |1. Tiếp nhận phản ánh qua các kênh 2. Xác minh thông tin khách hàng và xe 3. Trac cứu lịch sử tương tác 4. Kiểm tra ticket đã tồn tại  5. Tạo hoặc cập nhật ticket và chuyển bộ phận kỹ thuật  6. Phản hồi khách hàng |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3–4: Tra cứu lịch sử và đối chiếu ticket từ nhiều nguồn. Giả định mất 8–12 phút/yêu cầu khi thông tin phân tán |
| Impact (nếu không giải thì sao) |Khách phải mô tả nhiều lần, nhân viên mất thời gian tra cứu, có nguy cơ tạo ticket trùng khiến quá trình hỗ trợ bị chậm và giảm mức độ hài lòng|
| Success metric (baseline → target) |hời gian tra cứu lịch sử: 10 -> dưới 2 phút; tỷ lệ ticket trùng: giả định 15% -> dưới 5%; tỷ lệ khách phải cung cấp lại thông tin: giả định 30% -> dưới 10% |
| Phương án không dùng AI |Tích hợp dữ liệu từ các kênh vào CRM chung; dùng số điện thoại, mã khách hàng hoặc VIN để liên kết hồ sơ; thiết lập quy tắc kiểm tra ticket trùng |
| Giả thuyết về AI (nếu có) |Ai tóm tắt lịch sử khahcs hàng tương tác, nhận diện các phản ánh có cùng nội dung lỗi và gợi ý liên kết với ticket đang xử lý. Nhân viên xác nhận trước khi cập nhật |
| Cảm nhận nhanh | Workflow - ưu tiên tích hợp dữ liệu và chuẩn hóa quy trình, sau đó bổ sung AI để tóm tắt và phát hiện trùng ngữ nghĩa |

Quy trình nháp hiện tại:

HIỆN TẠI — 24 phút/yêu cầu (giả định, cần kiểm chứng)

┌──────────────────────────────────────────────────────────┐
│ 1. Tiếp nhận phản ánh — 2 phút                            │
│ Kênh: Hotline / Email / Ứng dụng VinFast                  │
│ Actor: Nhân viên CSKH                                     │
└──────────────────────────────────────────────────────────┘
                          │
                          ▼
              🔄 Handoff: Kênh → CSKH
                          │
                          ▼
┌──────────────────────────────────────────────────────────┐
│ 2. Xác minh khách hàng và thông tin xe — 3 phút           │
│ Kiểm tra số điện thoại, biển số xe hoặc VIN               │
└──────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────┐
│ 3. Tra cứu lịch sử tương tác — 7 phút                     │
│ Tìm thông tin từ các kênh và hệ thống liên quan           │
│ 🔴 BOTTLENECK: Thông tin có thể phân tán nhiều nơi        │
└──────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────┐
│ 4. Kiểm tra ticket trùng — 4 phút                         │
│ Đối chiếu lỗi xe với các yêu cầu đã được ghi nhận         │
│ 🔴 BOTTLENECK: Khó nhận diện cùng một lỗi mô tả khác nhau │
└──────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────┐
│ 5. Tạo/cập nhật ticket — 5 phút                           │
│ Ghi nhận vấn đề và chuyển bộ phận xử lý                   │
│ 🔄 Handoff: CSKH → Kỹ thuật / Xưởng dịch vụ               │
└──────────────────────────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────┐
│ 6. Phản hồi khách hàng — 3 phút                           │
│ Thông báo mã ticket và trạng thái xử lý                   │
└──────────────────────────────────────────────────────────┘

TỔNG THỜI GIAN: 24 phút/yêu cầu

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Gần gũi, thân thuộc với các học viên nhân.
- Câu hỏi muốn nhóm phản biện:
    1. AI tốt hơn phương án không dùng AI như FAQ hoặc mẫu trả lời có sẵn hay không?
### AI đã phản biện card thế nào

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa có số liệu thực tế về số lượng câu hỏi từ Messenger và comment, thời gian phản hồi trung bình của đội ngũ hỗ trợ. | Đồng ý | Chuyển các số liệu ban đầu thành giả định cần kiểm chứng; đề xuất thu thập dữ liệu từ Fanpage trong 2–4 tuần để xác định baseline. |
| Chưa phân biệt rõ câu hỏi lặp lại (lịch học, học phí, nội dung chương trình) và câu hỏi phức tạp cần tư vấn riêng. | Đồng ý | Giới hạn phạm vi AI ở việc gợi ý câu trả lời cho các câu hỏi phổ biến; câu hỏi phức tạp hoặc liên quan đến trường hợp cá nhân được chuyển cho nhân viên xử lý. |
| AI có thể đưa ra thông tin sai hoặc lỗi thời về học phí, lịch học, chính sách tuyển sinh. | Đồng ý | Đề xuất sử dụng nguồn dữ liệu chính thức, được cập nhật của chương trình; nhân viên kiểm duyệt câu trả lời trước khi gửi. |
| Success metric mới tập trung vào giảm thời gian phản hồi, chưa đánh giá chất lượng câu trả lời. | Đồng ý | Bổ sung tỷ lệ câu trả lời được nhân viên chấp nhận, tỷ lệ thông tin chính xác và tỷ lệ câu hỏi cần chuyển cho người phụ trách. |
| Phạm vi xử lý đồng thời Messenger và comment có thể phức tạp do khác biệt về ngữ cảnh và quyền truy cập dữ liệu. | Đồng ý | Đề xuất thử nghiệm trước với Messenger, sau đó mở rộng sang comment khi đã đánh giá được hiệu quả và khả năng tích hợp. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan |Gợi ý ra các ý tưởng |Có raart nhiều ý tưởng hay |Bài toán chưa cụ thể |Thêm context cho các ý tưởng |
| CP2 Problem Card |Sử dụng để sửa lại văn phong, format cho đồng bộ |Có thể thay thế việc soạn thảo thủ công, check lỗi format |Đôi khi thay đổi cả nội dung |Sửa lỗi chính tả, format |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
