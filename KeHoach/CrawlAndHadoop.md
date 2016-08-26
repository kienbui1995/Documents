# **CRAWL&SCRAPE - GRAPH API FACEBOOK - SPARK**
### *Tìm hiểu về CRAWL và SCRAPE, Graph API facebook, Spark(Hadoop) và xây dựng CRAWLER lấy thông tin từ Facebook với sự hỗ trợ của SPARK(Hadoop)*
## 1. Ý tưởng
  - Sử dụng 1 tài khoản facebook tham gia tất cả các group công khai về  Đại Học Thăng Long (TLU-k25/26/27/28/29), theo dõi page liên quan, CLB trong trường. Dựa vào Graph API facebook để  lấy dữ liệu từ facebook.
  - Dữ liệu từ Facebook là lượng dữ liệu lớn nên việc lấy về và lưu trữ cần được triển khai trên trên SPARK (Hadoop).
  - Các dữ liệu phải được tiền xử lý phục phụ cho đầu vào của "Máy học".
  
## 2. Môi trường làm việc
 - Hệ điều hành: Ubuntu 16.04
 - Ngôn ngữ: python cùng thư viện Scrapy (chưa rõ phiên bản nào cũng như thư viện nào hỗ trợ tốt nhất).
 - Lưu trữ và xử lý dữ liệu: SPARK (Hadoop: DFS)
  
## 3. Công việc cần thực hiện
 - Tìm hiểu về Graph API facebook.
 - Tìm hiểu về  Crawl, Scrape và thư viện Scrapy của python
 - Tìm hiểu về DFS, map-reduce.
 - Tìm hiểu về hệ thống SPARK(Hadoop).

## 4. Kế hoạch thực hiện
- Tìm hiểu về Graph API: cách thức tổ chức các nodes, edges, fields.
- Tìm hiểu và thử nghiệm làm việc với python và thư viện hỗ trợ Crawl và Scrape.
- Sử dụng Graph API kết hợp với việc trích xuất dữ liệu để tạo 1 tool cho phép sử dụng token định danh người dùng có sẵn đọc thông tin facebook thông qua tool.
- Triển khai một số bài toán cơ bản trên SPARK(hadoop) và tối ưu hệ thống, khởi tạo một số lượng máy lớn hơn trước.
- Nghiên cứu, thiết kế, xây dựng CRAWLER trên SPARK(Hadoop) để tổ chức lưu trữ dữ liệu theo cấu trúc đầu vào của  bài toán "Máy học".

## 5. Một số khó khăn hiện tại
- Tìm hiểu chi tiết về  Spark(hadoop).
- Khả năng thực thi việc trích xuất dữ liệu từ Facebook không thông qua Graph API chưa rõ ràng vì cấu trúc Facebook không như website thông thường (tin tức, blog,...).
