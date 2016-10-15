# Mô tả UseCase

**2.1\. Đăng ký** Chức năng cho phép người sử dụng chưa có tài khoản trên hệ thống có thể đăng ký tài khoản để sử hệ thống.
**2.1.1\. Đăng ký bằng FB** Chức năng cho phép người dùng đăng ký tài khoản bằng cách sử dụng tài khoản FB để đk tài khoản trên hệ thống. Hệ thống sẽ sử dụng avatar, Tên, email, giới tính,.. các thông tin này người dùng có thể chỉnh sửa, các thông tin khác người dùng sẽ tự nhập như lựa chọn vai trò của mình trên mạng xã hội rồi điền Mã sinh viên hoặc mã giảng viên,...
**2.1.2\. Đăng ký qua Form** Chức năng cho phép người dùng nhập thông tin đăng nhập và một số thông tin cá nhân (không bắt buộc).
**2.2\. Đăng nhập** Có thể đăng nhập bằng 3 cách:

- Qua facebook.
- Qua Mã sinh viên hoặc mã giảng viên, mã nhân viên.
- Qua Username, password.

**2.2.1. Đăng nhập bằng FB**
Sử dụng tài khoản FB để đăng nhập hệ thống.
**2.2.2. Đăng nhập qua giao diện**
Sử dụng Username hoặc Mã sinh viên hoặc mã giảng viên hoặc mã nhân viên.
**2.2.3. Quên mật khẩu**
Chức năng cho phép người sử dụng cấp lại mật khẩu thông qua email.
**2.3. Quản lý thiết đặt**
Chức năng cho phép người sử dụng quản lý các thiết đặt cho tài khoản của mình cũng như ứng dụng trên hệ thống của mình.
**2.3.1. Quản lý liên kết**
Quản lý liên kết tới FB và mã sinh viên, giảng viên, nhân viên.
**2.3.1.1. Liên kết tới FB**
Cho phép liên kết với tài khoản FB, người dùng có thể unlink tới tài khoản fb đó và liên kết tơi tài khoản fb mới, khi liên kết tới tài khoản fb mới thì sẽ đưa ra gợi ý có thay đổi thông tin liên quan tới FB như avatar email.
**2.3.1.2. Liên kết tới StudentCode**
Khi chưa xác thực thì người dùng có thể thay đổi mã này(sinh viên, giảng viên, nhân viên). còn khi đã xác thực thì không thể thay đổi được. Mã này cũng được định danh duy nhất trên hệ thống và cũng định danh duy nhât cho từng người.
**2.3.2. Cá nhân hóa tài khoản**
Quản lý các công việc, thông tin liên quan tới tài khoản và ứng dụng trên điện thoại di động.
**2.3.2.1. Quản lý thông tin cá nhân**
Chỉnh sửa các thông tin cá nhân và các thông tin về email và mật khẩu.
**2.3.2.2. Quản lý các thiết lập của ứng dụng**

**2.3.3. Quản lý quyền riêng tư**
  + quản lý các bài post tiếp theo sẽ tự động ở chế độ nào (public, friends, only me).
  + ai có thể kết bạn với bạn
  + ai có thể theo dõi bạn
  + ai có thể thấy bạn thông qua mã sinh viên, mã giảng viên, mã nhân viên.
  + ai có thể thấy bạn thông qua fb.
  + ai có thể thấy bạn thông qua email, số điện thoại.


**2.4. Quản lý bạn bè**
Chức năng cho phép nsd quản lý bạn bè và các mối quan hệ bạn bè.
**2.4.1. Kết bạn**
NSD có thể kết bạn vs 1 người dùng bất kỳ để có thể nhìn thấy bất cứ vị trí nào: trong lớp học, trong group, các tương tác vs các bài viết.(nếu người dùng cho phép)
**2.4.2. Hủy bỏ kết bạn**
 Vào danh sách bạn bè rồi chọn hủy kết bạn hoặc vào tường nhà để hủy kết bạn
