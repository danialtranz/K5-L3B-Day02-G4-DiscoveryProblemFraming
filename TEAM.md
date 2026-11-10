# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: G4
- Candidate problem nhóm chọn (1 câu): Khi nộp hồ sơ thực tập nhiều công ty, sinh viên CNTT/AI muốn đối soát JD với CV nhanh và đủ từ khóa, để giảm thời gian tùy biến hồ sơ và giảm rủi ro bị loại sớm ở vòng lọc
- Quyết định cuối (Go / Not Yet / No-Go): Go, phạm vi nhỏ

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Bùi Ngọc Hùng | 2A202603770 | Thành viên | Ngochung1772k4 |
| 2 | Vũ Quang Thanh | 2A202603736 | Thành viên | thanhvu101 |
| 3 | Phạm Minh Đức | 2A202603758 | Thành viên | ducpham13 |
| 4 | Đào Đức Duy | 2A202603900 | Thành viên | D121104 |
| 5 | Trần Cảnh Hưng | 2A202603759 | Trưởng nhóm | danialtranz |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Hưng | Đức, Duy, Thanh, Hùng | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Đức | Hưng, Duy, Thanh, Hùng | Assumption map, snapshot hoặc survey |
| CP4 — Research | Thanh | Đức, Hưng, Duy, Hùng | Bảng research có link |
| CP5 — Quy trình trước/sau | Hùng | Thanh, Duy, Hưng, Đức | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Đức | Duy, Thanh, Hùng, Hưng | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Duy | Thanh, Hùng, Đức, Hưng | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Hưng | Thanh, Duy, Hùng, Đức | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### BuiNgocHung-2A202603770

**Phần việc phụ trách:**

- Người chính: CP5 — Quy trình trước/sau
- Người hỗ trợ: CP3, CP4 Kiểm chứng, CP4 Research, CP5 PS v0, CP6 Mức can thiệp, CP6 Quyết định

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 Problem Card cá nhân (Git conflict, debug lỗi, theo dõi tiến độ nhóm); tham gia phản biện baseline/Rule trước khi nhảy AI
- Cùng nhóm chọn candidate #6 JD↔CV; làm rõ luồng ứng tuyển 6 bước và bottleneck ở đối chiếu / tìm gap / viết lại
- Rà soát actor, metric (baseline ~30–45' → target dưới 20') và ủng hộ Go phạm vi nhỏ với ngưỡng dừng pilot

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` §2.1 pitch #1–#2 (Hùng); phản biện nhận được từ Thanh/Đức
- `group_report.md` §4 quy trình trước/sau + before/after; §8 quyết định Go
- File cá nhân: `report/individual/2A202603770_BuiNgocHung.md`

**Điều mình học được từ phần nhóm:**

- Problem tốt cần actor–bottleneck–bằng chứng, không chỉ ý tưởng giải pháp; checklist/Rule có thể đủ trước khi nghĩ tới AI; cần phân biệt baseline đo được với target kỳ vọng.

### VuQuangThanh-2A202603736

**Phần việc phụ trách:**

- Người chính: CP4 — Research
- Người hỗ trợ: CP3, CP4 Kiểm chứng, CP5 Quy trình, CP5 PS v0, CP6 Mức can thiệp, CP6 Quyết định

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch #11 định giá chuyển nhượng và #12 rà soát hợp đồng; phản biện baseline lead của Hưng
- Người chính research: phối hợp đối chiếu hướng giải pháp đã có; Đức/Hưng hỗ trợ desk research tool (Jobscan, Teal, Resume Worded…) và tín hiệu Reddit
- Góp ý metric thời gian tailor + required skills cover trung thực; đồng ý Workflow + Rule + HITL và Go phạm vi nhỏ

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` §2.1 pitch #11–#12; §2.4 bất đồng nghiêng bài BĐS rồi xếp sau
- `group_report.md` §3.3 bảng research có link; §6–§8 mức can thiệp và quyết định
- File cá nhân: `report/individual/2A202603736_VuQuangThanh.md`

**Điều mình học được từ phần nhóm:**

- Problem tốt phải có actor và bước nghẽn cụ thể; dễ bị solution-first (chatbot/Agent) nếu chưa rõ bottleneck; keyword match ≠ đỗ ATS; nên Go phạm vi nhỏ với kill criteria rõ.

