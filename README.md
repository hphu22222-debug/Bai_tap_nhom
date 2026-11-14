# Dream12 – Web bán phụ tùng ô tô đa hãng

Web demo bán phụ tùng ô tô của nhiều hãng (Toyota, Honda, Hyundai, Ford, Mazda, Kia, Mitsubishi, VinFast), 

## Chức năng
- **Khách (vãng lai/thành viên):** tìm kiếm, lọc theo phân khúc/hãng/dòng xe/loại phụ tùng/giá, xem chi tiết và đời xe tương thích, giỏ hàng, đặt hàng (COD hoặc chuyển khoản), xem kho hàng, tra cứu đơn theo số điện thoại.
- **Admin:** đăng nhập, xem đơn, duyệt đơn và cập nhật trạng thái (Đã xác nhận → Đang giao → Hoàn thành), hủy đơn (trả hàng về kho).
- **Luồng đặt hàng:** kiểm tra tồn kho → thiếu hàng thì báo và không tạo đơn → đủ hàng thì tạo đơn và giữ hàng.

## Chạy trên máy
Mở file `index.html` bằng trình duyệt (hoặc dùng tiện ích Live Server trong VS Code).

## Cấu trúc
- `index.html` – khung trang
- `style.css` – giao diện
- `app.js` – dữ liệu sản phẩm (mảng `P`) và toàn bộ xử lý

## Lưu ý
- Đơn hàng và tồn kho lưu trong `localStorage` của từng trình duyệt, chưa có máy chủ/cơ sở dữ liệu.
- Mật khẩu Admin demo là `dream12`, kiểm tra ngay trên trình duyệt nên **không an toàn để dùng thật**. Muốn dùng thật cần backend.
- Dữ liệu sản phẩm, mã phụ tùng và giá là dữ liệu mẫu.
