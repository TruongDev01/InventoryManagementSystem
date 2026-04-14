# 📦 Hệ thống Quản lý Kho hàng (Inventory Management System)

Một ứng dụng Desktop chuyên nghiệp được xây dựng bằng **Java** và **SQL**, hỗ trợ các doanh nghiệp hoặc cửa hàng kiểm soát quy trình nhập/xuất kho, quản lý sản phẩm, khách hàng và theo dõi đơn hàng một cách hiệu quả.

---

## ✨ Tính năng chính (Features)

Ứng dụng cung cấp giao diện người dùng trực quan (GUI) với các chức năng cốt lõi:

- **🔐 Quản lý quyền truy cập:** Hệ thống đăng nhập bảo mật cho quản trị viên và nhân viên (`Login.java`).
- **👥 Quản lý Người dùng:** Thêm, sửa, xóa và phân quyền tài khoản người dùng trong hệ thống (`ManageUser.java`).
- **📂 Quản lý Danh mục & Sản phẩm:** - Phân loại sản phẩm theo danh mục (`ManageCategory.java`).
  - Quản lý thông tin chi tiết và số lượng tồn kho của từng sản phẩm (`ManageProduct.java`).
- **🤝 Quản lý Khách hàng:** Lưu trữ và tra cứu thông tin khách hàng (`ManageCustomer.java`).
- **🛒 Quản lý Đơn hàng:** - Tạo đơn hàng mới, tính toán tổng tiền tự động (`ManageOrder.java`).
  - Xem lại lịch sử các đơn hàng đã tạo (`ViewOrders.java`).
  - **Đặc biệt:** Hỗ trợ xuất hóa đơn bán hàng trực tiếp ra file PDF (`OpenPdf.java`).

---

## 🛠️ Công nghệ sử dụng (Tech Stack)

- **Ngôn ngữ lập trình:** Java (Java Swing cho Giao diện người dùng).
- **Cơ sở dữ liệu:** SQL (Tích hợp qua JDBC).
- **Môi trường phát triển (IDE):** Apache NetBeans.
- **Thư viện bên thứ ba:** Hỗ trợ xuất file PDF (iText / PDFBox - cấu hình trong thư mục `lib/`).

---

## 🚀 Cài đặt & Chạy dự án (Installation & Setup)

### Yêu cầu hệ thống (Prerequisites)
- Đã cài đặt [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) (Phiên bản 8 trở lên).
- Hệ quản trị cơ sở dữ liệu (MySQL Server hoặc SQL Server).
- Apache NetBeans IDE (hoặc bất kỳ IDE nào hỗ trợ Java Swing).

### Các bước triển khai
1. **Clone repository:**
   ```bash
   git clone [https://github.com/truongdev01/inventorymanagementsystem.git](https://github.com/truongdev01/inventorymanagementsystem.git)
