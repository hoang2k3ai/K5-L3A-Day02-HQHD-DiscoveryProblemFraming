# Báo cáo cá nhân — Lê Hồng Quân (2A202603705)

**Nhân Vật:** Tôi, Lê Hồng Quân, FullStack Developer ở một công ty Startup Product về Giáo Dục. Đang sử dụng Claude + Git để nhận issue, daily meeting vào 9 AM để làm rõ và nhận task tới 10 AM. Thường thì sẽ đọc hiểu issue, tạo mockup và đưa cho Manager duyệt, sau đó viết spec, duyệt và viết plan, chia sub-agent để coding và review full gate, báo cáo cho QC/BA kiểm thử trên Staging trước khi đăng lên Production

## 1. Thông tin học viên

- Họ tên: Lê Hồng Quân
- MSSV: 2A202603705
- Email trường (không bắt buộc, repo có thể để public): 26ai.quanlh3@vinuni.edu.vn
- Tên nhóm: HQHD
- Link repo nhóm: https://github.com/hoang2k3ai/K5-L3A-Day02-HQHD-DiscoveryProblemFraming/tree/main
---

## 2. Scan problem (CP1)
| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp | Khi lớp có 40 học sinh, giáo viên muốn biết em nào cần giúp và vì sao, không chỉ thấy cờ "Cần giúp", để nhắc đúng em | Giáo viên, học sinh | Cờ "Cần giúp" chỉ dựa trên ngưỡng ngày và điểm, không nêu lý do. Chưa có số lượng cụ thể trong lớp các vấn đề, chi tiết vấn đề của các bạn, chỉ cần 3 bạn báo Cần giúp là đã loạn thông tin|
| 2 | Lặp lại | Các giáo viên dạy Tiểu Học muốn có các tương tác, bài học mang hướng dễ thương, hồn nhiên, hiệu ứng âm thanh vui nhộn được thiết kế theo từng bài học, từng giáo án, nếu như làm bằng tay trên PPT, CapCut | Giáo Viên | Từ 30 phút với các bài ngắn hoặc 1, 2 tiếng chỉ để làm cho 1 bài giản có thể trở nên sinh động hơn |
| 3 | Tốn thời gian | Khi cần cập nhật các tool, teacher game mới để giới thiệu cho giáo viên, tôi muốn tìm nhanh những công cụ thật sự nổi bật, để chọn được thứ vừa thú vị vừa có lợi thật cho giáo viên; hiện thông tin nằm rải ở nhiều nguồn (web, youtube, drive) và tốn 1–3 tiếng mỗi lần research | Đội nội dung, giáo viên | 1–3 giờ mỗi lần tìm|
| 4 | Pain từ người khác | Khi bài blog có bản tiếng Anh chưa đủ, người đọc EN muốn thấy bản dịch chứ không phải bản tiếng Việt | Staff CMS, người đọc EN | Bài chỉ hiện EN khi đủ tiêu đề và thân bài EN. 32 bài còn thiếu EN |
| 5 | Cần đọc, tổng hợp | Khi nhập dữ liệu nguyên tố và hợp chất, người viết, soạn nội dung muốn biết chỗ nào lệch so với sách in, để không sai kiến thức | Biên tập viên | Tài liệu toolkit ghi "chưa đối chiếu với sách in" |
| 6 | Tốn thời gian | Khi cuối tháng, người quản trị trường muốn KPI từ nhiều nguồn trong một bảng kèm nhận xét, để báo cáo | Quản lý trường, Sở | S1 lần mỗi tháng, 5 trường có giáo viên không cập nhật hình ảnh làm 1 số trường không kịp KPI|
| 7 |Lặp lại|Các đề thi, trang sách của bộ giáo dục hay từ các bộ sách khác có thể update theo từng tuần, tháng|QC/BA|5 phút mỗi ngày để check nguồn, và nếu như có update cần tốn từ 10-15 phút để cập nhật, kéo trang sách về|
| 8 |Lặp lại|Khi phụ huynh mở báo cáo tuần, họ muốn đọc chi tiết về năng lực của con mình trong buổi chứ không phải là các mẫu template nhận xét chung chung|Giáo Viên|Nếu viết bằng tay chi tiết với từng lớp khoảng 40 bạn, mỗi bạn 2 phút thì ít nhất 1 giờ 30 phút trôi qua chỉ để nhận xét buổi học|
| 9 | Lặp lại | Mỗi Sáng Daily Cần Báo Cáo, Trao đổi với team lead về các task đang làm, nếu Tổng hợp thông tin quá nhiều có thể bị loạn, hiệu quả báo cáo với Team Lead không được tốt, không làm rõ được những nhiệm vụ đã làm xong, cần confirm trước khi làm | Dev lead, team | coord/board.md và comment claim trên GitHub đã có sẵn dữ liệu, thay vì 10 - 20 phút tự viết thủ công|
| 10 | Lặp lại | Khi Make Gate báo fail, tôi muốn biết ngay đó là lỗi thật hay chỉ do file tự sinh lệch, để không phải chờ và chạy lại gate 20 phút | Dev team, deploy | Gate ≥20 phút, fail vì file tự sinh. 10 lần/ngày|

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-
10 ý của tôi đều là tôi suy nghĩ áp dụng cho công việc thực tế, AI giúp tôi format, trình bày hợp lý hơn
---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Các giáo viên dạy Tiểu Học muốn có các tương tác, bài học mang hướng dễ thương, hồn nhiên, hiệu ứng âm thanh vui nhộn được thiết kế theo từng bài học, từng giáo án, nếu như làm bằng tay trên PPT, CapCut|Đây là yêu cầu chính để có thể tiếp tục phát triển hệ thống, yêu cầu cốt lỗi của công ty là tạo ra giá trị, giúp buổi học của giáo viên trở nên dễ tiếp thu với học sinh|Chưa chắc là trong các phương pháp đã áp dụng bao gồm interaction, motion, ... hướng nào sẽ đạt được chất lượng mong muốn|
| 2 |Khi phụ huynh mở báo cáo tuần, họ muốn đọc chi tiết về năng lực của con mình trong buổi chứ không phải là các mẫu template nhận xét chung chung|Nhu cầu thiết thực, đặt mình vào vai trò phụ huynh của con mình sau này, xuất phát từ tâm lý tạo ra sự tin tưởng, thoải mái cho những bậc phụ huynh|Cần đảm bảo vừa đẩy đủ thông tin, nhưng cũng không được quá dài dòng, vì phụ huynh không có nhiều thời gian để đọc và hiểu một bài nhận xét quá dài, chưa chắc về template áp dụng|
| 3 |Mỗi Sáng Daily Cần Báo Cáo, Trao đổi với team lead về các task đang làm, nếu Tổng hợp thông tin quá nhiều có thể bị loạn, hiệu quả báo cáo với Team Lead không được tốt, không làm rõ được những nhiệm vụ đã làm xong, cần confirm trước khi làm|Vấn đề thiết thực đang gặp phải từng ngày của bản thân tôi|Cách để cho Agent có thể tổng hợp đảm bảo không quá sơ sài, không bỏ sót ý chính đã từng làm|

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị bài giảng tiểu học, giáo viên muốn có tương tác và hiệu ứng vui nhộn đúng nội dung bài, để học sinh nhớ bài và tham gia hơn. |
| Actor | Giáo viên tiểu học (người soạn), học sinh lớp nhỏ (người được hưởng lợi) |
| Thời điểm / bối cảnh | Trước giờ dạy, khi soạn giáo án có ý định dùng tương tác |
| Quy trình hiện tại (3–7 bước) | 1. Đọc giáo án, chọn nội dung cần minh họa. 2. Tìm hình, âm thanh phù hợp (web, kho cá nhân). 3. Dựng slide trên PPT hoặc CapCut. 4. Thêm hiệu ứng, chuyển cảnh, âm thanh. 5. Thử trên máy, sửa lỗi hiển thị. 6. Trình chiếu trên lớp. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5 (dựng và chỉnh hiệu ứng). trung bình 30 phút với bài dễ, 2 tiếng với bài khá chi tiết|
| Impact (nếu không giải thì sao) | Giáo viên bỏ qua tương tác, dùng slide tĩnh; bài học kém hấp dẫn với học sinh nhỏ; khó mở rộng sang nhiều bài và nhiều môn. |
| Success metric (baseline → target) | Thời gian làm một tương tác: 30 phút (bài dễ) hoặc 2 giờ (bài chi tiết) → 15 phút (baseline ước tính, cần đo). Điểm giáo viên chấm mức "vui, đúng nội dung" (thang 1–5): 3 → ≥4 (baseline chưa khảo sát). Tỷ lệ giáo viên dùng lại tương tác đã tạo: 65% → 95% (baseline chưa đo). |
| Phương án không dùng AI | Thư viện mẫu theo chủ đề và lứa tuổi, có sẵn bố cục, màu sắc, âm thanh; giáo viên chỉ thay chữ và hình. |
| Giả thuyết về AI (nếu có) | LLM sinh kịch bản tương tác từ giáo án, rồi dựng bằng thư viện mẫu. Dự án đã có luồng kịch bản → build (Tạo tương tác), nên câu hỏi là chất lượng "vui nhộn" và giọng văn trẻ con có đạt không. |
| Cảm nhận nhanh | Workflow (AI soạn nháp, giáo viên duyệt và chỉnh) |

