# GIT
----------tải dữ liệu lên Github------------
1. tại vị trí chứa dữ liệu cần tải lên github -> chuột phải chọn "Git Bash Here"
2. git init
3. git add .
4. git commit -m "learn GIT"
5. git branch -M main
6. git remote add origin https://github.com/maivanhai88/GIT.git
7. git push -u origin main
8. chọn "sign in with a code"
9. Nhấn cancel vào bảng "git for windows"
10. username for 'https://github.com' nhập là : maivanhai88
11.password for 'https://maivanhai88@github.com': Phải chuột và paste Mã Token - enter (phần sau sẽ hướng dẫn lấy mã token) 
-----------Tải thêm file--------------
1. git add.
2. git commit -m "update"
3. git push
----------Xóa bớt file --------
giống như "Tải thêm file"
Chú ý : - Trước khi tải hoặc xóa file cần git clone https://github.com/maivanhai88/GIT.git
        để đảm bảo dữ liệu được cập nhật đầy đủ trước khi "git push"
        - Khi không git push được thì tạo lại mã token 
-----------Tạo mã Token --------------
1. Vào mục Setting
2. Developer settings
3. Personal access tokens
4. Generate new token
5. note: "test token"
6. tick tất cả các mục
7. generate token
---------Tải dữ liệu về --------------
1. git clone https://github.com/maivanhai88/GIT.git
