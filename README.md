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

## Nhánh

## Remote Repo

## Cấu hình Git

## Git Log

## Git Diff

## Git Reset

## Git Rebase

## Git Pull

## Git Push
