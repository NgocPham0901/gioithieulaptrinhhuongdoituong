# gioithieulaptrinhhuongdoituong
Giới thiệu về lập trình hướng đối tượng
Bảng phân công nhiệm vụ:
| STT | Họ và tên | Tên nhánh | Nhiệm vụ phân công |
| --- | --- | --- | --- |
| 1 | Phạm Trần Thái Ngọc | `main` / `nhanh-leader` | Tạo repository, viết README, tìm hiểu về Đối tượng & Lớp đối tượng , quản lý và tổng hợp bài |
| 2 | Nguyễn Thị Bích Ngọc | `nhanh-truutuong` | Tìm hiểu trừu tượng hóa đối tượng theo chức năng và Trừu tượng hóa đối tượng theo dữ liệu |
| 3 | Nguyễn Thảo Nhi | `nhanh-kethua` | Tìm hiểu Tính kế thừa và thành phần private|
| 4 | Trần Thảo Nhi | `nhanh-dahinh` | 	Tìm hiểu Tính đa hình và thành phần public |
| 5 | Lê Diễm Quỳnh | `nhanh-donggoi` | Tìm hiểu đóng gói và viết ưu&nhược điểm của OOP |

 BÀI LÀM
 GIỚI THIỆU VỀ LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG
1. Đối tượng (Object)
Trong lập trình hướng đối tượng (OOP), đối tượng (Object) là một thực thể cụ thể được tạo ra từ một lớp (Class).
Mỗi đối tượng thường bao gồm:
Thuộc tính (Attribute): Mô tả các đặc điểm hoặc trạng thái của đối tượng.
Phương thức (Method): Mô tả các hành động hoặc chức năng mà đối tượng có thể thực hiện.
Có thể hiểu đơn giản:
Class là khuôn mẫu, Object là một đối tượng cụ thể được tạo ra từ khuôn mẫu đó.

2. Lớp đối tượng (Class)
Lớp (Class) là một khuôn mẫu hoặc bản thiết kế dùng để tạo ra các đối tượng.
Class định nghĩa:
Các thuộc tính mà đối tượng có.
Các phương thức mà đối tượng có thể thực hiện.
Một Class có thể tạo ra nhiều Object khác nhau. Các Object được tạo từ cùng một Class có chung cấu trúc nhưng có thể có giá trị thuộc tính khác nhau.

3. Trừu tượng hóá đối tượng theo chức năng
-Khái niệm: là quá trình mô hình hoá phương thức của lớp dựa trên các hành động của các đối tượng.
-Các bước tiến hành:
+Tập hợp tất cả các hành động có thể có của các đối tượng.
+Nhóm các đối tượng có các hoạt động tương tự nhau
+Mỗi nhóm đối tượng đề xuất một lớp tương ứng.
+Các hành động chung của nhóm đối tượng sẽ cấu thành các phương thức của lớp tương ứng.
Ví dụ, mỗi ô tô là một đối tượng, chung các hành động:
+Có thể khởi động máy.
+Có thể chạy.
+Có thể dừng lại.
+Có thể tắt máy.
-Ngoài ra, một số ít xe có thể thực hiện một số hành động cá biệt như:
+Có thể giấu đèn pha
+Có thể tự bật đèn pha
+Có thể tự động phát tín hiệu báo động.

4. Trừu tượng hóa đối tượng theo dữ liệu
+ Khái niệm: là quá trình mô hình hóá các thuộc tính của lớp dựa trên các thuộc tính của các đối tượng tương ứng.
-Ví dụ, mỗi ô tô là một đối tượng có chung các thuộc tính:
+nhãn hiệu
+màu sắc
+giá bán
+công suất động cơ
-Ngoài ra, một số ít xe có thể có thêm các thuộc tính:
+dạn nghe nhạc
+màn hình xem ti vi
+kính chống nắng
+chống đạn...

5. Sự kế thừa (Inheritance)
-Khái niệm: Là cơ chế cho phép một lớp mới (lớp dẫn xuất) thừa hưởng và sử dụng lại các thuộc tính cũng như phương thức từ một lớp đã có (lớp cơ sở).
-Lợi ích và đặc điểm chính:
+Cài đặt tập trung: Chỉ cần cài đặt phương thức một lần tại lớp cơ sở, tất cả các lớp dẫn xuất đều có thể tái sử dụng ngay.
+Tránh dư thừa mã nguồn: Cho phép tránh sự cài đặt trùng lặp mã nguồn của chương trình.
+Tiết kiệm thời gian bảo trì: khi cần điều chỉnh dữ liệu hoặc cấu trúc chung của các lớp, lập trình viên chỉ cần chỉnh sửa một lần duy nhất tại lớp cơ sở.

