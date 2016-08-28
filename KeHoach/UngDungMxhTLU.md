# Kế hoạch xây dựng Mạng xã hội Thăng Long
### **I. Ý tưởng xây dựng ứng dụng Mạng xã hội**
Dựa trên những cuộc khảo sát và nhu cầu thực tế từ những sinh viên trong trường, họ cần một ứng dụng có thể giúp đỡ họ trong việc học tập, kết nối, giải trí trong ***trường Đại học Thăng Long***. Bên cạnh đó việc xây dựng một ứng dụng di động có thể giúp _nhà trường_, các _phòng ban_ hay _giảng viên_ có thể truyền đạt những thông báo trực tiếp tới từng sinh viên một cách khoa học và hiệu quả, tăng tính tương tác giữa sinh viên với nhà trường, giảng viên. Ứng dụng sẽ tạo ra một vòng kết nối thu nhỏ chỉ trong trường Đại học Thăng Long, nơi mọi thứ có thể tìm kiếm và chia sẻ dễ dàng hơn, ứng dụng sẽ đủ thông minh để biết bạn đang cần gì, tìm kiếm chính xác và hiệu quả. Tất cả những sự thông mình đó chính là thành quả của việc khai phá dữ liệu mạng xã hội facebook, đó là điểm nổi trội của ứng dụng so với _Facebook_ - mạng xã hội lớn nhất thế giới với một lượng thông tin khổng lồ

### **II. Các chức năng dự kiến**
#### ***1. Đối với sinh viên***
+ Kết bạn, theo dõi các sinh viên khác, giảng viên, các page(Các phòng ban,các bộ phận truyền thông của trường)
+ Chia sẻ status,ảnh,ghi chú,video
+ Chat 1-1, chat nhóm
+ Xem thời khóa biểu bao gồm: Lớp, phòng, giảng viên, giờ học
+ Xem danh sách sinh viên trong từng môn học của sinh viên trong học kỳ (Nếu sinh viên học cùng nhau nhiều môn có thể gợi ý kết bạn)
+ Xem và nhận thông báo lịch thi của mỗi kì
+ Nhắc nhở khi đến giờ học của 1 môn học có trong thời khóa biểu như thông báo phòng, ca học trước mỗi môn học của sinh viên khi sinh viên có môn học nào đó trong ngày.
+ Tạo ghi chú cho môn học, như tài liệu cần chuẩn bị, bài tập về nhà hay bất kì thông tin gì liên quan tới môn học, kèm theo chức năng thông báo nếu cần.
+ Tham gia lớp học trực tuyến, cứ mỗi môn học mà sinh viên đăng ký trong học kì,sinh viên có thể tham gia vào 1 lớp học trên ứng dụng do giảng viên quản lý. Một số tính năng như:

  \+ Nhận thông báo từ giảng viên giảng dậy môn học đó
  \+ Nhận được trợ giúp từ giảng viên
  \+ Trò chuyện với các sinh viên khác trong lớp
  \+ Tạo thảo luận về các vấn đề của môn học
  \+ Chia sẻ tài liệu, đánh giá tài liệu (Cân nhắc..)
+ Review môn học
+ Đánh giá giáo viên (Cân nhắc)

#### ***2. Đối với giảng viên***
+ Quản lý sinh viên trong các lớp trong kỳ mà giảng viên đó giảng dạy
+ Tạo thông báo, nhắc nhở cho từng lớp và gửi tới sinh viên trong từng lớp

#### ***3. Đối với nhà trường và các bộ phận khác***
+ Tạo thông báo tới sinh viên có thể ở dưới dạng thông báo hay là một bài viết hiển thị trên tường của sinh viên
+ Báo cáo thống kê ...(chưa có ý tưởng)



### **III. Môi trường phát triển**
  + Ngôn ngữ lập trình và nền tảng sử dụng: Android, Java
  + Hệ quản trị CSDL: Mysql, MongoDB, SQLite

### **IV. Công việc cần thực hiện**
  + Thực hiện khảo sát, xây dựng hồ sơ khảo sát tóm lược các chức năng và nghiệp vụ của một Mạng xã hội
  + Học ngôn ngữ Java và hệ điều hành Android
  + Thiết kế cơ sở dữ liệu
  + Viết tài liệu tổng thể hệ thống Mạng xã hội

### **V. Khó khăn **
+ Làm thế nào để xác định 1 sinh viên đúng với mỗi mã sinh viên và tài khoản trên hệ thống?

> **Phương án**:
Xác thực qua giảng viên và định danh chính xác sinh viên, những ai chưa xác thực chỉ có thể sử dụng một số tính năng

+ Có nên làm chức năng chat?
+ Việc chia sẻ tài liệu chưa rõ cách thức chia sẻ như thế nào, đối tượng thấy tài liệu như thế nào?
+ Báo cáo thống kê cho nhà trường sẽ gồm những thông tin gì?

____

## Kế hoạch tuần 2 (29/8 -> 4/8/2016)
+ Tiếp tục hoàn thiện các chức năng và giải quyết những khó khăn gặp phải ở [Phần 5](https://github.com/SENf-TLU/Documents/blob/master/KeHoach/UngDungMxhTLU.md#v-khó-khăn-)
+ Bắt đầu tìm hiểu Android và Java
___

## Lịch sử tài liệu theo tuần
* [Tuần 1](https://github.com/SENf-TLU/Documents/commit/48f8b71339fa341c7b11a871b1a0a272e6096199)
