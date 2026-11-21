# Dream12 – Web bán phụ tùng ô tô đa hãng

Web demo bán phụ tùng ô tô của nhiều hãng (Toyota, Honda, Hyundai, Ford, Mazda, Kia, Mitsubishi, VinFast), 

## Chức năng
- Khách (vãng lai/thành viên): tìm kiếm, lọc theo phân khúc/hãng/dòng xe/loại phụ tùng/giá, xem chi tiết và đời xe tương thích, giỏ hàng, đặt hàng (COD hoặc chuyển khoản), xem kho hàng, tra cứu đơn theo số điện thoại.
- Admin: đăng nhập, xem đơn, duyệt đơn và cập nhật trạng thái (Đã xác nhận → Đang giao → Hoàn thành), hủy đơn (trả hàng về kho), nhập thêm số lượng cho phụ tùng có sẵn.
- Luồng đặt hàng: kiểm tra tồn kho → thiếu hàng thì báo và không tạo đơn → đủ hàng thì tạo đơn và giữ hàng.

## Chạy trên máy
Mở file `index.html` bằng trình duyệt (hoặc dùng tiện ích Live Server trong VS Code).

## Cấu trúc
- app.js	Code chính: dữ liệu sản phẩm, chuyển trang, tìm kiếm và lọc, giỏ hàng, đặt hàng, kiểm tra tồn kho, quản trị, nhập kho	"Toàn bộ chức năng và logic của cửa hàng nằm ở đây"
- index.html:	Khung trang: logo, thanh tìm kiếm, menu, vùng hiển thị nội dung	"Đây là khung trang, chỉ có vài chục dòng"
- style.css	Giao diện: màu sắc, bố cục, chế độ tối, hiển thị trên điện thoại	"Đây là phần làm đẹp"
- images:	Ảnh minh họa phụ tùng
## Lưu ý
- Đơn hàng và tồn kho lưu trong `localStorage` của từng trình duyệt, chưa có máy chủ/cơ sở dữ liệu.
- Mật khẩu Admin demo là `dream12`, kiểm tra ngay trên trình duyệt nên **không an toàn để dùng thật**. Muốn dùng thật cần backend.
- Dữ liệu sản phẩm, mã phụ tùng và giá là dữ liệu mẫu.