6. Thành phần Private trong lớp
-Phạm vi riêng tư: Là khu vực dành riêng cho lớp, không chia sẻ với bất kì lớp khác từ bên ngoài.
-Giới hạn truy nhập: Thành phần private chỉ cho phép truy nhập trong phạm vi nội bộ lớp.
-Các đối tượng thuộc vùng private: Thông thường các thành phần sau sẽ được đặt vào khu vực private của lớp:
-Thuộc tính dữ liệu: Tất cả các thuộc tính dữ liệu của lớp
-Phương thức hỗ trợ nội bộ: Các phương thức trung gian, được sử dụng như các bước tính toán đệm cho các phương thức khác.

7.Tính đa hình(polymorphism): 
Là một đặng trưng của lập trình hướng đối tượng (OOP), cho phép cùng một tên phương thức nhưng có thể thực hiện nững hành động khác nhau tùy vào đối tượng được gọi
  +Nạp chồng phương thức (overloading):các phương thức cùng tên nhưng khác số lượng hoặc kiểu tham số 
  +Ghi đè phương thức (overloading): lớp con định nghĩa lại phương thức của lớp cha để thực hiện theo cách riêng
  +Cách hoạt động: khi gọi một phương thức, chương trình sẽ xác định phương thức phù hợp dựa trên đối tượng và kiểu tham số
=> Ý nghĩa: giúp chương trình linh hoạt, dễ mở rộng và dễ bảo trì, vì cùng một cách gọi nhưng mỗi đối tượng có thể có cách xử lí khác nhau

8.Thành phần public: 
Là thành phần của lớp có thể được truy cập từ bên trong và bên ngoài lớp. Thường dùng cho các phương thức mà đối tượng bên noài cần sử dụng

9.Khái niệm về sự đóng gói (Encapsulation): 
Là nguyên lý gom chung dữ liệu (thuộc tính) và các hàm xử lý dữ liệu đó (phương thức) vào bên trong một đơn vị duy nhất gọi là lớp, đồng thời che dấu sự cài đặt bên trong của phương thức, cho phép che dấu dữ liệu bên trong của đối tượng, cho phép hạn chế tối đa việc sửa lại mã chương trình.
Lợi ích chính của sự đóng gói:
Bảo mật dữ liệu: Ngăn chặn truy cập trái phép vào các thành phần bên trong.
Tăng tính linh hoạt: Dễ dàng thay đổi logic bên trong mà không ảnh hưởng đến mã bên ngoài.
Dễ bảo trì: Cải thiện khả năng quản lý mã nguồn.
Các thành phần của sự đóng gói: 
Access Modifiers (Các phạm vi truy cập):
private: Chỉ có thể truy cập từ bên trong lớp.
protected: Truy cập từ bên trong lớp và các lớp dẫn xuất.
public: Truy cập từ bất kỳ đâu.
internal (trong C#) / default (trong Java): Chỉ truy cập được trong cùng một package/assembly.
Getters và Setters:
Được sử dụng để truy cập và cập nhật giá trị của các trường (fields) được ẩn.
VÍ DỤ THỰC TẾ: 
Hãy tưởng tượng tài khoản ngân hàng của bạn:
Bạn không thể tự ý nhét tay vào két sắt hay tự sửa số dư tài khoản của mình.
Muốn lấy tiền hoặc xem số dư, bạn phải thông qua các giao dịch tại quầy hoặc cây ATM (các nút bấm, giao diện).
Các thao tác đó kiểm tra xem bạn có đủ tiền hay mật khẩu đúng không rồi mới thay đổi số dư.

10. Ưu điểm của OOP:
Tái sử dụng mã nguồn: Tính kế thừa cho phép tận dụng lại các đoạn code đã viết mà không cần lặp lại.
Dễ bảo trì và nâng cấp: Mã được chia thành các đối tượng độc lập giúp việc sửa lỗi hoặc thêm tính năng mới dễ dàng hơn.
Tính bảo mật cao: Tính đóng gói giúp ẩn đi dữ liệu bên trong và chỉ cho phép truy cập qua các phương thức được định nghĩa.
Khả năng mở rộng tốt: Dễ dàng xây dựng và phát triển các hệ thống phần mềm lớn và phức tạp nhờ tính trừu tượng
Nhược điểm của OOP:
Độ phức tạp cao: Chương trình có thể trở nên cồng kềnh và khó học hơn đối với người mới bắt đầu.
Ảnh hưởng hiệu năng: Tốc độ chạy chương trình có thể chậm hơn so với lập trình hướng thủ tục do tốn tài nguyên quản lý đối tượng.
Tốn thời gian thiết kế: Cần lập kế hoạch và phân tích kỹ lưỡng các lớp, đối tượng trước khi bắt đầu viết code.



