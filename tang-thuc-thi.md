# Workflow Example

<!-- Tầng Thực Thi -->
```mermaid
graph TD;
    C1[Thực Thi] --> C2[Thực thi Quản lý Dữ liệu];
    C2 --> C3[Thu thập và cập nhật dữ liệu];
    C2 --> C4[Thực thi cấp quyền];
    C2 --> C5[Thực thi bảo mật];
    C1 --> C6[Thực thi Báo cáo];
    C6 --> C7[Xuất báo cáo Realtime];
    C6 --> C8[Xuất báo cáo Định kì];
    C6 --> C9[Thực thi quy trình Báo cáo];