Quy trình nháp hiện tại:

```text
1. Giáo viên đọc giáo án, chọn nội dung cần minh họa
2. Tìm hình ảnh, âm thanh phù hợp (web, kho cá nhân)
3. Dựng slide trên PPT hoặc CapCut
4. Thêm hiệu ứng, chuyển cảnh, âm thanh
5. Thử trên máy, sửa lỗi hiển thị
6. Trình chiếu trên lớp
Bottleneck: bước 3–5 (số phút từng bước: _[bạn điền]_)
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi sáng thứ Hai nhận báo cáo tuần về con, phụ huynh muốn đọc được con đã làm gì và còn yếu chỗ nào, để biết cách hỏi và động viên con đúng lúc. |
| Actor | Phụ huynh học sinh (người đọc), giáo viên (người viết nhận xét) |
| Thời điểm / bối cảnh | Sáng thứ Hai, khi báo cáo tuần được gửi tự động |
| Quy trình hiện tại (3–7 bước) | 1. Hệ thống gửi báo cáo lúc 7h sáng thứ Hai, chỉ có số giờ học, số ngày học, top 3 sách. 2. Phụ huynh đọc con số. 3. Muốn biết chi tiết thì phải hỏi con hoặc giáo viên. 4. Giáo viên (nếu viết nhận xét) soạn tay từng em hoặc dùng mẫu chung. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: giáo viên soạn nhận xét từng em. 2 phút mỗi em, lớp 40 bạn thì gần 1 tiếng rưỡi |
| Impact (nếu không giải thì sao) | Phụ huynh thấy báo cáo chỉ là số liệu, mất tin tưởng; giáo viên không đủ thời gian viết nhận xét thật, nên dùng mẫu chung và báo cáo thành vô nghĩa. |
| Success metric (baseline → target) | Tỷ lệ phụ huynh mở báo cáo: 85% → 95% (baseline chưa đo). Thời gian giáo viên soạn nhận xét mỗi em: 2 phút (ước tính) → giảm 50%. Khảo sát phụ huynh "hiểu con đang học gì" (1–5): 2 → ≥4 (chưa khảo sát). |
| Phương án không dùng AI | Ghép câu theo luật từ dữ liệu có sẵn: mức Vững, Đạt, Cần giúp; bài đã học; điểm bài kiểm tra gần nhất. Mỗi mức có một câu mẫu đã duyệt. |
| Giả thuyết về AI (nếu có) | LLM viết 3–4 câu từ dữ liệu có cấu trúc và ghi chú của giáo viên, rồi giáo viên duyệt trước khi gửi. Ràng buộc: chỉ dùng dữ liệu có sẵn, không bịa, dưới khoảng 120 chữ. |
| Cảm nhận nhanh | Rule (có thể đủ trước), sau đó Workflow (AI soạn, người duyệt) |

Quy trình nháp hiện tại:

```text
1. Thứ Hai 7h: hệ thống gửi báo cáo (giờ học, số ngày, top 3 sách)
2. Phụ huynh đọc số liệu
3. Muốn hiểu con học gì: hỏi con hoặc giáo viên
4. Giáo viên soạn nhận xét từng em (hoặc dùng mẫu chung)
Bottleneck: bước 4, 2 phút mỗi em (số phút các bước còn lại: _[bạn điền]_)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi mỗi sáng phải báo cáo với team lead, tôi muốn có sẵn tóm tắt việc đã xong, việc đang làm và việc đang bị chặn, để báo cáo rõ ràng và không phải nhớ lại. |
| Actor | Bạn (người báo cáo), team lead (người nhận) |
| Thời điểm / bối cảnh | Mỗi sáng, trước buổi daily |
| Quy trình hiện tại (3–7 bước) | 1. Nhớ lại hôm qua đã làm gì. 2. Mở commit, PR, board để kiểm tra. 3. Liệt kê việc đã xong, đang làm, bị chặn. 4. Trao đổi với team lead. 5. Team lead hỏi lại hoặc yêu cầu xác nhận trước khi làm tiếp. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1–3 (nhớ và đối chiếu). Mỗi ngày sẽ là 1 giờ. |
| Impact (nếu không giải thì sao) | Mất thời gian mỗi sáng; báo cáo rối; team lead không nắm được tiến độ; việc phải xác nhận lại làm chậm công việc. |
| Success metric (baseline → target) | Thời gian chuẩn bị daily: 60 phút (ước tính) → ≤10 phút. Số câu team lead hỏi lại mỗi buổi: 50% câu hỏi (baseline chưa đo) → ≤1 câu/buổi. Số việc bị bỏ sót khi đối chiếu với board: 50% → 0 (baseline chưa đo). |
| Phương án không dùng AI | Script đơn giản: git log từ hôm qua, cộng với board.md và issue đã claim, xuất ra danh sách có sẵn ba mục. Bạn chỉnh tay phần ý nghĩa. |
| Giả thuyết về AI (nếu có) | Agent đọc commit, PR, board, issue, rồi soạn nháp ba mục. Mục nào không chắc chắn thì đánh dấu để bạn xác nhận, không tự kết luận. |
| Cảm nhận nhanh | Rule trước (script), Agent sau nếu script chưa đủ |

