# Reup Studio updates

Kênh cập nhật chính thức của Reup Studio.

- Phiên bản ổn định: **3.4.1**.
- Sửa lỗi `No module named updater` khi chạy bằng Python nhúng chế độ cô lập. Máy bị lỗi 3.4.0 cần chạy lại bản kích hoạt nhỏ 3.4.1 một lần.
- `stable.json`: gói mã chương trình nén có chữ ký RSA SHA-256, không cần đăng nhập GitHub để tải.
- Tool kiểm tra và áp dụng bản mới khi mở, trước khi khởi động hàng đợi. Không dừng lượt đăng đang chạy.
- Mất mạng hoặc chữ ký sai: dùng tiếp bản hiện tại. Kiểm tra khởi động thất bại: khôi phục tệp chương trình cũ.

Gói không chứa tài khoản Facebook, cookie, hàng đợi hoặc khóa ký riêng. Bộ runtime lớn được giữ nguyên. Thay đổi thư viện/runtime cần bản vá riêng; tiện ích Chrome unpacked có thể cần Reload khi mã tiện ích đổi.

Đã kiểm thử nâng cấp, chữ ký, khôi phục, khởi động và lỗi Python cô lập trên tệp trích từ EXE. Chưa chạy EXE trực tiếp trên Windows tại môi trường build.
