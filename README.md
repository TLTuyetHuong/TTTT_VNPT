<h1 align='center'> BÁO CÁO TIẾN ĐỘ</h1>

***Tên đề tài: Quản lý đào tạo 💥***

***Sinh viên thực hiện: Trần Lê Tuyết Hương 💫***

### 🌷 Câu 1: Angular là gì? Lợi ích của Angular so với javascript thuần 💭
- Angular là một nền tảng hay JavaScript Framework được phát triển để xây dựng các Single Page Application (SPA) sử dụng HTML, JavaScript và TypeScript.
- Angular được viết bằng TypeScript và khuyến nghị sử dụng TypeScript để viết các ứng dụng Angular. Angular đã loại bỏ một số khái niệm được sử dụng trong AngularJS, chẳng hạn như phạm vi, bộ điều khiển và nhà máy. Nó cũng có một cú pháp khác cho các thuộc tính và sự kiện ràng buộc. Một điểm khác biệt lớn nữa là thư viện Angular là dạng mô-đun và do đó bạn có thể chọn các mô-đun mà bạn cần để giảm kích thước gói. Angular cũng giới thiệu các khái niệm nâng cao như biên dịch trước thời gian (AOT), tải lười biếng và lập trình phản ứng.
- Lợi ích của Angular:
    - Angular giúp nâng cao năng suất của các lập trình viên.
    - Cấu trúc phát triển rõ ràng.
    - Angular giúp giảm tối đa kích thước và tăng tối đa hiệu suất của ứng dụng.
    - Hỗ trợ đầy đủ tính năng điều hướng (routing)

### 🌱 Câu 2: So sánh CSDL quan hệ và CSDL không quan hệ 💭
|                   |       **CSDL quan hệ**         |      **CSDL không quan hệ**       |
|:------------------|:---------------------------|:------------------------------|
| **Khối lượng công việc tối ưu**| Cơ sở dữ liệu quan hệ được thiết kế dành cho các ứng dụng xử lý giao dịch trực tuyến (OLTP).| Các cơ sở dữ liệu NoSQL được thiết kế cho các mẫu truy cập dữ liệu, bao gồm các ứng dụng có độ trễ thấp.|
|**Mô hình dữ liệu**| Mô hình quan hệ chuẩn hóa dữ liệu vào bảng được hình thành từ hàng và cột.| Các cơ sở dữ liệu NoSQL cung cấp nhiều mô hình dữ liệu khác nhau như khóa-giá trị, tài liệu và biểu đồ, được tối ưu hóa để đạt hiệu năng và quy mô tối ưu. |
|**Thuộc tính ACID**| Cơ sở dữ liệu quan hệ có các thuộc tính mang tính nguyên tố, nhất quán, tách biệt và bền vững (ACID)| Cơ sở dữ liệu NoSQL thường phải đánh đổi bằng cách nới lỏng một số thuộc tính ACID này của cơ sở dữ liệu quan hệ để có mô hình dữ liệu linh hoạt hơn có khả năng thay đổi quy mô theo chiều ngang. |
|**Hiệu năng**| Hiệu năng thường phụ thuộc vào hệ thống con của ổ đĩa.|Hiệu năng thường được xem là chức năng của kích cỡ cụm phần cứng ngầm, độ trễ mạng và ứng dụng đưa ra lệnh gọi.|
|**Quy mô**| Cơ sở dữ liệu quan hệ thường tăng quy mô bằng cách tăng năng lực điện toán của phần cứng hoặc tăng quy mô bằng cách thêm bản sao của khối lượng công việc chỉ đọc.|Cơ sở dữ liệu NoSQL thường có tính phân mảnh cao do các mẫu truy cập khóa-giá trị có khả năng tăng quy mô bằng cách sử dụng kiến trúc được phân phối để tăng thông lượng, đem đến hiệu năng ổn định với quy mô gần như không giới hạn.|
|**API**| Yêu cầu lưu trữ và truy xuất dữ liệu được truyền đạt bằng cách sử dụng các truy vấn nhất quán với ngôn ngữ truy vấn có cấu trúc (SQL). | API trên cơ sở đối tượng cho phép các nhà phát triển ứng dụng dễ dàng lưu trữ và truy xuất cấu trúc dữ liệu trong bộ nhớ. |