Quy trình nháp hiện tại:

```text
1. Nhớ lại việc hôm qua
2. Mở commit, PR, board để đối chiếu
3. Liệt kê việc đã xong, đang làm, bị chặn
4. Trao đổi với team lead
5. Team lead hỏi lại hoặc yêu cầu xác nhận trước khi làm
Bottleneck: bước 1–3 (ước 60 phút, cần đo; số phút từng bước: _[bạn điền]_)
```

### Card muốn pitch nhất

- **Card số:** 1
- **Vì sao:** đây là giá trị cốt lõi của công ty: buổi học dễ tiếp thu hơn với học sinh, và nếu giải được thì hệ thống có lý do để phát triển tiếp. Card 1 cũng là vấn đề có tác động lớn nhất trong ba card. Dự án đã có luồng AI tạo tương tác (Tạo tương tác, kịch bản → build), nên pitch có thể tập trung vào khoảng trống thật: chất lượng "vui nhộn, hồn nhiên" cho lớp nhỏ, không phải tự tạo tương tác bằng AI.
- **Rủi ro cần xử lý trước buổi pitch:**
  1. Demo khó trong thời gian ngắn. Nên chuẩn bị một bài mẫu đã làm bằng luồng hiện tại để so sánh.
  2. Cần chuyên môn cứng duyệt kịch bản cho bài học
