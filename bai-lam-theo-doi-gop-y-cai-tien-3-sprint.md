# Thiết kế cách theo dõi góp ý và cải tiến qua ba Sprint (RikkeiAssist)

Người thực hiện: Thu Hà, Scrum Master.
Đề xuất cho Scrum Team: Product Owner Minh Anh, Thu Hà và 5 Developers.

**Nhìn nhanh dữ liệu Sprint 11–13** (để chu trình nhắm đúng chỗ):

| Sprint | Góp ý | Đã hỏi rõ | Đưa vào xem xét Product Backlog | Improvement mới | Improvement còn mở cuối Sprint |
|---|---|---|---|---|---|
| 11 | 12 | 5 (42%) | 3 (25%) | 3 | 2 |
| 12 | 15 | 7 (47%) | 6 (40%) | 2 | 3 |
| 13 | 18 | 10 (56%) | 5 (28%) | 2 | 4 |

- Số góp ý tăng, tỷ lệ được hỏi rõ tăng chậm. Tỷ lệ được đưa vào xem xét Product Backlog không đều.
- Improvement còn mở tăng đều từ 2 lên 4 qua ba Sprint.
- **Cần xác nhận:** cuối Sprint 13 có 4 Improvement còn mở, nhưng đề chỉ liệt kê 3 (IM-11-02, IM-12-04, IM-13-03). Cái thứ tư chưa có dữ liệu. Mình không đoán nội dung và đánh dấu "chưa có thông tin" để nhóm bổ sung.

---

## Phần 1 – Chu trình theo dõi

Hai vòng chạy riêng, mỗi vòng gắn với một sự kiện. Không gộp Sprint Review và Sprint Retrospective, và không trộn góp ý sản phẩm với vấn đề nội bộ. Cả hai vòng dùng chung một nơi lưu (một trang hoặc bảng của nhóm) với hai bảng: **Sổ góp ý** và **Sổ Improvement**.

### Vòng A – Góp ý: từ Sprint Review tới Product Backlog

```
(1) Sprint Review: ghi góp ý vào Sổ góp ý, trạng thái "Mới"
     [Ghi: Thu Hà hoặc Minh Anh tại buổi họp; Developers bổ sung]
        ↓
(2) Làm rõ với nguồn góp ý (ngay tại Review hoặc trong 2 ngày làm việc sau)
     → trạng thái "Đã làm rõ" hoặc "Chưa rõ: còn thiếu gì"
     [Cập nhật: Minh Anh, cùng người hỏi lại nguồn]
        ↓
(3) Gom góp ý trùng ý, giữ nguyên mã cũ, gắn "trùng với F-xx-yy"
     [Cập nhật: Thu Hà]
        ↓
(4) Product Backlog refinement: xem xét và ghi quyết định
     → "Đã liên kết PBI-xx" / "Cần thêm thông tin" / "Chưa làm, kèm lý do" / "Không làm, kèm lý do"
     [Cập nhật: Minh Anh. Đây là quyết định xem xét, không phải cam kết]
        ↓
(5) Sprint Planning kế tiếp: chỉ PBI được chọn mới vào Sprint Backlog
     [Cập nhật: Developers cùng Minh Anh]
        ↓
(6) Sprint Review kế tiếp: báo lại cho nguồn góp ý trạng thái hiện tại, rồi ghi góp ý mới
     [Báo: Minh Anh]  ───►  quay lại (1)
```

### Vòng B – Improvement: từ Sprint Retrospective tới lần kiểm tra ở Sprint sau

```
(1) Sprint Retrospective: nhóm chọn tối đa 2 Improvement, ghi vào Sổ Improvement
     (hành động, nhóm theo dõi, lúc kiểm tra, bằng chứng, trạng thái "Mới")
     [Ghi: Thu Hà ghi, kết luận do cả Scrum Team quyết định]
        ↓
(2) Đưa Improvement vào Sprint Backlog của Sprint kế tiếp để làm cùng công việc khác
     [Cập nhật: Developers]
        ↓
(3) Trong Sprint: nhóm theo dõi cập nhật bằng chứng khi có, không chờ cuối Sprint
     [Cập nhật: nhóm theo dõi đã ghi]
        ↓
(4) Đầu Sprint Retrospective kế tiếp (khoảng 10 phút): nhóm xem bằng chứng và quyết định
     → "Hoàn thành (có bằng chứng)" / "Tiếp tục" / "Sửa lại" / "Dừng (có lý do)"
     [Cập nhật: Thu Hà ghi quyết định của Scrum Team]
        ↓
(5) Nếu "Tiếp tục" hoặc "Sửa lại": ghi lần kiểm tra tiếp theo  ───►  quay lại (3)
```

Cách tách hai vòng: nếu trong Retrospective có ý kiến về sản phẩm, Thu Hà ghi sang Sổ góp ý để Minh Anh xử lý ở Vòng A và không bàn trong Retrospective. Ngược lại, vấn đề cách làm việc trong Review được ghi sang Retrospective.

