# Workflow Example

<!-- Tầng Quản Lý -->
```mermaid
graph TD;
    B1[Quản Lý] -->|Chỉ đạo và giám sát| C1[Thực Thi];
    B1 --> B2[Quản lý Dữ liệu];
    B2 --> B3[Phân loại dữ liệu];
    B2 --> B4[Quản lý thông tin];
    B2 --> B5[Quản lý project];
    B2 --> B6[Quản lý cấp quyền];
    B2 --> B7[Bảo mật dữ liệu];
    B1 --> B8[Quản lý Báo cáo];
    B8 --> B9[Báo cáo Realtime];
    B8 --> B10[Báo cáo Định kì];
    B8 --> B11[Quản lý Quy trình Báo cáo];
