- Tạo commit sử dụng lệnh:
+ git add ./README.md
+ git commmit -m "add commit"
- Push commit lên github:
<<<<<<< HEAD
<<<<<<< HEAD
    + git push origin main
- Khi code lỗi mà muốn trở về trạng thái commit gần nhất (trường hợp chưa dùng git add, git commit) thì chỉ cần dùng lệnh 
    + git restore <tên file>
- Khi code lỗi mà muốn trở về trạng thái commit gần nhất (trường hợp đã gõ lệnh git add) thì dùng 2 lệnh liên tiếp:
    + git restore --staged  <tên file>
    + git restore <tên file>
- Khi code lỗi mà muốn trở về trán thái commit gần nhất (trường hợp đã gõ lệnh git commmit)
=======
    + git push origin main
>>>>>>> parent of 631c717 (add git restore)
=======
    + git push origin main
>>>>>>> parent of 631c717 (add git restore)
