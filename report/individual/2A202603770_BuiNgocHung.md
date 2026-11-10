# Báo cáo cá nhân — Bùi Ngọc Hùng

> CP1–CP2 ghi lại các Problem Card cá nhân của tôi. Từ CP3 trở đi, nội dung phản ánh quá trình nhóm G4 chọn **Problem Card #6 — Đối soát JD ↔ CV khi ứng tuyển thực tập** của Đức, với quyết định **Go, phạm vi nhỏ**. Các số liệu ước lượng cần được phân biệt với kết quả đã đo.
> Hướng dẫn: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Bùi Ngọc Hùng
- MSSV: 2A202603770
- Email trường (không bắt buộc):
- Tên nhóm: G4
- Link repo nhóm: https://github.com/danialtranz/K5-L3B-Day02-G4-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

> Các chỉ số dưới đây là ước lượng ban đầu theo trải nghiệm cá nhân, chưa được đo bằng log hoặc bấm giờ. Hãy kiểm tra lại từng con số trước khi nộp.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu / ước lượng cần xác nhận |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi làm dự án nhóm, tôi muốn theo dõi thay đổi code của các thành viên để tránh xung đột và cập nhật code kịp thời. | Thành viên nhóm phát triển phần mềm | Ước lượng kiểm tra Git 2–3 lần/ngày; khi có conflict mất 10–20 phút. Cần xem lịch sử Git và bấm giờ xử lý conflict. |
| 2 | Tốn thời gian | Khi làm dự án nhóm, tôi muốn biết tiến độ công việc của từng thành viên để phối hợp và hoàn thành đúng hạn. | Thành viên và trưởng nhóm | Ước lượng 10–15 phút/lần để hỏi và tổng hợp; 1–2 lần/ngày khi gần deadline. Cần ghi thời gian ở dự án gần nhất. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi gặp lỗi lập trình, tôi muốn tìm được nguyên nhân và hướng sửa phù hợp để tiếp tục phát triển ứng dụng. | Sinh viên IT / lập trình viên | Ước lượng 15–45 phút/lỗi, vài lần/tuần tùy dự án. Cần ghi lại lỗi và thời gian xử lý thực tế. |
| 4 | Lặp lại | Khi học từ vựng tiếng Hàn, tôi muốn ghi nhớ những từ đã học và ôn lại từ chưa thuộc để cải thiện khả năng ghi nhớ. | Người học tiếng Hàn | Ước lượng ôn 20–30 phút/ngày; cần theo dõi số từ nhớ lại sau vài ngày để xác nhận việc quên từ cũ. |
| 5 | Tốn thời gian | Khi sử dụng Internet tại ký túc xá, tôi muốn có kết nối ổn định để học tập và làm việc trực tuyến không bị gián đoạn. | Sinh viên sống tại ký túc xá | Ước lượng mạng chậm vài lần/ngày; mỗi lần mất 5–10 phút kiểm tra/chuyển mạng. Cần ghi nhật ký sự cố vài ngày. |
| 6 | Tốn thời gian | Khi cần tìm dịch vụ gần nơi ở, tôi muốn biết giá cả và chất lượng thực tế để lựa chọn dịch vụ phù hợp. | Sinh viên sống tại ký túc xá | Ước lượng 10–20 phút/lần, 1–3 lần/tuần. Cần bấm giờ một lần tìm dịch vụ thực tế. |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đồng bộ thay đổi code và xử lý conflict | Lặp lại khi làm dự án nhóm; có thể kiểm tra lịch sử Git và ghi thời gian xử lý. | Ước lượng kiểm tra Git 2–3 lần/ngày, conflict 10–20 phút; cần xác nhận bằng log và bấm giờ. |
| 2 | Tìm nguyên nhân lỗi lập trình | Có quy trình xử lý lỗi và thời gian mỗi lỗi để theo dõi. | Ước lượng 15–45 phút/lỗi; độ phức tạp mỗi lỗi khác nhau. |
| 3 | Theo dõi tiến độ bài nhóm | Có thể ghi thời gian hỏi/tổng hợp và số việc trễ. | Ước lượng 10–15 phút/lần; chưa xác nhận bottleneck chính. |

