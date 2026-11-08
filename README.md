# Reup Studio updates

Phiên bản ổn định: **3.5.1**.

## 3.5.1

- Chọn Page trực tiếp trong form Video đơn hoặc Kênh YouTube; tìm theo tên/ID, chọn nhiều, lựa chọn hai form độc lập.
- Đổi Page cho lần thêm mới không hủy, đổi đích hay chặn lượt đã tạo. Lịch kênh cũ giữ danh sách Page đã lưu. Dừng rõ ràng bằng Hủy, Tạm dừng kênh hoặc ngắt kết nối.
- Đăng ngay ưu tiên lượt mới trước lượt chưa bắt đầu; vẫn phải tải video và chờ Facebook, không ngắt lượt đang chạy.
- Xóa từng lượt, xóa các lượt đang hiển thị theo bộ lọc hoặc xóa kênh cùng lịch sử liên quan. Không xóa lượt đang tải/gửi/xử lý, không xóa bài Facebook. Lưu khóa bỏ qua tối thiểu để quét nguồn không tự thêm lại mục vừa xóa.
- Nếu Post còn khóa nhưng Next vừa khả dụng, quay lại chuyển bước đúng.
- UploadNotReady: thêm trạng thái nút/trường bắt buộc và ảnh khung đăng che nội dung đang nhập. Tối đa 20 ảnh lưu trên máy; xem qua Xem Facebook lúc lỗi. Ảnh không được tải lên kho này hoặc kèm JSON sao chép báo lỗi.

**Lỗi Post bị khóa trên Facebook thật chưa được xác nhận khắc phục toàn bộ. Cần đối chiếu khung đăng thực tế của lượt lỗi.**

## 3.5.0

Chrome dùng đăng nhập, sau đó chuyển riêng phiên Facebook sang trình duyệt ẩn cục bộ. Facebook yêu cầu xác minh thì dừng. Quét Page theo nhóm và lưu ID, không mở lần lượt từng Trang hay giới hạn 100. Tự xóa video sau khi mọi lượt liên quan đã đăng thành công hoặc được hủy; giữ nếu còn chờ/lỗi/chưa rõ.

## Nhận cập nhật

Máy đã có bộ cập nhật: đóng hẳn cửa sổ lệnh tool, mở lại và kiểm tra phiên bản. stable.json là gói chương trình nén, ký RSA SHA-256, tải không cần đăng nhập GitHub. Giữ dữ liệu và bộ runtime lớn. Thay đổi runtime cần bản vá riêng. Tiện ích Chrome unpacked có thể cần Reload khi mã tiện ích đổi.

Gói công khai không chứa tài khoản, cookie, dữ liệu hàng đợi hay khóa ký riêng. Đã kiểm thử hàng đợi, đổi lựa chọn Page, xóa, giao diện Chromium mô phỏng và nâng cấp. Chưa chạy EXE trực tiếp trên Windows hoặc xác minh toàn bộ luồng với Facebook thật.
