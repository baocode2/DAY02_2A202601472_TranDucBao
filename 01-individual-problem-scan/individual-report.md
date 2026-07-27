# 01 — Individual Problem Scan

## Thông tin cá nhân

| Họ và tên | Mã học viên |
|---|---|
|Trần Đức Bảo |2A202601472 |

## Case nghiên cứu: Quá trình xin giấy tờ từ ban CTSV của sinh viên


---

## Scan rộng

> Tối thiểu 5 problems, càng cụ thể càng tốt. Bonus nếu 8-10+ problems mà vẫn cụ thể (không tính list dài nhưng chung chung).

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Xin giấy xác nhận sinh viên từ CTSV (vay vốn, xin việc, thực tập, học bổng...) mỗi khi cần | Sinh viên, CTSV |  3-5 ngày xử lý/lượt, phải đến trực tiếp 2-3 lần |
| 2 | Tốn thời gian | Xin xác nhận / chữ ký từ cố vấn học tập trước khi nộp CTSV | Sinh viên, cố vấn học tập | 1-2 ngày chờ + phải đi lại |
| 3 | AI có thể tốt hơn | Không có checklist rõ cần giấy tờ gì cho từng mục đích (vay vốn khác xin việc khác học bổng) | Sinh viên | Bị trả đơn / phải làm lại vì thiếu giấy tờ đính kèm |
| 4 | Pain từ người khác | CTSV phải xử lý thủ công nhiều đơn giống nhau; sinh viên hỏi lại tiến độ liên tục qua email/Facebook | CTSV, sinh viên | Email/tin nhắn hỏi "đơn tôi tới đâu rồi" lặp lại |
| 5 | Lặp lại | Viết báo cáo tiến độ thực tập tuần cho cả mentor công ty và giảng viên trường, 2 định dạng khác nhau | Sinh viên thực tập, mentor, giảng viên | 30-40 phút/tuần x 12-16 tuần thực tập |
| 6 | Tốn thời gian | Tìm lại quy định/thủ tục cũ (học bổng, miễn giảm học phí, đăng ký thực tập) trong nhóm Zalo/Facebook lớp | Sinh viên cả lớp |  10-15 phút/lần tìm, nhiều lần không ra phải hỏi lại |
| 7 | Pain từ người khác | Bạn cùng lớp hỏi lại nhau cùng một câu hỏi thủ tục nhiều lần trong nhóm chat | Sinh viên cả lớp | Câu hỏi lặp lại 2-3 lần/tuần cao điểm (đầu kỳ, gần deadline) |
| 8 | Tốn thời gian | Đọc thông báo/quy chế học vụ dài (PDF nhiều trang) trước hạn nộp đơn để biết đủ điều kiện không | Sinh viên | 20-30 phút/lần đọc, dễ bỏ sót điều kiện |
| 9 | AI có thể tốt hơn | Không có công cụ nhắc hạn nộp theo từng loại thủ tục CTSV (học bổng, miễn giảm, gia hạn...) | Sinh viên | Từng trễ hạn nộp ít nhất 1 lần vì quên/không để ý thông báo |
| 10 | Lặp lại | Tổng hợp lại công việc đã làm trong tuần thực tập trước khi viết report | Sinh viên thực tập | 15-20 phút/tuần |

*Lăng kính gợi ý: Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác.*

---

## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Xin giấy tờ từ CTSV | Workflow rõ (7 bước), ảnh hưởng nhiều sinh viên, có thể ước lượng thời gian cụ thể | Con số "3-5 ngày" là ước tính, cần khảo sát thêm vài bạn để chắc chắn baseline |
| 2 | Viết báo cáo thực tập tuần (2 định dạng) | Lặp lại đều đặn hằng tuần, dễ đo thời gian, có 2 actor rõ (mentor + giảng viên) | Mức khác biệt định dạng giữa công ty/trường có thể không giống nhau ở mọi nơi thực tập |
| 3 | Tìm lại quy định cũ trong nhóm chat lớp/CTSV | Nhiều người cùng gặp, dấu hiệu thật dễ thấy (câu hỏi lặp lại trong chat) | Phạm vi "quy định" khá rộng, khó xác định nguồn dữ liệu chuẩn để tra cứu |

