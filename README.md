# lichtuan

Skill Codex để nhập lịch công tác tuần từ bảng Word vào hệ thống họp không giấy của Kiểm toán nhà nước. Mỗi dòng trong bảng được đăng ký thành một lịch riêng.

## Bắt đầu

1. Tải [SKILL.md](./SKILL.md) và lưu vào thư mục kỹ năng cá nhân của Codex. Trên Windows với cấu hình mặc định, đường dẫn là `%USERPROFILE%\.codex\skills\lichtuan\SKILL.md`.
2. Mở Codex trên ứng dụng desktop và đính kèm file lịch tuần (.doc hoặc .docx).
3. Gửi yêu cầu sau. Nếu hệ thống họp yêu cầu xác thực, đăng nhập trực tiếp trong tab trình duyệt tích hợp.

~~~text
$lichtuan nhập lịch tuần từ file này
~~~

## Dữ liệu được đưa vào biểu mẫu

| Trong bảng Word | Trên hệ thống |
| --- | --- |
| Ngày và giờ | Chọn ngày và giờ bắt đầu. Giờ kết thúc mặc định sau 3 giờ 30 phút. |
| Nội dung công việc | Chép vào **Nội dung cuộc họp**. |
| Thành phần | Chép vào **Thành phần**, rồi dùng nút **THÊM** để chọn người hoặc đại diện đơn vị. |
| Bộ phận chuẩn bị nội dung | Chọn đơn vị tương ứng trong danh sách, kể cả khi file dùng tên viết tắt. |
| Địa điểm | Chọn **Địa điểm khác** và chép địa điểm từ file. |
| Ghi chú | Dùng tên ở đây để chọn thêm người khi cột **Thành phần** ghi “các thành viên khác” hoặc tương tự. |

Trường **Đơn vị** được đặt thành **Kiểm toán nhà nước** cho mỗi lịch.

## Kiểm tra và sửa lịch

- **Khi nhập tiếp:** Skill đối chiếu ngày, giờ, nội dung và địa điểm với danh sách tuần để tránh tạo trùng.
- **Khi danh mục không hiện:** Nếu danh sách **Bộ phận chuẩn bị nội dung** trống, skill lưu lịch trước và ghi lại mục thiếu để bổ sung sau.
- **Khi cần chỉnh sửa:** Vào **Quản lý lịch họp → Phê duyệt lịch**, chọn đúng tuần, mở **Tác vụ → Phê duyệt** ở cuối dòng và dùng **Xác nhận** để lưu thay đổi.
- **Sau khi nhập:** Đối chiếu danh sách tuần và kiểm tra các mục chưa khớp trong danh bạ. Lịch đã đăng ký có thể ở trạng thái **Chờ duyệt**.

Xem [SKILL.md](./SKILL.md) để biết các quy tắc chọn lãnh đạo, cá nhân và đại diện đơn vị.
