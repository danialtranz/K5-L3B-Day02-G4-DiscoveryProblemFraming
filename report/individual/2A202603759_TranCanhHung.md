# Báo cáo cá nhân — 2A202603759_TranCanhHung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Cảnh Hưng
- MSSV: 2A202603759
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: G1
- Link repo nhóm: https://github.com/danialtranz/K5-L3-Day02-G1-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

Bối cảnh scan: **bất động sản nói chung** — đội sale / lead ops nhận lead đa kênh (landing page, Facebook Lead Ads, hotline, Zalo…). Sale phải tự đọc và đoán ai là khách tiềm năng trong khi dữ liệu trùng/nhiễu/thiếu, chính sách–chiết khấu–giỏ hàng đổi liên tục theo phân khu / dự án.

> Scan **chỉ xoay quanh chuỗi lead scoring / enrich / route** — không mở sang content, attribution marketing, hay tư vấn pháp lý chung.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi hàng loạt lead mới về từ landing page, Facebook Lead Ads, hotline hoặc Zalo trong ngày, tôi muốn biết nhanh ai là khách nóng theo nhu cầu–ngân sách–độ sẵn sàng, để không bỏ sót khách tốt và không tốn giờ vào khách rác | Sale BĐS, Lead Ops | Volume lớn mỗi ngày (có thể tới hàng trăm–hàng nghìn lead tùy quy mô); sale tự đọc–đoán từng lead; lead nóng dễ bị trễ trong hàng đợi |
| 2 | Tốn thời gian | Khi phải tự đọc từng form/tin nhắn để “chấm” lead bằng cảm tính, tôi muốn có điểm ưu tiên rõ ràng trước khi gọi, để sắp xếp cuộc gọi theo thứ tự đáng làm nhất | Sale BĐS | Ước lượng ~5–15 phút/lead để đọc, đoán độ nóng và quyết định gọi trước/sau; nhân với volume lớn → cả buổi chỉ lọc lead |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi cùng một khách xuất hiện ở nhiều kênh với SĐT/tên/ghi chú lệch nhau, tôi muốn nhận ra đó là một người và gộp thông tin đủ dùng, để không gọi trùng và không chấm điểm trên dữ liệu sai | Lead Ops, Sale, khách hàng | Lead trùng/nhiễu/khuyết thiếu phổ biến khi chạy đa kênh trong BĐS; gọi trùng làm khách khó chịu và làm lệch pipeline |
| 4 | Tốn thời gian | Khi hồ sơ lead thiếu ngân sách, phân khu quan tâm hoặc thời điểm mua, tôi muốn biết còn thiếu field nào và cần bổ sung gì trước khi chấm, để điểm số không dựa trên đoán mò | Lead Ops, Sale | Lead từ ads/hotline thường thiếu field; sale phải gọi “dò thông tin” trước khi biết có đáng chase không |
| 5 | Pain từ người khác | Khi lead đã được giao nhưng không đúng sale hoặc không đúng phân khu, tôi muốn được nhận đúng người phụ trách, để khách được chăm đúng sản phẩm và không bị đẩy qua lại | Sale nhận lead, trưởng nhóm, khách | Giao sai phân khu → trả lead / chuyển tay; khách chờ; trưởng nhóm phải can thiệp tay |
| 6 | Pain từ người khác | Khi hệ thống hoặc đồng nghiệp đưa một thứ tự ưu tiên lead, tôi muốn hiểu vì sao lead này điểm cao/thấp, để tin và gọi theo đúng thứ tự thay vì bỏ qua danh sách | Sale BĐS, trưởng nhóm | Sale không tin “hộp đen” → vẫn tự đoán lại; điểm số không giải thích = không dùng |
| 7 | Lặp lại | Khi chính sách bán, chiết khấu hoặc trạng thái giỏ hàng đổi theo từng phân khu, tôi muốn tiêu chí ưu tiên lead vẫn khớp thực tế bán hiện tại, để không đẩy sale vào khách không còn căn / không còn ưu đãi phù hợp | Sale, vận hành phân khu, khách | Chính sách–giỏ hàng đổi liên tục; chấm điểm dựa rule cũ dễ lệch với hàng còn bán |
| 8 | Pain từ người khác | Khi điểm số hoặc phân luồng tự động có thể sai, tôi muốn trưởng nhóm được xem lại, sửa điểm và đổi người nhận trước khi chốt, để vẫn kiểm soát chất lượng và trách nhiệm với khách | Trưởng nhóm sale BĐS, Sale | Cần human-in-the-loop: override phân luồng; không để máy tự chốt toàn bộ khi volume và rủi ro cao |

