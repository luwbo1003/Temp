# Workflow Example

<!-- Tầng Quản Lý -->
```mermaid
graph TD;

    A1[Quản trị] -->|Yêu cầu và kiểm duyệt| B1[Quản lý];
    A1 --> A2[Dashboard Tầng Quản trị Dữ liệu];
    A2 --> A3[Quy trình đăng kí bản quyền];
    A2 --> A4[Lưu trữ];
    A2 --> A5[Sản xuất];
    A2 --> A6[Cập nhật thông tin];
    A2 --> A7[Upload];
    A2 --> A8[Cấp quyền];
    A2 --> A9[Cập nhật phiên bản];
    A2 --> A10[Cấu hình báo cáo định kì];