**2.4.3. Theo dõi**
Theo dõi bất kì user nào nếu họ bật chức năng cho phép theo dõi. Có thể theo dõi tất cả các bài viết pub hoặc các thao tác như like hay cmt ở đâu đó (những group, page, tường nhà bạn bè khác mà ng đó public)
**2.4.4. Hủy theo dõi**
Vào danh sách bạn bè rồi chọn hủy theo dõi hoặc vào tường nhà để hủy theo dõi
**2.4.5. Xem danh sách bạn bè**
liệt kê tất cả các bạn bè, thứ tự mặc định xếp theo tên, có thể sửa thứ tự hiển thị = cách chọn ưu tiên theo: mức độ quan tâm,.... bạn cùng lớp,...
**2.4.6. Chặn người dùng**
ẩn hoàn toàn vs người dùng bất kì nào trên hệ thống, mọi tương tác đều k được  tồn tại, các bài viết cũ, hay các bài viết liên quan cũ có mention hoặc post lên tường đều bị ẩn tên người dùng hoặc làm mờ k bấm liên kết dc.
**2.4.7. Hủy chặn người dùng**
khôi phục lại quan hệ bình thường ban đầu
**2.5. Quản lý bài viết**
người dùng có thể viết trạng thái, chia sẻ video, ảnh, tài liệu và có thể nhắc tới bạn bè.
Việc chia sẻ tài liệu, ng dùng up file lên, chia sẻ ảnh có thể chụp trực tiếp hoặc lấy ảnh trong thiết bị hoặc lấy ảnh trong kho lưu trữ trên mxh, viêc nhắc tới bạn bè thì chỉ việc viết @, viết chữ cái đầu tiên hiện ra các bạn bè, nếu chưa hiện ra bạn bè cần thì viết tiếp sao cho thấy bạn bè r bấm chọn vào bạn bè đó.
Bài viết có thể lựa chọn public, private hoặc chỉ chia sẻ nhóm bạn bè nhấ định( có thể chọn nhiều nhóm đối tượng).
**2.6. Quản lý Chat**
2.6.1.
**2.7. Quản lý tài nguyên media**
Các tài nguyên này được up lên trực tiếp hoặc up lên thông qua viết bài và đính kèm media đó
**2.7.1. Quản lý ảnh**
 Ảnh được hiển thị lần lượt ngược thời gian, khi bấm vào xem chi tiết ảnh thì  hiện lên caption hoặc các bài viết có sử dụng ảnh
**2.7.2. Quản lý album**
Danh sách các ảnh trong album hiển thị, các album cũng có mô tả về album, có những album tự động tạo như Profile Pictures, Timeline Photos, Cover Photos,...
**2.7.3. Quản lý video**

**2.8. Tương tác bài viết**
Các tương tác đối vs tất cả các bài viết bất kì
**2.8.1. Thích**
  Thích bài viết bất kì, khi mình chọn like thì có thể unlike danh sách người like có thể được hiển thị
