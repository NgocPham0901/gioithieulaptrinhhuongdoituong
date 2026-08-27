1. Sự kế thừa (Inheritance)
-Khái niệm: Là cơ chế cho phép một lớp mới (lớp dẫn xuất) thừa hưởng và sử dụng lại các thuộc tính cũng như phương thức từ một lớp đã có (lớp cơ sở).
-Lợi ích và đặc điểm chính:
+Cài đặt tập trung: Chỉ cần cài đặt phương thức một lần tại lớp cơ sở, tất cả các lớp dẫn xuất đều có thể tái sử dụng ngay.
+Tránh dư thừa mã nguồn: Cho phép tránh sự cài đặt trùng lặp mã nguồn của chương trình.
+Tiết kiệm thời gian bảo trì: khi cần điều chỉnh dữ liệu hoặc cấu trúc chung của các lớp, lập trình viên chỉ cần chỉnh sửa một lần duy nhất tại lớp cơ sở.

2. Thành phần Private trong lớp
-Phạm vi riêng tư: Là khu vực dành riêng cho lớp, không chia sẻ với bất kì lớp khác từ bên ngoài.
-Giới hạn truy nhập: Thành phần private chỉ cho phép truy nhập trong phạm vi nội bộ lớp.
-Các đối tượng thuộc vùng private: Thông thường các thành phần sau sẽ được đặt vào khu vực private của lớp:
-Thuộc tính dữ liệu: Tất cả các thuộc tính dữ liệu của lớp
-Phương thức hỗ trợ nội bộ: Các phương thức trung gian, được sử dụng như các bước tính toán đệm cho các phương thức khác.
