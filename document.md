# git config

## git config --global user.name "user name"

## git config --global user.email "abc@gmail.com"

## git config --list (Dùng để kiểm tra các git config) => nhấn Q để thoát

# Khởi tạo local repository

## git init

=> tạo ra local repository với nhánh chính master

## git init -b main

=> taọ ra local repository với nhánh chính là main

## Tạo remote repository => lên github tạo repository

=> Khi tạo remote repository nhánh chính sẽ là nhánh main (github, gitlab)

## git add . ( Dùng để thêm những file đã thay đổi vào trong staging area )

=> Những file nằm trong staging area thông qua lệnh git add mới có thể đc đưa lên remote repository

## git rm --cached <file> (Dùng để đưa file từ staging area => về lại working)

## git commit -m "message" (Dùng để commit nội dung cho những file đang ở staging)

# Tạo SSH keys

## ssh-keygen -t ed25519 -C "abc@gmail.com"

## lấy đường dẫn nơi lưu trữ ssh key

## cat <đường dẫn file .pub> (Dùng để hiển thị nội dung file key.pub)

## copy nội dung đc hiển thị ra và add vào trong tài khoản github

## git remote add origin <đường dẫn remote repository (SSH)> (Chỉ cần chạy 1 lần)

## git push -u origin main (Dùng để đẩy code từ local repository lên remote repository)

=> -u origin : chỉ cần sử dụng ở lần git push đầu tiền => từ lần thứ 2 chỉ cần gõ git push

## git clone (Dùng để clone 1 source code từ remote repository về máy)

## git pull (Dùng để lấy code mới nhất từ remote repository)

## git branch (liệt kê các nhánh hiện tại)

## git switch -c <tên nhánh> (tạo 1 nhánh mới và chuyển qua nhánh đó)

## git checkout -b <tên nhánh>

## git merge
