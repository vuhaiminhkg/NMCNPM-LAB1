# 💾 ERD – Thiết kế Cơ sở Dữ liệu Hệ thống Quản lý Khách sạn

## 1. Bảng `Room`
| Tên cột | Kiểu dữ liệu | Ghi chú |
|----------|--------------|---------|
| room_id | VARCHAR(10) | Khóa chính |
| room_type | VARCHAR(50) | Loại phòng |
| price | DECIMAL(10,2) | Giá mỗi đêm |
| status | BOOLEAN | Trạng thái phòng |

## 2. Bảng `Customer`
| customer_id | VARCHAR(10) | Khóa chính |
| name | VARCHAR(50) | Tên khách hàng |
| phone | VARCHAR(15) | Số điện thoại |
| email | VARCHAR(50) | Email |

## 3. Bảng `Invoice`
| invoice_id | VARCHAR(10) | Khóa chính |
| customer_id | VARCHAR(10) | FK → Customer |
| room_id | VARCHAR(10) | FK → Room |
| total_amount | DECIMAL(10,2) | Tổng tiền |
| check_in | DATE | Ngày nhận |
| check_out | DATE | Ngày trả |