### 🍁 Câu 3: So sánh mô hình microservice và mô hình nguyên khối 💭
|       **Mô hình Microservice**         |          **Mô hình nguyên khối**       |
|:------------------------------|:------------------------------|
|- Các microservice hoạt động tách biệt nhau trong hệ thống, do vậy việc build một microservice cũng độc lập với việc build các microservice khác. |- Toàn bộ ứng dụng là một khối lớn, trong khối lớn ấy có chia thành các mô đun nhỏ, mỗi mô đun thực hiện một nhiệm vụ riêng và các mô đun thường gọi nhau qua function call.
|- Mỗi microservice là một dịch vụ chuyên biệt, có thể hoạt động độc lập.|- Việc phát triển và triển khai ứng dụng với kiến trúc này khá đơn giản khi mà các IDE hỗ trợ rất tốt việc kiểm tra và chạy ứng dụng với chỉ một cú click chuột hay một phím tắt.|
|-Kiến trúc microservice sinh ra là để dành cho các hệ thống từ lớn đến vô cùng lớn.|Kiến trúc này cũng đặc biệt phù hợp với các công ty outsource.|

### 🌹 Câu 4: Cơ sở dữ liệu phân tán là gì? 💭
CSDL phân tán là một tập hợp dữ liệu có liên quan (về logic) được dùng chung và phân tán về mặt vật lí trên một mạng máy tính.

### 🍀 Câu 5: Spring boot là gì? 💭
- Spring Boot là một dự án phát triển bởi JAV (ngôn ngữ java) trong hệ sinh thái Spring framework. Nó giúp cho các lập trình viên chúng ta đơn giản hóa quá trình lập trình một ứng dụng với Spring, chỉ tập trung vào việc phát triển business cho ứng dụng.
- Spring Boot là một giải pháp được sử dụng rộng rãi ngày nay để phát triển ứng dụng web Java. Nó có một quy ước cố định về cách tiếp cận cấu hình. Nó hoàn toàn được điều khiển bởi cấu hình và làm cho việc sử dụng Spring Framework và nhiều thư viện của bên thứ ba khác trở nên thú vị. Các ứng dụng Spring Boot là cấp sản xuất và chỉ có thể chạy trong bất kỳ môi trường nào có cài đặt JVM. Nó sử dụng một thùng chứa servlet được nhúng như Tomcat, Jetty hoặc Undertow để chạy ứng dụng. Nó tự động cấu hình Spring bất cứ khi nào có thể với các giá trị mặc định hợp lý và có POM khởi động cho nhiều mô-đun và thư viện của bên thứ ba. Nó không yêu cầu bất kỳ cấu hình XML nào và cho phép bạn tùy chỉnh các bean tự động định cấu hình bằng cách sử dụng cấu hình Java.

### 💐Câu 6: Sơ đồ usecase 💭
![SoDoUseCase](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoUsecase.png)

**1. Chức năng Quản lý danh mục tổ chức** 🍂

- Tìm kiếm tổ chức: tìm kiếm theo: mã tổ chức, tên tổ chức.

**2. Chức năng Quản lý danh mục chứng chỉ** 🍂

- Tìm kiếm: tìm kiếm theo tên danh mục chứng chỉ.

- Quản lý trạng thái danh mục chứng chỉ: mỗi danh mục chứng chỉ có trạng thái hoặc “Đang sử dụng” hoặc “Ngưng sử dụng”

- Khóa chứng chỉ:
    - Thay dổi trạng thái danh mục chứng chỉ sang “Ngưng sử dụng”.
    - Đảm bảo lưu trữ chứng chỉ của nhân viên dù chứng chỉ đã ngưng sử dụng.

**3. Chức năng Quản lý chứng chỉ** 🍂
- Tìm kiếm: tìm kiếm chứng chỉ của nhân viên theo: mã nhân viên, tên nhân viên, tên đơn vị.
- Xuất file danh sách: xuất file danh sách chứng chỉ của nhân viên.
- 
**4. Chức năng Quản lý đào tạo** 🍂
- Thêm chương trình đào tạo.
- Thêm lịch đào tạo: mỗi Chương trình đào tạo sẽ có một hoặc nhiều lịch đào tạo theo: mã đào tạo, tên đào tạo, ngày bắt đầu, ngày kết thúc, trạng thái.
- Tìm kiếm: tìm kiếm chương trình đào tạo.
- Quản lý học viên thuộc chương trình đào tạo: thêm học viên vào chương trình đào tạo, xóa học viên khỏi chương trình đào tạo.
- 
**5. Chức năng Quản lý học viên** 🍂
- Đánh giá học viên sau khóa học.
- Điểm danh: điểm danh các học viên.
- Thanh toán: đánh dấu các học viên đã thanh toán học phí.

