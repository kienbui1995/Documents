## DANH SÁCH Ý TƯỞNG
=======================

***Bài toán đặt ra:*** Theo khảo sát mà chúng tôi mới thực hình cho thầy rằng các bạn sinh viên trường Đại học Thăng Long rất cần một hệ thống có thể kết nối mạnh mẽ hơn giữa họ với trường, giáo viên, môn học, với mọi vấn đề trong trường. Vì vậy chúng tôi lập ra dự án này mong muốn xây dựng một mạng xã hội thông mình, hiểu người dùng trong lĩnh vực giáo dục.

### 1.Khai phá mạng xã hội (Social mining)
**Ý tưởng:** Bài toán của của project này mà chúng tôi phải đặt ra là làm sao để người dùng có thể ở lại với mạng xã hội của mình, làm sao để cho hệ thống của mình là một mạng xã hội thực sự mạnh về mảng giáo dục so với các mạng xã hội nổi tiếng như facebook, twitter, ... hay các mạng xã hội Việt Nam có như Zing,... Để làm được điều đó mạng xã hội mà dự án này đặt ra ngoài có tính năng cơ bản của một mạng xã hội giáo dục thì còn phải hiểu người dùng cần gì, luôn luôn chủ động với người dùng,... để đủ giữ người dùng ở lại với mạng. Vì vậy chúng tôi sẽ kết hợp với bài toàn DataMining trong lĩnh vực social mining(khai phá mạng xã hội) và hệ khuyến nghị (recommendation system. Và như mọi người cũng biết bài toán Datamining là một bài toán cần một tài nguyên về dữ liệu cực kỳ lớn, đó cũng chính là khó khăn đầu tiên của chúng tôi trong việc tìm kiếm dữ liệu học. 
- Nhưng chúng tôi đã có biến pháp ban đầu đó chính là dữ liệu facebook. Facebook một mạng xã hội lớn nhất thế giới cho tới thời điểm hiện tại, nơi mà mọi người kết nối với nhau và để lại dữ liệu cho facebook vô cùng lớn, đó chính là một mỏ kim cương cỡ bự của các nhà khai phá dữ liệu. Và may thay Facebook họ cung cấp các API để kéo lấy dữ liệu công khai của người dùng,các dữ liệu trong các group công khai,... Thật thú vị khi hệ thống của chúng ta có thể phân tích đống dữ liệu đó của người dùng để có thể đự đoán được họ có hành vi như thế nào, thuộc đối tượng nào, sở thích, sở ghét, ngành nghề ... Và đó chính là mỏng kim cương đầu tiên của chúng tôi trong dự án này.
- Phía trên đó là bài toán khi họ vào hệ thống, còn bây giờ sẽ là bài toán trụ cột của dự án đó chính khai phá dữ liệu mạng xã hội trên chính mạng xã hội của ta. Đó chính là bài toán hệ thống phải hiểu người sử dụng đang làm gì, đang có mối quan tâm về vấn đề gì, thích gì ... để có thể gợi ý cho họ những thứ mà họ thích, quan tâm. Đó chính là chìa khóa then chốt trong việc phát triển mạng xã hội này.

### 2.Hệ khuyến nghị (recommendation system)
**Ý tưởng:** Dựa vào việc khai phá dữ liệu của người dùng trên mạng xã hội Facebook + bài toán khai phá dữ liệu trên hệ thông để có thể chủ động đưa ra những vấn đề họ đang quan tâm. Hay còn gọi đó là recommendation system. Sau đây là một số tính năng mong muốn recommendation system có thể thực hiện:
+ Gợi ý các bài viết, các thẻ tag, nhóm chủ đề có liên quan đến nội dung câu hỏi mà người dùng định post trong mục hỏi đáp.
+ Hệ thống có thể hiểu được vấn đề mà người dùng viết, cám xúc, tâm trạng của người viết để có thể  hướng vào đối tượng quan tâm nhất.
+ Hệ thống có thể hiểu được ngưởi sử dụng,sự tương tác người dùng với hệ thống, để có thể gọi ý cho họ những người nên kết bạn, những nhóm lĩnh vực... Ví dụ: Trong một sự kiện, mọi người muốn kết nối với nhau nhưng họ không biết thì hệ thống có thể gọi ý kết bạn với họ thông qua nhiều tiêu chí như ip wifi, gps, ... Hay khi các bạ sinh viên vừa đăng ký học xong họ thường up thời khóa biểu của họ lên mong muốn tìm bạn cùng lớp, thì hệ thống có khả năng phân tích thời khóa biểu và đưa ra các gợi ý về nhóm môn học, giảng viên của lớp đó, sinh viên trong cùng lớp, ...
+ Hệ thống có khả năng hiểu mọi thứ người sử dụng tương tác với nó. và có thể  biết bình luận nào không tốt bình luận nào không tốt, hay bình luận nào được cho là tốt nhất để hiển thị lên đầu tiên.
+ Các fanpage thông báo của trường, bộ môn, hệ thống sẽ hiểu và luôn luôn đặt bài viết ưu tiên nhất cho đến khi biết được rằng người dùng đã đọc nó. Để đảm bảo mọi thông bào quan trọng đều có thể truyệt đạt đúng đối tượng...
+ Hệt thống hiểu người dùng nên chúng sẽ biết người sử dụng đang quan tâm tới vấn đề gì để có thể gắn họ với các cộng đồng, các hoạt động,... mà họ thích.
+ Kết thúc mỗi kỳ trường thường khảo sát sinh viên về chất lượng giảng dạy của môn học, thì hệ thống này có thể làm điều đó một cách tốt, chính xác nhất. Để đánh giá được chất lượng của giáo viên với môn học, hệ thống dựa trên rất nhiều tiêu chí, ngoài phiếu khảo sát online ẩn sau khi hết mỗi kỳ học, hệ thống sẽ dựa trên mức độ học tập của sinh viên dựa trên sự tương tác môn học với hệ thống. Ngoài ra hệ thống còn có thể hiểu và tóm lược được những đóng góp ý kiến của sinh viên gửi về cho giáo viên và nhà trường nhằm cải thiển chất lượng giảng dạy <tất cả những bình luận đánh giá môn học và giảng viên đều được ẩn với người khác và được hệ thống kiểm duyệt phát hiện hành vi không trung thực dựa trên thống kê>
+ Cũng chính vì hệ thống hiểu hết các hành vi của người dùng nên ban lãnh đạo, tổ chức,... có thể biết hành vi, thái độ,.. của sinh viên khi trường đưa ra những chính sách mới để có biện pháp kịp thời.
***Luôn để người dùng ở thế bị động*** => níu kéo người dùng ở lại với hệ thống.
***Mạng xã hội hướng đối tượng người sử dụng đến những vấn đề họ cần một cách chủ động ***

###Chia sẻ tài liệu
+ Chia sẻ tài liệu
+ gợi ý khi có tài liệu liên quan mà đang yêu cầu
+ móc nối sinh viên khóa trước để nhận được tài liệu

###Đánh giá giáo viên
+ Gần giống với phiếu đánh giá giáo viên cuối mỗi môn học mà trường thỉnh thoảng khảo sát (theo từng môn học, lớp học), tránh tiêu cực.
+ Đánh giá của sinh viên không được công khai.

###Thông báo CLB, Phòng Ban, Tổ chức
+ Hỗ trợ thông báo cho các phòng ban, tổ chức, quản lý chia sẻ thông tin PR cho nhau.
+ Gơi ý thông tin cần thiết cho phòng ban

Xu hướng (giải trí) trong trường, thống kê mức độ quan tâm của người dùng.
Xây dựng bộ lọc ngôn từ, chặn đường dẫn xấu.
Hỗ trợ tạo môn học, quản lý page môn học, tư vấn môn học.
Hệ thống hướng đối tượng người dùng
