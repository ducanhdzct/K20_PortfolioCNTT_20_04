không hiện ảnh
không đúng đường dẫn
# Nhật ký lỗi

## 1. Trang Portfolio không hiển thị ảnh
- **Hiện tượng:** Người dùng báo trang không hiện ảnh.
- **Kiểm tra:** Trong `index.html` hiện không có thẻ `<img>`; vì vậy trang chính không khai báo ảnh để hiển thị.
- **Nguyên nhân có thể:** Chưa thêm phần tử ảnh, hoặc chưa cập nhật đường dẫn ảnh tương ứng.
- **Cách kiểm tra lại:** Mở `index.html` trên trình duyệt và kiểm tra khu vực dự kiến có ảnh. Hiện chưa thể xác nhận ảnh sau khi sửa vì chưa có đường dẫn/tệp ảnh được cung cấp.
- **Trạng thái:** Đã xác nhận trang chính chưa khai báo ảnh; chưa sửa.

## 2. Đường dẫn không đúng
- **Hiện tượng:** Người dùng báo có đường dẫn không đúng.
- **Kiểm tra:** Chưa có URL hoặc liên kết cụ thể được chỉ ra để tái hiện. Trong mã đã xem, CSS được tham chiếu bằng `css/style.css`, form chuyển đến `ket-qua.html`, và liên kết quay lại dùng `index.html#lien-he`.
- **Nguyên nhân:** Chưa xác định; cần biết liên kết nào bị lỗi và URL/tệp mong muốn.
- **Trạng thái:** Đã ghi nhận theo báo cáo; chưa thể xác minh hoặc sửa khi chưa có đường dẫn cụ thể.