**6. Chức năng quản lý dự toán** 🍂
- Tìm kiếm: tìm kiếm dự toán đào tạo theo: mã dự toán, số lượng học viên.
- In dự toán.

### 🌿Câu 7: Sơ đồ class 💭
![SoDoUseClass](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoClass.png)

**1. TỔ CHỨC** 🌱

Lớp Tổ chức dùng để lưu thông tin các tổ chức trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi tổ chức có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của tổ chức|
|3|	NoiDung|	Varchar|	Nội dung thông tin về tổ chức |

**2. DANH MỤC CHỨNG CHỈ** 🌱

Lớp Danh mục chứng chỉ dùng để lưu thông tin danh mục chứng chỉ của quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi danh mục chứng chỉ có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của danh mục chứng chỉ|
|3|	NoiDung|	Varchar|	Nội dung thông tin về chứng chỉ|
|4|	ThoiGianHieuLuc|	Integer|	Thời gian hiệu lực của từng chứng chỉ|

**3. TRẠNG THÁI DANH MỤC CHỨNG CHỈ** 🌱

Lớp Trạng thái chứng chỉ dùng để lưu thông tin trạng thái của chứng chỉ trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi trạng thái chứng chỉ có một mã riêng biệt để phân biệt|
|2|	TrangThai|	Varchar|	Trạng thái của từng chứng chỉ|

**4. CHỨNG CHỈ** 🌱

Lớp chứng chỉ dùng để lưu thông tin về các chứng chỉ trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	NgayCap|	Date|	Ngày cấp của chứng chỉ|
|2|	NgayHetHan|	Date|	Ngày hết hạn của chứng chỉ|
|3|	URLChungChi|	Varchar	|Đường dẫn tới chứng chỉ|

**5. NHÂN VIÊN** 🌱

Lớp Nhân viên dùng để lưu thông tin nhân viên trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi nhân viên có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của nhân viên|
|3|	NgaySinh|	Date|	Ngày sinh của nhân viên|
|4|	GioiTinh|	Varchar|	Giới tính của nhân viên|

**6. CHỨC DANH** 🌱

Lớp chức danh dùng để lưu các chức danh của nhân viên trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi chức danh có một mã riêng biệt để phân biệt|
|2|	ChucDanh|	Varchar|	Tên của chức danh|

**7. KHOA** 🌱

Lớp Khoa dùng để lưu thông tin các khoa của nhân viên trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi khoa có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của khoa|

**8. BỆNH VIỆN** 🌱

Lớp Bệnh viên dùng để lưu thông tin các bệnh viện trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi bệnh viện có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của bệnh viện|

**9. ĐỐI TƯỢNG** 🌱

Lớp đối tượng dùng để lưu thông tin các đối tượng có trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi đối tượng có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của đối tượng|
|3|	MoTa|	Varchar|	Mô tả đối tượng|

**10. CHƯƠNG TRÌNH ĐÀO TẠO** 🌱

Lớp Chương trình đào tạo dùng để lưu thông tin các chương trình đào tạo có trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar	|Mỗi chương trình đào tạo có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của chương trình đào tạo|
|3|	NgayBatDau|	Date|	Ngày bắt đầu chương trình đào tạo|
|4|	NgayKetThuc|	Date|	Ngày kết thúc chương trình đào tạo|
|5|	DiaDiem|	Varchar|	Nơi diễn ra khóa đào tạo|
|6|	NoiDung|	Varchar	|Nội dung chương trình đào tạo|
|7|	TrangThai|	Varchar	|Trạng thái chương trình đào tạo|
|8|	SoBuoiHoc|	Int	|Số buổi học chương trình đào tạo|
|9|	DaDuyet|	Varchar	|Đã duyệt chương trình đào tạo hay chưa|

**11. LỊCH ĐÀO TẠO** 🌱

Lớp Lịch đào tạo dùng để  lưu thông tin về lịch đào tạo của chương trình đào tạo trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi lịch đào tạo có một mã riêng biệt để phân biệt|
|2|	ThoiGianBatDau|	Date|	Thời gian bắt đầu của lịch đào tạo|
|3|	ThoiGianKetThuc|	Date|	Thời gian kết thúc của lịch đào tạo|
|4|	NoiDungDaoTao	|Varchar|	Nội dung thông tin cần đào tạo|
|5|	TenLichDaoTao	|Varchar	|Tên lịch đào tạo|

