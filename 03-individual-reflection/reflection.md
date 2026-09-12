# 03 — Individual Reflection

## Thông tin cá nhân

- Họ và tên: Nguyễn Thị Bảo Trang
- Mã học viên: 2A202602580
- Nhóm: Ryzen - Zone C
- Candidate problem nhóm chọn: Sinh viên đại học phải tổng hợp deadline bài tập, quiz, thuyết trình và lịch họp từ LMS, email, nhóm chat và lịch học; thông tin phân tán làm mất thời gian và có nguy cơ bỏ sót.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Lập 10 vấn đề từ trải nghiệm sinh viên Fintech, gồm tìm tài liệu, kết nối Finance–Technology, bàn giao task, theo dõi deadline và debug Python/SQL. | Cung cấp 3 Problem Cards có actor, workflow, bottleneck, metric và phương án non-AI để nhóm so sánh. |
| Pitch Problem Card | Pitch bài toán bàn giao task giữa thành viên mạnh Finance và Technology; nêu bottleneck ở bước ghép bài và metric giảm thời gian ghép từ 30–60 phút xuống dưới 20 phút. | Giúp nhóm có một candidate về workflow nhóm để đặt cạnh các candidate khác khi shortlist. |
| Challenge bài của bạn khác | Đặt câu hỏi liệu nguyên nhân của vấn đề là thông tin phân tán hay thói quen quản lý thời gian; đồng thời hỏi một lịch tập trung có đủ không. | Nhóm thu hẹp candidate cuối vào bước thu nhận, đối chiếu và cập nhật deadline, thay vì chỉ làm thêm reminder. |
| Gom trùng / cluster | Nhận ra các đề xuất về handoff task, requirement mơ hồ và quên deadline đều có điểm chung là thiếu thông tin rõ ràng ở thời điểm cần hành động. | Hỗ trợ nhóm nhìn thấy cluster “thông tin phân tán/thiếu ngữ cảnh” và ưu tiên bài deadline vì actor rộng hơn, dễ validation hơn. |
| Chọn candidate problem | So sánh candidate của mình với bài deadline theo actor, workflow, khả năng đo và phạm vi pilot; đồng ý không chọn bài handoff vì actor hẹp hơn. | Nhóm chọn bài deadline đa nguồn với baseline sơ bộ 10 phút/ngày và 3–4 kênh theo dõi. |
| Validation / research | Đọc Canvas Calendar, Google Calendar/Tasks và Todoist để xác định phần nào đã giải được bằng Rule hoặc calendar feed. | Nhóm tránh giả định AI phải làm toàn bộ; AI chỉ được đặt ở bước trích xuất email/chat không cấu trúc. |
| Workflow nhóm | Góp ý current workflow phải có bước đối chiếu phiên bản mới nhất và sửa đúng bản ghi cũ. | Bottleneck được xác định rõ ở bước đối chiếu 3–4 nguồn; future workflow có bước sinh viên review trước khi cập nhật lịch. |
| Problem Statement | Góp phần giữ metric cụ thể: giảm từ khoảng 10 xuống không quá 3 phút/ngày, không bỏ sót deadline trong pilot và theo dõi tỷ lệ trường AI trích xuất đúng. | PS v1 có baseline, metric đo được và boundary không cho AI tự ghi lịch hoặc tự quyết định kế hoạch học. |
| Rule / Workflow / Agent | Lập luận Rule đủ cho nguồn có cấu trúc, còn email/chat cần AI hỗ trợ ngôn ngữ; không cần Agent tự quyết định hành động tiếp theo. | Nhóm chọn mức Workflow, có human-in-the-loop và cơ chế hoàn tác. |
| Decision | Đồng ý Go với pilot 2 tuần, 3–5 sinh viên và 20–30 thông báo đã ẩn dữ liệu nhạy cảm. | Quyết định có điều kiện rollback nếu AI trích xuất dưới 90%, vẫn tốn trên 5 phút/ngày hoặc có deadline bị bỏ sót. |

**Dấu tay rõ nhất của tôi trong artifact cuối:**