**2.8.2. Gợi nhắc**
gõ @ và tên ng dùng sẽ được hiển thị để chọn
trong bình luận. người dùng đc nhắc tới sẽ đc thông báo, nếu ng dùng bị block thì k nhắc tới và tên ng nhắc bị làm mờ và k  link tới đc. có thể nhắc nhiều người trong cùng 1 cmt
**2.8.3. Chia sẻ**
chia sẻ lên bất kì nơi nào như group, cá nhân
**2.8.4. Bình luận**
bình luận vs nội dung bất kì đối với bài viết, trong đó có thể nhắc tới người dùng khác.
ng dùng có thê chỉnh sửa, xóa cmt.
**2.9. Tương tác trang**
cho phép theo dõi các bài viết
**2.9.1. Theo dõi**
hiển thị các bài viết mỗi khi có bài viết mới
**2.9.2. Chia sẻ**
**2.9.3. Inbox trang** mới bổ sung
hỏi đáp, trao đổi thông tin riêng page
**2.10. Quản lý lịch**
timetable, người dùng có thể add các lịch làm việc, lịch học, các cài đặt thông báo như đăng ký học, thi.
Vs lịch hiện ra theo tuần và mỗi ngày được chia ra theo ca học/giảng dạy đối vs sinh viên và giảng viên.
ng dung có thể thiết đặt các thông báo theo giờ cụ thể
**2.11. Quản lý nhóm**
Các nhóm do admin quản lý, các nhóm không được tự tạo. Các nhóm có các thành viên tham gia có thể viết bài như bình thường như viết tâm trạng, các trao đổi trong nhóm cũng như các tương tác bài viết cũng y hệt bên ngoài nhóm.
**2.12. Quản lý hoạt động**
Các hoạt động cá nhân bao gồm việc tương tác ng dùng, page, group,... gần như log đối vs mọi hành động trên mạng xh của ng dùng để ng dùng có thể theo dõi và chỉnh sửa lại khi cần thiết như unilike, edit comment.
**2.13. Báo cáo vi phạm**
các bài viêt, người dùng có những sai phạm như spam, nội dung viết, sử dụng mxh k hợp lý,....
các ng dùng có thể báo cáo bất kì bài viết hay người dùng nào.
**2.14. Tìm kiếm**
tìm kiếm có thể lựa chọn tìm kiếm theo mã sinh viên, nhóm đối tượng, fb,.... các thông tin tìm kiếm được lưu lại dạng lịch sử và có thể xóa theo last day, last week, last month, all.
**2.15. Quản lý thông báo**
có 2 loại thông báo:
+ thông báo khẩn: các thông tin về việc học, liên quan tới thông báo từ nhà trường, lớp học, các thông tin về đặt lịch trong quản lý sự kiện. Các thông báo này khi không bật ứng dụng nhưng vẫn hiển thị lên màn hình thiết bị. sau khi thông báo được đọc, thì thông báo sẽ ở trạng thái đã đọc và nằm trong danh sách các thông báo thường.
+ Thông báo thường: các thông tin về các bài viết mình theo dõi, các phản hồi , các cmt hay bài viết dcc nhắc tới. Có thể đánh dấu đã đọc đối vs từng thông báo hoặc đánh dấu tất cả.
Các **cài đặt** thông báo:
+ bật tắt nhận thông báo;
+ lựa chọn các thông báo từ các page, lớp học

**2.16. Quản lý page**
**2.16.1. Quản lý thông báo**
thông báo tới từng nhóm người dùng
**2.16.2. Quản lý báo cáo**
danh sách các người dùng bị page báo cáo hoặc chặn hoạt động trên page của mình
**2.16.3. Quản lý tương tác** Xóa bỏ

**2.16.4. Quản lý người dùng theo dõi**
hiển thị danh sách các người dùng theo dõi
**2.16.5. Quản lý tài nguyên**
như quản lý tài nguyên trên cá nhân bình thường
**2.16.6. Quản lý cài đặt**

**2.16.7. Quản lý bài viết**
quản lý các bài viết trên page: thêm sửa xóa

### Các chức năng thuộc mảng học tập
#### 2.17. Quản lý lớp học
=======
**2.2.1\. Đăng nhập bằng FB** Sử dụng tài khoản FB để đăng nhập hệ thống. **2.2.2\. Đăng nhập qua giao diện** Sử dụng Username hoặc Mã sinh viên hoặc mã giảng viên hoặc mã nhân viên. **2.2.3\. Quên mật khẩu** Chức năng cho phép người sử dụng cấp lại mật khẩu thông qua email. **2.3\. Quản lý thiết đặt** Chức năng cho phép người sử dụng quản lý các thiết đặt cho tài khoản của mình cũng như ứng dụng trên hệ thống của mình. **2.3.1\. Quản lý liên kết** Quản lý liên kết tới FB và mã sinh viên, giảng viên, nhân viên. **2.3.1.1\. Liên kết tới FB** Cho phép liên kết với tài khoản FB, người dùng có thể unlink tới tài khoản fb đó và liên kết tơi tài khoản fb mới, khi liên kết tới tài khoản fb mới thì sẽ đưa ra gợi ý có thay đổi thông tin liên quan tới FB như avatar email. **2.3.1.2\. Liên kết tới StudentCode** Khi chưa xác thực thì người dùng có thể thay đổi mã này(sinh viên, giảng viên, nhân viên). còn khi đã xác thực thì không thể thay đổi được. Mã này cũng được định danh duy nhất trên hệ thống và cũng định danh duy nhât cho từng người. **2.3.2\. Cá nhân hóa tài khoản** Quản lý các công việc, thông tin liên quan tới tài khoản và ứng dụng trên điện thoại di động. **2.3.2.1\. Quản lý thông tin cá nhân** Chỉnh sửa các thông tin cá nhân và các thông tin về email và mật khẩu. **2.3.2.2\. Quản lý các thiết lập của ứng dụng**

