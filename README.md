# bước 1: Kiểm tra trạng thái 
`git status `
# bước 2: Add file
`git add path-file-name`
# bước 3: Kiểm tra lại trạng thái
- nếu màu xanh thì push lên được
- nếu màu đỏ thì chưa push lên được
`git status`
# bước 4: Commit file
`git commit -m "content"`
# bước 5: Push file
-branch name là branch hiện tại
`git push origin branch-name`  



# add nhiều file
`git add .` hoặc `git add *`

# git checkout 
- dùng để chuyển branch
`git checkout branch-name`



# git pull
- git pull dùng để lấy code mới nhất từ trên git về
- trước khi pull thì phải commit code lên
`git pull origin branch-name`
# tạo branch
- Mục đích tạo branch là copy toàn bộ branch hiện tại sang 1 branch mới
`git branch -m branch-name`