```text
Dấu tay rõ nhất của tôi là cách nhóm đặt bottleneck ở bước đối chiếu và cập nhật deadline, thay vì gọi chung là “quên deadline”. Tôi cũng góp phần giữ lựa chọn ở mức Workflow: AI chỉ đề xuất dữ liệu từ thông báo không cấu trúc, còn sinh viên kiểm tra nguồn và xác nhận trước khi lịch thay đổi.
```

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Sau khi tự liệt kê vấn đề, dùng AI gợi ý thêm problem theo bốn lăng kính và cách đo sơ bộ. | Giúp mở rộng từ vấn đề cá nhân sang pain của thành viên nhóm và việc theo dõi deadline đa kênh. | AI từng gợi ý “gia sư AI cho mọi môn” hoặc “tự làm toàn bộ project”, quá rộng và không có workflow thật. | Chỉ giữ vấn đề đã từng gặp, có actor, dấu hiệu và thời gian cụ thể. |
| Problem Card | Dùng AI phản biện actor, bottleneck, metric và nguy cơ nhảy sang Agent quá sớm. | Nhắc tôi tách “task chưa rõ”, “thiếu kiến thức” và “lỗi ghép bài”. | AI không thể xác nhận nguyên nhân thật trong nhóm hoặc tự đánh giá đúng/sai của công thức và code. | Thu hẹp Card #1 vào handoff/ghép bài, thêm metric thời gian và số lần hỏi lại, giữ thành viên kiểm tra cuối. |
| Workflow | Dùng AI gợi ý cách thể hiện before/after workflow và fallback. | Giúp tách Rule cho dữ liệu có cấu trúc, AI cho ngôn ngữ tự nhiên và người dùng cho xác nhận. | Sơ đồ có thể làm lu mờ bước đối chiếu phiên bản cũ và khiến workflow trông tự động hơn thực tế. | Giữ bước review nguồn, chặn mục xung đột và thêm cơ chế hoàn tác trước khi cập nhật lịch. |
| Research | Dùng AI gợi ý từ khóa/tên công cụ, sau đó tự kiểm Canvas, Google Calendar/Tasks, Todoist và bài nghiên cứu về nudges. | Tăng tốc việc tìm lựa chọn sẵn có để so sánh với ý tưởng nhóm. | AI có thể tóm tắt quá chắc; khảo sát bên ngoài không thay thế được validation tại VinUni. | Chỉ dùng nguồn có link kiểm được và không dùng số liệu bên ngoài làm baseline của nhóm. |
| Problem Statement | Dùng AI để đặt câu hỏi phản biện metric và boundary của PS v0. | Giúp kiểm tra rằng “nhanh hơn” chưa phải metric và AI không được tự ghi lịch. | AI không biết dữ liệu pilot có sẵn hay người dùng có thật sự duy trì review hằng ngày không. | Chuyển metric thành 10 xuống không quá 3 phút/ngày, 0 deadline bỏ sót trong scope và tỷ lệ trường trích xuất đúng. |
| Rule / Workflow / Agent | Dùng AI rà lại sự khác nhau giữa ba mức giải pháp. | Hữu ích khi chỉ ra Rule phù hợp với calendar feed, còn AI chỉ cần ở email/chat không cấu trúc. | AI có xu hướng đề xuất Agent dù nguồn, thứ tự xử lý và điểm rẽ nhánh đã biết. | Nhóm chọn Workflow vì không cần hệ thống tự lập kế hoạch hay tự chọn tool; sinh viên vẫn là owner. |
| Decision | Dùng AI như một người phản biện cho điều kiện Go và rollback. | Giúp liệt kê các chỉ số cần đo trong pilot và rủi ro khi trích sai ngày hoặc phiên bản. | AI không thể quyết định thay nhóm mức rủi ro nào chấp nhận được. | Chọn Go có điều kiện: xác nhận trước mọi thay đổi, log/hoàn tác và dừng AI khi không đạt ngưỡng. |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Khi nghe top 3 problems của các bạn, tôi nhận ra một ý tưởng nghe hấp dẫn chưa chắc là bài tốt cho lab nếu actor hoặc workflow còn mơ hồ. Ban đầu tôi muốn bảo vệ bài toán bàn giao task giữa Finance và Technology vì đó là pain tôi gặp khi làm nhóm, nhưng phần challenge khiến tôi thấy phạm vi người gặp hẹp hơn và nguyên nhân còn lẫn giữa task chưa rõ với chênh lệch kiến thức. Tôi thay đổi ý kiến và ủng hộ bài deadline đa nguồn vì mọi thành viên đều hiểu workflow này, có thể hỏi người dùng nhanh và đo bằng thời gian theo dõi hằng ngày. Nhóm có lúc nghiêng về ý tưởng dùng Agent để tự đọc nhiều nguồn và tự sắp lịch, nhưng khi vẽ workflow tôi thấy các bước chính đã biết trước. Vì vậy, việc cần làm không phải là làm hệ thống tự chủ hơn mà là giảm phần đối chiếu lặp lại, đồng thời giữ người dùng kiểm tra thông báo gốc. Phần tôi đóng góp rõ nhất là làm rõ bottleneck không chỉ là “quên deadline” mà là phải so khớp phiên bản mới nhất trên 3–4 kênh rồi sửa đúng bản ghi cũ. Điều khó nhất với tôi là đặt metric vừa có ích vừa không hứa quá mức, vì baseline 10 phút/ngày mới là sơ bộ và chưa thể khẳng định AI sẽ luôn đúng. Tôi học được rằng boundary quan trọng ngang metric: AI không được tự ghi lịch khi chưa có xác nhận, dù điều đó làm future workflow nhanh hơn trên giấy. Nếu làm lại, tôi sẽ challenge sớm hơn về chất lượng validation, đặc biệt tách rõ dữ liệu phỏng vấn thật với giả định hoặc evidence từ bên ngoài. Tôi cũng sẽ yêu cầu nhóm thử Rule/calendar feed trước ở các nguồn có cấu trúc để biết chính xác bước nào AI thực sự tạo thêm giá trị.
```

---

## 4. Tự kiểm cuối bài

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