Chi phí thêm cho nhóm: khoảng 10 phút rà soát đầu Retrospective và vài phút ghi chép sau mỗi sự kiện, không thêm cuộc họp nào.

---

## Phần 2 – Bảng theo dõi

### Bảng 1 – Sổ góp ý (cột)

| Cột | Ý nghĩa |
|---|---|
| Mã | F-Sprint-số thứ tự |
| Nguồn | Ai góp ý |
| Nội dung | Ghi nguyên văn, không sửa lại |
| Làm rõ | Đã làm rõ / Chưa rõ (ghi còn thiếu gì) |
| Xem xét Product Backlog | Chưa xem xét / Đã xem xét (kèm quyết định và lý do) |
| Liên kết PBI | Mã PBI; có dấu "?" nếu chưa xác nhận |
| Trùng/Xung đột | Gom với mã nào, xung đột với góp ý nào |
| Người cập nhật | Người ghi lần cuối |
| Ghi chú lịch sử | Mỗi lần đổi trạng thái ghi thêm một dòng, không xóa dòng cũ |

**Mẫu F-11-04** (nguồn: Trưởng nhóm CSKH; nội dung: "Chuyển người sớm hơn khi AI không chắc chắn")

| Sprint | Điều ghi nhận | Làm rõ | Xem xét Product Backlog / Liên kết PBI | Người cập nhật |
|---|---|---|---|---|
| 11 | Ghi tại Sprint Review, trạng thái "Mới". | Chưa rõ ngưỡng. | Không có liên kết. | Thu Hà / Minh Anh |
| 12 | Không có thông tin nào làm rõ thêm; giữ nguyên, **không** đổi sang "đã tiếp nhận". | Vẫn chưa rõ ngưỡng. | Không có liên kết. | Minh Anh |
| 13 | F-13-05 (Nhân viên CSKH ca tối: "Chuyển cho người ngay khi AI trả lời 'tôi không chắc'") được gom là **trùng ý** với F-11-04, giữ cả hai mã. Gắn cờ "lặp lại qua 2 Sprint". Ghi xung đột với F-12-11 (Chủ cửa hàng muốn tự động hóa 90%). | Vẫn chưa rõ ngưỡng. | Không có liên kết. Việc cần làm: làm rõ ngưỡng trước Sprint Review Sprint 14. | Thu Hà |

### Bảng 2 – Sổ Improvement (cột)

| Cột | Ý nghĩa |
|---|---|
| Mã | IM-Sprint-số thứ tự |
| Improvement | Hành động cụ thể |
| Nhóm theo dõi | Một nhóm hoặc vai trò, không phải chỉ tiêu cá nhân |
| Lúc kiểm tra | Sự kiện hoặc Sprint cụ thể |
| Bằng chứng | Con số hoặc sản phẩm nhìn thấy được |
| Quyết định mỗi lần rà soát | Hoàn thành / Tiếp tục / Sửa lại / Dừng, kèm lý do |
| Ghi chú lịch sử | Mỗi lần rà soát ghi thêm một dòng, không xóa dòng cũ |

**Mẫu IM-11-02** ("Cấp đủ quyền môi trường thử nghiệm từ Ngày 1 và chạy Integration Test khi PBI đầu tiên sẵn sàng"; nhóm theo dõi: Developers)

| Sprint | Bằng chứng | Quyết định tại Retrospective |
|---|---|---|
| 11 | Integration Test đầu tiên ở **Ngày 8**. Đây là lúc tạo Improvement. | Mới. Kiểm tra ở Sprint 12. |
| 12 | Integration Test đầu tiên ở **Ngày 7**. Mới nhích 1 ngày. | Tiếp tục (chưa đạt). |
| 13 | Integration Test đầu tiên ở **Ngày 8**. Không cải thiện sau hai lần kiểm tra. | Tiếp tục, đưa vào Retrospective Sprint 14 để sửa lại. Xem Phần 3. |

Chỗ thiếu dữ liệu: chưa có bằng chứng về việc "cấp đủ quyền từ Ngày 1", và chưa ghi **ngày PBI đầu tiên sẵn sàng** nên chưa biết Integration Test chậm bao nhiêu so với mốc đề ra. Từ Sprint 14, ghi thêm cột "Ngày PBI đầu tiên sẵn sàng".

---

## Phần 3 – Quy tắc xử lý

### Tình huống 1: Chủ cửa hàng muốn tăng tự động hóa, nhân viên CSKH muốn chuyển người sớm

- Ghi hai góp ý thành hai dòng riêng với nguồn riêng (F-12-11 và F-11-04/F-13-05), không gộp và không bỏ dòng nào.
- Ghi quan hệ "xung đột" ở cả hai bên, và thêm rủi ro còn thiếu cho F-12-11 (chuyển người sớm làm giảm tỷ lệ tự động hóa, và ngược lại).
- Review chỉ ghi nhận, không chọn bên. Minh Anh làm rõ từng góp ý (đo ngưỡng "không chắc chắn", ý nghĩa của con số 90%) rồi quyết định thứ tự ở Product Backlog refinement và ghi lý do.
- Con số 90% chưa phải cam kết cho đến khi có quyết định của Product Owner.

