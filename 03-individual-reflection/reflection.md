# 03 — Individual Reflection

## Đóng góp của Trần Đức Bảo trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Scan 10 problems quanh trải nghiệm sinh viên + thực tập (xin giấy tờ CTSV, báo cáo thực tập 2 định dạng, tìm quy định cũ trong nhóm chat...) | Có 3 Problem Card chi tiết với workflow trước/sau riêng, dùng làm nền để pitch với nhóm |
| Pitch | Pitch hướng "người mới tập gym sai động tác & khối lượng" cho nhóm, ngoài 3 candidate đã scan cá nhân | Candidate gym được nhóm chọn làm bài chính, đạt 31/35 điểm — cao nhất trong 3 candidate vào vòng chấm |
| Research & Validation (vai trò được phân công trong nhóm) | Tìm và tổng hợp giải pháp đã có (Gymscore, QuickPose SDK, dự án mã nguồn mở pose estimation) và số liệu kiểm chứng pain (khảo sát OnePoll/Isopure n=2.000, ACE, dữ liệu NEISS về chấn thương liên quan tập luyện) | Nhóm có đủ căn cứ để không "Go" ngay, mà chọn "Not Yet" với 3 việc cụ thể cần validate trước khi triển khai |
| Rule / Workflow / Agent + Decision | Tham gia lập luận vì sao chọn Workflow (chưa chọn Agent) cho pilot, và vì sao quyết định cuối là "Not Yet" thay vì "Go" ngay | Nhóm tránh được việc chốt success metric (≥80%) khi chưa có baseline thật tại Việt Nam |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan cá nhân | Nhờ AI dựng khung bảng scan theo 4 lăng kính và gợi ý thêm góc nhìn cho bối cảnh sinh viên + thực tập | Giúp nhanh có đủ 10 dòng, đa dạng lăng kính, không bị bí ý tưởng | AI tự điền số liệu thời gian (vd 3-5 ngày xin giấy tờ, 30-40 phút báo cáo) dựa trên "quy trình phổ biến" chứ không phải tôi tự đo | Cần đối chiếu lại với trải nghiệm thật của bản thân trước khi dùng số liệu này để pitch, không giữ nguyên số AI đưa |
| Problem Card | Nhờ AI dựng Problem Card đầy đủ field + draft workflow trước/sau cho 3 candidate | Cấu trúc rõ ràng, đủ field theo template, dễ so sánh 3 card cùng lúc | Một số con số (tỷ lệ trễ hạn, % lần không tìm ra thông tin) là ước tính hợp lý chứ chưa verify | Đã đánh dấu rõ phần nào là ước tính để tự kiểm lại sau, không đưa thẳng vào bản pitch chính thức |
| Research (nhóm) | Nhờ AI tổng hợp research giải pháp form-check gym có sẵn và số liệu kiểm chứng pain | Giúp tìm ra đúng sản phẩm thương mại (Gymscore) đã giải quyết bài toán tương tự, tránh nhóm build lại từ đầu | Bản research đầu tiên AI đưa toàn nguồn tự liệt kê (Fitbod, Freeletics, ACSM) chưa có link/trích dẫn thật | Nhóm tự tìm và thay bằng nguồn có trích dẫn thật (Gymscore, QuickPose, OnePoll/Isopure, NEISS) trước khi đưa vào Problem Statement |
| Rule/Workflow/Agent + Decision | Nhờ AI liệt kê rủi ro từng mức và soát lại logic trước khi nhóm chốt | Giúp thấy rõ vì sao chưa nên chọn Agent ngay (rủi ro sức khỏe nếu AI tự chẩn đoán) | Bản nháp đầu của AI nghiêng về chốt "Go" khá nhanh, chưa nhấn đủ mạnh vào các giả định (baseline VN, độ chính xác kỹ thuật) còn chưa validate | Nhóm tự siết lại thành "Not Yet" và liệt kê rõ 3 việc cần làm trước khi Go |

## Bài học của Trần Đức Bảo

- Số liệu "nghe hợp lý" chưa chắc là số liệu thật — bản scan cá nhân đầu tiên của tôi đều do AI ước tính (3-5 ngày, 30-40 phút...) dựa trên quy trình phổ biến chứ không phải tôi tự đo, nên trước khi pitch cần tự xác nhận lại bằng trải nghiệm thật thay vì tin luôn con số AI đưa.
- Research có trích dẫn thật khác hẳn research do AI "liệt kê tên tool quen thuộc" — bản đầu (Fitbod, Freeletics, ACSM) là AI tự đoán chưa xác minh, còn bản sau (Gymscore, QuickPose, OnePoll/Isopure, NEISS) có link/trích dẫn thật nên đáng tin hơn nhiều để làm căn cứ quyết định.
- Quyết định "Go" quá sớm rất dễ xảy ra nếu không ai đóng vai phản biện — nhóm suýt chốt success metric ≥80% khi chưa có baseline tại Việt Nam, may là dừng lại ở "Not Yet" sau khi soi lại các giả định chưa validate.
- Agent không phải lựa chọn mặc định chỉ vì bài toán "có vẻ" phức tạp — dù ma trận độ mơ hồ/phức tạp gợi ý Agent có thể phù hợp, nhóm vẫn chọn Workflow trước vì rủi ro sức khỏe (AI chấm sai form) cần người thật (PT) kiểm tra định kỳ, không thể để AI tự quyết một mình.

Nếu làm lại:

```text
Tôi sẽ tự đi hỏi thật 2-3 người mới tập gym ở Việt Nam ngay từ giai đoạn scan cá nhân,
thay vì để đến Phase 4 mới phát hiện toàn bộ số liệu kiểm chứng (OnePoll, ACE, NEISS)
đều lấy mẫu ở Mỹ. Nếu có dữ liệu Việt Nam sớm hơn, success metric ở Problem Statement
có thể đã thực tế hơn ngay từ v0, thay vì phải hạ quyết định xuống "Not Yet".
```

---

*03 — Individual Reflection — Day 02 Lab*
