# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   | Nguyễn Hoàng Hải | 2A202601426 | Trưởng nhóm |
| 2   | Phạm Quốc Bảo | 2A202601502 | Thành viên |
| 3   | Nguyễn Văn Thành | 2A202601030 | Thành viên |
| 4   | Nguyễn Duy Khánh | 2A202601530 | Thành viên |
| 5   | Ngô Xuân Ninh | 2A202601068 | Thành viên |
| 6   | Trần Đức Bảo | 2A202601472 | Thành viên |
| 7   | Trần Hoàng Long | 2A202601646 | Thành viên |
| 8   | Phạm Công Đạt | 2A202601406 | Thành viên |
| 9   | Nguyễn Sỹ Mạnh Cường | 2A202601040 | Thành viên |
| 10  | Nguyễn Chiến Thắng | 2A202601734 | Thành viên |

---

# 02 — Group Problem Statement

Case nhóm chọn: **Người mới tập gym gặp vấn đề về động tác & khối lượng bài tập, dẫn tới hệ quả sức khỏe xấu.**


## Group Convergence

### Bước 3.1 — Trình bày top 3

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Dấu hiệu thật / số liệu |
|---|---|---|---|---|---|
| 1 | Nguyễn Hoàng Hải *(trưởng nhóm)* | Tổng hợp tiến độ đồ án nhóm hằng tuần từ Trello/Discord/Github để báo cáo giảng viên | Sinh viên làm đồ án nhóm | Gom dữ liệu từ 3 nguồn rồi tự viết lại narrative | 45-60 phút/tuần, lặp lại suốt 12-14 tuần đồ án |
| 2 | Phạm Quốc Bảo | Tìm lại tài liệu bài giảng cũ trên LMS/Drive khi ôn thi, nhiều file trùng tên | Sinh viên ôn thi | Search theo từ khoá kém hiệu quả | 15-20 phút/lần tìm, 3-4 lần/tuần thi cử, ~20% lần không tìm ra phải hỏi lại |
| 3 | Nguyễn Văn Thành | Review code bạn cùng nhóm trước khi merge, đọc diff dài | Sinh viên làm dự án nhóm code | Đọc hiểu diff dài trước khi duyệt | 20-30 phút/lần review, 2-3 lần/tuần trong kỳ làm đồ án |
| 4 | Nguyễn Duy Khánh | Theo dõi deadline bài tập lớn từ 4-5 môn song song, dễ quên/nhớ nhầm | Sinh viên | Không có nơi tổng hợp deadline tập trung | Từng trễ hạn nộp 1-2 lần/kỳ học vì quên/nhớ nhầm |
| 5 | Ngô Xuân Ninh | Người mới tập gym không biết chọn bài tập phù hợp mục tiêu (giảm mỡ/tăng cơ) | Người mới tập gym | Chọn sai bài tập/nhóm cơ so với mục tiêu | 10-15 phút/buổi tự mò bài tập, 1-2 tháng đầu không thấy kết quả rõ |
| 6 | Trần Đức Bảo | Người mới tập gym sai động tác & khối lượng tập, dẫn tới chấn thương | Người mới tập gym | Không ai kiểm tra form/khối lượng khi mới bắt đầu | 45-60 phút/buổi có rủi ro sai form; chấn thương có thể khiến nghỉ tập 1-3 tuần |
| 7 | Trần Hoàng Long | Lên thực đơn ăn uống phù hợp lịch tập gym và ngân sách sinh viên | Người mới tập gym, sinh viên | Không biết cân đối dinh dưỡng theo mục tiêu tập | 20-30 phút/lần lên thực đơn, lặp lại mỗi tuần |
| 8 | Phạm Công Đạt | Tổng hợp câu hỏi ôn tập từ nhiều nhóm chat môn học trước kỳ thi | Sinh viên ôn thi | Câu hỏi rải rác nhiều nhóm chat, khó tổng hợp | 30-40 phút/lần tổng hợp, lặp lại 2-3 lần/năm học (mỗi kỳ thi) |
| 9 | Nguyễn Sỹ Mạnh Cường | Theo dõi chi tiêu cá nhân hằng tháng rải rác nhiều app/ví điện tử | Sinh viên | Dữ liệu chi tiêu phân mảnh nhiều nguồn | 20-30 phút/tháng tổng hợp, thường lệch 10-15% so với thực tế |
| 10 | Nguyễn Chiến Thắng | Viết feedback cho bài bạn cùng lớp trong buổi peer-review, không có checklist chuẩn | Sinh viên | Feedback thiếu nhất quán, tiêu chí không rõ | 15-20 phút/bài feedback, 3-5 bài/đợt peer-review |