> Đây là top 3 cá nhân tôi pitch. Sau thảo luận, nhóm chọn candidate #6 của Đức về đối soát JD ↔ CV khi ứng tuyển thực tập; lựa chọn này khác với các Problem Card cá nhân ở trên.

### Problem Card #1 — Đồng bộ thay đổi code và xử lý conflict

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm dự án nhóm, tôi muốn theo dõi thay đổi code của các thành viên để tránh xung đột và cập nhật code kịp thời. |
| Actor | Thành viên nhóm phát triển phần mềm. |
| Thời điểm / bối cảnh | Khi nhiều thành viên cùng cập nhật code trong một dự án. |
| Quy trình hiện tại | Kiểm tra trạng thái Git → lấy thay đổi mới → xem diff → xử lý conflict nếu có → chạy thử và xác nhận thay đổi. |
| Bottleneck | Xem và xử lý conflict; ước lượng 10–20 phút mỗi lần, cần bấm giờ xác nhận. |
| Impact | Có thể chậm cập nhật hoặc phát sinh lỗi khi ghép thay đổi; cần ghi ví dụ từ dự án thật nếu đã gặp. |
| Success metric | Baseline ước lượng: kiểm tra Git 2–3 lần/ngày, xử lý conflict 10–20 phút/lần. Target đề xuất: dưới 10 phút/conflict. Đo bằng nhật ký Git và thời gian xử lý từng lần. |
| Phương án không dùng AI | Quy ước branch/commit, pull thường xuyên, checklist xử lý conflict và review code. |
| Giả thuyết về AI | AI có thể giải thích diff hoặc gợi ý điểm xung đột; thành viên phải tự kiểm tra và chạy test trước khi giữ thay đổi. |
| Cảm nhận nhanh | Thử Rule/checklist trước; chỉ cân nhắc AI khi diff phức tạp và có người kiểm tra. |

```text
HIỆN TẠI — thời lượng từng bước là ước lượng cần xác nhận
[1 Kiểm tra trạng thái Git: ~1'] → [2 Lấy thay đổi mới: ~1–2']
→ [3 Xem diff: ~3–7'] → [4 Xử lý conflict nếu có: ~10–20'] ← BOTTLENECK
→ [5 Chạy thử và xác nhận: ~3–5']
Tần suất kiểm tra ước lượng 2–3 lần/ngày; bước xử lý conflict chỉ xảy ra khi có conflict.
```

### Problem Card #2 — Tìm nguyên nhân lỗi lập trình

| Trường | Nội dung |
|---|---|
| Job Story | Khi gặp lỗi lập trình, tôi muốn tìm được nguyên nhân và hướng sửa phù hợp để tiếp tục phát triển ứng dụng. |
| Actor | Sinh viên IT / lập trình viên. |
| Thời điểm / bối cảnh | Khi chạy ứng dụng hoặc kiểm thử và nhận lỗi cần xử lý. |
| Quy trình hiện tại | Tái hiện lỗi → đọc log/thông báo → tìm tài liệu hoặc issue tương tự → thử cách sửa → chạy lại kiểm thử. |
| Bottleneck | Đọc log, tìm hướng xử lý và thử giải pháp; ước lượng tổng 15–45 phút/lỗi tùy độ phức tạp. |
| Impact | Công việc phát triển bị dừng hoặc kéo dài; cần ghi ví dụ lỗi và thời gian bị chặn. |
| Success metric | Baseline ước lượng 15–45 phút/lỗi. Target đề xuất giảm thời gian trung vị 25% mà không tăng lỗi hồi quy. Đo thời gian theo từng lỗi và kết quả kiểm thử. |
| Phương án không dùng AI | Tài liệu xử lý lỗi thường gặp, log rõ ràng và checklist debug. |
| Giả thuyết về AI | AI có thể giải thích log và gợi ý hướng kiểm tra; người dùng tự xác nhận nguyên nhân và chạy test. |
| Cảm nhận nhanh | Workflow có thể hỗ trợ; cần so sánh trước với checklist/tài liệu. |

