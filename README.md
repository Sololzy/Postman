# CallPostMan

## 1. Giới thiệu về Postman

Postman là một nền tảng toàn diện cho việc phát triển, sử dụng và quản lý API. Nó cung cấp nhiều tính năng giúp các nhà phát triển và tester dễ dàng tạo, gửi, kiểm tra và chia sẻ các yêu cầu API. Postman hiện là một trong những công cụ phổ biến nhất được sử dụng trong lĩnh vực kiểm thử API.

### Các tính năng chính của Postman:
* **Tạo yêu cầu HTTP:** Cho phép tạo các yêu cầu HTTP với nhiều phương thức khác nhau (GET, POST, PUT, DELETE, v.v.). Bạn có thể nhập URL API, thêm header, body và các tham số yêu cầu.
* **Gửi yêu cầu và xem phản hồi:** Cho phép gửi các yêu cầu HTTP đến API và xem phản hồi; quan sát mã trạng thái HTTP, header, body và nội dung phản hồi.
* **Kiểm tra API:** Cung cấp nhiều công cụ hỗ trợ kiểm tra API bao gồm trình soạn thảo JSON, trình xác minh JSON, trình gỡ lỗi và bộ sưu tập (Collection).
* **Chia sẻ API:** Cho phép chia sẻ các yêu cầu, bộ sưu tập và môi trường với nhóm để cộng tác phát triển và kiểm thử.
* **Quản lý môi trường:** Quản lý linh hoạt nhiều môi trường API khác nhau (phát triển, thử nghiệm, sản xuất) thông qua biến môi trường.
* **Tự động hóa:** Cung cấp tính năng chạy tự động hóa các tác vụ kiểm thử thông qua Collection Runner.
* **Bảo mật:** Hỗ trợ các cơ chế bảo mật, xác thực và phân quyền (API Key, Bearer Token, OAuth, v.v.).

### Giao diện overview
![Giao diện overview]([images/00_overview.png](https://github.com/Sololzy/Postman/blob/main/00_Overview.png))

---

## 2. Kiểm thử API cơ bản

Các yêu cầu HTTP cơ bản với API khóa học:

### Yêu cầu GET
* **Mô tả:** Gửi yêu cầu GET để lấy danh sách dữ liệu khóa học.
![Yêu cầu GET](images/01_get_course.png)

### Yêu cầu POST
* **Mô tả:** Gửi yêu cầu POST kèm Body JSON để tạo mới một khóa học.
![Yêu cầu POST](images/02_post_course.png)

### Yêu cầu PUT
* **Mô tả:** Gửi yêu cầu PUT để cập nhật thông tin chi tiết của một khóa học.
![Yêu cầu PUT](images/03_put_course.png)

### Yêu cầu DELETE
* **Mô tả:** Gửi yêu cầu DELETE để xóa một bản ghi khóa học theo ID.
![Yêu cầu DELETE](images/04_delete_course.png)

### Test
* **Mô tả:** Viết kịch bản kiểm tra tự động trạng thái phản hồi `200 OK` trong tab Scripts/Tests và quan sát kết quả PASS tại Test Results.
![Test](images/05_test_script.png)

### Sử dụng biến để lưu 1 URL
* **Mô tả:** Thiết lập biến môi trường `base_url` để lưu trữ đường dẫn máy chủ và tái sử dụng cho các yêu cầu API.
![Sử dụng biến để lưu 1 URL](images/06_variable_url.png)

---

## 3. THỰC HÀNH GET của 1 API thời tiết

* **Mô tả:** Thực hành gửi yêu cầu GET tới API thời tiết công khai để lấy dữ liệu nhiệt độ, thời tiết thực tế dạng JSON.
* **Kết quả thực hiện:**

![Thực hành GET của 1 API thời tiết](images/07_weather_api.png)