---

## Problem Card #1 — Xin giấy tờ từ CTSV

**Problem 1 câu:**
Mỗi khi cần giấy xác nhận sinh viên (vay vốn, xin việc, thực tập, học bổng...), sinh viên mất trung bình 3-5 ngày làm việc và phải đến trực tiếp văn phòng CTSV 2-3 lần vì thiếu thông tin, sai mẫu đơn, hoặc không rõ đơn đang xử lý đến đâu.

**Actor:**
Sinh viên cần giấy tờ xác nhận cho mục đích vay vốn / xin việc / thực tập / học bổng.

**Thời điểm / bối cảnh:**
Rải rác quanh năm, tăng mạnh vào đầu mỗi kỳ học và các đợt deadline nộp hồ sơ thực tập/vay vốn (khoảng tháng 8-9 và tháng 1-2).

**Current workflow (3-7 bước):**

```text
1. Tìm đúng mẫu đơn trên website trường/CTSV
2. Điền đơn (tay hoặc online)
3. Xin xác nhận/chữ ký từ cố vấn học tập hoặc phòng ban liên quan
4. Nộp đơn tại quầy CTSV, xếp hàng chờ
5. Chờ CTSV xử lý và duyệt
6. Quay lại nhận giấy tờ, xếp hàng
7. Kiểm tra lại thông tin trên giấy, nếu sai phải làm lại từ bước 1
```

**Bottleneck:**
Bước 3 và bước 5 — chờ duyệt qua nhiều cấp mà không có công cụ tra cứu tiến độ, khiến sinh viên phải chủ động hỏi lại (email/hỏi trực tiếp) khoảng 2-3 lần mỗi lượt xin để biết đơn đến đâu.

**Impact:**
Tổng thời gian mỗi lượt xin giấy tờ khoảng 3-5 ngày (chủ yếu là thời gian chờ), cộng thêm khoảng 60-90 phút thao tác chủ động của sinh viên (đi lại + xếp hàng + hỏi lại tiến độ). Mỗi sinh viên có thể cần xin loại giấy tờ này 2-3 lần/năm học. Nếu trễ, có thể ảnh hưởng đến deadline nộp hồ sơ vay vốn/thực tập.

**Success metric:**
Giảm thời gian xử lý từ 3-5 ngày xuống còn 1-2 ngày; giảm số lần sinh viên phải đến trực tiếp từ 2-3 lần xuống 1 lần; giảm số lượt hỏi lại "đơn tôi tới đâu rồi" gửi tới CTSV.

**Non-AI alternative:**
Hệ thống tra cứu trạng thái đơn online (rule-based) + form chuẩn hóa online để tránh sai mẫu đơn ngay từ đầu.

**AI hypothesis:**
AI hỗ trợ sinh viên xác định đúng loại đơn/giấy tờ cần dựa trên mục đích sử dụng (vay vốn, xin việc,...) và đưa checklist giấy tờ đính kèm, giảm việc bị trả đơn vì thiếu/sai. AI không tự động duyệt hoặc ký thay CTSV.

**Quick gut:**
- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — khoảng 3-5 ngày (trong đó ~90 phút thao tác chủ động)