```text
HIỆN TẠI — ước lượng từng bước, tổng khoảng 15–45 phút/lỗi
[1 Tái hiện lỗi: ~2–4'] → [2 Đọc log: ~3–8']
→ [3 Tìm tài liệu/issue: ~3–12'] ← BOTTLENECK cần xác nhận
→ [4 Thử cách sửa: ~5–15'] → [5 Chạy lại kiểm thử: ~2–6']
```

### Problem Card #3 — Theo dõi tiến độ bài nhóm

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm dự án nhóm, tôi muốn biết tiến độ công việc của từng thành viên để phối hợp và hoàn thành đúng hạn. |
| Actor | Thành viên và trưởng nhóm. |
| Thời điểm / bối cảnh | Trong lúc thực hiện dự án nhóm, đặc biệt khi gần deadline. |
| Quy trình hiện tại | Thống nhất đầu việc → chia người phụ trách → hỏi/cập nhật tiến độ → tổng hợp việc còn thiếu → điều chỉnh hoặc nhắc việc. |
| Bottleneck | Hỏi và tổng hợp tiến độ; ước lượng 10–15 phút/lần, 1–2 lần/ngày gần deadline. Cần xác nhận bước nào tốn thời gian nhất. |
| Impact | Có thể phát hiện việc trễ hoặc thiếu phần việc muộn; cần ghi ví dụ cụ thể từ dự án gần nhất. |
| Success metric | Baseline ước lượng 10–15 phút/lần. Target đề xuất dưới 5 phút/lần và không tăng số việc trễ. Đo thời gian cập nhật và số đầu việc trễ mỗi tuần. |
| Phương án không dùng AI | Bảng công việc chung có người phụ trách, deadline và trạng thái cập nhật. |
| Giả thuyết về AI | Chưa rõ cần AI; có thể bắt đầu bằng bảng trạng thái và nhắc deadline theo Rule. |
| Cảm nhận nhanh | Rule hoặc Workflow đơn giản; chưa có lý do cho Agent. |

```text
HIỆN TẠI — ước lượng tổng 10–15 phút/lần cập nhật
[1 Thống nhất đầu việc/deadline: ~2–3'] → [2 Chia người phụ trách: ~2–3']
→ [3 Hỏi/cập nhật tiến độ: ~4–6'] ← BOTTLENECK cần xác nhận
→ [4 Tổng hợp việc còn thiếu: ~2–3'] → [5 Điều chỉnh/nhắc việc: ~1–2']
Gần deadline: ước lượng 1–2 lần/ngày; cần xác nhận bằng nhật ký.
```

### Card muốn pitch nhất

