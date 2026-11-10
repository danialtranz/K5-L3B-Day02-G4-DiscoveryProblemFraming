# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Quang Thanh
- MSSV: 2A202603736
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: G1
- Link repo nhóm: https://github.com/danialtranz/K5-L3-Day02-G1-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| #   | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                                  | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
| ---: | --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ | --------------------------------------------------------- |
| 1   | lặp lại                           | khi tới buổi sáng hàng ngày, tôi muốn viết báo cáo hàng ngày vào cùng một thời điểm để nộp daily standup                                       | phoenix            | mỗi ngày 1 lần, tự viết khoảng 5 phút                     |
| 2   | lặp lại                           | khi tới buổi tối 7h hàng ngày, tôi muốn kiểm tra lịch để xem có một buổi workshop, mentor duty hay office hour nào không.                      | team, mentor       | 2 lần gần nhất sát giờ                                    |
| 3   | tốn thời gian                     | khi vừa xong một buổi workshop, mentor hay office hour, tôi muốn có danh sách việc cần học và ghi nhớ để không bỏ lỡ thông tin quan trọng nào. | team               | 2 giờ/buổi                                                |
| 4   | cần đọc, tổng hợp nhiều thông tin | khi cần biết team đang thảo luận chức năng nào, tôi muốn tìm hiểu thêm thông tin liên quan để có thể cùng tranh luận                           | cả team            | 30 phút/lần                                               |
| 5   | pain từ người khác                | khi team leader cần chuẩn bị họp team, team leader muốn có phản hồi ngay khi hỏi, để nắm chắc buổi họp                                         | team, team leader  | 2 lần lỡ hẹn                                              |

**Nếu có dùng AI để gợi ý thêm:**

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #3 — Tổng hợp việc cần học sau workshop, mentor hoặc office hour | Mất nhiều thời gian nhất; xảy ra sau sự kiện cụ thể và có thể vẽ quy trình rõ | Cần kiểm chứng 2 giờ/buổi là đo thực tế hay ước lượng; cần xác định đầu ra tối thiểu |
| 2 | #4 — Tìm và tổng hợp thông tin để tham gia thảo luận chức năng | Có bottleneck đọc và tổng hợp nhiều nguồn, ảnh hưởng đến cả team | Chưa biết thường đọc bao nhiêu nguồn và chất lượng ý kiến có bị ảnh hưởng không |
| 3 | #1 — Viết báo cáo daily standup | Lặp lại mỗi ngày, baseline dễ đo và quy trình ngắn | Chưa chắc 5 phút là bottleneck lớn nhất; cần kiểm tra thời gian tìm lại thông tin |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                                                |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi kết thúc một workshop, buổi mentor hoặc office hour, tôi muốn xác định các kiến thức và việc cần làm tiếp theo, để không bỏ sót thông tin quan trọng.               |
| Actor                                     | Thành viên team tham dự workshop, mentor hoặc office hour                                                                                                               |
| Thời điểm / bối cảnh                      | Ngay sau mỗi buổi; thông tin nằm trong ghi chú cá nhân, tài liệu và nội dung trao đổi                                                                                   |
| Quy trình hiện tại (3–7 bước)             | 1. Phân tích nội dung của buổi workshop/menter duty/office hour qua audio/video 2. Tóm tắt nội dung chính 3. Lọc kiến thức cần nhớ 4. Viết việc cần làm 5. Kiểm tra lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–3: đọc lại và lọc thông tin quan trọng, chiếm phần lớn trong khoảng 2 giờ/buổi                                                                                   |
| Impact (nếu không giải thì sao)           | Mất khoảng 2 giờ sau mỗi buổi; có thể quên kiến thức, bỏ sót việc cần làm hoặc phải xem lại tài liệu nhiều lần                                                          |
| Success metric (baseline → target)        | Thời gian tổng hợp từ khoảng 120 phút xuống tối đa 45 phút/buổi; danh sách vẫn có đủ kiến thức chính và việc cần làm sau khi người học kiểm tra                         |
| Phương án không dùng AI                   | Dùng mẫu ghi chú cố định gồm kiến thức chính, việc cần làm, câu hỏi còn mở và thời hạn; rà soát bằng checklist 10 phút                                                  |
| Giả thuyết về AI (nếu có)                 | AI tạo bản nháp kiến thức chính và việc cần làm từ ghi chú/tài liệu; người học phải kiểm tra và chỉnh sửa                                                               |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 120 phút/buổi

