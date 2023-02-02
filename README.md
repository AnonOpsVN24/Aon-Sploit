# AonSploit
No Cap
Hầu hết các CVE này cũng được công nhận bởi oxagast
Đây là một fuzzer, được viết bằng BASH SHELL, được thiết kế để tìm lỗi trong các chương trình BASH SHELL
Đây là một công cụ để xây dựng danh sách từ dựa trên những điều đã biết về người dùng.
Công cụ này tạo một danh sách tất cả các tệp thực thi suid 0 từ kho lưu trữ ap
CVE-2006-3392
Webmin <=1,29 khai thác root từ xa
Khai thác này, nâng cookie Webmin với khai thác ngang thư mục và đọc tùy ý, sau đó sử dụng lại cookie để sử dụng khai thác người dùng được xác thực để lấy quyền root từ xa.

CVE-2010-2626
Tải lên đường ống Perl và shell cho Miyabi CGI Tools <=1.02 và iOffice 0.1
Khai thác này tải lên một chương trình perl thông qua các lần đọc mở perl lỗi (|). Sau khi đẩy chương trình, nó chmods và sinh ra một trình bao. Nên hoạt động trở lại nếu máy chủ có tường lửa hay không.

CVE-2016-10401
Khai thác root từ xa bộ định tuyến PK5001Z
Sử dụng người dùng telnet đã biết và mật khẩu gốc để đăng nhập với quyền root.

CVE-2018-17336
UDisks <=2.8.0 DoS
Đây là mã ví dụ làm hỏng udisks2 thông qua nhãn hệ thống tệp không đúng định dạng mà khi được gắn rồi ghi nhật ký, tồn tại một lỗ hổng định dạng chuỗi cho phép đọc/ghi bộ nhớ tùy ý với quyền root.
# Image
<img src="https://raw.githubusercontent.com/AnonOpsVN24/Aon-Sploit/main/Screenshot_2023-02-02-22-30-24-33.jpg" >
<img src="https://raw.githubusercontent.com/AnonOpsVN24/Aon-Sploit/main/Screenshot_2023-02-02-20-59-19-52_30a42d6a209f6598350fa5f61642e1a9.jpg" >
1. git clone https://github.com/AnonOpsVN24/Aon-Sploit/

2. cd Aon-Sploit

3. chmod +x *

4. ./aon
