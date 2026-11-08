# Reup Studio updates

Phiên bản ổn định: **3.5.0**.

## Thay đổi

- Chrome hiện tại dùng đăng nhập Facebook; nút **Kết nối Facebook và chạy ẩn** chuyển riêng phiên Facebook sang trình duyệt ẩn cục bộ, rồi kiểm tra đăng nhập. Sau khi kết nối thành công có thể đóng tab nguồn. Không đọc hồ sơ Chrome hoặc cookie trang khác. Facebook có thể yêu cầu xác minh lại; tool dừng, không vượt xác minh.
- Xử lý lời mời thêm nút tùy chọn đã nhận diện bằng Anh/Việt, ưu tiên nút khả dụng, nhớ thông báo thành công để chờ liên kết bài mới. Không tự gửi lại nếu kết quả chưa rõ.
- Quét danh sách Page theo lô, bỏ giới hạn 100 và bỏ bước mở lần lượt từng Trang. Tra địa chỉ dạng tên theo nhóm, lưu ID; giữ lựa chọn cũ khi quét chưa đầy đủ. Tốc độ thực tế còn phụ thuộc Facebook.
- Mặc định xóa video tải về khi mọi lượt dùng video đó đã thành công hoặc bị hủy; giữ file khi còn chờ, lỗi hoặc chưa xác minh. Có thể tắt trong giao diện. Không xóa hàng đợi, thiết lập hoặc phiên đăng nhập.

## Tự cập nhật

`stable.json` chứa gói chương trình nén, ký RSA SHA-256. Các máy đã có bộ cập nhật 3.4.1 nhận bản mới khi đóng hẳn tool và mở lại. Máy chưa chạy được bộ cập nhật cần bản vá kích hoạt nhỏ. Không cần GitHub trên máy người dùng. Bộ runtime lớn được giữ nguyên; nâng runtime cần bản vá riêng. Tiện ích Chrome unpacked có thể cần Reload khi mã tiện ích đổi.

Gói công khai không chứa tài khoản, cookie, dữ liệu hàng đợi hay khóa ký riêng.

Đã thử các tình huống đăng trên Chromium với giao diện mô phỏng, danh sách 1.200 Page, chuyển phiên được giả lập, dọn file và nâng cấp từ bộ cập nhật 3.4.1. Chưa xác minh toàn bộ luồng với Facebook thật hoặc EXE chạy trực tiếp trên Windows.
