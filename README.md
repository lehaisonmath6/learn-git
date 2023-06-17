- Tạo commit sử dụng lệnh:
+ git add ./README.md
+ git commmit -m "add commit"
- Push commit lên github:
    + git push origin main
- Khi code lỗi mà muốn trở về trạng thái commit gần nhất (trường hợp chưa dùng git add, git commit) thì chỉ cần dùng lệnh 
    + git restore <tên file>
- Khi code lỗi mà muốn trở về trạng thái commit gần nhất (trường hợp đã gõ lệnh git add) thì dùng 2 lệnh liên tiếp:
    + git restore --staged  <tên file>
    + git restore <tên file>
- Khi code lỗi mà muốn trở về trạng thái commit gần nhất (trường hợp đã gõ lệnh git commmit) thì dùng các lệnh sau:
    + git log (để xem danh sách commit)
    + git revert <tên commit hash gần nhất>
- Tạo một nhánh mới từ nhánh hiện tại, xem danh sách nhánh và chuyển sang nhánh mới, push nhánh lên github
    + git branch <tên nhánh>
    + git branch -a
    + git checkout <tên nhánh>
    + git push origin <tên nhánh>

- Hợp nhánh develop vào nhánh main sử dụng rebase
    + trên nhánh develop commit vài commit kiểu rebase 1, rebase 2