### Bước 3.2 — Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Sức khỏe & tập luyện | #5 Ninh (chọn bài tập theo mục tiêu), #6 Bảo (form/khối lượng), #7 Long (dinh dưỡng theo lịch tập) | Người mới tập gym thiếu kiến thức nền để tự lên kế hoạch tập luyện/dinh dưỡng an toàn | 3/10 thành viên độc lập đề xuất — tín hiệu hội tụ mạnh nhất |
| B — Báo cáo / tổng hợp tiến độ | #1 Hải (tiến độ đồ án nhóm) | Gom dữ liệu từ nhiều nguồn rồi viết lại cho người khác đọc | Chỉ 1/10 thành viên đề xuất; pattern giống ví dụ mẫu (Weekly Report) |
| C — Tìm kiếm / tổng hợp tài liệu | #2 Quốc Bảo (tài liệu ôn thi), #8 Đạt (câu hỏi ôn tập) | Tìm đúng thông tin trong nhiều nguồn rời rạc | Phụ thuộc quyền truy cập dữ liệu (LMS, nhóm chat) |
| D — Review / feedback | #3 Thành (review code), #10 Thắng (feedback peer-review) | Đọc bản của người khác và chỉ ra thiếu sót theo tiêu chí chưa chuẩn hoá | Phạm vi hẹp, giới hạn trong lớp/nhóm code |
| E — Planning / theo dõi cá nhân | #4 Khánh (deadline), #9 Cường (chi tiêu) | Theo dõi trạng thái một việc kéo dài qua thời gian, dễ quên | Nhiều app có sẵn, khó tạo khác biệt |

### Bước 3.3 — Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Cluster A — Gym | 3/10 thành viên độc lập đề xuất, actor rõ (người mới tập gym), pain có hậu quả cụ thể (chấn thương) | Không ai trong nhóm là chuyên gia thể hình/y tế — cần boundary rõ, không để AI tự chẩn đoán |
| Cluster D — Review/feedback | 2/10 thành viên đề xuất, workflow rõ (đọc bản nháp → chỉ ra thiếu sót), dễ hình dung before/after | Phạm vi hẹp (chỉ trong lớp/nhóm code), khó đo impact ngoài phạm vi lab |
| Cluster C — Tìm kiếm tài liệu | 2/10 thành viên đề xuất, nhiều người khác cũng gặp dù không pitch, impact có thể rộng hơn | Phụ thuộc quyền truy cập dữ liệu LMS/nhóm chat, có thể ngoài tầm kiểm soát trong thời gian lab |

### Bước 3.4 — Score để đồng thuận

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Cluster A — Gym | 5 | 4 | 5 | 4 | 4 | 5 | 4 | 31 |
| Cluster D — Review/feedback | 4 | 4 | 3 | 3 | 4 | 4 | 3 | 25 |
| Cluster C — Tìm kiếm tài liệu | 4 | 3 | 4 | 3 | 3 | 4 | 3 | 24 |

Candidate nhóm chọn:

```text
Cluster A — Người mới tập gym: sai động tác & khối lượng tập.
```

Vì sao chọn:

- Có 3/10 thành viên độc lập nêu vấn đề liên quan, nên pain evidence mạnh nhất trong 3 candidate.
- Actor cụ thể (người mới tập gym), hậu quả có thể quan sát/đo được (chấn thương nhẹ, tỷ lệ bỏ tập).
- Có thể so sánh rõ Rule (bảng khối lượng chuẩn) / Workflow (AI cá nhân hoá + theo dõi tiến độ) / Agent (AI tự theo dõi và tự chẩn đoán) — mỗi mức có rủi ro khác biệt rõ ràng để tranh luận.
- Nhiều thành viên có kinh nghiệm tập gym cá nhân nên nhóm hiểu domain tương đối tốt dù không phải chuyên gia.

Vì sao không chọn các candidate còn lại:

- Cluster D (Review/feedback): workflow rõ nhưng phạm vi hẹp (chỉ trong lớp/nhóm code), khó thể hiện impact rộng ra ngoài buổi lab.
- Cluster C (Tìm kiếm tài liệu): impact có thể rộng nhưng phụ thuộc quyền truy cập dữ liệu LMS/nhóm chat mà nhóm không kiểm soát được trong thời gian lab, dễ trượt sang scope quá lớn.

Nếu có disagreement, nhóm xử lý thế nào:

```text
3/10 thành viên độc lập đưa cùng một cluster (gym) nên không có bất đồng lớn về việc chọn candidate.
Điểm cần thống nhất thêm: có nên gộp luôn "dinh dưỡng" (candidate #9) vào scope hay không.
Nhóm quyết định thu hẹp trước: tập trung vào "động tác & khối lượng tập" (candidate #1, #8);
phần dinh dưỡng (#9) để mở rộng sau nếu còn thời gian, tránh Problem Statement quá rộng.
```

---

## Quick Validation

Nhóm hỏi nhanh người mới tập gym quen biết (bao gồm một vài thành viên từng tự tập và bạn cùng ký túc xá/phòng gym trường).

| Nguồn | Số người | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Quick interview | 4 | 3/4 từng tập sai form ít nhất 1 bài (thường là squat/deadlift) trong tháng đầu; 2/4 từng đau lưng/vai phải nghỉ tập vài ngày | 1/4 có bạn tập cùng rành kỹ thuật nên được chỉnh form trực tiếp, không thấy cần thêm công cụ | Thu hẹp problem: không phải "mọi vấn đề khi tập gym", mà là "người mới tập KHÔNG có ai kèm cạnh (không thuê PT, không có bạn tập rành)" |
| Mini poll trong lớp | 8 | 5/8 từng tập gym; 3/5 nói từng tập sai khối lượng hoặc form ít nhất 1 lần trong 2 tháng đầu | 2/5 nói chỉ cần xem video YouTube kỹ là đủ, không thấy cần AI | Thêm non-AI alternative rõ ràng (video hướng dẫn có sẵn + bảng khối lượng chuẩn) để so sánh công bằng với AI |

Insight sau validation:

```text
Pain thật không nằm ở việc thiếu bài tập mẫu (có rất nhiều video có sẵn trên YouTube).
Pain nằm ở việc không ai cá nhân hoá và kiểm tra lại form/khối lượng theo đúng thể trạng
và tiến độ của từng người mới bắt đầu tập.
```

## Research giải pháp

> Các link dưới đây cần nhóm tự bấm kiểm tra lại trước khi nộp (mình không thể duyệt web để xác nhận còn hoạt động tại thời điểm nộp bài).

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Fitbod | https://fitbod.me/ | Tạo giáo án tập cá nhân hoá dựa trên thiết bị có sẵn & lịch sử tập | Tốt cho cá nhân hoá khối lượng/bài tập theo tiến độ | Không kiểm tra form thời gian thực, vẫn cần người tự đánh giá đúng/sai động tác | AI có thể tạo giáo án tốt, nhưng phần kiểm tra form vẫn cần con người/video tham chiếu |
| Freeletics AI Coach | https://www.freeletics.com/ | AI điều chỉnh cường độ bài tập theo phản hồi người dùng | Điều chỉnh khối lượng/cường độ linh hoạt theo feedback | Chủ yếu bodyweight, không sâu về kỹ thuật tạ tự do (squat/deadlift) | Học pattern "AI điều chỉnh dựa trên feedback", nhưng cần bổ sung hướng dẫn kỹ thuật tạ riêng |
| JEFIT | https://www.jefit.com/ | Thư viện bài tập kèm video hướng dẫn form + log tiến độ | Video demo động tác chi tiết theo từng nhóm cơ | Không có phản hồi cá nhân hoá real-time về form của chính người dùng | Dùng làm nguồn video chuẩn tham chiếu, chưa giải quyết việc "tự kiểm form của mình" |
| Khuyến nghị ACSM (American College of Sports Medicine) cho người mới tập | https://www.acsm.org/ | Chuẩn khối lượng/tần suất tập an toàn cho người mới bắt đầu | Nguồn uy tín, dùng làm baseline rule | Không cá nhân hoá theo từng người, chỉ là khung chung | Dùng làm Rule nền cho giáo án ban đầu, AI chỉ tinh chỉnh thêm theo mục tiêu/thiết bị |

Research takeaway:

```text
Không nên để AI/agent tự chẩn đoán form hay chấn thương. Hướng hợp lý hơn là Workflow:
dùng khung khối lượng chuẩn (ACSM) làm rule nền, AI cá nhân hoá giáo án theo mục tiêu/thiết bị,
người tập tự đối chiếu video mẫu (JEFIT/YouTube) để tự kiểm form, và dừng lại tìm HLV/bác sĩ thật
nếu có dấu hiệu bất thường.
```

## Workflow before/after

File nhóm nộp kèm (nếu vẽ lại bằng ảnh/Mermaid):

```text
02-group-problem-statement-workflow.png/pdf/md
```

Nội dung workflow:

```text
CURRENT STATE — 6 bước, rủi ro cao ở giữa buổi tập

[1 Tự tìm bài tập trên YouTube/Google theo mục tiêu mơ hồ: 10-15']
→ [2 Tự chọn khối lượng tạ/số reps theo cảm tính hoặc bắt chước người khác: 5']
→ [3 Tập theo form tự đoán, không ai kiểm tra động tác: 45-60']  <-- bottleneck
→ [4 Cảm thấy đau/mỏi bất thường sau buổi tập, tự tra Google: 15-20']
→ [5 Nếu đau kéo dài: nghỉ tập hoặc đi khám (mất vài ngày đến vài tuần)]  <-- bottleneck
→ [6 Quay lại tập nhưng vẫn lặp lại sai lầm cũ vì không ai chỉnh sửa]

FUTURE STATE — 5 bước, kiểm soát rủi ro ngay từ đầu

[1 Nhập mục tiêu, thể trạng, thiết bị có sẵn vào AI/app: 3']  -- Workflow step
→ [2 AI tạo giáo án khối lượng/set-rep theo rule nền (ACSM) + mục tiêu cá nhân: 2']  -- Rule + AI
→ [3 Tập theo giáo án, đối chiếu video mẫu để tự kiểm form: 45-60']
→ [4 AI theo dõi log, cảnh báo nếu tăng khối lượng quá nhanh: tự động]  -- Workflow step
→ [5 Người tập tự xác nhận trước khi tăng tạ; nếu có dấu hiệu đau bất thường thì dừng và hỏi HLV/bác sĩ thật]  -- Human boundary

Fallback:
AI gợi ý sai hoặc không chắc chắn về form/chấn thương → không tự làm theo AI,
phải hỏi HLV thật hoặc chuyên gia y tế.

Bottleneck mới:
Bước 5 — người tập tự xác nhận. Đây là bottleneck chấp nhận được vì AI không được phép
tự quyết định thay cho các vấn đề liên quan sức khỏe.
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Effort chuẩn bị trước buổi tập | 15-20 phút/buổi (mò mẫm) | 3-5 phút/buổi | Nhờ giáo án đã cá nhân hoá sẵn |
| Số bước | 6 | 5 | Gộp bước tìm bài tập + chọn khối lượng thành 1 bước có AI hỗ trợ |
| Rủi ro sai form/khối lượng | Cao, không ai kiểm tra | Giảm nhờ giáo án chuẩn hoá + video đối chiếu | Vẫn còn rủi ro nếu người tập tự đối chiếu sai |
| Bottleneck chính | Tự đoán form/khối lượng | Người tập tự xác nhận trước khi tăng tạ | Chuyển từ "không ai kiểm tra" sang "có checkpoint" |
| Risk mới | Không có AI hallucination | Có rủi ro AI gợi ý sai lệch nếu input thể trạng không chính xác | Cần dừng lại hỏi HLV/bác sĩ thật khi nghi ngờ |

## Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Người mới tập gym (sinh viên, người đi làm mới bắt đầu), chưa có kiến thức nền về động tác và khối lượng tập. |
| **Workflow** | Tự tìm bài tập → tự chọn khối lượng/số reps theo cảm tính → tập không ai kiểm tra form → gặp đau/chấn thương → tự tra cứu hoặc đi khám → có thể bỏ tập. |
| **Bottleneck** | Không có ai (người hoặc công cụ) kiểm tra form và khối lượng tập phù hợp ngay từ đầu, khiến sai lệch tích lũy qua nhiều buổi. |
| **Impact** | Rủi ro chấn thương nhẹ-vừa trong 1-3 tháng đầu, phải nghỉ tập, tốn chi phí/thời gian, giảm động lực và tăng tỷ lệ bỏ tập. |
| **Success Metric** | Giảm tỷ lệ tự báo cáo đau/khó chịu liên quan đến sai form trong 4 tuần đầu; tăng tỷ lệ người mới duy trì tập đều sau tháng đầu. |
| **Boundary** | AI không tự chẩn đoán y tế, không thay thế HLV/bác sĩ khi có dấu hiệu chấn thương thật; chỉ hỗ trợ gợi ý giáo án khối lượng ban đầu và nhắc nhở dựa trên khuyến nghị chuẩn (ACSM). |

## Bước 6.0 — Ma trận độ phù hợp với AI

Bài toán của nhóm nằm ở ô nào?

```text
Độ mơ hồ trung bình-cao + Độ phức tạp cao
```

Vì sao?

```text
Độ mơ hồ: "form đủ tốt" không phải lúc nào cũng có một đáp án tuyệt đối đúng/sai —
còn tùy thể trạng, mục tiêu, kinh nghiệm từng người, nên có nhiều cách trả lời chấp nhận được.

