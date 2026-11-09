# Báo cáo nhóm — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm

- Tên nhóm: HQHD
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Giáo viên tiểu học cần tạo tương tác và hiệu ứng vui nhộn đúng nội dung từng bài giảng nhanh hơn, để học sinh lớp nhỏ nhớ bài và tham gia hơn (card #1 của Lê Hồng Quân, đề xuất để nhóm đồng thuận).
- Quyết định cuối: Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Lê Hồng Quân (card muốn pitch nhất) | Khi chuẩn bị bài giảng tiểu học, giáo viên muốn có tương tác và hiệu ứng vui nhộn đúng nội dung bài, để học sinh nhớ bài và tham gia hơn | Giáo viên tiểu học; học sinh lớp nhỏ | Bước 3–5 (dựng và chỉnh hiệu ứng): 30 phút với bài dễ, 2 giờ với bài chi tiết | Hỏi về áp dụng ở đâu trong thực tế, ai là người kiểm chứng trong thực tế ? (Dũng hỏi)  |
| 2 | Lê Hồng Quân | Khi sáng thứ Hai nhận báo cáo tuần về con, phụ huynh muốn biết con đã học gì và còn yếu chỗ nào, để hỏi và động viên con đúng lúc | Phụ huynh; giáo viên viết nhận xét | Bước 4: soạn nhận xét 2 phút mỗi em, lớp 40 em khoảng 1 giờ 30 phút | Về chi tiết từng điểm được đánh giá như nào, Phụ Huynh có chịu khi đợt trước điểm con người ta đang cao mà bây giờ điểm thấp hay không ? (Hoàng hỏi) |
| 3 | Lê Hồng Quân | Khi mỗi sáng báo cáo với team lead, tôi muốn có sẵn tóm tắt việc đã xong, đang làm và bị chặn, để không phải nhớ lại | Bản thân (người báo cáo); team lead | Bước 1–3: nhớ và đối chiếu, ước 60 phút/ngày  | Triển khai mô hình như thế nào, liệu có cần thiết hơn với việc tự nhớ và báo cáo với Team Lead không ? (Huy hỏi) |
| 4 | Bùi Quang Huy | Khi ứng viên hoặc học viên hỏi qua Messenger/bình luận Fanpage, tôi muốn có câu trả lời gợi ý dựa trên thông tin đã xác thực, để phản hồi nhanh và nhất quán | Nhân viên trực Fanpage/tư vấn tuyển sinh; ứng viên và học viên | Bước 3: tra cứu FAQ/tài liệu hoặc hỏi điều phối viên, khoảng 5 phút/câu khi thông tin thay đổi | Nếu thông tin tuyển sinh hoặc lịch học thay đổi liên tục, làm sao đảm bảo AI chỉ gợi ý câu trả lời từ nguồn đã xác thực và không cung cấp thông tin cũ? |
| 5 | Bùi Quang Huy | Khi sắp có buổi học hoặc lịch học thay đổi, tôi muốn nhận nhắc nhở kịp thời về thông tin buổi học, để tham gia đầy đủ và chuẩn bị tốt | Học viên; điều phối viên lớp học | Bước 3–4: lấy danh sách/kênh nhận và gửi nhắc thủ công; dễ bỏ sót lớp khi lịch thay đổi sát giờ | Nếu lịch học thay đổi sát giờ hoặc học viên không nhận được thông báo, hệ thống làm sao phát hiện và đảm bảo không bỏ sót người cần nhắc? |
| 6 | Bùi Quang Huy | Khi chủ xe VinFast báo lỗi qua email, hotline hoặc ứng dụng, tôi muốn xem lịch sử tương tác và trạng thái xử lý tập trung, để khách không phải cung cấp lại thông tin và tránh tạo ticket trùng | Nhân viên CSKH VinFast; bộ phận kỹ thuật; cố vấn dịch vụ | Bước 3–4: tra cứu lịch sử và đối chiếu ticket từ nhiều nguồn, ước tính 8–12 phút/yêu cầu | Nếu dữ liệu CSKH VinFast nằm ở nhiều hệ thống khác nhau và không có mã định danh thống nhất, làm sao hợp nhất chính xác lịch sử tương tác mà không ghép nhầm khách hàng hoặc tạo ticket trùng? |
| 7 | Đào Huy Hoàng | Khi quay lại một dự án sau khi bị chuyển sang việc ưu tiên khác, tôi muốn nhanh chóng nhớ mình đã làm đến đâu và bước tiếp theo là gì, để tiếp tục mà không phải dò lại từ đầu | Junior AI Engineer đang làm nhiều dự án | Đọc lại log/task và commit để tìm điểm đang dở: khoảng 60 phút lần gần nhất (4 bước × ~15 phút) | Dũng hỏi: “Các thông tin plan, log/task và commit đã đủ để truy xuất trạng thái dự án chưa?” |
| 8 | Đào Huy Hoàng | Khi nhiều dự án có deadline khác nhau cùng được giao, tôi muốn biết việc nào cần ưu tiên và khi nào chuyển việc, để không bỏ lỡ mốc quan trọng của dự án nào | Junior AI Engineer theo dõi nhiều dự án | So sánh deadline, trạng thái và ưu tiên để chọn task tiếp theo: khoảng 8 phút trong ~20 phút rà soát mỗi sáng | Bạn dựa vào tiêu chí nào để chọn dự án ưu tiên khi có nhiều deadline khác nhau? |
| 9 | Đào Huy Hoàng | Khi có tin mới ở nhiều kênh Discord của chương trình, tôi muốn biết tin nào liên quan và cần xử lý, để không bỏ lỡ thông báo hoặc việc cần làm | Học viên chương trình Đào tạo AI thực chiến | Xác định tin liên quan và việc cần làm giữa nhiều kênh: khoảng 8 phút mỗi lần kiểm tra (~15 phút/lần, khoảng 2 tiếng một lần) | Trong khoảng 50 tin nhắn mới, có tin quan trọng nào bạn đọc muộn hoặc bỏ lỡ, và việc đó ảnh hưởng thế nào? |
| 10 | Hồ Văn Dũng | Khi chọn tài liệu tự học HTML/CSS, tôi muốn chọn nguồn phù hợp với trình độ hiện tại, để hiểu bài mà không phải liên tục đổi nguồn | Bản thân — người tự học lập trình web | Đọc/xem thử để đánh giá độ phù hợp khoảng 20 phút; tìm và chọn nguồn mất 30–50 phút, bỏ qua 3–4 nguồn | _[chưa có câu hỏi]_ |
| 11 | Hồ Văn Dũng | Khi muốn tạo form đăng nhập HTML/CSS nhưng chưa biết bắt đầu từ đâu, tôi muốn xác định kiến thức và từ khóa cần tìm, để tìm được tài liệu hướng dẫn đúng nhu cầu | Bản thân — người mới tự học web | Xác định kết quả tìm được có đáp ứng mục tiêu hay không; cả quá trình tìm khoảng 20 phút, đổi từ khóa/nguồn 3–4 lần | _[chưa có câu hỏi]_ |
| 12 | Hồ Văn Dũng | Khi chỉ cần một nội dung cụ thể trong khóa Java dài, tôi muốn tìm đúng bài hoặc đoạn liên quan, để tiếp cận kiến thức cần nhanh hơn | Bản thân — người tự học lập trình qua video | Tìm đoạn chứa nội dung OOP: khoảng 20 phút tổng, bước 4 khoảng 5 phút | _[chưa có câu hỏi]_ |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | 4, 6, 9, 10, 11, 12 | Người làm cần một thông tin đúng nhưng phải dò nhiều nguồn rời rạc (FAQ, kênh chat, lịch sử ticket, tài liệu, video) và đối chiếu thủ công |
| B | 3, 7, 8 | Người làm mất thời gian khôi phục ngữ cảnh: đã làm đến đâu, việc nào ưu tiên, bước tiếp theo là gì |
| C | 1, 2, 5 | Việc soạn nội dung hoặc nhắc lịch lặp lại theo chu kỳ, dễ tốn thời gian thủ công và dễ bỏ sót người nhận |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian tra cứu, khôi phục ngữ cảnh và soạn việc lặp lại mà người làm phải bỏ ra mỗi ngày
├── Opportunity A: Tìm đúng thông tin nhanh từ nhiều nguồn rời rạc (cluster A)
├── Opportunity B: Khôi phục trạng thái công việc và ưu tiên nhanh khi chuyển việc hoặc bắt đầu ngày (cluster B)
└── Opportunity C: Soạn nội dung và nhắc việc lặp lại không bỏ sót người nhận (cluster C)
```

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Quân — dạy tiểu học, tương tác và hiệu ứng vui nhộn cho bài giảng (#1) | 4 | 4 | 3 | 2 | 5 | 5 | 5 | 28 |
| Huy — gợi ý trả lời câu hỏi Fanpage/Messenger tuyển sinh (#4) | 4 | 4 | 3 | 3 | 3 | 4 | 3 | 24 |
| Hoàng — quay lại dự án sau khi bị chuyển việc (#7) | 5 | 4 | 3 | 3 | 3 | 4 | 3 | 25 |
| Dũng — chọn tài liệu tự học HTML/CSS phù hợp trình độ (#10) | 5 | 4 | 3 | 3 | 4 | 4 | 4 | 27 |


**Candidate được chọn:** Quân — card #1 (giáo viên tiểu học, tương tác và hiệu ứng cho bài giảng). Nhóm bỏ phiếu 3/4

**Vì sao chọn:**
- Đây là vấn đề có tác động vào học sinh, và công ty đã có luồng "Tạo tương tác" (kịch bản → build), nên bài toán có chỗ để gắn AI thật.
- Bottleneck được mô tả cụ thể (bước 3–5, 30 phút đến 2 giờ mỗi bài), dễ so với phương án không dùng AI (thư viện mẫu).
- Điểm cao nhất ở "Vừa sức lab" và "So sánh được" (5/5), đây là hai điều kiện để làm pilot.

**Vì sao loại các candidate còn lại:**
- Hoàng (25 điểm): vấn đề rõ và dễ thử với chính người viết, nhưng người dùng là một Junior AI Engineer tự làm việc, tác động lên tổ chức nhỏ. Có thể dùng làm pilot cá nhân sau.
- Dũng (27): pain và quy trình rõ, nhưng người dùng là một người tự học, khó đo tác động đồng đều. Có thể giữ làm nghiên cứu tiếp theo.
- Huy (24): cần dữ liệu Fanpage và quyền truy cập API, rủi ro sai thông tin tuyển sinh cao. Chưa phù hợp làm pilot đầu tiên trong buổi lab.
- Quân có tổng điểm nháp cao nhất (28), nhưng điểm "Impact đo được" (2) thấp hơn Hoàng và Dũng (3). Nhóm chọn Quân dựa trên tác động cho học sinh và khả năng gắn AI thật, không chỉ dựa trên tổng điểm nháp. Điểm "Impact đo được" cần chấm lại trong buổi chốt.

**Xử lý bất đồng (nếu có):** 
- Mọi người bất động về cách hiểu về trách nhiệm cá nhân và nhóm trong bài LAB, và cả team đã daily 30 phút để thống nhất cách để từ bài cá nhân áp dụng vào group_report.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Giáo viên tiểu học thật sự mất 30 phút đến 2 giờ cho mỗi tương tác | Value | 5 | 3 | Có, đo bằng cách bấm giờ 3 bài soạn thực tế, tình trạng feedback của Giáo Viên về việc hàng ngày người ta tốn thời gian để soạn |
| 2 | Học sinh lớp nhỏ nhớ bài hơn khi có tương tác đúng nội dung | Value | 5 | 1 | Có, nhưng cần thiết kế thử nghiệm (so sánh lớp có và không có tương tác) |
| 3 | Giáo viên sẽ dùng lại tương tác do công cụ tạo ra (không chỉ thử một lần) | Usability | 4 | 1 | Có, theo dõi số lần dùng lại trong 2–4 tuần |
| 4 | Giáo viên đủ chuyên môn và thời gian duyệt kịch bản AI viết cho bài học | Usability | 5 | 5 | Có, phỏng vấn giáo viên về cách họ duyệt nội dung, kỹ năng sư phạm của giáo viên rất cao, sẽ thấy được điểm tốt và chưa tốt của phương án |
| 5 | Luồng "Tạo tương tác" hiện có đạt chất lượng "vui nhộn, hồn nhiên" cho lớp nhỏ | Feasibility | 4 | 1 | Có, làm khá nhiều bài mẫu và cho 2–3 giáo viên chấm |
| 6 | Phương án thư viện mẫu (không AI) chưa đủ giải quyết vấn đề | Viability | 4 | 1 | Có, so sánh thời gian với mẫu sẵn thì không dùng AI không đạt chất lượng yêu cầu |


### 3.2. Kiểm chứng

Cách đã dùng: Xây dựng các bài dạy mẫu để Giáo Viên áp dụng thử trong một số buổi học trên lớp(không tính các bài học thao giảng, mang tính thi cử), xin Feedback

Kế hoạch đề xuất:
- Phỏng vấn 2–3 giáo viên tiểu học theo mẫu snapshot bên dưới. Hỏi họ dựng tương tác như thế nào, mất bao lâu, dùng công cụ nào, và họ có duyệt nội dung do AI viết không.
- Bấm giờ 3 bài soạn thực tế dùng luồng hiện có để có baseline.

Interview snapshot :

| Trường | Nội dung |
|---|---|
| Người được hỏi | Giáo Viên các Trường Tư, Công Lập gần khu vực Bình Thạnh, HCMC |
| Câu nói đáng nhớ nhất | Nếu giải pháp này thực sự hoạt động tốt hiểu qua giống như trong kịch bản trình chiếu tôi đưa ra thì thực sự rất hiệu quả và tiết kiệm thời gian |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Mỗi buổi viết giáo án luôn gặp tình trạng này |
| Hiện đang xử lý bằng cách nào (workaround)? | Tạo thủ công bằng PPTX hoặc dựng Video Capcut |
| Mất bao lâu, bao lần? | 30 Phút Đến 2 Tiếng, 1 lần/tuần bình quân |
| Insight / opportunity rút ra | Dự án dùng AI tạo Interaction, Slide hoặc Motion thực sự cần thiết và đáng triển khai |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn giáo viên tiểu học | 5 | 5 | 0 |
| Bấm giờ bài soạn thực tế | 3 | 3 | 0 |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** 
- Nhóm đã sửa lại vấn đề thời gian và số lần giáo viên gặp phải sau cuộc kiểm chứng, đồng thời tiếp thu ý kiến của giáo viên feedback về cách Giáo Viên dùng nó trong lớp học, nên và không nên làm gì trong khi dùng AI tạo.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Canva Magic Design và AI Quiz / Magic Activities | [Teachers First: Canva AI for Educators](https://teachersfirst.org/blog/2025/05/experience-the-magic-canva-ai-for-educators/); [Educators Technology: Canva AI for Teachers](https://www.educatorstechnology.com/2026/10/canva-ai-for-teachers.html) | Bước 3–4 (dựng slide và thêm hiệu ứng), bước 5 (tạo câu hỏi tương tác) | Tạo bản nháp slide từ prompt ngắn; giáo viên miễn phí sau khi xác minh | Nguồn là blog giáo viên; Canva cảnh báo nội dung AI có thể sai, cần duyệt | Phương án "AI soạn nháp, giáo viên duyệt" có sẵn công cụ, nên nhóm cần chứng minh giá trị khác biệt so với Canva |
| Curipod | [Chalkie: 7 interactive lesson slides generators](https://chalkie.ai/en/blog/lesson-slide-tools-for-teachers) | Bước 3–4 (slide tương tác), tập trung vào poll và câu hỏi trực tiếp | Học sinh vào bằng mã, không cần tài khoản | Tương tác là poll và quiz, ít hiệu ứng và âm thanh; gói trường có giá | Tương tác trong lớp khác với hiệu ứng hoạt hình; cần chọn đúng loại tương tác mong muốn |
| Jotform AI Slide Generator | [Jotform: AI Slide Generator for Teachers](https://www.jotform.com/ai/presentation-agent/use-cases/education/) | Bước 1–4 (từ giáo án đến slide), có narration giọng nói | Tạo slide từ giáo án có sẵn, có thuyết minh bằng giọng nói | Thông tin từ trang quảng cáo; chưa rõ chất lượng giọng và mức độ "vui nhộn" với trẻ nhỏ | Narration là điểm khác biệt đáng thử cho lớp nhỏ |
| Krikey AI (Animaker) | [Krikey: AI Lesson Plan Generator for Animated Lesson Planning](https://www.krikey.ai/animaker/create/book-report) | Bước 4 (hiệu ứng và nhân vật hoạt hình) | Nhân vật hoạt hình có lời nói, phù hợp hoạt động vui nhộn | Chủ yếu là hoạt hình và video, không phải bài tương tác; cần kiểm chứng | Gần với nhu cầu "vui nhộn", nên thử bằng một bài mẫu |
| Chalkie | [Chalkie: 7 interactive lesson slides generators](https://chalkie.ai/en/blog/lesson-slide-tools-for-teachers) | Bước 2–4 (tạo slide, hoạt động, từ vựng, media nhúng) | Tạo bài học có hoạt động trong vài chục giây theo mô tả | Blog so sánh cho biết không xuất sang PowerPoint/Google Slides, bất lợi với trường dùng Google Workspace | Cần kiểm tra khả năng xuất file trước khi chọn |
| Gamma | [Gamma: Best AI presentation tools for educators](https://gamma.app/explore/content/guides/best-ai-presentation-tools-for-educators) | Bước 3–4 (dựng slide nhanh) | Tạo slide thiết kế đẹp nhanh | Nguồn cho thấy chủ yếu là bố cục; chưa thấy âm thanh | Phù hợp làm slide nền, chưa đủ cho phần tương tác |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ:

```text
1. Đọc giáo án, chọn nội dung cần minh họa
2. Tìm hình ảnh, âm thanh phù hợp (web, kho cá nhân)
3. Dựng slide trên PPT hoặc CapCut       ← bottleneck (3–5)
4. Thêm hiệu ứng, chuyển cảnh, âm thanh  ← bottleneck (3–5)
5. Thử trên máy, sửa lỗi hiển thị        ← bottleneck (3–5)
6. Trình chiếu trên lớp
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Giáo viên | Giáo án | Nội dung cần minh họa | Có sẵn giáo án | Đã đo |
| 2 | Giáo viên | Nội dung cần minh họa | Hình, âm thanh | 1 phút cho 1 ảnh tìm kiểm trên web | Phụ thuộc kho tài nguyên |
| 3 | Giáo viên | Hình, âm thanh, nội dung | Slide dựng xong | 30 phút (bài dễ) đến 1 giờ (bài chi tiết) | Từ Giáo Viên |
| 4 | Giáo viên | Slide | Slide có hiệu ứng | Một phần của tổng 2 giờ | Từ Giáo Viên |
| 5 | Giáo viên | Slide có hiệu ứng | Slide đã kiểm tra | 2 Giờ | Từ Giáo Viên |
| 6 | Giáo viên | Slide | Buổi học | Theo lịch dạy | Không thuộc phạm vi bottleneck |

**Bottleneck chính:** bước 3–5 (dựng và chỉnh hiệu ứng). Theo Giáo Viên 30 phút với bài dễ và 2 giờ với bài chi tiết. 

### 4.2. Quy trình tương lai

Phương án đề xuất (Workflow): AI soạn nháp, giáo viên duyệt. Không phải Agent.

```text
1. Giáo viên dán giáo án vào công cụ                         [con người]
2. AI đề xuất kịch bản tương tác: câu hỏi, gợi ý hiệu ứng,
   lời thoại ngắn phù hợp lứa tuổi, dựa trên giáo án          [AI]
3. Giáo viên chọn, sửa nội dung và kiểm tra kiến thức         [con người — BOUNDARY]
4. Công cụ ghép kịch bản vào thư viện mẫu (bố cục, màu, âm thanh có sẵn)  [Rule / template]
5. Giáo viên xem thử, sửa lỗi hiển thị                          [con người]
6. Trình chiếu trên lớp                                         [con người]

Phương án quay về khi AI sai: giáo viên dùng thư viện mẫu không AI ở bước 4 và tự nhập nội dung.
```

Boundary: AI không tự đưa kiến thức ra học sinh mà không có giáo viên duyệt; AI không sinh hình ảnh hoặc âm thanh không rõ nguồn bản quyền; AI không thay đổi nội dung giáo án đã được duyệt.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 | 6 | Số bước giữ nguyên, bước 3–5 được rút gọn |
| Tổng thời gian | 30 phút đến 2 giờ | 15 phút (kỳ vọng) | Kỳ vọng |
| Số bước thủ công | 3 (dựng, hiệu ứng, thử) | 1 (duyệt) | Kỳ vọng |
| Bottleneck chính | Bước 3–5 | Bước 3 (duyệt nội dung của giáo viên) | Bottleneck có thể chuyển sang duyệt |
| Rủi ro mới phát sinh | — | Nội dung sai, lời thoại không phù hợp, bản quyền tài nguyên | Xem mục 8.1 |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Giáo viên tiểu học soạn bài giảng; học sinh lớp nhỏ là người hưởng lợi |
| **Quy trình** | Từ giáo án đến tương tác có hiệu ứng và âm thanh, trình chiếu trên lớp |
| **Bottleneck** | Dựng và chỉnh hiệu ứng (bước 3–5), 30 phút với bài dễ, 2 giờ với bài chi tiết |
| **Impact** | Giáo viên bỏ qua tương tác, dùng slide tĩnh; bài kém hấp dẫn với học sinh nhỏ; khó mở rộng sang nhiều bài và môn |
| **Success Metric** (baseline → target, cách đo) | Thời gian làm một tương tác: 30 phút đến 2 giờ → 15 phút . Điểm giáo viên chấm "vui, đúng nội dung" 1–5: 1 → ≥4. Tỷ lệ giáo viên dùng lại tương tác: 50% → 95% |
| **Boundary** | AI không đưa kiến thức ra học sinh khi chưa có giáo viên duyệt; không thay nội dung giáo án đã duyệt |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- Luồng "Tạo tương tác" hiện có có thể đã đủ "vui nhộn" chưa? Nếu đã đủ, vấn đề thật là gì? Nhóm đã xem thử bài mẫu và cảm thấy ổn để triển khai.
- Giáo viên có chịu duyệt kịch bản AI viết không, hay chỉ muốn mẫu để chỉnh? Giáo viên sẽ cảm thấy tốt nếu sảm phẩm tạo ra đủ chất lượng, Nhóm đồng ý.
- Làm sao biết học sinh nhớ bài hơn, không chỉ là giáo viên thấy đẹp hơn? Thông qua thái độ hợp tác của học sinh trên lớp. Nhóm đồng ý.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **độ mơ hồ vừa, độ phức tạp vừa**. Yêu cầu "vui nhộn, đúng nội dung" có nhiều cách hiểu (mơ hồ), nhưng quy trình soạn bài có các bước rõ (phức tạp vừa).

Vì sao: Quy trình đã có các bước rõ, nên Workflow có thể chia việc giữa AI và giáo viên. Yêu cầu chất lượng "vui" khó định lượng, nên chưa đủ rõ để giao hẳn cho Agent.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Thư viện mẫu theo chủ đề và lứa tuổi, giáo viên chỉ thay chữ và hình | Nếu giáo viên chấp nhận mẫu sẵn và thời gian giảm đủ | Mẫu không đúng nội dung từng bài; ít cá nhân hóa | Baseline so sánh |
| **Rule** | Ghép bố cục, hiệu ứng theo bảng quy tắc theo môn và lứa tuổi | Nếu nội dung đã có cấu trúc (từ vựng, câu hỏi) | Không hiểu giáo án tự do | Chưa chọn, dùng làm bước 4 |
| **Workflow** | AI đề xuất kịch bản từ giáo án, giáo viên duyệt, thư viện mẫu dựng | Khi giáo viên cần nội dung riêng cho từng bài và có thời gian duyệt | AI sai kiến thức, lời thoại không phù hợp trẻ nhỏ | Chọn |
| **Agent** | AI tự tạo và xuất bài học, giáo viên chỉ nhận kết quả | Chưa có trường hợp nào cần | Sai kiến thức không được phát hiện; khó kiểm soát trẻ nhỏ | Không chọn |

**Mức chọn:** Workflow, nhóm bỏ phiếu 4/4.

**Vì sao không chọn mức đơn giản hơn:** No AI và Rule là baseline cần so sánh trước. Nếu thư viện mẫu đạt mục tiêu thời gian và điểm "vui, đúng nội dung" ≥4, nhóm sẽ không cần AI. Đây là lý do nhóm đề xuất kiểm chứng baseline trước khi quyết định.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Kịch bản tương tác nháp (câu hỏi, gợi ý hiệu ứng, lời thoại ngắn) từ giáo án |
| **Judgment** — con người cân nhắc, quyết định gì? | Giáo viên quyết định nội dung đúng, lời thoại phù hợp, có dùng hay không |
| **Action** — hành động cuối cùng là gì, ai làm? | Giáo viên chọn và dựng bài; học sinh xem trên lớp |
| **Outcome** — đo kết quả bằng gì? | Thời gian dựng, điểm giáo viên chấm, tỷ lệ dùng lại |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Giáo án của bài (có sẵn, do giáo viên soạn); thư viện mẫu (cần xây) |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Giáo viên sửa kịch bản, lưu lại các chỗ sửa để cải thiện prompt |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Được hỗ trợ (augment), vì giáo viên là người chịu trách nhiệm nội dung với học sinh.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Báo nhầm (sai kiến thức) tệ hơn, vì học sinh có thể học sai. Thiết kế xử lý bằng bước duyệt của giáo viên trước khi trình chiếu (bước 3 trong quy trình tương lai).

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Giáo viên tiểu học soạn bài; học sinh lớp nhỏ |
| **Quy trình** | Giáo án → kịch bản tương tác (AI nháp, giáo viên duyệt) → thư viện mẫu dựng → trình chiếu |
| **Bottleneck** | Dựng và chỉnh hiệu ứng (bước 3–5), và thời gian duyệt nội dung cho từng bài |
| **Impact** | Tương tác bị bỏ qua hoặc làm quá lâu; bài kém hấp dẫn với học sinh nhỏ |
| **Success Metric** (baseline → target, cách đo) | Thời gian làm một tương tác: 30 Phút tới 2 Giờ → giảm 50%. Điểm "vui, đúng nội dung" ≥4 trên 5 . Tỷ lệ kịch bản AI được giữ nguyên sau duyệt: 95% |
| **Boundary** | AI không đưa nội dung ra học sinh khi chưa được giáo viên duyệt; không tạo tài nguyên không rõ bản quyền; không thay giáo án đã duyệt |
| **AI intervention point** | Bước 2 (đề xuất kịch bản nháp) |
| **Mức chọn** | Workflow  |
| **Rủi ro & người kiểm tra** | Sai kiến thức, lời thoại không phù hợp trẻ nhỏ. Người kiểm tra: giáo viên soạn bài và tổ chuyên môn |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Thời gian và điểm "vui" | Thêm tỷ lệ kịch bản được giữ sau duyệt | Đo chất lượng đầu ra của AI, không chỉ tốc độ |
| Boundary | Chung chung | Cụ thể về nội dung kiến thức và bản quyền | Rủi ro chính là sai kiến thức với trẻ nhỏ |
| Mức chọn | Chưa có | Workflow| Sau khi so sánh 4 mức ở mục 6.2 |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đúng nội dung giáo án | Mọi khái niệm trong kịch bản có trong giáo án | Có khái niệm không có trong giáo án hoặc sai |
| 2 | Phù hợp lứa tuổi | Lời thoại ngắn, dễ hiểu, không có từ khó với học sinh lớp nhỏ | Dùng từ khó hoặc nội dung không phù hợp trẻ em |
| 3 | Dùng được với ít chỉnh sửa | Giáo viên chỉnh dưới 20% nội dung | Giáo viên phải viết lại gần hết |
| 4 | An toàn và rõ nguồn | Không có tài nguyên không rõ bản quyền | Có hình hoặc âm thanh không rõ nguồn |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | TB | Có nhu cầu được mô tả rõ, nhưng chưa phỏng vấn giáo viên nào; chưa có bằng chứng dùng lại |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Cao | Giáo viên phải duyệt nội dung mà họ chưa chắc có thời gian hoặc kỹ năng; chưa kiểm chứng |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | TB | Đã có luồng "Tạo tương tác" và nhiều công cụ tương tự (mục 3.3); chất lượng "vui nhộn" cho lớp nhỏ chưa được thử |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | TB | Bản quyền tài nguyên và quy định nội dung cho trẻ em cần người phụ trách; chưa rõ ai vận hành |

### 8.2. Kết luận

**Quyết định:** Go

**Lý do:** Vấn đề có bằng chứng: nhóm đã bấm giờ 3 bài soạn (30 phút đến 2 giờ mỗi bài) và phỏng vấn 5 giáo viên tiểu học, các tín hiệu đều xác nhận pain. Phương án Workflow (AI soạn nháp, giáo viên duyệt) có boundary rõ, giáo viên giữ quyền duyệt nội dung trước khi trình chiếu. Rủi ro Usability (giáo viên duyệt kịch bản AI) và chất lượng "vui, đúng nội dung" được chuyển thành điều kiện của pilot thay vì chặn quyết định.

**Nếu Go — pilot nhỏ nhất:** 2–3 giáo viên, 1 môn, 4 bài, so sánh với thư viện mẫu không AI. Đo theo metric ở mục 7: thời gian dựng, điểm "vui, đúng nội dung" (1–5), tỷ lệ kịch bản AI được giữ sau duyệt, và số chỗ giáo viên phải sửa.

**Điều kiện đi kèm Go (kiểm tra trong pilot):**
1. Giáo viên tự duyệt kịch bản AI trên giáo án thật; ghi thời gian duyệt và số chỗ phải sửa (Usability).
2. Chấm "vui, đúng nội dung" trên bài do AI soạn, so với bài mẫu không AI.
3. Chạy thử 3 công cụ ở mục 3.3 (ví dụ Canva, Jotform, Krikey) trên cùng một giáo án để chọn công cụ.

**Nếu No-Go — nên làm gì thay AI:** Nếu thư viện mẫu không AI đạt mục tiêu thời gian và điểm "vui", nhóm nên xây thư viện mẫu theo môn và lứa tuổi (không AI), để giáo viên thay chữ và hình.

**Ngưỡng dừng** (nếu sau 4 tuần pilot mà thời gian dựng vẫn trên 60 phút mỗi bài, hoặc điểm "vui" không đạt ≥4 với mẫu AI, thì quay về thư viện mẫu không AI): Xác nhận ngưỡng dừng 4 tuần.

---

## 9. Hạn chế và hướng tiếp theo

- Điểm shortlist là nháp, chưa chấm chung.
- Thông tin về công cụ ở mục 3.3 lấy từ trang quảng cáo và blog, chưa kiểm chứng giá và tính năng hiện tại.
- Tổng hợp và kế hoạch kiểm chứng ở mục 3.2 và mục 8.2 là việc tiếp theo của nhóm.

## 10. Tài liệu tham khảo

- Teachers First, "Experience the Magic: Canva AI for Educators" — https://teachersfirst.org/blog/2025/05/experience-the-magic-canva-ai-for-educators/
- Educators Technology, "Canva AI for Teachers" — https://www.educatorstechnology.com/2026/10/canva-ai-for-teachers.html
- Chalkie, "7 Best Interactive Lesson Slides Generators for Teachers" — https://chalkie.ai/en/blog/lesson-slide-tools-for-teachers
- Jotform, "AI Slide Generator for Teachers" — https://www.jotform.com/ai/presentation-agent/use-cases/education/
- Krikey AI, "AI Lesson Plan Generator for Animated Lesson Planning" — https://www.krikey.ai/animaker/create/book-report
- Gamma, "Best AI presentation tools for educators" — https://gamma.app/explore/content/guides/best-ai-presentation-tools-for-educators