**Nếu có dùng AI để gợi ý thêm:** giữ các pain quanh **đoán độ nóng (#1–2)**, **dữ liệu bẩn/thiếu (#3–4)**, **sai phân luồng (#5)**, **thiếu giải thích (#6)**, **chính sách/giỏ hàng đổi (#7)**, **cần HITL (#8)**. 

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

Ba card dưới đây là **ba lát cắt của cùng bài toán chấm điểm & phân luồng lead trong bất động sản**, không phải ba bài toán ngành khác.

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tự đoán độ nóng & ưu tiên gọi (#1–2) | Đúng pain cốt lõi trong BĐS đa kênh: volume lớn, sale tự đọc–đoán, bỏ sót khách nóng / lãng phí vào khách rác; đo được bằng phút/lead và thứ tự gọi | Baseline phút/lead và tỷ lệ “lead nóng bị gọi trễ” chưa đo trên data thật |
| 2 | Lead đa kênh trùng / thiếu / nhiễu trước khi chấm (#3–4) | Không làm sạch–làm giàu thì điểm số vô nghĩa; đây là bước bắt buộc trước khi chấm | Ghép trùng bằng SĐT đã đủ bao nhiêu %? Field nào thiếu nhiều nhất theo kênh? |
| 3 | Phân luồng sai + không giải thích + thiếu HITL (#5–6–8) | Ngay cả khi có điểm, sale không tin và trưởng nhóm không override được thì không đi vào vận hành thật | Ngưỡng điểm bao nhiêu thì auto-route, bao nhiêu bắt buộc trưởng nhóm duyệt? |

### Problem Card #1 — Chấm độ nóng & ưu tiên lead

| Trường | Nội dung |
|---|---|
| Job Story | Khi hàng loạt lead mới về từ landing page, Facebook Lead Ads, hotline hoặc Zalo trong ngày, tôi muốn biết nhanh ai là khách nóng theo nhu cầu–ngân sách–độ sẵn sàng, để không bỏ sót khách tốt và không tốn giờ vào khách rác |
| Actor | Sale BĐS (gọi lead) + Lead Ops / điều phối (xếp hàng đợi) trong doanh nghiệp bất động sản |
| Thời điểm / bối cảnh | Trong ngày bán hàng, lead đổ về liên tục đa kênh; sale phải chọn gọi ai trước khi khách “nguội” |
| Quy trình hiện tại (3–7 bước) | 1. Lead vào từ landing / FB Lead Ads / hotline / Zalo · 2. Sale hoặc điều phối mở từng record · 3. Đọc form/ghi chú, tự đoán nhu cầu–ngân sách–độ nóng · 4. Tự xếp thứ tự gọi trong đầu hoặc Excel · 5. Gọi / nhắn · 6. Ghi kết quả lại CRM |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4 (đọc + đoán + xếp ưu tiên): khoảng **5–15 phút/lead**; khi volume lớn thì cả buổi bị kẹt ở lọc lead thay vì bán |
| Impact (nếu không giải thì sao) | Bỏ sót khách nóng; lãng phí thời gian sale vào khách rác; tỷ lệ chuyển đổi phễu giảm; trải nghiệm khách không đồng đều giữa các ca |
| Success metric (baseline → target) | Thời gian quyết định ưu tiên: ~10 phút/lead → dưới 2 phút/lead; % lead “nóng” được liên hệ trong SLA (ví dụ 15–30 phút) tăng rõ; giảm tỷ lệ thời gian sale dành cho lead cuối cùng không chuyển đổi (đo trên mẫu 1–2 tuần) |
| Phương án không dùng AI | Rubric chấm tay 0–100 theo checklist (ngân sách, phân khu, thời điểm mua, nguồn) + queue sắp xếp trên CRM/Excel + SLA “lead nóng gọi trước” do trưởng nhóm định nghĩa |
| Giả thuyết về AI (nếu có) | Hệ thống đề xuất điểm 0–100 kèm lý do ngắn (nhu cầu / ngân sách / độ nóng) và mức tin cậy; sale/trưởng nhóm vẫn quyết định gọi theo điểm đã duyệt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ước lượng 5–15 phút/lead chỉ để quyết định "gọi trước hay sau"

[1 Lead vào đa kênh: landing / FB / hotline / Zalo]
→ [2 Mở từng record trên CRM/Excel: ~1']
→ [3 Đọc form/ghi chú, tự đoán nhu cầu–ngân sách–độ nóng: ~4–10'] ← BOTTLENECK
→ [4 Tự xếp thứ tự gọi: ~1–3'] ← BOTTLENECK
→ [5 Gọi / nhắn khách]
→ [6 Cập nhật kết quả]
```

### Problem Card #2 — Làm sạch & làm giàu lead đa kênh trước khi chấm

| Trường | Nội dung |
|---|---|
| Job Story | Khi cùng một khách xuất hiện ở nhiều kênh với thông tin lệch hoặc thiếu, tôi muốn gộp thành một hồ sơ đủ field cần chấm, để điểm ưu tiên không dựa trên dữ liệu trùng/nhiễu/đoán mò |
| Actor | Lead Ops / data sales BĐS; Sale chịu ảnh hưởng vì nhận lead “rỗng” hoặc trùng |
| Thời điểm / bối cảnh | Trước hoặc ngay khi lead vào hàng đợi chấm điểm; dữ liệu từ Meta, Zalo, hotline, landing không cùng schema |
| Quy trình hiện tại (3–7 bước) | 1. Lead đổ về từ nhiều webhook/form · 2. Nhân viên dò trùng SĐT/tên thủ công · 3. Copy–dán field còn thiếu từ kênh khác · 4. Hỏi lại sale/hotline nếu vẫn thiếu ngân sách–phân khu · 5. Mới đưa vào bước chấm / giao |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–4 (dedupe + bổ sung field): khoảng **5–20 phút/case trùng hoặc thiếu**; dễ bỏ sót trùng → gọi 2 lần hoặc chấm 2 hồ sơ |
| Impact (nếu không giải thì sao) | Điểm số sai vì input sai; sale gọi trùng; thống kê chuyển đổi phễu bị nhiễu; không biết kênh nào thật sự tạo khách nóng |
| Success metric (baseline → target) | % lead đủ field tối thiểu trước khi chấm: thấp (cần đo) → ≥90%; % lead bị phát hiện trùng trước khi gọi tăng; thời gian làm sạch/case giảm ít nhất 50% trên mẫu vận hành |
| Phương án không dùng AI | Rule khớp SĐT chuẩn hóa + bắt buộc field tối thiểu trên form + hàng đợi “thiếu dữ liệu” tách khỏi hàng “sẵn sàng chấm” + checklist enrich thủ công |
| Giả thuyết về AI (nếu có) | Gợi ý lead tương tự / field còn thiếu / câu hỏi enrich cần hỏi thêm; **không** tự bịa thông tin tài chính; người xác nhận trước khi ghi nhận |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 5–20 phút/case khi lead trùng hoặc thiếu field

[1 Lead vào từ nhiều kênh, schema khác nhau]
→ [2 Dò trùng SĐT/tên thủ công: ~3–8'] ← BOTTLENECK
→ [3 Copy–dán / gộp field từ kênh khác: ~2–5'] ← BOTTLENECK
→ [4 Gọi dò thêm nếu thiếu ngân sách–phân khu: ~5–10']
→ [5 Đưa vào bước chấm / giao]
```

### Problem Card #3 — Phân luồng đúng sale/phân khu + giải thích + HITL

| Trường | Nội dung |
|---|---|
| Job Story | Khi lead đã có mức ưu tiên, tôi muốn giao đúng sale/phân khu kèm lý do rõ ràng và cho trưởng nhóm sửa được trước khi chốt, để khách được chăm đúng người và đội ngũ chịu dùng hệ thống |
| Actor | Trưởng nhóm sale BĐS (duyệt/override) + Sale nhận lead + khách được phân công |
| Thời điểm / bối cảnh | Sau khi có điểm/ưu tiên; trước cuộc gọi đầu; chính sách–chiết khấu–giỏ hàng đang đổi theo phân khu |
| Quy trình hiện tại (3–7 bước) | 1. Điều phối xem lead đã đọc sơ · 2. Đoán phân khu / gán sale theo quen biết hoặc ca trực · 3. Sale nhận, đôi khi trả lại vì sai phân khu · 4. Trưởng nhóm xử lý tay các case tranh chấp · 5. Sale mới bắt đầu gọi |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–4 (gán sai → trả lead → trưởng nhóm xử lý): mỗi case sai lệch thêm **10–30 phút** và làm trễ khách nóng |
| Impact (nếu không giải thì sao) | Khách bị đẩy qua lại; sale mất niềm tin vào danh sách được giao; trưởng nhóm thành nút thắt tay; khó gắn trách nhiệm chuyển đổi theo phân khu |
| Success metric (baseline → target) | % lead bị reassign trong 24h giảm rõ; thời gian từ “đã có điểm” → “đã có owner chính thức” → dưới X phút (đo baseline trước); ≥ tỷ lệ lead có ghi chú lý do phân luồng mà sale đọc được trước khi gọi |
| Phương án không dùng AI | Ma trận routing theo phân khu / ca trực / sức chứa sale trên CRM + quyền override của trưởng nhóm + bắt buộc ghi chú lý do khi chuyển tay |
| Giả thuyết về AI (nếu có) | Đề xuất sale/phân khu + giải thích ngắn + kèm confidence; **bắt buộc HITL** với lead điểm cao / thiếu dữ liệu / conflict; trưởng nhóm được sửa điểm và đổi owner trước khi chốt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — mỗi case giao sai thêm ~10–30 phút (ước lượng)

[1 Lead đã đọc sơ / đã có cảm nhận độ nóng]
→ [2 Điều phối gán sale–phân khu theo quen biết/ca trực: ~2–5'] ← BOTTLENECK
→ [3 Sale nhận; nếu sai thì trả lead: + chờ]
→ [4 Trưởng nhóm xử lý tay tranh chấp: ~10–20'] ← BOTTLENECK
→ [5 Sale chính thức bắt đầu gọi]
```

### Card muốn pitch nhất

- Card số: **#1** (Chấm độ nóng & ưu tiên lead) — pain cốt lõi của chuỗi lead scoring BĐS
- Vì sao: Đây là pain nhìn thấy ngay trên phễu bán BĐS đa kênh (bỏ sót khách nóng / lãng phí khách rác). Card #2 và #3 là điều kiện để #1 chạy được trong thực tế (input sạch + route có giải thích/HITL). Nhóm có thể chốt candidate là **#1**, và đưa enrich + HITL routing vào boundary / quy trình tương lai ở CP5–CP6 thay vì chọn ba bài khác nhau.
- Câu hỏi muốn nhóm phản biện: Trong lab, ta thu hẹp phạm vi chỉ còn **chấm điểm 0–100 + giải thích + hàng đợi ưu tiên** (HITL trưởng nhóm), còn chuỗi enrich/route đầy đủ để thành “hướng tiếp theo” — hay bắt buộc giữ cả chuỗi enrich→score→route ngay từ candidate?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Bản mô tả ban đầu dễ trượt **solution-first** (tự xây agent, nhồi tech stack); nếu copy nguyên vào Problem Card sẽ lệch lab | Đồng ý | Tách pain thành Job Story/quy trình/bottleneck; tech stack chỉ giữ ở giả thuyết / hướng sau lab, không nhét vào cột Job Story; không gắn tên công ty cụ thể |
| “Hàng nghìn lead/ngày” và phút/lead chưa có số đo từ một DN cụ thể | Đồng ý | Giữ như ước lượng theo thực trạng BĐS đa kênh; đánh dấu cần kiểm chứng CP4 (phỏng vấn sale/trưởng nhóm BĐS hoặc survey) |
| Dễ nhảy Agent đa bước trong khi Rule rubric + ma trận routing có thể cover một phần | Đồng ý một phần | Ba card đều để cảm nhận **Workflow**; nhấn phương án không dùng AI; HITL bắt buộc ở card #3; Agent chỉ là giả thuyết nâng cao sau khi Rule/Workflow không đủ |
| Card #1 sẽ fail nếu bỏ qua dữ liệu bẩn (#2) và niềm tin/HITL (#3) | Đồng ý | Pitch #1 nhưng ghi rõ #2 và #3 là dependency; đề xuất đưa vào boundary và quy trình tương lai thay vì bỏ |

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
| CP1 Scan | Nhờ AI giúp tách pain thuần khỏi phần giải pháp/tech stack trong bài toán lead scoring BĐS | Liệt kê đủ các pain quanh đoán độ nóng, dữ liệu bẩn, sai route, thiếu giải thích, HITL | Hay viết lại thành “xây LeadScorer Agent / multi-agent” hoặc gắn tên công ty | Giữ Job Story không chứa tên sản phẩm/AI/công ty; scan chỉ trong chuỗi lead scoring BĐS nói chung |
| CP2 Problem Card | Đóng vai PM hoài nghi phản biện 3 card lead scoring BĐS | Chỉ ra bản đầu đang solution-first; metric chưa đo; dễ nhảy Agent sớm | Gợi ý nhồi full multi-agent/tech stack vào Problem Card | Tách 3 lát cắt pain (score / enrich / route+HITL); cảm nhận Workflow; tech stack để sau lab |
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

- Thực trạng vận hành lead đa kênh trong **bất động sản nói chung**: tự đoán độ nóng, dữ liệu trùng/nhiễu/thiếu, phân luồng sale/phân khu, cần HITL & bảo vệ dữ liệu khách (không gắn tên công ty; không copy tech stack vào Job Story)
- [docs/01-worksheet.md](../../docs/01-worksheet.md) — template và tiêu chí từng checkpoint
- [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md) — bài mẫu (học cách viết Job Story / Problem Card, không copy nội dung)
- [CHECKPOINTS.md](../../CHECKPOINTS.md) — CP1 / CP2
