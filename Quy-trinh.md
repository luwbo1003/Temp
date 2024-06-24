# Workflow Example

<!-- Tầng Quản Lý -->
```mermaid
%% Dashboard Tầng Quản trị Dữ liệu
graph TD;

    A[Quy trình đăng kí bản quyền] -->|Checkbox trong chi tiết TSTT| A1[Theo khối, đơn vị, các khâu sản xuất];
    B[Lưu trữ] -->|Phân loại theo khối, đơn vị, khâu, thư mục| B1[Toàn bộ TSTT có];
    C[Sản xuất] -->|Dashboard thống kê| C1[Toàn bộ nội dung tài sản số đã được sản xuất];
    C -->|Các TSTT đạt, không đạt chậm deadline| C2[MỐc thời gian các sản phẩm lỗi];
    C -->|Cấu hình & xuất báo cáo theo kì thời gian| C3[Nội dung những tài sản theo tiến trình sản xuất];
    D[Cập nhật thông tin] -->|Theo từng khối, đơn vị| D1[Các TSTT đã đầy đủ thông tin hoặc chưa];
    D -->|Notify cho người sở hữu và quản lý| D2[Của đơn vị đó];
    E[Upload] -->|Check các loại TSTT đã đủ| E1[Trong từng khâu sản xuất của đơn vị, khối];
    E -->|Quá trình Sync từ trên hệ thống xuống local và từ local lên hệ thống| E2[];
    F[Cấp quyền] -->|Danh sách TSTT được chia sẻ| F1[Cấp quyền cho nhiều khối, phòng ban];
    F -->|Được sử dụng nhiều lần, gói vào các gói nội dung| F2[];
    G[Cập nhật phiên bản] -->|Theo từng khối, đơn vị, người thực hiện các task| G1[Danh sách các TSTT có nhiều phiên bản trở lên];

    H[Cấu hình báo cáo định kì] -->|Thời gian + người chịu trách nhiệm nhận định| H1[Checkbox có nhận thông báo hay không];
    H -->|Submit| H2[];
