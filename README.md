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