- **Câu hỏi muốn nhóm phản biện:**
  1. Luồng Tạo tương tác hiện có đã đủ "vui nhộn" chưa? Nếu đã đủ, vấn đề thật là gì?
  2. Giáo viên có chịu duyệt một kịch bản do AI viết, hay họ chỉ muốn có mẫu để chỉnh?
  3. Làm sao biết học sinh nhớ bài hơn, chứ không chỉ là giáo viên thấy đẹp hơn?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì / kế hoạch sửa |
|---|---|---|
| Card 2 mâu thuẫn: "chi tiết" với "không dài dòng". Không có ngưỡng độ dài thì không kiểm tra được. | Đồng ý | Ghi ngưỡng cụ thể (khoảng 120 chữ) và một tiêu chí "đủ chi tiết": có ít nhất một điểm mạnh và một điểm cần cải thiện. |
| Card 2 chưa cho biết giáo viên viết nhận xét thế nào hiện nay. Không biết bước này thì không biết đây là vấn đề thật hay không. | Đồng ý | Phỏng vấn 2–3 giáo viên, ghi lại cách viết và thời gian. |
| Card 2 có thể giải bằng luật (câu mẫu theo mức), không nhất thiết cần LLM. | Đồng ý | Ghi phương án Rule là lựa chọn đầu tiên. LLM chỉ khi luật cho câu cứng nhắc. |
| Card 3 dễ bị hiểu là "agent thay mình làm daily", trong khi việc khó nhất là quyết định và xác nhận. Agent không thể thay bạn nói ra việc đã xong. | Một phần | Ghi rõ agent chỉ soạn nháp; bạn vẫn xác nhận và chịu trách nhiệm từng mục. |
| Card 3 chưa đo thời gian thật. Số "1 tiếng" là ước tính. | Đồng ý | Kế hoạch (chưa làm): đo 5 buổi trước khi pitch, ghi số thực tế. |
| Card 3 thiếu cách kiểm tra chất lượng: không có tiêu chí để biết báo cáo của agent có đúng không. | Đồng ý | Đã thêm metric "số việc bị bỏ sót khi đối chiếu với board". Kế hoạch (chưa làm): để team lead chấm điểm báo cáo thử trong một tuần. |
---
## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Tôi đưa ra 10 problem scan và 3 top problem|Đóng góp được vào sự lựa chọn của nhóm bằng ý tưởng riêng của mình |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Đa phần các câu hỏi tôi sẽ hỏi về số liệu các bạn đã kiểm chứng, và các ý tưởng của các bạn có áp dụng tốt trong thực tế, cuộc sống hằng ngày hay không ?| Làm rõ được chất lượng đầu ra, chi tiết về câu trả lời chung của nhóm, chốt được bài nào có chất lượng tốt nhất nằm trong file của nhóm|
| Nhận phản biện | Câu hỏi tôi nhận được: Hỏi về áp dụng ở đâu trong thực tế| Tôi đã sửa gì: sửa lại ghi rõ về áp dụng của phần tôi trong thực tế môi trường công ty giáo dục|
| Gom cluster / cây OST | Tham gia thảo luận cluster A/B/C và cây OST 1 outcome, 3 opportunity. _[Bạn xác nhận phần tự làm cụ thể]_ | Nhóm thống nhất cluster và OST, xem `group_report.md` mục 2.2–2.3 |
| Chọn candidate problem | Pitch card #1 (giáo viên tiểu học, tương tác và hiệu ứng) làm candidate chính. Chấm điểm nháp 27/28/25/24 ở mục 2.4 | Nhóm bỏ phiếu 3/4 chọn card này, xem `group_report.md` mục 2.4 |
| Kiểm chứng / research | Phỏng vấn và bấm giờ theo nhóm: 5 giáo viên, 3 bài soạn (`group_report.md` mục 3.2). _[Bạn xác nhận phần tự làm cụ thể]_ | Pain được giáo viên xác nhận; Usability (giáo viên duyệt nội dung AI) vẫn là rủi ro cao, xem mục 8.1 |
| Quy trình nhóm |Tham gia làm cá nhân, góp ý nhóm| |
| Problem Statement | Đóng góp PS v0 và v1 cho card #1 (`group_report.md` mục 5, 7). _[Bạn xác nhận phần tự viết]_ | PS v1 thêm metric giữ kịch bản sau duyệt và boundary về bản quyền |
| Mức can thiệp AI | Đề xuất Workflow (AI soạn nháp, giáo viên duyệt), so sánh 4 mức ở mục 6.2 | Nhóm bỏ phiếu 4/4 chọn Workflow |
| Quyết định | Nhóm ghi Yet 4/4 (mục 8.2) | _[Lưu ý: phần lý do trong group_report ghi "Đã có cơ sở để GO", chưa nhất quán với Yet. Nhóm cần sửa]_ |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Không AI | Không AI | Không AI | Không AI |
| CP2 Problem Card | AI Phản Biện | Cho tôi các điểm hạn chế của Card | Chưa đọc được nguyên ý tưởng gốc project và đưa ra điểm hạ chế quá đúng đắn | Dựa theo phản biện, sửa lại flow AI viết sai |
| CP4 Research | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ |
| CP5 Quy trình | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ |
| CP5–6 Problem Statement | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ |
| CP6 Mức can thiệp / quyết định | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ | _[Bạn điền]_ |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). 

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

_[Bạn tự viết. Không dùng AI viết thay.]_

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

_[Bạn tự viết. Không dùng AI viết thay.]_

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Không đổi ý, ý tưởng của tôi khá hợp lý, áp dụng ở môi trường thực tế rồi.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

_[Bạn tự viết. Không dùng AI viết thay.]_

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Phân biệt triệu chứng và nguyên nhân gốc rễ, nhiều problem chi tiết theo lý thuyết mình nghĩ là vậy tuy nhiên nếu áp dụng vào product thì có thể chưa đúng, cần QC/BA thực sự trao đổi với khách hàng để đưa ra nguyên nhân gốc rễ để giải quyết. 

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ thay đổi thêm nhiều problem card tốt hơn, phân tích kỹ và sâu hơn về Top 3 problem card, các số đo có thể đo ở phạm vị mở rộng hơn để kết quả đánh giá cần tốt nhất.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

_[Bạn tự viết 5–8 câu, không nhìn tài liệu.]_

---

## 7. Tài liệu tham khảo

-