Độ phức tạp: cần phối hợp nhiều thông tin (thể trạng, mục tiêu, thiết bị, tiến độ tích lũy
qua nhiều buổi tập) — bước sau (tăng khối lượng tuần sau) phụ thuộc kết quả bước trước.

Theo ma trận, ô này gợi ý "Agent có thể phù hợp, nhưng cần boundary, người thật kiểm tra
và phương án quay về rất rõ". Vì đây là vấn đề sức khỏe, nhóm chọn hạ mức xuống Workflow
thay vì Agent, để giữ người tập là người quyết định cuối cùng ở các bước rủi ro.
```

## Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Bảng khối lượng/set-rep chuẩn theo trình độ (beginner template cố định theo ACSM) | Đủ nếu người tập có thể trạng khá đồng nhất, không có mục tiêu đặc biệt | Không cá nhân hoá theo tiến độ thực tế; không phù hợp nếu thể trạng đặc biệt | Không chọn làm toàn bộ, nhưng dùng làm rule nền cho giáo án ban đầu |
| **Workflow** | Nhập thể trạng/mục tiêu → AI tạo giáo án dựa trên rule nền → theo dõi log tiến độ → AI gợi ý điều chỉnh khối lượng theo tuần → người tập tự xác nhận trước khi tăng tạ | Hợp vì input khá rõ (thể trạng, mục tiêu, thiết bị) và có chuẩn tham chiếu làm nền | Giáo án/gợi ý có thể sai nếu input không chính xác | Chọn |
| **Agent** | AI tự động theo dõi liên tục qua camera/wearable, tự chẩn đoán chấn thương và tự điều chỉnh giáo án không cần xác nhận | Chỉ cần nếu chấp nhận AI tự quyết định các vấn đề liên quan sức khỏe | Rủi ro quá cao vì sai sót có thể dẫn tới chấn thương thật, không có ai chịu trách nhiệm | Chưa chọn |

Mức chọn:

```text
Workflow.
```

Vì sao:

- Input tương đối rõ (thể trạng, mục tiêu, thiết bị có sẵn).
- Có chuẩn tham chiếu uy tín (ACSM) làm rule nền, giảm rủi ro AI tự bịa khối lượng tập.
- AI chỉ hỗ trợ cá nhân hoá giáo án và nhắc nhở tiến độ; người tập vẫn tự xác nhận trước khi tăng khối lượng.
- Chưa cần Agent vì rủi ro sức khỏe quá cao nếu để AI tự chẩn đoán/tự quyết định mà không có ai xác nhận lại.

## Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Người mới tập gym, chưa có kiến thức nền về động tác và khối lượng tập, không có PT/bạn tập rành kỹ thuật kèm cạnh. |
| **Workflow** | Nhập thể trạng/mục tiêu → AI tạo giáo án dựa trên rule nền (ACSM) → tập và đối chiếu video mẫu để tự kiểm form → AI theo dõi log và gợi ý điều chỉnh khối lượng theo tuần → người tập tự xác nhận. |
| **Bottleneck** | Không có checkpoint kiểm tra form/khối lượng phù hợp thể trạng ngay từ đầu, dẫn tới sai lệch tích lũy. |
| **Impact** | Rủi ro chấn thương nhẹ-vừa trong 1-3 tháng đầu; giảm động lực, tăng tỷ lệ bỏ tập. |
| **Success Metric** | Giảm tỷ lệ tự báo cáo đau/khó chịu do sai form trong 4 tuần đầu; tăng tỷ lệ duy trì tập đều sau tháng đầu. |
| **Boundary** | AI không tự chẩn đoán y tế, không thay thế HLV/bác sĩ; chỉ gợi ý giáo án ban đầu và nhắc điều chỉnh dựa trên chuẩn tham chiếu. |
| **AI intervention point** | Sau khi người tập nhập thể trạng/mục tiêu (trước buổi tập đầu tiên) và ở bước theo dõi tiến độ hằng tuần. |
| **Mức chọn** | Workflow: rule nền (ACSM) cho giáo án ban đầu, AI cá nhân hoá và theo dõi tiến độ, người tập tự xác nhận trước khi tăng khối lượng. |
| **Rủi ro & người thật kiểm tra** | Rủi ro: AI gợi ý sai lệch dẫn tới chấn thương. Người thật kiểm tra: người tập tự quan sát dấu hiệu bất thường; nếu đau kéo dài phải hỏi HLV/bác sĩ thật, AI không tự chẩn đoán thay. |

## Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Actor cụ thể, workflow 5 bước rõ ràng |
| Baseline và success metric đã đo được chưa? | Not Yet | Cần khảo sát thêm số lượng lớn hơn để có baseline tỷ lệ chấn thương đáng tin cậy |
| Có data/input đủ dùng chưa? | Not Yet | Chưa có dữ liệu thật về thể trạng/tiến độ tập của người dùng thử nghiệm |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes (có điều kiện) | Chấp nhận được nếu luôn có boundary dừng lại hỏi HLV/bác sĩ thật |
| Có người review/owner vận hành không? | Not Yet | Nhóm chưa có ai đóng vai trò kiểm duyệt nội dung tập luyện (không phải chuyên gia) |
| Có cách non-AI đơn giản hơn không? | Yes | Video hướng dẫn có sẵn (YouTube/JEFIT) + bảng khối lượng chuẩn (ACSM) |

Decision:

```text
Go với scope nhỏ (pilot), có giám sát chặt.
```

Nếu Go, pilot nhỏ nhất là:

```text
- Dùng bảng khối lượng chuẩn (ACSM) làm rule nền, không để AI tự đề xuất khối lượng ngoài khung này.
- Thử nghiệm với 5-10 người mới tập trong nhóm/bạn bè, theo dõi 2-4 tuần.
- Người tập tự log lại: có đau/khó chịu bất thường không, có tự tin về form không.
- Đo tỷ lệ tự báo cáo khó chịu/đau và mức độ tuân thủ giáo án so với nhóm đối chứng
  (nhóm chỉ dùng video YouTube, không có AI cá nhân hoá).
