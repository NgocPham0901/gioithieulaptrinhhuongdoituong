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


