## Đề bài:
- Thời gian làm bài: 30 phút
- Yêu cầu ứng viên xây dựng một ứng dụng Vue đơn giản có các chức năng sau:
## Chức năng
1. Danh sách công việc (To-do List)
- Tạo một component TodoList để hiển thị danh sách các công việc.
- Mỗi công việc bao gồm: tên công việc, và trạng thái (hoàn thành/chưa hoàn thành).
- Cho phép chỉnh sửa tên công việc khi trạng thái của nó là chưa hoàn thành (nếu đã hoàn thành thì không cho chỉnh sửa nữa).
- Thêm một công việc mới vào danh sách.
- Xóa một công việc ra khỏi danh sách.
- Đánh dấu một công việc là hoàn thành hoặc chưa hoàn thành.
2. Component con
- Sử dụng một component con để hiển thị từng mục công việc (TodoItem), với props truyền xuống từ component cha (TodoList).
3. Local storage (Bonus - không bắt buộc)
- Lưu trạng thái của danh sách công việc vào localStorage để khi reload trang vẫn giữ lại được danh sách công việc đã thêm.
## Yêu cầu:
- Sử dụng Vue.js phiên bản 3.
- Sử dụng TailwindCss để style cho components.
## Các tiêu chí đánh giá:
- Kiến thức cơ bản về VueJS: Sử dụng đúng cách các directive như v-for, v-bind, v-model, và v-on.
- Quản lý state: Kiểm tra cách quản lý dữ liệu trong component và khả năng tương tác giữa component cha - con.
- Clean Code: Cách cấu trúc code, đặt tên biến, và cách giải quyết vấn đề.
- Bonus: Nếu có thêm phần lưu dữ liệu vào localStorage là một điểm cộng.