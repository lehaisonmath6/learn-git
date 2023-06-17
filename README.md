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
- Khi code lỗi mà muốn trở về trạng thái commmit gần nhất (trường hợp đã gõ lện git push) thì dùng tương tự như bên trên