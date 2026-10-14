# Website Tiệm Mô Hình – HTML + CSS + PHP thuần + MySQL (1 website duy nhất)

1. Chép thư mục vào `htdocs/` (XAMPP).
2. Import `database.sql` bằng phpMyAdmin (CSDL `shop_db`).
3. Sửa thông tin MySQL trong `ketnoi.php` nếu cần.
4. Mở `/index.php`. Chủ tiệm bấm "Chủ tiệm đăng nhập": `admin` / `admin123` (đổi ngay ở "Đổi mật khẩu").

Khi đăng nhập, cùng website đó hiện thêm các chức năng quản lý.

| File | Ai dùng | Việc |
|---|---|---|
| ketnoi.php | chung | Kết nối MySQL, hàm dùng chung |
| database.sql | chung | Tạo bảng + dữ liệu mẫu |
| menu.php, style.css | chung | Thanh menu (tự đổi theo đăng nhập), CSS |
| index.php | khách + chủ | Menu, tìm món, đặt hàng (chủ tiệm thấy thêm cột Sửa/Xoá) |
| dathang.php | khách | Xử lý đặt hàng |
| tracuu.php | khách | Tra cứu đơn bằng số điện thoại |
| dangnhap.php, dangxuat.php | chủ | Đăng nhập / đăng xuất |
| create.php, update.php, delete.php | chủ | Thêm / sửa / xoá món |
| donhang.php | chủ | Lịch sử đơn + cập nhật trạng thái |
| thongke.php | chủ | Thống kê theo tuần / tháng |
| doimatkhau.php | chủ | Đổi mật khẩu |
| check.php | chủ | Chặn người chưa đăng nhập |
