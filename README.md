# Đồ án Simple Shell-
Sinh viên thực hiện: 
Nguyễn Thanh Trí -  1612722

Đồ án này bao gồm thiết kế chương trình C một giao diện shell chấp nhận các lệnh của người dùng và sau đó thực thi mỗi lệnh trong một quy trình riêng biệt. Đồ án liên quan đến việc sử dụng các lệnh gọi hệ thống UNIX fork (), exec (), Wait (), dup2 () và pipe () và được hoàn thành trên hệ thống Linux.
Các lệnh cơ bản để giao tiếp với shell: 
1. ls 
- In ra danh sách các file có trong thư mục hiện hành

2. ls -l 
- In ra đầy đủ thông tin của các file có trong thư mục hiện hành.

3. pwd
- In ra ngoài màn hình đường dẫn của thư mục đang hoạt động.

4. history 
- In ra màn hình các lệnh đã nhập vào. 

5. > 
- Chuyển hướng đầu ra của lệnh được nhập vào một file.
Ví dụ: 
Lệnh: ls > out.txt
Kết quả: Danh sách các file có trong thư mục hiện hành sẽ được ghi vào file out.txt
6. < 
- Chuyển hướng đầu vào của một file, lấy dữ liệu từ file đó và thực hiện lệnh nhập vào.
Ví dụ: 
Command: sort < in.txt 
Kết quả: In ra màn hình danh sách các kí tự đầu tiên của các dòng trong file in.txt được sắp xếp theo thứ tự c từ 'a' đến 'z'.

Hướng dẫn sử dụng: 
Bước 1. Mở terminal trong thư mục chứa mã nguồn cần thực thi
Bước 2. Nhập vào lệnh:  g++ -o <Tên Chương Trình> <Tên file mã nguồn>. Ví dụ:  g++ -o shell Shell.c
Bước 3. Nhập tên chương trình để chạy. Ví dụ: ./shell
Bước 4. Nhập vào các lệnh cần thực hiện. Ví dụ: ls, pwd, ls -l
Bước 5. Nhập 'exit' để thoát khỏi chương trình.

