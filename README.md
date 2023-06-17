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

- Trộn nhánh develop vào merge:
    - Trên develop commit vài cái kiểu merge1, merge2
    - Checkout lại main rồi dùng lệnh: git merge develop

- Hợp nhánh develop vào nhánh main sử dụng rebase
    + trên nhánh develop commit vài commit kiểu rebase 1, rebase 2, rebase 3
    + switch sang nhánh main và gõ lệnh git rebase develop => lúc này các commit rebase 1, rebase 2, rebase 3 cũng sẽ xuất hiện trên git log của nhánh main

=> Tính năng này chỉ có ở main
=> Tính năng mới ở main
=> Tôi merge thằng develop vào main


=> Tôi thêm tính năng 1 vào develop
=> Thêm tính năng 2 vào develop
=> Tính năng 3 của develop
=> Tính năng 4 vào develop

=> tôi vừa merge thằng main vào develop

=> Tính nawg 5 vào dev
=> Tính nawg 6 vao dev

=> Tính năng 7 dev
=> Tính nawg 8 dev
=> Feautre 9 main
=> Feature 10 dev