```

Nếu Not Yet, cần validate gì trước:

```text
Cần khảo sát rộng hơn 12 người hiện tại (ít nhất 20-30 người mới tập) để có baseline
tỷ lệ chấn thương/khó chịu đáng tin cậy hơn, và cần tìm ít nhất một người có chuyên môn
thể hình (HLV, sinh viên ngành thể thao) để review nội dung giáo án trước khi thử nghiệm thật.
```

Nếu No-Go, nên làm gì thay AI:

```text
Dùng bảng khối lượng chuẩn (ACSM) + danh sách video hướng dẫn form uy tín (JEFIT/kênh HLV thật)
làm tài liệu tham khảo cố định, không cần cá nhân hoá bằng AI.
```

Decision rationale:

- Problem rõ, có tín hiệu hội tụ mạnh (3/10 thành viên độc lập đề xuất) và validate nhanh cho thấy pain có thật.
- Có non-AI components rõ ràng (rule nền ACSM, video mẫu JEFIT) để so sánh công bằng.
- AI chỉ can thiệp ở bước cá nhân hoá giáo án và nhắc nhở tiến độ, không tự chẩn đoán y tế.
- Có boundary và fallback rõ ràng khi có dấu hiệu chấn thương thật.
- Vẫn còn thiếu baseline dữ liệu đáng tin cậy và người có chuyên môn review, nên quyết định là "Go với scope nhỏ, giám sát chặt" thay vì Go toàn diện.

---

*Group Report — Day 02 Lab*
