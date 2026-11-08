# Reup Studio updates

Kênh cập nhật chính thức của Reup Studio.

## Kênh ổn định

- Phiên bản: **3.4.0**.
- `stable.json`: gói mã chương trình nén có chữ ký RSA SHA-256.
- Máy người dùng không cần đăng nhập GitHub.
- Cần cài bản kích hoạt tự cập nhật 3.4.0 một lần. Các bản cũ chưa đọc kênh này.
- Tool kiểm tra và áp dụng bản mới khi mở, trước khi khởi động hàng đợi. Không dừng lượt đăng đang chạy.
- Mất mạng hoặc chữ ký sai: dùng tiếp bản hiện tại. Kiểm tra khởi động thất bại: khôi phục tệp chương trình cũ.

Gói không chứa tài khoản Facebook, cookie, hàng đợi, trình duyệt cá nhân hoặc khóa ký riêng. Bộ runtime lớn được giữ nguyên. Thay đổi thư viện/runtime cần bản vá riêng; tiện ích Chrome unpacked có thể cần Reload khi mã tiện ích đổi.

Đã kiểm thử nâng cấp, xác minh chữ ký, khôi phục và kiểm tra nhập ứng dụng. Chưa chạy EXE trực tiếp trên Windows tại môi trường build.
