# Git Cheat Sheet

## Git cơ bản

| Lệnh                            | Mô tả                                                                                                    |
| ------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `git init <directory>`          | Tạo repo trống trong thư mục được chỉ định. Nếu không cung cấp thư mục sẽ tạo repo cho thư mục hiện tại. |
| `git clone <repo>`              | Clone remote repo có đường dẫn `<repo>` về máy.                                                          |
| `git config user.name <name>`   | Đặt lại tên tác giả.                                                                                     |
| `git add <directory> or <file>` | Đưa thư mục hoặc file vào index để chuẩn bị cho commit tiếp theo.                                        |
| `git commit -m "<message>"`     | Commit tất cả file trong index với mô tả là `<message>`.                                                 |
| `git status`                    | Xem trạng thái của các file.                                                                             |
| `git log`                       | Hiện toàn bộ lịch sử commit.                                                                             |
| `git diff`                      | Hiển thị những thay đổi hiện tại mà bạn tạo ra so với index (chưa được add vào index).                   |

## Huỷ bỏ thay đổi

| Lệnh                  | Mô tả                                                            |
| --------------------- | ---------------------------------------------------------------- |
| `git revert <commit>` | Tạo một commit đảo ngược với `<commit>` để huỷ bỏ `<commit>`.    |
| `git reset <file>`    | Bỏ `<file>` ra khỏi index (vẫn giử lại nội dung thay đổi).       |
| `git clean -df`       | Xoá bỏ tất cả file và thư mục không muốn đưa vào Git (file rác). |

## Thay đổi lịch sử

| Lệnh                 | Mô tả                                                                                  |
| -------------------- | -------------------------------------------------------------------------------------- |
| `git commit --amend` | Commit nối vào commit gần nhất (không tạo commit mới).                                 |
| `git rebase <base>`  | Dùng `<base>` làm base mới. (`<base>` có thể là nhánh, tag, commit).                   |
| `git reflog`         | Xem lịch sử thay đổi của `HEAD` (rất hữu ích khi lỡ tay làm mất code và muốn tìm lại). |

## Nhánh

| Lệnh                       | Mô tả                                                            |
|----------------------------|------------------------------------------------------------------|
| `git branch`               | Liệt kê tất cả nhánh trong repo. Thêm `-a` để xem remote branch. |
| `git branch <branch>`      | Tạo nhánh mới với tên `<branch>`.                                |
| `git checkout <branch>`    | Chuyển sang nhánh có tên `<branch>`.                             |
| `git checkout -b <branch>` | Tạo và chuyển sang nhánh `<branch>`.                             |
| `git branch -D <branch>`   | Xoá nhánh `<branch>`.                                            |
| `git merge <branch>`       | Merge nhánh `<branch>` vào nhánh hiện tại.                       |

## Remote Repo

| Lệnh                          | Mô tả                                                                                               |
|-------------------------------|-----------------------------------------------------------------------------------------------------|
| `git remote add <name> <url>` | Tạo kết nối với remote repo tại `<url>` (sau đó có thể dùng `<name>` như là shortcut).              |
| `git fetch <branch>`          | Fetch nhánh `<branch>` từ remote repo. Không cung cấp tên nhánh có nghĩa là fetch tất cả các nhánh. |
| `git pull`                    | Fetch nhánh hiện tại và đồng thời merge nhánh remote vào local.                                     |
| `git push <remote> <branch>`  | Push nhánh lên remote repo.                                                                         |

## Cấu hình Git

## Git Log

## Git Diff

## Git Reset

## Git Rebase

## Git Pull

## Git Push
