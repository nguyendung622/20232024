# Kho lưu giữ bài tập và bài giảng năm học 20232024
## Clone thư mục git về máy tính

git clone https://github.com/nguyendung622/20232024.git

## Kéo các thay đổi từ server vào nhánh hiện tại

git pull [remote] [branch]

Ví dụ:

Kéo các thay đổi từ nhánh origin về nhánh hiện tại main

git pull origin main

## Thêm các file mới hoặc file đã thay đổi vào phiên bản hiện tại

Thêm tất cả

git add .

Thêm file được chỉ định

git add <file>

## Lưu giữ trạng thái hiện tại của mã nguồn vào kho lưu trữ

git commit -m "message"

Ví dụ:

git commit -m "Thêm chức năng xử lý đăng nhập"

## Git push đẩy các commit lên kho lưu trữ từ xa

git push <remote> <branch>

# Tạo SSH Key

ssh-keygen -t rsa -b 4096 -C "địa chỉ email"

# Xem nơi lưu SSH Key

ls ~/.ssh