- Card số: **#1 — Đồng bộ thay đổi code và xử lý conflict**.
- Vì sao: có thể xem lịch sử Git và bấm giờ xử lý conflict ở dự án gần nhất.
- Câu hỏi muốn nhóm phản biện: Bottleneck chính là xử lý conflict hay quy ước branch/commit chưa rõ? Checklist có giảm thời gian đủ không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline và tần suất mới là ước lượng; hậu quả chưa có ví dụ cụ thể. | Đồng ý. | Gắn nhãn ước lượng; cần bấm giờ và ghi tình huống thật. |
| Bottleneck trong từng quy trình chưa được xác nhận. | Đồng ý. | Ghi rõ bước nghi là điểm nghẽn và việc cần đo. |
| Checklist, lịch nhắc hoặc bảng phân công có thể giải quyết mà không cần AI. | Đồng ý. | Đưa phương án đơn giản vào card để so sánh trước khi kết luận cần AI. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Nội dung tôi tham gia |
|---|---|
| Pitch Problem Card | Tôi trình bày ba Problem Card cá nhân: xử lý Git conflict, tìm nguyên nhân lỗi lập trình và theo dõi tiến độ bài nhóm. |
| Phản biện bài của bạn khác | Tôi đặt câu hỏi về bottleneck và bằng chứng thời gian trong candidate chấm độ nóng, ưu tiên lead; đồng thời nêu câu hỏi liệu checklist/Rule-based có thể giải quyết trước khi cần AI. |
| Nhận phản biện | Tôi ghi nhận câu hỏi của Vũ về nguồn số liệu 10–20 phút cho Git conflict và của Đức về việc thử checklist debug/Rule trước khi cân nhắc AI. |
| Gom cluster / cây OST | Tôi tham gia thảo luận cách gom vấn đề theo nút thắt. Nhóm đặt JD↔CV trong cluster đối chiếu tài liệu và xác định outcome chung là giảm thời gian từ đầu vào đến quyết định đúng mà không tăng lỗi. |
| Chọn candidate problem | Tôi cùng nhóm chọn **#6 — JD ↔ CV ứng tuyển thực tập** do Đức đề xuất. Đây là bài toán của nhóm, không phải một trong ba Problem Card cá nhân của tôi. |
| Kiểm chứng / research | Tôi tham gia xem xét các ghi nhận phỏng vấn và nghiên cứu thị trường được tổng hợp trong báo cáo nhóm; các ghi nhận gồm hai snapshot phỏng vấn và các công cụ hiện có. Tôi không ghi mình là người trực tiếp thực hiện phỏng vấn. |
| Quy trình nhóm | Tôi cùng nhóm làm rõ luồng ứng tuyển: chọn JD → tách yêu cầu bắt buộc/ưu tiên → đối chiếu CV → xác định khoảng trống và bằng chứng → chỉnh CV → người dùng rà soát và nộp. Nhóm xác định bước đối chiếu, tìm khoảng trống và viết lại là điểm tốn công. |
| Problem Statement và metric | Tôi tham gia rà soát actor, bottleneck và chỉ số. Nhóm ghi nhận thời gian nền khoảng 30–45 phút cho một hồ sơ đã tùy biến (các snapshot được báo cáo trong khoảng 20–60 phút), đặt mục tiêu dưới 20 phút; đây là baseline/target của nhóm cần kiểm tra trong pilot. |
| Mức can thiệp AI | Tôi tham gia cân nhắc giải pháp hiện có và checklist trước khi tự xây công cụ. Phạm vi nhóm chọn là công cụ/checklist sẵn có với người dùng kiểm tra kết quả; không xây scorer riêng, không tự nộp hồ sơ và không bịa kỹ năng/dự án. |
| Quyết định | Nhóm thống nhất **Go, phạm vi nhỏ**: pilot hai tuần, mỗi thành viên tùy biến ít nhất hai JD thực tế và ghi thời gian. Nếu median không giảm ít nhất 30% so với baseline tự bấm giờ thì quay về Excel/checklist; nếu có ít nhất hai gợi ý kỹ năng sai mà người dùng suýt giữ lại thì dừng phần AI viết gợi ý. |

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | Giới hạn / phần tôi tự kiểm tra |
|---|---|---|---|
| CP1 Scan | AI gợi ý cách sắp xếp và diễn đạt các vấn đề tôi tự nêu. | Hỗ trợ trình bày Job Story và nhóm ý. | Gợi ý không phải bằng chứng trải nghiệm; các con số cá nhân vẫn cần tôi xác nhận. |
| CP2 Problem Card | AI hỗ trợ cấu trúc card và đặt câu hỏi phản biện. | Nhắc kiểm tra actor, bottleneck, metric và phương án không dùng AI. | Thời lượng và target trong bản nháp là ước lượng, không được xem là dữ liệu đo. |
| CP3–CP6 | Khi hoàn thiện báo cáo, AI hỗ trợ đối chiếu bản cá nhân với `group_report.md`, sắp xếp đóng góp theo checkpoint và chỉnh cấu trúc/diễn đạt. | Giúp phát hiện nội dung cũ còn lệch sang Lead và làm rõ đâu là bài toán cá nhân, đâu là lựa chọn của nhóm. | Ở lần rà soát đầu, AI vẫn để sót quyết định Lead/Not Yet từ bản cũ, không khớp `group_report.md`. Tôi đối chiếu báo cáo nhóm và sửa lại thành JD↔CV, Go phạm vi nhỏ. AI không xác minh trải nghiệm hay phỏng vấn thay tôi; tôi cần kiểm tra mô tả đóng góp và số liệu. |
| CP7 Reflection | Tôi tự viết câu trả lời; AI góp ý độ rõ ràng, mức nhất quán với báo cáo nhóm và hỗ trợ đưa phần tôi cung cấp vào file. | Giúp nhận ra chỗ cần làm rõ, như phân biệt baseline với target và tránh nhầm dự án nhóm đã chọn. | Suy nghĩ và trải nghiệm trong reflection là của tôi; tôi cần đọc lại để bảo đảm câu chữ phản ánh đúng quan điểm của mình. |

