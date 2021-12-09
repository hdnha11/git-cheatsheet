# Git Cheat Sheet

## Git cơ bản

## Huỷ bỏ thay đổi

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