[Mở video/audio: 1'] → [Lọc kiến thức quan trọng: 120'] ← BOTTLENECK
→ [Viết việc cần làm: 15'] → [Kiểm tra lại: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi team đang thảo luận một chức năng chưa quen thuộc, tôi muốn tìm và tổng hợp thông tin liên quan, để có thể tham gia tranh luận với ý kiến có căn cứ. |
| Actor | Thành viên team cần chuẩn bị trước khi thảo luận chức năng |
| Thời điểm / bối cảnh | Trước hoặc trong một lần team thảo luận; thông tin nằm ở tài liệu, lịch sử trao đổi và các nguồn bên ngoài |
| Quy trình hiện tại (3–7 bước) | 1. Xác định nội dung cần hiểu 2. Tìm nguồn liên quan 3. Đọc tài liệu và trao đổi 4. So sánh, lọc thông tin 5. Ghi kết luận hoặc câu hỏi |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: đọc và tổng hợp từ nhiều nguồn, khoảng 20 phút trong tổng 30 phút/lần |
| Impact (nếu không giải thì sao) | Có thể đến buổi thảo luận mà chưa đủ ngữ cảnh, đưa ý kiến thiếu căn cứ hoặc hỏi lại thông tin đã trao đổi |
| Success metric (baseline → target) | Thời gian chuẩn bị từ khoảng 30 phút xuống tối đa 15 phút/lần; vẫn tìm được nguồn chính và nêu được ít nhất một kết luận hoặc câu hỏi có căn cứ |
| Phương án không dùng AI | Chuẩn hóa nơi lưu tài liệu, dùng danh sách từ khóa và mẫu tổng hợp gồm nguồn, ý chính, kết luận và câu hỏi |
| Giả thuyết về AI (nếu có) | AI hỗ trợ tìm điểm liên quan và tạo bản tổng hợp có trích nguồn từ tài liệu được cung cấp; người dùng kiểm tra nguồn |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 30 phút/lần

[Xác định nội dung cần hiểu: 5'] → [Tìm nguồn liên quan: 5']
→ [Đọc tài liệu và trao đổi: 15'] ← BOTTLENECK
→ [So sánh + ghi kết luận/câu hỏi: 5']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi sắp tới daily standup mỗi sáng, tôi muốn nhớ và viết lại các việc đã làm, để cập nhật tiến độ chính xác cho team. |
| Actor | Thành viên team tham gia daily standup |
| Thời điểm / bối cảnh | Mỗi buổi sáng trước daily standup; cần nhớ lại công việc từ ngày hôm trước và việc đang bị vướng |
| Quy trình hiện tại (3–7 bước) | 1. Mở lịch sử công việc hoặc tin nhắn 2. Nhớ lại việc đã làm 3. Viết việc đã hoàn thành 4. Ghi việc đang làm và trở ngại 5. Đọc lại trước khi nộp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1–2: tìm và nhớ lại thông tin công việc, nằm trong khoảng 5 phút mỗi ngày |
| Impact (nếu không giải thì sao) | Mỗi ngày mất khoảng 5 phút; có thể ghi thiếu việc, cập nhật không chính xác hoặc mất thêm thời gian giải thích |
| Success metric (baseline → target) | Thời gian chuẩn bị từ khoảng 5 phút xuống tối đa 2 phút/ngày; không tăng số lần phải sửa hoặc giải thích lại update |
| Phương án không dùng AI | Dùng mẫu cố định gồm hôm qua, hôm nay, blocker; cập nhật ngắn ngay sau mỗi việc thay vì nhớ lại vào buổi sáng |
| Giả thuyết về AI (nếu có) | AI tạo bản nháp update từ ghi chú hoặc lịch sử công việc; người dùng kiểm tra và chịu trách nhiệm trước khi nộp |
| Cảm nhận nhanh | Rule hoặc Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 5 phút/ngày

[Mở lịch sử công việc/tin nhắn: 2'] → [Nhớ lại việc đã làm: 1']
→ [Viết update: 1'] → [Ghi blocker + đọc lại: 1']
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Đây là vấn đề có baseline thời gian lớn nhất và quy trình sau workshop có các bước đọc, lọc, tổng hợp rõ ràng. Nếu xác nhận được mốc 2 giờ/buổi, vấn đề có impact đủ lớn để tiếp tục kiểm chứng.
- Câu hỏi muốn nhóm phản biện: Bottleneck thật sự là đọc lại tài liệu hay là quyết định nội dung nào cần ghi nhớ? Checklist hoặc mẫu ghi chú không dùng AI có thể giảm bao nhiêu thời gian?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| “2 giờ/buổi” chưa cho biết là đo thực tế hay ước lượng | Đồng ý | Ghi rõ đây là baseline cần kiểm chứng bằng cách bấm giờ ở một vài buổi gần nhất |
| “Danh sách kiến thức và việc cần làm” có thể quá rộng, khó đánh giá đạt hay chưa | Đồng ý | Tách đầu ra thành kiến thức chính, việc cần làm, câu hỏi còn mở và thời hạn |
| Có nguy cơ nhảy sang AI trước khi thử cách đơn giản hơn | Đồng ý | Bổ sung phương án mẫu ghi chú và checklist không dùng AI trước khi đánh giá Workflow |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?                                                                                                                       | Kết quả / ảnh hưởng tới bài nhóm                                                                                                                                           |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pitch Problem Card         | Tôi trình bày ba card về tổng hợp sau workshop, tìm thông tin cho thảo luận và viết daily standup                                    | Nhóm thấy các vấn đề này có quy trình khá rõ, nhưng card workshop có impact lớn nhất cần kiểm chứng thêm.                                                                  |
| Phản biện bài của bạn khác | Tôi hỏi Hưng: “10 phút/lead BĐS là đo thật hay giả định lab? Form chuẩn và rule CRM đã xử lý được bao nhiêu phần trước khi cần AI?”. | Nhóm nhận ra baseline Lead BĐS chỉ là giả định, nên candidate JD–CV có bằng chứng và khả năng kiểm chứng tốt hơn.                                                          |
| Nhận phản biện             | Tôi được hỏi 2 giờ/buổi workshop là số liệu bấm giờ hay ước lượng, và đầu ra “kiến thức cần nhớ” có thể đánh giá thế nào.            | Tôi đổi thành “ước lượng cần xác nhận”, tách đầu ra thành kiến thức chính, việc cần làm, câu hỏi còn mở và thời hạn.                                                       |
| Gom cluster / cây OST      | Tôi tham gia gom các vấn đề đọc nhiều thông tin vào cluster “đối chiếu và ưu tiên thông tin”.                                        | Cây OST dùng outcome giảm thời gian đi từ dữ liệu đầu vào đến quyết định tiếp theo, không dùng tên công cụ làm opportunity.                                                |
| Chọn candidate problem     | Tôi cùng nhóm chọn **#6 — Đối soát JD ↔ CV khi ứng tuyển thực tập** do Đức đề xuất.                                                  | Candidate đạt 34/35 điểm và trở thành bài toán chung của nhóm; các candidate khác thiếu baseline hoặc khó tiếp cận dữ liệu.                                                |
| Kiểm chứng / research      | Tôi tham gia ghi lại workflow thực tế của sales BĐS khi xử lý lead thực tế hiện tại khi không dùng AI                                | Lead đến từ landing page, Facebook Lead Ads, hotline hoặc Zalo; sales tự đọc, hỏi bổ sung thông tin, đánh giá nhu cầu–ngân sách–độ sẵn sàng rồi mới ưu tiên gọi.           |
| Quy trình nhóm             | Tôi góp ý mô tả đúng quy trình thủ công hiện tại của sales BĐS                                                                       | Quy trình hiện tại là tiếp nhận lead → gom thông tin → đọc và kiểm tra nội dung → hỏi bổ sung nếu thiếu → tự đánh giá mức độ ưu tiên → chuyển cho sales phụ trách/gọi lại. |
| Problem Statement          | Tôi góp ý dùng metric thời gian tailor và tỷ lệ required skills được đối soát trung thực, không hứa hẹn đỗ ATS.                      | Statement v1 thu hẹp actor vào sinh viên CNTT/AI có hành vi tailor CV và bổ sung boundary không bịa kinh nghiệm.                                                           |
| Mức can thiệp AI           | Tôi đồng ý chọn **Workflow + Rule + HITL**: tool/checklist tách required/preferred và tạo bảng gap, người dùng duyệt.                | Không chọn Agent, không tự xây scorer, không tự viết hoặc nộp hồ sơ.                                                                                                       |
| Quyết định                 | Tôi đồng ý với quyết định **Go, phạm vi nhỏ**.                                                                                       | Pilot 2 tuần; nếu median không giảm ít nhất 30% so với baseline thì quay về Excel/checklist; nếu có 2 gợi ý kỹ năng sai mà người dùng suýt giữ lại thì dừng AI viết gợi ý. |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                                                   | AI hữu ích ở đâu?                                                                                | AI sai hoặc hời hợt ở đâu?                                                           | Tôi sửa gì bằng nhận định của mình?                                                                        |
| ------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- |
| CP1 Scan                       | x                                                                        | x                                                                                                | x                                                                                    | x                                                                                                          |
| CP2 Problem Card               | Phân tích CP1, đề xuất top 3 và phản biện các bottleneck.                | Giúp nhìn ra card workshop có quy trình và metric rõ hơn.                                        | AI hiểu sai card #3 là “đọc lại ghi chú” thay vì phân tích audio/video của buổi học. | Tôi sửa lại quy trình và ghi rõ 2 giờ/buổi chỉ là ước lượng cần bấm giờ.                                   |
| CP4 Research                   | x                                                                        | x                                                                                                | x                                                                                    | x                                                                                                          |
| CP5 Quy trình                  | Giúp ghi lại workflow Sales BĐS hiện tại theo những gì nhóm đã tìm hiểu. | Giúp sắp xếp các bước thủ công: tiếp nhận lead, gom thông tin, hỏi bổ sung, đánh giá và gọi lại. | x                                                                                    | x                                                                                                          |
| CP5–6 Problem Statement        | Phản biện v0 và gợi ý metric, boundary.                                  | Nhắc nhóm không đồng nhất keyword match với khả năng đỗ ATS.                                     | Target “pass mọi ATS” là phi thực tế.                                                | Tôi dùng baseline 30–45 phút, target dưới 20 phút và yêu cầu 100% required skills được đối soát minh bạch. |
| CP6 Mức can thiệp / quyết định | So sánh No AI, Rule, Workflow và Agent.                                  | Giúp làm rõ Workflow + Rule + HITL phù hợp hơn Agent.                                            | AI có thể bịa kỹ năng hoặc viết bullet sai sự thật.                                  | Tôi đồng ý **Go, phạm vi nhỏ**, không tự xây scorer và đặt kill criteria.                                  |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe các bạn trình bày, tôi nhận ra một problem tốt không chỉ là việc gây khó chịu mà còn phải có actor và bước nghẽn cụ thể. Các vấn đề về Git conflict, đối soát JD với CV và phân loại ticket khác domain nhưng đều có điểm chung là người dùng phải đọc nhiều thông tin rồi đưa ra một quyết định. Tôi chú ý đến cách các bạn ghi thời gian cho từng bước thay vì chỉ viết “mất nhiều thời gian”. Vì vậy tôi sửa card của mình: “tổng hợp sau workshop” phải chỉ rõ bước đọc, lọc và ghi việc cần làm. Tôi cũng học được rằng cùng một vấn đề có thể được giải quyết bằng checklist hoặc Rule trước khi cần AI. Nếu chỉ thiếu một trường thông tin trong lead thì form chuẩn hóa có thể hiệu quả hơn một mô hình phức tạp. Ngược lại, khi dữ liệu đến từ nhiều kênh và cách diễn đạt khác nhau, Workflow có người kiểm tra mới đáng cân nhắc. Top 3 không nhất thiết là ba ý tưởng sản phẩm hay nhất, mà là ba vấn đề có đủ bằng chứng để tiếp tục kiểm chứng trong thời gian ngắn.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm có lúc bị "solution-first". Khi thảo luận bài toán JD–CV, nhóm đã sớm nghĩ đến chatbot hoặc Agent tự động đọc JD, sửa CV và chấm điểm match. Đây là solution-first vì lúc đó chưa rõ ứng viên đang mất thời gian nhất ở bước nào và các công cụ hiện có đã đáp ứng đến đâu. Nhóm quay lại quy trình thật: chọn JD, tách required/preferred, đối chiếu CV, tìm gap, viết lại bullet và tự duyệt trước khi nộp. Research cho thấy đã có nhiều tool sẵn, nên nhóm không tự xây scorer mà chọn Workflow + Rule + HITL. Cách xử lý này cũng làm rõ AI không được bịa kỹ năng, tự nộp hồ sơ hay hứa hẹn đỗ ATS. Nhóm chuyển trọng tâm từ “xây một hệ thống AI” sang đo thời gian tailor và tính minh bạch của bảng đối chiếu. Tôi thấy một giải pháp nghe thông minh vẫn có thể giải quyết sai bottleneck nếu chưa hiểu người dùng đang làm gì.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã đổi ý về candidate của nhóm sau khi nghe phản biện về Lead BĐS. Ban đầu tôi thấy bài toán ưu tiên lead có impact lớn, nhưng khi được hỏi 10 phút/lead là số đo thật hay giả định lab, tôi nhận ra nhóm chưa có baseline và cũng chưa có dữ liệu vận hành. Ngược lại, bài toán JD–CV có quy trình rõ hơn và có thể kiểm chứng bằng các bộ hồ sơ thật. Nhóm vẫn giữ yêu cầu không nhảy ngay vào AI: Excel hai cột là baseline No AI, còn tool sẵn có chỉ được dùng trong pilot. Sau phản biện, tôi ủng hộ chọn JD–CV, Go phạm vi nhỏ và đặt mục tiêu dưới 20 phút thay vì khẳng định chắc chắn công cụ sẽ giúp ứng viên đỗ ATS. Tôi cũng đồng ý rằng mọi bullet viết lại phải do người dùng duyệt và không được thêm kinh nghiệm không có.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điều làm tôi bất ngờ là thời gian tailor CV không cố định như 75 phút ban đầu. Hai snapshot được nhóm tổng hợp nằm khoảng 20–60 phút, nên nhóm chọn baseline tham chiếu 30–45 phút cho một hồ sơ đã tùy biến và ghi rõ phải bấm giờ thêm trong pilot. Research cũng cho thấy thị trường đã có Jobscan, Teal, Resume Worded và các tool tương tự. Điều này làm thay đổi hướng đi: nhóm không cần tự code một scorer, mà nên thử một Workflow có sẵn kết hợp checklist. Tín hiệu phản bác là keyword match không đồng nghĩa ứng viên sẽ đỗ ATS; một tool có thể gợi ý kỹ năng không thật hoặc bỏ qua ngữ cảnh dự án. Vì vậy nhóm chốt Go, phạm vi nhỏ trong hai tuần, không xem target dưới 20 phút là kết quả đã đạt. Nếu median không giảm ít nhất 30% so với baseline hoặc có hai gợi ý sai mà người dùng suýt giữ lại, nhóm sẽ quay về Excel/checklist hoặc dừng phần AI viết gợi ý.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là viết statement JD–CV mà không biến nó thành lời hứa “giúp ứng viên đỗ ATS”. Tôi phải tách actor thành sinh viên CNTT/AI đang tailor CV, quy trình thành sáu bước và bottleneck thành đối chiếu, tìm gap, viết lại. Metric cũng cần trung thực: baseline 30–45 phút là khoảng tham chiếu từ snapshot, target dưới 20 phút là kỳ vọng pilot, không phải kết quả đã đo. Boundary phải nói rõ AI không được bịa kinh nghiệm, tự nộp hồ sơ hoặc quyết định ứng viên phù hợp. Tôi cũng phải phân biệt required skills được đối soát đầy đủ với việc ứng viên phải có đủ mọi kỹ năng. Sau khi viết lại, statement hẹp hơn và phù hợp với quyết định Go phạm vi nhỏ. Một statement tốt chỉ cần chỉ ra quy trình, bottleneck, metric, boundary và cách kiểm chứng rõ ràng.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ thu thập các bộ JD–CV thật sớm hơn và ghi riêng thời gian đọc JD, đối chiếu, tìm gap và viết lại. Tôi sẽ hỏi thêm sinh viên có kinh nghiệm khác nhau để tránh lấy một cách tailor làm chuẩn chung. Tôi cũng sẽ kiểm tra required/preferred được đánh dấu có nhất quán không và tool có gợi ý kỹ năng không tồn tại trong CV hay không. Ở phần phản biện, tôi sẽ mạnh hơn ở ba điểm: hỏi baseline cho từng mốc thời gian, yêu cầu thử Excel/checklist trước khi dùng AI, và kiểm tra đầu ra trên các JD khác ngành. Tôi sẽ giữ kill criteria của nhóm: median không giảm ít nhất 30% thì quay về No AI/Rule; có hai gợi ý sai mà người dùng suýt giữ lại thì dừng AI viết gợi ý. Mục tiêu là giúp nhóm pilot nhỏ, có dữ liệu và có ngưỡng dừng thay vì cố chứng minh AI chắc chắn cần thiết.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài nhóm chọn vấn đề sinh viên CNTT/AI mất thời gian đối chiếu yêu cầu trong JD với CV khi ứng tuyển thực tập. Quy trình gồm chọn JD, tách required/preferred, đối chiếu CV, tìm gap, chỉnh bullet rồi người dùng tự duyệt và nộp. Bottleneck là bước 3–5; baseline tham chiếu 30–45 phút và target pilot dưới 20 phút/bộ hồ sơ. AI chỉ được hỗ trợ tách yêu cầu và tạo bảng gap, không được bịa kỹ năng, tự viết không kiểm duyệt hoặc tự nộp hồ sơ. Mức can thiệp là Workflow + Rule + HITL, dùng tool/checklist có sẵn thay vì tự xây scorer. Nhóm quyết định **Go, phạm vi nhỏ** trong hai tuần. Nếu median không giảm ít nhất 30% hoặc có hai gợi ý sai mà người dùng suýt giữ lại, nhóm sẽ quay về Excel/checklist hoặc dừng phần AI viết gợi ý.

---

## 7. Tài liệu tham khảo

- [docs/01-worksheet.md](../../docs/01-worksheet.md)
- [README.md](../../README.md)
- [RUBRIC.md](../../RUBRIC.md)
- [Research Current Workflow of Sales](https://digital.lib.ueh.edu.vn/bitstream/UEH/69636/1/8.pdf)