[1 Tìm đúng mẫu đơn: 10']
→ [2 Điền đơn: 15']
→ [3 Xin xác nhận/chữ ký liên quan: 1-2 ngày chờ + 20' đi lại]  <-- bottleneck
→ [4 Nộp đơn tại quầy CTSV, xếp hàng: 30']
→ [5 CTSV xử lý và duyệt: 2-4 ngày]  <-- bottleneck
→ [6 Quay lại nhận giấy, xếp hàng: 20']
```

### Draft future workflow

```text
FUTURE STATE — khoảng 1-2 ngày (trong đó ~30 phút thao tác chủ động)

[1 AI gợi ý đúng loại đơn + checklist giấy tờ cần: 3']
→ [2 Điền đơn online theo mẫu chuẩn hoá: 10']
→ [3 Nộp online, hệ thống tự cập nhật trạng thái: 2']
→ [4 CTSV duyệt và xử lý: 1-2 ngày]  <-- human boundary (CTSV vẫn là người duyệt cuối)
→ [5 Nhận thông báo khi đơn xong, nhận giấy (điện tử hoặc đến 1 lần): 15']

Fallback: nếu AI gợi ý sai loại giấy tờ hoặc CTSV yêu cầu bổ sung → sinh viên quay lại quy trình thủ công, liên hệ trực tiếp CTSV.
```

---

## Problem Card #2 — Viết báo cáo thực tập tuần (2 định dạng)

**Problem 1 câu:**
Mỗi tuần thực tập, sinh viên mất khoảng 30-40 phút viết 2 phiên bản báo cáo tiến độ — một cho mentor công ty theo mẫu công ty, một cho giảng viên hướng dẫn theo mẫu trường — với nội dung gần như giống nhau nhưng phải trình bày khác nhau.

**Actor:**
Sinh viên đang trong kỳ thực tập (khoảng 10-16 tuần), phải báo cáo song song cho công ty và trường.

**Thời điểm / bối cảnh:**
Cuối mỗi tuần thực tập, thường vào thứ Sáu hoặc cuối tuần trước khi nộp.

**Current workflow (3-7 bước):**

```text
1. Tổng hợp lại công việc đã làm trong tuần từ note/task tracker
2. Viết báo cáo theo mẫu công ty, gửi mentor
3. Viết lại báo cáo theo mẫu trường, gửi giảng viên
4. Rà soát lại 2 bản trước khi gửi
```

**Bottleneck:**
Bước 3 — viết lại gần như cùng nội dung nhưng đổi format cho trường, cảm giác làm trùng công việc.

**Impact:**
30-40 phút/tuần x 12-16 tuần thực tập ≈ 6-10 giờ trong một kỳ thực tập chỉ để viết lại báo cáo trùng nội dung.

**Success metric:**
Giảm xuống 15-20 phút/tuần (chỉ viết 1 bản gốc, chuyển định dạng nhanh hơn); giảm số lần mentor/giảng viên phải hỏi lại vì thiếu thông tin.

**Non-AI alternative:**
Thống nhất 1 mẫu chung gộp đủ field cả 2 bên yêu cầu, nếu công ty và trường đồng ý dùng chung một mẫu.

**AI hypothesis:**
AI dựa trên 1 bản báo cáo gốc, tự động re-format sang mẫu công ty và mẫu trường; sinh viên vẫn review lại nội dung trước khi gửi.

**Quick gut:**
- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 30-40 phút/tuần

[1 Tổng hợp việc đã làm trong tuần: 10']
→ [2 Viết báo cáo cho mentor: 10']
→ [3 Viết lại báo cáo cho giảng viên (đổi format): 10-15']  <-- bottleneck
→ [4 Rà soát trước khi gửi: 5']
```

### Draft future workflow

```text
FUTURE STATE — 15-20 phút/tuần

[1 Tổng hợp việc đã làm (giữ nguyên): 10']
→ [2 AI re-format thành 2 bản theo mẫu công ty + mẫu trường: 2']
→ [3 Sinh viên review + chỉnh sửa: 5-8']  <-- human boundary
→ [4 Gửi 2 bản: 2']

Fallback: nếu AI format sai hoặc thiếu field bắt buộc → sinh viên tự viết lại bản đó như quy trình cũ.
```

---

## Problem Card #3 — Tìm lại quy định/thủ tục cũ trong nhóm chat lớp/CTSV

**Problem 1 câu:**
Mỗi khi cần biết lại một thủ tục cụ thể (điều kiện học bổng, hạn miễn giảm học phí, thủ tục xin thực tập), sinh viên mất 10-15 phút lục lại tin nhắn cũ trong nhóm Zalo/Facebook của lớp, và một phần đáng kể số lần không tìm ra nên phải hỏi lại.

**Actor:**
Sinh viên trong lớp, đặc biệt sinh viên năm nhất/năm hai chưa quen thủ tục.

**Thời điểm / bối cảnh:**
Rải rác quanh năm, tăng đột biến gần các đợt deadline học bổng / miễn giảm học phí / đăng ký thực tập.

**Current workflow (3-7 bước):**

```text
1. Nhớ lại đại khái thông tin từng được thông báo khi nào
2. Scroll/search từ khoá trong nhóm chat
3. Nếu không tìm ra, hỏi lại trong nhóm hoặc nhắn riêng người biết, chờ phản hồi
4. Xác nhận lại thông tin có còn hiệu lực không
```

**Bottleneck:**
Bước 2 — tìm kiếm bằng từ khoá trong chat rất kém hiệu quả vì thông tin nằm rải rác nhiều tin nhắn, không có cấu trúc hay index.

**Impact:**
*(ước tính)* 10-15 phút/lần tìm; nếu phải hỏi lại có thể mất thêm vài giờ chờ phản hồi. Nếu không tìm ra kịp, có thể lỡ hạn nộp liên quan đến thủ tục đó.

**Success metric:**
Giảm thời gian tìm xuống dưới 3 phút; giảm tỷ lệ "phải hỏi lại vì không tìm ra" xuống gần 0.

**Non-AI alternative:**
Một kênh/file FAQ cố định do lớp trưởng hoặc CTSV duy trì, ghim lại các thủ tục hay được hỏi.

**AI hypothesis:**
AI tóm tắt và index lại các thông báo thủ tục từ lịch sử chat thành FAQ có thể tra cứu, trả lời dựa trên thông báo gốc kèm trích dẫn nguồn.

**Quick gut:**
- [ ] No AI / process fix
- [ ] Rule
- [ ] Workflow
- [x] Agent / Workflow 
- [ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 10-15 phút/lần (có thể tới vài giờ nếu phải hỏi lại)

[1 Nhớ lại mốc thời gian thông báo: 2']
→ [2 Tìm trong lịch sử chat: 10-15']  <-- bottleneck
→ [3 Hỏi lại nếu không tìm ra: chờ phản hồi (không cố định)]
→ [4 Xác nhận thông tin còn hiệu lực: 5']
```

### Draft future workflow

```text
FUTURE STATE — dưới 3 phút

[1 Đặt câu hỏi cho FAQ/AI tra cứu: 1']
→ [2 AI trả lời kèm trích dẫn thông báo gốc: 1']
→ [3 Sinh viên xác nhận lại với nguồn trích dẫn: 1']  <-- human boundary

Fallback: nếu AI không tìm thấy nguồn hoặc thông tin có thể đã lỗi thời → hỏi trực tiếp CTSV/lớp trưởng như quy trình cũ.
```

---

## Card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
Problem Card #1 — Xin giấy tờ từ CTSV
```

Vì sao:

```text
Đây là case có workflow rõ nhất (7 bước cụ thể), ảnh hưởng tới số đông sinh viên (không riêng ai đi thực tập mới gặp), và có thể ước lượng thời gian/before-after rõ ràng nhất trong 3 card.
```

Câu hỏi tôi muốn nhóm challenge:

```text
Liệu CTSV có sẵn sàng số hoá quy trình duyệt/tra cứu trạng thái không, hay thực tế chỉ có thể cải thiện được ở phần checklist giấy tờ cần chuẩn bị trước khi nộp?
```

---

*01 — Individual Problem Scan — Day 02 Lab*