### Tình huống 2: Góp ý trùng ý khác chữ, và PBI có dấu hỏi

- Góp ý trùng: gom lại bằng cột "Trùng", giữ cả hai mã và nguyên văn từng góp ý. Ví dụ F-13-05 trùng ý với F-11-04. Khi đếm góp ý, đếm thành một chủ đề và ghi rõ lặp qua mấy Sprint.
- PBI có dấu hỏi: F-12-07 giữ "PBI-52?" cho tới khi Minh Anh xác nhận hai bên thật sự liên quan. Khi còn dấu "?", **không tính** là "đã đưa vào xem xét Product Backlog". Nếu xác nhận không liên quan thì chuyển về "chưa có liên kết", ghi thêm một dòng lịch sử, không xóa dấu cũ.

### Tình huống 3: PO muốn báo mọi góp ý là "đã tiếp nhận"; Developer muốn đóng mọi Improvement quá một Sprint

**Quy tắc chung.**
1. Dùng bốn trạng thái riêng cho góp ý: "Đã ghi nhận" → "Đã làm rõ" → "Đã xem xét trong Product Backlog" → "Đã có quyết định". Báo cáo cuối Sprint ghi số lượng của từng trạng thái, không gộp thành "đã tiếp nhận".
2. Improvement chỉ đóng khi Scrum Team quyết định minh bạch tại Retrospective, với lý do và bằng chứng. **Tuổi của Improvement không phải lý do để đóng.** Khi đóng, dòng cũ vẫn giữ trong lịch sử.
3. Muốn bảng gọn hơn thì ra quyết định (hoàn thành, sửa lại hoặc dừng), không xóa hay ẩn dòng.

**Áp dụng cụ thể:**

| Improvement | Quyết định đề xuất cho Retrospective Sprint 14 | Lý do |
|---|---|---|
| **IM-11-02** | **Giữ mở và sửa lại.** Nhóm hỏi "vì sao ba Sprint vẫn Ngày 7–8" (nguyên nhân gốc), tách thành hành động nhỏ hơn có mốc rõ, chốt lại lúc kiểm tra. | Mới mở một Sprint thì chưa có kết luận, nhưng đã qua ba Sprint mà ngày chạy Integration Test không đổi. Đóng sẽ làm mất vấn đề đang lặp lại. Giữ nguyên chữ cũ thì lại lặp lại điều chưa hiệu quả. |
| **IM-12-04** (theo dõi lỗi kênh đã ngừng thí điểm) | **Dừng** bằng quyết định của Scrum Team, ghi "Dừng, không còn phù hợp", lý do "kênh không còn dùng", bằng chứng "kênh không còn dùng". Chuyển người theo dõi từ cá nhân Gia Huy sang nhóm. | Đây là trường hợp duy nhất có căn cứ để dừng: lý do là kênh đã ngừng, không phải vì để lâu. Dừng không tính là "Hoàn thành". |
| **IM-13-03** (Pairing khi tái hiện lỗi tích hợp) | **Tiếp tục thêm một lần kiểm tra** ở Sprint 14, sau đó nhóm quyết định hoàn thành hoặc đưa thành thỏa thuận làm việc. | Mới kiểm tra một lần, có hai phiên Pairing và thời gian tái hiện giảm nhưng chưa đủ để kết luận. Cũng không phải mở quá một Sprint. |

Improvement thứ tư còn mở cuối Sprint 13 (chưa có thông tin) sẽ được rà soát theo cùng quy tắc khi nhóm bổ sung.

### Tiêu chí đo được: sau 3 Sprint tới (Sprint 14–16) chu trình tạo ra thay đổi thật

> **Ngày chạy Integration Test đầu tiên sớm hơn mốc nhóm thống nhất ở ít nhất 2 trong 3 Sprint.**

- **Mốc cơ sở:** Ngày 8, 7, 8 ở Sprint 11–13. Mốc mục tiêu do nhóm chốt ở Retrospective Sprint 14; đề xuất không muộn hơn Ngày 4, để tính theo "ngày PBI đầu tiên sẵn sàng".
- **Nguồn dữ liệu:** cột bằng chứng của IM-11-02 trong Sổ Improvement.
- **Vì sao chọn tiêu chí này:** đây là kết quả công việc, không phải việc họp đúng lịch hay điền bảng đủ cột. Nó đo chu trình Retrospective → Improvement → kiểm tra có làm ngày chạy thật sự đổi hay không. Nếu không đạt, kết luận đó cũng được ghi lại và nhóm sửa lại hành động ở Retrospective kế tiếp.
- **Chỉ số phụ để theo dõi, không dùng thay tiêu chí chính:** tỷ lệ góp ý lặp lại (như F-11-04/F-13-05) có quyết định rõ ở Product Backlog, và số Improvement còn mở có kết luận.
