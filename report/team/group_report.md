# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Lê Hồng Quân (card muốn pitch nhất) | Khi chuẩn bị bài giảng tiểu học, giáo viên muốn có tương tác và hiệu ứng vui nhộn đúng nội dung bài, để học sinh nhớ bài và tham gia hơn | Giáo viên tiểu học; học sinh lớp nhỏ | Bước 3–5 (dựng và chỉnh hiệu ứng): 30 phút với bài dễ, 2 giờ với bài chi tiết | Hỏi về áp dụng ở đâu trong thực tế (người hỏi: _[bổ sung]_) |
| 2 | Lê Hồng Quân | Khi sáng thứ Hai nhận báo cáo tuần về con, phụ huynh muốn biết con đã học gì và còn yếu chỗ nào, để hỏi và động viên con đúng lúc | Phụ huynh; giáo viên viết nhận xét | Bước 4: soạn nhận xét 2 phút mỗi em, lớp 40 em khoảng 1 giờ 30 phút | _[chưa có câu hỏi]_ |
| 3 | Lê Hồng Quân | Khi mỗi sáng báo cáo với team lead, tôi muốn có sẵn tóm tắt việc đã xong, đang làm và bị chặn, để không phải nhớ lại | Bản thân (người báo cáo); team lead | Bước 1–3: nhớ và đối chiếu, ước 60 phút/ngày (chưa đo) | _[chưa có câu hỏi]_ |
| 4 | Bùi Quang Huy | Khi ứng viên hoặc học viên hỏi qua Messenger/bình luận Fanpage, tôi muốn có câu trả lời gợi ý dựa trên thông tin đã xác thực, để phản hồi nhanh và nhất quán | Nhân viên trực Fanpage/tư vấn tuyển sinh; ứng viên và học viên | Bước 3: tra cứu FAQ/tài liệu hoặc hỏi điều phối viên, khoảng 5 phút/câu khi thông tin thay đổi | Nếu thông tin tuyển sinh hoặc lịch học thay đổi liên tục, làm sao đảm bảo AI chỉ gợi ý câu trả lời từ nguồn đã xác thực và không cung cấp thông tin cũ? |
| 5 | Bùi Quang Huy | Khi sắp có buổi học hoặc lịch học thay đổi, tôi muốn nhận nhắc nhở kịp thời về thông tin buổi học, để tham gia đầy đủ và chuẩn bị tốt | Học viên; điều phối viên lớp học | Bước 3–4: lấy danh sách/kênh nhận và gửi nhắc thủ công; dễ bỏ sót lớp khi lịch thay đổi sát giờ | Nếu lịch học thay đổi sát giờ hoặc học viên không nhận được thông báo, hệ thống làm sao phát hiện và đảm bảo không bỏ sót người cần nhắc?|
| 6 | Bùi Quang Huy | Khi chủ xe VinFast báo lỗi qua email, hotline hoặc ứng dụng, tôi muốn xem lịch sử tương tác và trạng thái xử lý tập trung, để khách không phải cung cấp lại thông tin và tránh tạo ticket trùng | Nhân viên CSKH VinFast; bộ phận kỹ thuật; cố vấn dịch vụ | Bước 3–4: tra cứu lịch sử và đối chiếu ticket từ nhiều nguồn, ước tính 8–12 phút/yêu cầu | Nếu dữ liệu CSKH VinFast nằm ở nhiều hệ thống khác nhau và không có mã định danh thống nhất, làm sao hợp nhất chính xác lịch sử tương tác mà không ghép nhầm khách hàng hoặc tạo ticket trùng? |
| 7 | Đào Huy Hoàng | Khi quay lại một dự án sau khi bị chuyển sang việc ưu tiên khác, tôi muốn nhanh chóng nhớ mình đã làm đến đâu và bước tiếp theo là gì, để tiếp tục mà không phải dò lại từ đầu | Junior AI Engineer đang làm nhiều dự án | Đọc lại log/task và commit để tìm điểm đang dở: khoảng 60 phút lần gần nhất (4 bước × ~15 phút) | _[chưa có câu hỏi]_ |
| 8 | Đào Huy Hoàng | Khi nhiều dự án có deadline khác nhau cùng được giao, tôi muốn biết việc nào cần ưu tiên và khi nào chuyển việc, để không bỏ lỡ mốc quan trọng của dự án nào | Junior AI Engineer theo dõi nhiều dự án | So sánh deadline, trạng thái và ưu tiên để chọn task tiếp theo: khoảng 8 phút trong ~20 phút rà soát mỗi sáng | _[chưa có câu hỏi]_ |
| 9 | Đào Huy Hoàng | Khi có tin mới ở nhiều kênh Discord của chương trình, tôi muốn biết tin nào liên quan và cần xử lý, để không bỏ lỡ thông báo hoặc việc cần làm | Học viên chương trình Đào tạo AI thực chiến | Xác định tin liên quan và việc cần làm giữa nhiều kênh: khoảng 8 phút mỗi lần kiểm tra (~15 phút/lần, khoảng 2 tiếng một lần) | _[chưa có câu hỏi]_ |
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

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- Chưa có ý nào bị loại ở bước này; sẽ bổ sung khi nhóm thảo luận.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Quân — dạy tiểu học, tương tác và hiệu ứng vui nhộn cho bài giảng (#1) | 5 | 4 | 3 | 3 | 3 | 4 | 3 | 25 |
| Huy — gợi ý trả lời câu hỏi Fanpage/Messenger tuyển sinh (#4) | 4 | 4 | 3 | 3 | 3 | 4 | 3 | 24 |
| Hoàng — quay lại dự án sau khi bị chuyển việc (#7) | 4 | 4 | 3 | 2 | 5 | 5 | 5 | 28 |
| Dũng — chọn tài liệu tự học HTML/CSS phù hợp trình độ (#10) | 5 | 4 | 3 | 3 | 4 | 4 | 4 | 27 |

_Điểm nháp do mình suy ra từ các card cá nhân; nhóm cần chấm lại theo thang 1–5 trước khi chốt._

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
