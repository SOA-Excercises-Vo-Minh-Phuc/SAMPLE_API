# Môn Kiến trúc phần mềm hướng dịch vụ (25D1INF50902201)
## Excercise 1

### Mô tả các kiến thức đã áp dụng
**.Net Core Web Service và MongoDB**:
- **Thiết lập cơ sở dữ liệu**:
  - Cài đặt MongoDB và Mongo Compass.
  - Tạo database và thêm dữ liệu mẫu (document).
- **Cấu hình ứng dụng**:
  - Cài đặt MongoDB Driver.
  - Tạo các model: `Book`, `BookStoreDatabaseSettings`.
  - Thiết lập kết nối MongoDB trong `Program.cs` bằng Dependency Injection (DI).
- **Xây dựng API**:
  - Phát triển `BooksService` xử lý CRUD (Create, Read, Update, Delete) với MongoDB.
  - Tạo `BooksController` cung cấp các endpoint API (GET, POST, PUT, DELETE).
- **Công cụ hỗ trợ**:
  - Sử dụng Swagger để kiểm thử các API.

### Kết quả đạt được
- Hoàn thiện ứng dụng Web Service:
  - Triển khai thành công các chức năng CRUD với MongoDB.
  - Tích hợp Swagger để kiểm thử và hiển thị API trực quan.
- API hoạt động ổn định với dữ liệu từ MongoDB và được truy cập qua Swagger tại `https://localhost:7295/swagger/index.html`.

![Alt text](https://github.com/SOA-Excercises-Vo-Minh-Phuc/SAMPLE_API/blob/master/1.png)
![Alt text](https://github.com/SOA-Excercises-Vo-Minh-Phuc/SAMPLE_API/blob/master/2.png)
