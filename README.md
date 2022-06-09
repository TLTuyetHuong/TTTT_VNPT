<h1 align='center'> BÁO CÁO TIẾN ĐỘ</h1>

***Họ tên: Trần Lê Tuyết Hương***

### ⚡️ Câu 1: Angular là gì? Lợi ích của Angular so với javascript thuần ✏️
- Angular là một nền tảng hay JavaScript Framework được phát triển để xây dựng các Single Page Application (SPA) sử dụng HTML, JavaScript và TypeScript.
- Angular được viết bằng TypeScript và khuyến nghị sử dụng TypeScript để viết các ứng dụng Angular. Angular đã loại bỏ một số khái niệm được sử dụng trong AngularJS, chẳng hạn như phạm vi, bộ điều khiển và nhà máy. Nó cũng có một cú pháp khác cho các thuộc tính và sự kiện ràng buộc. Một điểm khác biệt lớn nữa là thư viện Angular là dạng mô-đun và do đó bạn có thể chọn các mô-đun mà bạn cần để giảm kích thước gói. Angular cũng giới thiệu các khái niệm nâng cao như biên dịch trước thời gian (AOT), tải lười biếng và lập trình phản ứng.
- Lợi ích của Angular:
    - Angular giúp nâng cao năng suất của các lập trình viên.
    - Cấu trúc phát triển rõ ràng.
    - Angular giúp giảm tối đa kích thước và tăng tối đa hiệu suất của ứng dụng.
    - Hỗ trợ đầy đủ tính năng điều hướng (routing)

### 🌱 Câu 2: So sánh CSDL quan hệ và CSDL không quan hệ ✏️
|                   |       **CSDL quan hệ**         |      **CSDL không quan hệ**       |
|:------------------|:---------------------------|:------------------------------|
| **Khối lượng công việc tối ưu**| Cơ sở dữ liệu quan hệ được thiết kế dành cho các ứng dụng xử lý giao dịch trực tuyến (OLTP).| Các cơ sở dữ liệu NoSQL được thiết kế cho các mẫu truy cập dữ liệu, bao gồm các ứng dụng có độ trễ thấp.|
|**Mô hình dữ liệu**| Mô hình quan hệ chuẩn hóa dữ liệu vào bảng được hình thành từ hàng và cột.| Các cơ sở dữ liệu NoSQL cung cấp nhiều mô hình dữ liệu khác nhau như khóa-giá trị, tài liệu và biểu đồ, được tối ưu hóa để đạt hiệu năng và quy mô tối ưu. |
|**Thuộc tính ACID**| Cơ sở dữ liệu quan hệ có các thuộc tính mang tính nguyên tố, nhất quán, tách biệt và bền vững (ACID)| Cơ sở dữ liệu NoSQL thường phải đánh đổi bằng cách nới lỏng một số thuộc tính ACID này của cơ sở dữ liệu quan hệ để có mô hình dữ liệu linh hoạt hơn có khả năng thay đổi quy mô theo chiều ngang. |
|**Hiệu năng**| Hiệu năng thường phụ thuộc vào hệ thống con của ổ đĩa.|Hiệu năng thường được xem là chức năng của kích cỡ cụm phần cứng ngầm, độ trễ mạng và ứng dụng đưa ra lệnh gọi.|
|**Quy mô**| Cơ sở dữ liệu quan hệ thường tăng quy mô bằng cách tăng năng lực điện toán của phần cứng hoặc tăng quy mô bằng cách thêm bản sao của khối lượng công việc chỉ đọc.|Cơ sở dữ liệu NoSQL thường có tính phân mảnh cao do các mẫu truy cập khóa-giá trị có khả năng tăng quy mô bằng cách sử dụng kiến trúc được phân phối để tăng thông lượng, đem đến hiệu năng ổn định với quy mô gần như không giới hạn.|
|**API**| Yêu cầu lưu trữ và truy xuất dữ liệu được truyền đạt bằng cách sử dụng các truy vấn nhất quán với ngôn ngữ truy vấn có cấu trúc (SQL). | API trên cơ sở đối tượng cho phép các nhà phát triển ứng dụng dễ dàng lưu trữ và truy xuất cấu trúc dữ liệu trong bộ nhớ. |


### ⚡️ Câu 3: So sánh mô hình microservice và mô hình nguyên khối ✏️
|       **Mô hình Microservice**         |          **Mô hình nguyên khối**       |
|:------------------------------|:------------------------------|
|- Các microservice hoạt động tách biệt nhau trong hệ thống, do vậy việc build một microservice cũng độc lập với việc build các microservice khác. |- Toàn bộ ứng dụng là một khối lớn, trong khối lớn ấy có chia thành các mô đun nhỏ, mỗi mô đun thực hiện một nhiệm vụ riêng và các mô đun thường gọi nhau qua function call.
|- Mỗi microservice là một dịch vụ chuyên biệt, có thể hoạt động độc lập.|- Việc phát triển và triển khai ứng dụng với kiến trúc này khá đơn giản khi mà các IDE hỗ trợ rất tốt việc kiểm tra và chạy ứng dụng với chỉ một cú click chuột hay một phím tắt.|
|-Kiến trúc microservice sinh ra là để dành cho các hệ thống từ lớn đến vô cùng lớn.|Kiến trúc này cũng đặc biệt phù hợp với các công ty outsource.|

### 🌱 Câu 4: Cơ sở dữ liệu phân tán là gì? ✏️
CSDL phân tán là một tập hợp dữ liệu có liên quan (về logic) được dùng chung và phân tán về mặt vật lí trên một mạng máy tính.

### ⚡️ Câu 5: Spring boot là gì? ✏️
Spring Boot là một dự án phát triển bởi JAV (ngôn ngữ java) trong hệ sinh thái Spring framework. Nó giúp cho các lập trình viên chúng ta đơn giản hóa quá trình lập trình một ứng dụng với Spring, chỉ tập trung vào việc phát triển business cho ứng dụng.