## 6. Reflection (CP7)

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Khi nghe các bài toán của các thành viên, tôi nhận ra mỗi vấn đề cần được nhìn từ quy trình thực tế và người trực tiếp gặp khó khăn, thay vì chỉ nhìn vào ý tưởng giải pháp. Ví dụ, với bài toán chấm độ nóng và ưu tiên lead, tôi chú ý đến việc cần xác định rõ tiêu chí nào khiến một lead được ưu tiên và bước nào trong quy trình hiện tại đang tốn thời gian. Nếu chưa có bằng chứng về thời gian hoặc hiệu quả của cách làm hiện tại thì chưa thể kết luận giải pháp mới thực sự cần thiết.

Với bài toán JD↔CV do Đức đề xuất, tôi thấy rõ hơn một vấn đề có thể được phân tích thành các bước cụ thể: chọn JD, tách yêu cầu, đối chiếu CV, tìm khoảng trống và chỉnh sửa hồ sơ. Nhờ đó, nhóm có thể xác định bước nào tốn công nhất và đặt mục tiêu đo lường phù hợp.

Qua các bài toán này, tôi học được rằng một Problem Card tốt không chỉ cần mô tả khó khăn mà còn phải xác định được actor, bottleneck, tác động và bằng chứng cần kiểm chứng. Tôi cũng hiểu rằng không nhất thiết bài toán nào có thể áp dụng AI cũng nên dùng AI ngay; cần xem xét quy trình hiện tại và các cách đơn giản hơn trước.

### 6.2. Tôi có lúc nào bị solution-first không?

Có. Khi thảo luận về bài toán JD↔CV, tôi từng nghĩ đến việc sử dụng AI để tự động phân tích JD và CV, xác định mức độ phù hợp hoặc đề xuất nội dung chỉnh sửa. Tuy nhiên, sau khi xem xét các công cụ hiện có và phương án checklist, tôi nhận ra chưa chắc cần xây dựng một hệ thống AI riêng. Vấn đề quan trọng hơn là xác định công đoạn nào thực sự tốn thời gian và những giải pháp hiện tại chưa đáp ứng được điều gì. Qua đó, tôi hiểu rằng nên bắt đầu từ vấn đề thực tế rồi mới lựa chọn công nghệ phù hợp.

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.

Có. Khi trình bày Problem Card về Git conflict, tôi nhận được câu hỏi của Vũ về nguồn số liệu 10–20 phút xử lý conflict. Đức cũng đặt vấn đề liệu checklist debug hoặc Rule-based có thể giải quyết một số khó khăn mà không cần AI hay không. Những phản biện này khiến tôi nhận ra các con số mình đưa ra mới chỉ là ước lượng, chưa có log hoặc kết quả bấm giờ để xác nhận. Tôi đã điều chỉnh cách trình bày bằng cách ghi rõ đây là giả thuyết và bổ sung phương án không sử dụng AI để so sánh. Tôi học được rằng cần có bằng chứng trước khi kết luận một vấn đề cần ứng dụng AI.

### 6.4. Kết quả kiểm chứng có làm tôi bất ngờ không? Điều gì?