**2.3.3\. Quản lý quyền riêng tư**

- quản lý các bài post tiếp theo sẽ tự động ở chế độ nào (public, friends, only me, custom friends groups).
- ai có thể kết bạn với bạn
- ai có thể thấy bạn thông qua mã sinh viên, mã giảng viên, mã nhân viên.
- ai có thể thấy bạn thông qua fb.
- ai có thể thấy bạn thông qua email, số điện thoại. **2.4\. Quản lý bạn bè** Chức năng cho phép nsd quản lý bạn bè và các mối quan hệ bạn bè. **2.4.1\. Kết bạn** NSD có thể kết bạn vs 1 người dùng bất kỳ để có thể nhìn thấy bất cứ vị trí nào: trong lớp học, trong group, các tương tác vs các bài viết. **2.4.2\. Hủy bỏ kết bạn** **2.4.3\. Theo dõi** **2.4.4\. Hủy theo dõi** **2.4.5\. Xem danh sách bạn bè** **2.4.6\. Chặn người dùng** **2.4.7\. Hủy chặn người dùng** **2.5\. Quản lý bài viết** **2.6\. Quản lý Chat** 2.6.1\. 2.7\. Quản lý tài nguyên media 2.7.1\. Quản lý ảnh 2.7.2\. Quản lý album 2.7.3\. Quản lý video 2.8\. Tương tác bài viết 2.8.1\. Thích 2.8.2\. Gợi nhắc 2.8.3\. Chia sẻ 2.8.4\. Bình luận 2.9\. Tương tác trang 2.9.1\. Theo dõi 2.9.2\. Chia sẻ 2.10\. Quản lý lịch 2.11\. Quản lý nhóm 2.12\. Quản lý hoạt động 2.13\. Báo cáo vi phạm 2.14\. Tìm kiếm 2.15\. Quản lý thông báo 2.16\. Quản lý page 2.16.1\. Quản lý thông báo 2.16.2\. Quản lý báo cáo 2.16.3\. Quản lý tương tác 2.16.4\. Quản lý người dung theo dõi 2.16.5\. Quản lý tài nguyên 2.16.6\. Quản lý cài đặt 2.16.7\. Quản lý bài viết

## Các chức năng thuộc mảng học tập

### 2.17\. Quản lý lớp học
- Chức năng dành cho sinh viên và giảng viên có thể quản lý những lớp học mà mình đã học và dạy, cụ thể sẽ có một số chức năng như quản lý thông báo, liên hệ sinh với sinh viên, đánh giá môn học, quản lý điểm danh, thảo luận các vấn đề liên quan tới lịch học và phòng học. Đặc biệt có thể xem được ca học và phòng học

- ##### 2.17.1\. Quản lý sinh viên

  - Quản lý sinh viên, chức năng dành cho giảng viên khi họ muốn quản lý sinh viên trong lớp học mà họ sẽ giảng dạy trong kì. Mục đích có thể dễ dàng kiểm soát được sinh viên trong lớp để liên lạc và điểm danh

- #### 2.17.2\. Quản lý thông báo

  - Chức năng này dành cho giảng viên, họ có thể xem thông báo đã gửi, gửi thông báo về các vấn đề liên quan tới môn học cho toàn bộ sinh viên hoặc cho từng sinh viên và nhóm sinh viên

- #### 2.17.3\. Liên hệ sinh viên

  +

- #### 2.17.4\. Quản lý thảo luận

  - Chức năng dành cho sinh viên và giảng viên, chức năng này dành áp dụng cho mỗi môn học mà giảng viên và sinh viên tham gia trong kì. Người dùng có tạo thảo luận, chỉnh sửa , xóa bài viết và thảo luận và bài trả lời. Đối với giảng viên, có thể xóa tất cả các bài viết trong lớp học.

