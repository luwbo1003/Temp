# Workflow Example

<!-- Tầng Thực Thi -->
```mermaid
graph TD;
    A1[Quản Trị] -->|Yêu cầu và kiểm duyệt| B1[Quản Lý];
    A1 --> A2[Dashboard Tầng Quản trị Dữ liệu];
    A2 --> A3[Thống kê toàn bộ nội dung tài sản số theo các loại dữ liệu];
    A3 --> A4[Đăng ký bản quyền trạng thái];
    A3 --> A5[Phân loại];
    A3 --> A6[Thông tin];
    A3 --> A7[Các project];
    A3 --> A8[Cấp quyền];
    A3 --> A9[Bảo mật];
    A2 --> A10[Báo cáo loại realtime];
    A2 --> A11[Báo cáo theo định kì];
    A11 --> A12[Cấu hình định kì + thời gian];
    A11 --> A13[Các dữ liệu báo cáo được cấu hình];
    A11 --> A14[Cấu hình thời điểm báo cáo];
    A2 --> A15[Quy trình báo cáo định kì];
    A15 --> A16[Xuất báo cáo -> các khối sản xuất, đơn vị];
    A15 --> A17[Submit báo cáo + nhận định];
    A17 --> A18[Thông báo cho Quản trị và các khối];
    A2 --> A19[Danh sách lưu trữ báo cáo];