Qua các ghi nhận phỏng vấn và nghiên cứu được tổng hợp trong báo cáo nhóm, tôi nhận thấy thời gian tùy biến CV có sự khác biệt đáng kể giữa các trường hợp. Các snapshot được báo cáo nằm trong khoảng 20–60 phút, có trường hợp sử dụng CV chung chỉ mất khoảng 5 phút, trong khi baseline nhóm lựa chọn là 30–45 phút cho một hồ sơ đã tùy biến. Điều này giúp tôi nhận ra không phải ứng viên nào cũng thực hiện cùng một quy trình hoặc mất cùng một khoảng thời gian. Tuy nhiên, những ghi nhận này chưa đủ để khẳng định giải pháp sẽ tiết kiệm được bao nhiêu thời gian. Nhóm vẫn cần đo trực tiếp trong pilot để kiểm chứng hiệu quả.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Khó khăn lớn nhất đối với tôi là xác định đúng bottleneck thay vì chỉ mô tả hiện tượng chung là sinh viên mất nhiều thời gian chỉnh CV. Khi phân tích workflow, tôi nhận ra cần tách các bước đọc JD, xác định yêu cầu, đối chiếu CV, tìm khoảng trống và chỉnh sửa nội dung. Bên cạnh đó, tôi cũng phải phân biệt baseline được ghi nhận từ các snapshot với target do nhóm đề xuất. Qua đó, tôi hiểu rằng Problem Statement cần mô tả đúng vấn đề hiện tại và có các chỉ số đủ rõ để kiểm chứng.

### 6.6. Nếu làm lại, tôi sẽ đổi gì?

Nếu làm lại, tôi sẽ chủ động thu thập dữ liệu và đo thời gian từng công đoạn sớm hơn. Tôi cũng sẽ tìm hiểu kỹ các công cụ hiện có để so sánh với quy trình hiện tại, thay vì vội đề xuất xây dựng một giải pháp mới. Khi thảo luận nhóm, tôi sẽ phản biện rõ hơn về tính cần thiết của từng chức năng, đặc biệt là việc có cần AI hay chỉ cần checklist và công cụ sẵn có. Điều này giúp nhóm thu hẹp phạm vi, tránh phát triển những chức năng không thực sự cần thiết và đánh giá hiệu quả một cách khách quan hơn.

### 6.7. Explain the chain: Problem → Workflow → Metric → Boundary → AI intervention → Decision

Bài toán nhóm lựa chọn là sinh viên mất nhiều thời gian khi đối chiếu yêu cầu của JD với CV để ứng tuyển thực tập. Workflow gồm chọn JD, tách yêu cầu bắt buộc và ưu tiên, đối chiếu CV, xác định khoảng trống, chỉnh sửa nội dung và rà soát trước khi nộp. Baseline nhóm sử dụng là khoảng 30–45 phút cho một hồ sơ đã tùy biến, trong khi các snapshot được báo cáo nằm trong khoảng 20–60 phút; mục tiêu pilot là giảm thời gian xuống dưới 20 phút và trước khi nộp, người dùng đánh dấu cover/không cover cho 100% yêu cầu bắt buộc. Boundary là không tự nộp hồ sơ, không bịa kỹ năng hoặc dự án và người dùng phải kiểm tra lại các gợi ý. Nhóm ưu tiên sử dụng công cụ và checklist hiện có, kết hợp AI hỗ trợ khi phù hợp, thay vì xây dựng một hệ thống chấm điểm riêng. Quyết định cuối cùng là **GO với phạm vi nhỏ**: pilot trong hai tuần, mỗi thành viên tùy biến ít nhất hai JD thực tế và ghi lại thời gian thực hiện. Nếu thời gian trung vị không giảm ít nhất 30% so với baseline tự đo, nhóm sẽ quay lại Excel/checklist; nếu có ít nhất hai gợi ý kỹ năng sai mà người dùng suýt giữ lại, nhóm sẽ dừng phần AI viết gợi ý.

---

## 7. Tài liệu tham khảo

- [README.md](../../README.md) — mục tiêu, thứ tự đọc và quy tắc chung của lab.
- [CHECKPOINTS.md](../../CHECKPOINTS.md) — yêu cầu CP1–CP2 và CP7.
- [docs/01-worksheet.md](../../docs/01-worksheet.md) — hướng dẫn và template từng checkpoint.
- [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md) — ví dụ cách trình bày; không sao chép nội dung.
- [group_report.md](../team/group_report.md) — báo cáo chung làm căn cứ cho CP3–CP7.