- #### 2.17.5\. Quản lý điểm danh

  - Chức năng dành cho giảng viên cho giáo viên, giáo viên sẽ có danh sách sinh viên trong kì , hệ thống sẽ dựa vào tuần học hiện tại của môn học để hiển thị ra danh sách sinh viên để giảng viên có thể điểm danh theo từng tuần. Hệ thống cũng hỗ trợ giảng viên điểm danh những ai chưa điểm danh một cách dễ dàng

### 2.18\. Xác thực sinh viên

### 2.19\. Quản lý nhóm môn học

Chức năng dành sinh viên có thể xem đánh giá môn học và tham gia thảo luận về các môn học trong trường. Bất kề người dùng nào cũng có thể xem và tham gia thảo luận.

- ##### 2.19.1\. Đánh giá môn học

  Mỗi một môn học trong trường sẽ đều có thể được đánh giá, những người đã từng học những môn này có thể chia sẻ kinh nghiệm học tập, hướng học tập để có thể học được môn đó một cách dễ dàng và điểm cao. Những bình luận và đánh giá hay có thể được đánh giá để hiển thị lên trên. Chức năng đánh giá sẽ do người dùng vote, người dùng có thể vote qua số sao. Từ 1 đến 5 sao.

- #### 2.19.2\. Thảo luận môn học

  Với mỗi môn học , sinh viên có thể vào những mục môn học đó. Hệ thống sẽ hiển thị ra danh sách các môn học mà sinh viên ngành phải học . Khi bấm vào một môn bất kì và chấp nhận tham gia vào nhóm thảo luận của môn học đó thì sinh viên có thể tạo thảo luận tham gia bình luận về những chủ đề liên quan tới môn học đó. Những chủ đề nào nóng hay nhiều nguời quan tâm thì sẽ hiển thị lên đầu nhóm.

### 2.20\. Quản lý đăng ký học

- ##### 2.20.1\. Quản lý thông báo đăng ký học

  Chức năng dành cho sinh viên, sinh viên có thể quản lý những lớp học đã tham gia trong kì, đăng ký thử những môn học trong kì tới. Mục đích là để sinh viên có thể tiện nhất khi đăng ký học

- #### 2.20.2\. Quản lý đăng ký học nháp

  Chức năng dành cho sinh viên trước kì đăng kí học sẽ hiển thị danh sách các môn học trong kì tới sẽ hiển thị ra cho sinh viên. Sinh viên có thể chọn môn tương ứng trên danh sách và hiển thị thời gian và lớp học. Sinh viên có thể đăng ký thử. Môn đó sẽ được hiển thị lên thời khóa biểu nháp của sinh viên, không cho phép đăng ký 2 môn trùng nhau. Sau khi hoàn thành đăng ký sinh viên có thể chia sẻ TKB đó lên trang cá nhân dưới dạng ảnh.

- #### 2.20.3\. Quản lý tham gia lớp học

  Chức năng này dành cho sinh viên, họ có thể quản lý những lớp học mà họ đã tham gia, Khi chọn chức năng này thì mặc địch sẽ hiển thị ra các lớp học của những môn học đã đăng ký trong kì hiện tại. (Có nên cho phép sinh viên out khỏi lớp học ko?)

#### 2.21\. Quản lý lớp học của sinh viên

Chức năng này dành cho sinh viên khi họ đã tham gia vào một lớp học trong kì. Sinh viên sẽ có chức năng tham gia vào nhóm chat với các thành viên trong lớp, tạo những cuộc thảo luận ,điểm danh

- #### 2.21.1\. Quản lý chat nhóm cả lớp học

- #### 2.21.2\. Quản lý thảo luận lớp học

- #### 2.21.3\. Quản lý nhóm sinh viên

- #### 2.21.4\. Quản lý cài đặt

- #### 2.21.5\. Quản lý diểm danh

## Các chức năng của quản trị hệ thống

### 2.22\. Quản lý nhóm người dùng

### 2.23\. Quản lý người dùng

### 2.24\. Quản lý môn học

### 2.25\. Quản lý phân quyền

### 2.26\. Quản lý page

### 2.27\. Quản lý nhóm

### 2.28\. Quản lý báo cáo

### 2.29\. Quản lý cấu hình

### 2.30\. Quản lý backup và restore