### PhamMinhDuc-2A202603758

**Phần việc phụ trách:**

- Người chính: CP4 — Kiểm chứng; CP5 — Problem Statement v0
- Người hỗ trợ: CP3, CP4 Research, CP5 Quy trình, CP6 Mức can thiệp, CP6 Quyết định

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Owner candidate #6 JD↔CV; pitch thêm #7 rubric lab và #8 action item họp; bảo vệ #6 đạt 34/35
- Người chính kiểm chứng: khung Mom Test, gắn snapshot PV, hạ baseline 75' → ~30–45'; thu hẹp claim “đỗ ATS”
- Viết/chốt PS v0 (và đóng góp nâng v1): actor, bottleneck, metric phút/bộ, boundary HITL; hỗ trợ research tool và so 4 mức → Workflow

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` §2.1 #6–#8; §2.4 chọn #6; §3 Assumption map + snapshot PV; §5 PS v0; §7 PS v1
- `report/assets/cp4-interview-snapshot-1.md` (và snapshot liên quan CP4)
- File cá nhân: `report/individual/2A202603758_PhamMinhDuc.md`

**Điều mình học được từ phần nhóm:**

- Lab ưu tiên bài kiểm chứng được hơn bài “nghe lớn”; phản biện ATS buộc thu hẹp metric về thời gian và trung thực; thị trường đã có tool → không tự xây scorer; boundary chống bịa skill là then chốt.

### DaoDucDuy-2A202603900

**Phần việc phụ trách:**

- Người chính: CP6 — Mức can thiệp + Problem Statement v1
- Người hỗ trợ: CP3, CP4 Kiểm chứng, CP4 Research, CP5 Quy trình, CP5 PS v0, CP6 Quyết định

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch #3 ticket, #4 hồ sơ hành chính, #5 nguyên liệu quán; phản biện then chốt cho #6 về “mỗi ATS khác nhau / Excel đã thử chưa?”
- Người chính CP6: chốt hướng Workflow (+ Rule required/preferred) + HITL, không Agent; góp phần siết PS v1 (actor tailor, boundary, eval)
- Tham gia cluster A/B/E; hỗ trợ kiểm chứng/research và theo dõi ngưỡng dừng pilot

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` §2.1 #3–#5 và câu hỏi phản biện tại #6; §2.2 cluster; §6 so sánh 4 mức; §7 PS v1 + eval
- File cá nhân: `report/individual/2A202603900_DaoDucDuy.md`

**Điều mình học được từ phần nhóm:**

- Cùng pattern routing/đối chiếu có thể khác domain nhưng metric/baseline quyết định shortlist; phản biện ATS giúp nhóm bỏ claim ảo; nên so Rule trước khi đẩy AI; Go nhỏ phải có điều kiện dừng rõ.

### TranCanhHung-2A202603759

**Phần việc phụ trách:**

- Người chính: CP3 — Hội tụ nhóm; CP6 — Quyết định
- Người hỗ trợ: CP4 Kiểm chứng, CP4 Research, CP5 Quy trình, CP5 PS v0, CP6 Mức can thiệp
- Vai trò thêm: trưởng nhóm — điều phối thời gian, phân công, thống nhất metric phút/bộ

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch #9 Lead→Sales và #10 tra cứu tài liệu BĐS; phản biện Duy/Đức/Thanh; điều phối + ghi cluster/OST/shortlist
- Đổi hướng từ nghiêng #9 sang chốt #6 vì team sống pain JD↔CV và kiểm chứng được trong lab
- Hỗ trợ research (Reddit complaints); điều phối thống nhất quy trình/PS; người chính chốt **Go, phạm vi nhỏ** theo 4 rủi ro + pilot/kill criteria

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` §2.1 #9–#10; §2.2–2.4 cluster/OST/chấm điểm và bất đồng #9 vs #6; §8 quyết định Go
- File cá nhân: `report/individual/2A202603759_TranCanhHung.md`

**Điều mình học được từ phần nhóm:**

- Lab chấm bài đo được và nhóm hiểu domain, không chấm ý tưởng enterprise nhất; dễ solution-first nếu gom theo tên tool; đổi ý sau phản biện là chọn bài chứng minh được; metric phút/bộ phải neo hành vi tailor thật.
