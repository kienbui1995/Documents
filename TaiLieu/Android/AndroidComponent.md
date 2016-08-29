# Các thành phần của một ứng dụng Android
Các thành phần ứng dụng trong Android là các thành phần cần thiết  để xây dựng nên một ứng dụng Android. Các thành phần này được liên kết với nhau bằng một file manifest (Bản kê khai) có tên là _AndroidManifest.xml_ . File này sẽ mô tả mỗi thành phần của ứng dụng đó và cách chúng tương tác với nhau như thế nào?

Có 4 thành phần chính thường được hay sử dụng trong một ứng dụng Android:

Tên thành phần| Mô tả
--- | ---
Activies | Thành phần sẽ gọi đến UI và sử lý những tương tác giữa người dùng với màn hình điện thoại
Services | Thành phần này sẽ sử lý những tiến trình nền được liên kết với ứng dụng
Broadcast Receivers | Thành phần sẽ giao tiếp giữa Android OS và ứng dụng
Content Providers | Thành phần sẽ xử lý dữ liệu và quản lý database

## Activities

Một activity sẽ hiển thị một màn hình đơn với giao diện người dùng, nó cho phép thực hiện những hành động trên màn hình. Ví dụ, một ứng dụng email thì sẽ có 1 activity có thể hiển thị danh sách thư mới, một cái khác có thể soạn thảo emailm hoặc một cái nữa có thể đọc email. Nếu ứng dụng nó nhiều hơn 1 activity thì bạn phải chọn 1 activity mặc định sẽ hiển thị đầu tiên khi ứng dụng được khởi động

Một activity thì được mở rộng là một lớp con của **Activity** cha theo cú pháp

```java
public class MainActivity extends Activity {

}
```
