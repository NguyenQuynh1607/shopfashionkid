## Website bán quần áo trẻ em

**Giới thiệu**

Đây là project website bán quần áo trẻ em được xây dựng trong môn Java nâng cao.
Website mô phỏng một hệ thống bán hàng online với đầy đủ chức năng từ phía người dùng đến quản trị viên.

Hệ thống có hỗ trợ thanh toán bằng mã QR và đã được chạy thử trên môi trường online.

**Demo**

Link demo (chỉ hoạt động khi server đang chạy):

https://urban-space-goldfish-x594gjj7xjpvhpjq7-8080.app.github.dev/

Lưu ý:
	-	Khi dừng server (Ctrl + C) thì website sẽ không truy cập được
	-	Đây là môi trường chạy tạm để test, không phải hosting cố định


**Công nghệ sử dụng**
	-	Java Spring Boot
	-	Thymeleaf
	-	MySQL
	-	HTML / CSS / JavaScript
	-	Maven


_Chức năng chính_

**Người dùng**
	-	Đăng ký, đăng nhập
	-	Xem danh sách sản phẩm
	-	Tìm kiếm sản phẩm theo tên
	-	Xem chi tiết sản phẩm
	-	Thêm sản phẩm vào giỏ hàng
	-	Cập nhật / xóa giỏ hàng
	-	Đặt hàng
	-	Thanh toán bằng mã QR
	-	Xem đơn hàng của mình

**Quản trị viên**
	-	Quản lý sản phẩm (thêm, sửa, xóa)
	-	Quản lý danh mục
	-	Quản lý đơn hàng
	-	Quản lý người dùng
	-	Quản lý nhà cung cấp

## Cách chạy project**
1. Tạo database MySQL (ví dụ: shopfashionkid)
2. Import file `database/database.sql`
3. Cấu hình lại username/password trong `application.properties`
4. Chạy project bằng Spring Boot
5. Truy cập: http://localhost:8080
