# 🐶🐱 Admin Petshop - Story Report Tổng Hợp

## 🧩 Mục tiêu dự án
Xây dựng hệ thống quản trị bán hàng cho cửa hàng thú cưng (Petshop), giúp Admin dễ dàng quản lý sản phẩm, đơn hàng, khách hàng, thống kê doanh thu và vận hành cửa hàng hiệu quả.

---

## 📁 MODULE 1: Quản lý tài khoản Admin

### 1.1 Story: Đăng ký / Đăng nhập Admin
- [ ] Cho phép đăng nhập bằng email và mật khẩu
- [ ] Mỗi tài khoản có role: `admin` hoặc `superadmin`
- [ ] Sử dụng xác thực bảo mật (JWT hoặc session)
- [ ] Cho phép thay đổi mật khẩu

### 1.2 Story: Phân quyền quản trị
- [ ] Superadmin có thể tạo / chỉnh sửa / xóa admin khác
- [ ] Mỗi admin có giới hạn thao tác theo quyền

---

## 📁 MODULE 2: Quản lý sản phẩm thú cưng

### 2.1 Story: Quản lý danh mục sản phẩm
- [ ] Tạo / sửa / xóa danh mục (Chó, Mèo, Cá, Hamster, Phụ kiện,...)

### 2.2 Story: Quản lý sản phẩm
- [ ] Thêm / sửa / xóa sản phẩm (tên, mô tả, giá, hình ảnh, tồn kho)
- [ ] Gắn sản phẩm vào danh mục
- [ ] Quản lý tồn kho sản phẩm
- [ ] Tìm kiếm và lọc sản phẩm theo danh mục / tên / trạng thái

---

## 📁 MODULE 3: Quản lý đơn hàng

### 3.1 Story: Danh sách đơn hàng
- [ ] Hiển thị toàn bộ đơn hàng và trạng thái: đang xử lý, đã giao, đã hủy, lỗi
- [ ] Tìm kiếm đơn theo mã đơn / tên khách hàng

### 3.2 Story: Cập nhật trạng thái đơn hàng
- [ ] Cho phép cập nhật trạng thái đơn theo luồng: đang xử lý → đang giao → đã giao
- [ ] Cho phép hủy đơn hàng

### 3.3 Story: Đơn hàng lỗi
- [ ] Hiển thị đơn hàng bị lỗi: thất bại thanh toán, sai địa chỉ, giao không thành công,...
- [ ] Cho phép admin ghi chú nguyên nhân
- [ ] Gửi thông báo đến khách hàng nếu đơn lỗi

---

## 📁 MODULE 4: Quản lý khách hàng

### 4.1 Story: Xem thông tin khách hàng
- [ ] Hiển thị danh sách khách hàng đã từng mua hàng
- [ ] Hiển thị lịch sử đặt hàng của từng khách

### 4.2 Story: Tìm kiếm & lọc khách hàng
- [ ] Tìm kiếm theo tên, email, số điện thoại
- [ ] Lọc theo số lần mua, khách thân thiết,...

---

## 📁 MODULE 5: Dashboard thống kê

### 5.1 Story: Thống kê doanh thu
- [ ] Hiển thị doanh thu theo ngày / tháng / năm
- [ ] Biểu đồ xu hướng bán hàng

### 5.2 Story: Top sản phẩm bán chạy
- [ ] Thống kê sản phẩm được mua nhiều nhất
- [ ] Hiển thị theo từng danh mục

### 5.3 Story: Đơn hàng theo trạng thái
- [ ] Số lượng đơn đang xử lý / đã giao / lỗi / bị hủy

---

## 📁 MODULE 6: Cài đặt hệ thống

### 6.1 Story: Cấu hình thông tin cửa hàng
- [ ] Tên shop, địa chỉ, hotline, email
- [ ] Cấu hình phí vận chuyển, thuế

### 6.2 Story: Xuất báo cáo
- [ ] Xuất file đơn hàng ra CSV
- [ ] Xuất báo cáo doanh thu

---

## ✅ Tổng kết

### Acceptance Criteria (Tiêu chí hoàn thành)
- Giao diện dễ dùng, responsive
- Phân quyền rõ ràng
- Xác thực bảo mật
- Dữ liệu hiển thị đúng và cập nhật theo thời gian thực
- Code dễ bảo trì, có thể mở rộng

### Ước lượng thời gian tổng thể
- Tổng: 15–20 ngày (nếu chia team)
- Có thể chia làm 3 Sprint chính

---

📌 **Lưu ý:**
- Có thể tích hợp thanh toán trong tương lai
- Ưu tiên xây dựng backend API rõ ràng và RESTful

