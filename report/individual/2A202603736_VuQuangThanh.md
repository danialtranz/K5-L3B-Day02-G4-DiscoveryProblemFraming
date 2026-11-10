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

| Hoạt động                  | Tôi đã làm gì?                  | Kết quả / ảnh hưởng tới bài nhóm                                                                                                                                                                                                                   |
| -------------------------- | ------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pitch Problem Card         | Thảo luận với nhóm problem card | Cùng lắng nghe và phân tích từng problem                                                                                                                                                                                                           |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:             |                                                                                                                                                                                                                                                    |
| Nhận phản biện             | Câu hỏi tôi nhận được:          | Tôi đã sửa gì:                                                                                                                                                                                                                                     |
| Gom cluster / cây OST      |                                 |                                                                                                                                                                                                                                                    |
| Chọn candidate problem     | Chọn problem của team leader    | team leader problem: Khi hàng loạt lead mới về từ landing page, Facebook Lead Ads, hotline hoặc Zalo trong ngày, tôi muốn biết nhanh ai là khách nóng theo nhu cầu–ngân sách–độ sẵn sàng, để không bỏ sót khách tốt và không tốn giờ vào khách rác |
| Kiểm chứng / research      | Research workflow Sales BĐS     | Nhóm biết được workflow chính của Sales BĐS trong thực tế                                                                                                                                                                                          |
| Quy trình nhóm             |                                 |                                                                                                                                                                                                                                                    |
| Problem Statement          |                                 |                                                                                                                                                                                                                                                    |
| Mức can thiệp AI           |                                 |                                                                                                                                                                                                                                                    |
| Quyết định                 |                                 |                                                                                                                                                                                                                                                    |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu?                                                     | AI sai hoặc hời hợt ở đâu?         | Tôi sửa gì bằng nhận định của mình?                                                                            |
| ------------------------------ | ---------------------- | --------------------------------------------------------------------- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| CP1 Scan                       | x                      | x                                                                     | x                                  | x                                                                                                              |
| CP2 Problem Card               | phân tích cp1          | đưa ra top 3 problem, phân tích các trường trong problem và phản biện | Hiểu sai quy trình problem card #3 | Sửa lại: không đọc lại ghi chú mà phân tích nội dung của buổi workshop/menter duty/office hour qua audio/video |
| CP4 Research                   |                        |                                                                       |                                    |                                                                                                                |
| CP5 Quy trình                  |                        |                                                                       |                                    |                                                                                                                |
| CP5–6 Problem Statement        |                        |                                                                       |                                    |                                                                                                                |
| CP6 Mức can thiệp / quyết định |                        |                                                                       |                                    |                                                                                                                |

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
