# Bài 1 : Sự cố không truy cập được hệ thống quản trị

## Phần 1. Phân tích
### Xác định Input (Tên miền) / Output (IP address) và mô tả sơ đồ luồng dữ liệu của DNS.
- input: http://phong-dieu-phoi.grenlog.vn
- output: DNS_PROBE_FINISHED_NXDOMAIN

## Phần 2: Triển khai
### Đề xuất quy trình kiểm tra mã trạng thái HTTP Status Code để xác nhận xem yêu cầu đã chạm tới máy chủ hay chưa.
- F2 trên web để vào developer tools trên web rồi vào network xem ở phần status

## Phần 3: Kiểm thử 
### Giả định Nam sửa đúng tên miền nhưng vẫn nhận mã **404 Not Found**, hệ thống đang gặp vấn đề gì?
- Hệ thống đang gặp lỗi không tìm thấy trang
