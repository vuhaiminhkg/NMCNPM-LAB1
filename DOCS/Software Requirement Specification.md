# 📄 Software Requirement Specification (SRS)

## 1. Giới thiệu

### 1.1 Mục đích
Tài liệu này mô tả các yêu cầu chức năng và phi chức năng của hệ thống **SmartGrocery – Ứng dụng bán lẻ tạp hóa công nghệ 4.0**. Hệ thống giúp chủ tiệm tạp hóa quản lý sản phẩm, kho hàng, đơn hàng, khách hàng và thanh toán một cách thông minh, hiệu quả.

### 1.2 Đối tượng sử dụng
- Nhóm phát triển phần mềm
- Khách hàng (chủ tiệm tạp hóa)
- Tester
- Quản trị viên hệ thống

### 1.3 Phạm vi hệ thống
- Quản lý sản phẩm, tồn kho, đơn hàng, khách hàng
- Giao diện web/mobile cho người bán và người mua
- Tích hợp thanh toán điện tử và phân tích dữ liệu bán hàng
- Cảnh báo hàng hết hạn, đề xuất nhập hàng thông minh
- Thống kê doanh thu, sản phẩm bán chạy, lịch sử giao dịch

---

## 2. Yêu cầu chức năng

| ID   | Chức năng                  | Mô tả                                                                 |
|------|-----------------------------|----------------------------------------------------------------------|
| F01  | Quản lý sản phẩm            | Thêm, sửa, xóa, tìm kiếm sản phẩm theo mã, tên, loại hàng            |
| F02  | Quản lý kho                 | Theo dõi tồn kho, cảnh báo hết hàng, hết hạn                         |
| F03  | Bán hàng                    | Tạo đơn hàng, tính tiền, in hóa đơn, áp dụng khuyến mãi              |
| F04  | Thanh toán điện tử          | Hỗ trợ QR code, ví điện tử (Momo, ZaloPay, VNPay)                    |
| F05  | Quản lý khách hàng          | Lưu thông tin, lịch sử mua hàng, tích điểm                           |
| F06  | Phân tích dữ liệu           | Thống kê doanh thu, sản phẩm bán chạy, đề xuất nhập hàng             |
| F07  | Quản lý nhân viên           | Phân quyền truy cập, theo dõi hoạt động bán hàng                     |
| F08  | Giao diện khách hàng        | Đặt hàng online, xem khuyến mãi, theo dõi đơn hàng                   |

---

## 3. Yêu cầu phi chức năng

- **Hiệu năng:** Hệ thống xử lý đơn hàng trong <2 giây  
- **Bảo mật:** Mã hóa dữ liệu, phân quyền truy cập, xác thực 2 lớp  
- **Khả năng mở rộng:** Có thể tích hợp AI, IoT, chatbot trong tương lai  
- **Khả dụng:** Hệ thống hoạt động 24/7, downtime <1%  
- **Khả năng tương thích:** Chạy tốt trên Chrome, Firefox, Safari, Android/iOS  
- **Ngôn ngữ:** Tiếng Việt và tiếng Anh

---

## 4. Ràng buộc hệ thống

- **Cơ sở dữ liệu:** MySQL hoặc MongoDB  
- **Frontend:** ReactJS (Web), Flutter (Mobile)  
- **Backend:** Node.js hoặc Django  
- **Hạ tầng:** Cloud-based (Firebase, AWS hoặc Azure)  
- **Thanh toán:** Tích hợp API ví điện tử phổ biến tại Việt Nam

---

## 5. Kết luận

Tài liệu SRS này là cơ sở để nhóm phát triển triển khai hệ thống SmartGrocery một cách hiệu quả, đảm bảo đáp ứng đúng nhu cầu thực tế của người dùng và khả năng mở rộng trong tương lai.
