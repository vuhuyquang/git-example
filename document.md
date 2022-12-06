1. git init
// khởi tạo repo dưới local
2. git status
// xem trạng thái commit, nhánh hiện tại
3. 
git checkout -b develop
// tạo nhánh mới tên "develop"
git checkout branch_name
// chuyển sang nhánh "branch_name"
4. 
git add file_name
// add từng file
git add .
// add tất cả file
5. git commit -m "Message"
// commit code với mô tả "Message"
6. 
git branch
// xem nhánh
git branch -d branch_name
// xóa nhánh tên là "branch_name"
7. git remote add origin https://github.com/vuhuyquang/git-example.git
// tạo mới 1 remote
8. git push origin develop
// đẩy code lên nhánh develop
9. git pull origin develop
// lấy code từ nhánh develop về máy tính