**12. HỌC VIÊN** 🌱

Lớp Học viên dùng để lưu thông tin học viên trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi học viên có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar	|Tên của học viên|

**13. PHIẾU ĐÁNH GIÁ** 🌱

Lớp Phiếu đánh giá dùng để lưu thông tin về điểm và đánh giá của từng học viên trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varcha|	Mỗi lịch đào tạo có một mã riêng biệt để phân biệt|
|2|	Diem|	Float|	Điểm của học viên|
|3|	DanhGiaHocVien|	Varchar|	Đánh giá kết quả của học viên|
|4|	DanhGiaKhoaDaoTao|	Varchar|	Đánh giá về khóa đào tạo|
|5|	SoBuoiThamDu|	Int|	Số buổi tham dự của học viên|

**14. PHIẾU THANH TOÁN HỌC PHÍ** 🌱

Lớp Phiếu thanh toán học phí dùng đề lưu thông tin về  thanh toán học phí trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	NgayThanhToan|	Date|	Ngày thanh toán|
|2|	MucPhi|	Float|	Mức phí thanh toán|

**15. DỰ TOÁN** 🌱

Lớp dự toán dùng để lưu thông tin về các dự toán trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi chương trình đào tạo có một mã riêng biệt để phân bi|ệt|
|2	|NgayBatDau	|Date|	Ngày bắt đầu chương trình đào tạo|
|3	|NgayKetThuc|	Date|	Ngày kết thúc chương trình đào tạo|
|4|	NoiDung|	Varchar|	Nội dung thông tin dự toán|
|5|	SoLopDaoTao|	Integer	|Số lớp đào tạo|
|6|	SoLuongHocVien|	Integer|	Số lượng học viên|

**16. GIẢNG VIÊN** 🌱

Lớp Giảng viên dùng để lưu thông tin giảng viên trong quản lý đào tạo.
|**STT**|	**Thuộc tính**|	**Kiểu dữ liệu**|	**Ý nghĩa**|
|:---|:-----------|:------------|:---------|
|1|	Ma|	Varchar|	Mỗi giảng viên có một mã riêng biệt để phân biệt|
|2|	Ten|	Varchar|	Tên của giảng viên|
|3|	NgaySinh|	Date|	Ngày sinh của giảng viên|
|4|	GioiTinh|	Varchar|	Giới tính của giảng viên|

### 🌼Câu 8: Sơ đồ Sequence 💭
1. Tìm kiếm tổ chức 🍄

![alt](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoTT_TimKiemToChuc.png)

2. Xóa danh mục tổ chức 🍄

![alt](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoTT_XoaDMTC.png)

3. Sửa danh mục tổ chức 🍄

![alt](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoTT_SuaDMTC.png)

4. In chứng chỉ 🍄

![alt](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoTT_InChungChi.png)

5. Khóa chứng chỉ 🍄

![alt](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoTT_KhoaChungChi.png)

6. Điểm danh 🍄

![alt](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoTT_DiemDanh.png)

7. Thêm chương trình đào tạo 🍄

![alt](https://huongb1809130.000webhostapp.com/LTWeb/Image_QLDT/SoDoTT_ThemCTDT.png)

### 🐚Câu 9: JHipster là gì? 💭
JHipster( viết tắt của Java Hipster) là phương pháp đơn giản để chúng ta tạo ra một project xung quanh những công nghệ được ưa thích nhất với Spring technologies và Angular/React. 🐳

- 🌺Tại sao lựa chọn JHipster?
    - JHipster cung cấp nhiều công nghệ như spring boot, gradle, maven, postgreSQL, ...
    - Với những framework frondend mạnh mẽ như html5, css3, bootstrap, angular, ...
    - Deply dự án dễ dàng nhờ docker, heroku, aws, ...

🍃 Chúng ta sẽ dễ dàng có được một project đủ mạnh mẽ đầy đủ những thứ cơ bản để bắt đầu với thời gian nhanh nhất.

### 🌸Câu 10: Các áp dụng Angular trong JHipster? 💭

🌻 Các áp dụng:
- Thư viện ng-jhipster chứa các chức năng tiện ích và các thành phần phổ biến.
- Angular CLI được sử dụng để xây dựng và thử nghiệm các ứng dụng JHipster.
- Cấu trúc dự án được sử dụng theo kiểu Angular.
- Sử dụng bộ định tuyến Angular để tổ chức các phần khác nhau của ứng dụng khách.