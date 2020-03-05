# Development Team's Good Practices

## Git

### Commmit Writing

#### References
- [https://github.com/trein/dev-best-practices/wiki/Git-Commit-Best-Practices](https://github.com/trein/dev-best-practices/wiki/Git-Commit-Best-Practices)

#### Basic Rules
1. **Commit Related Changes:** Mỗi commit tương đương với 1 sự thay đổi, ví dụ nếu fix 2 bugs thì phải tách thành 2 commit.
2. **Commit Often:** Commit thường xuyên, giữ cho commit đủ nhỏ để đảm bảo sự linh hoạt khi có điều chỉnh.
3. **Don't Commit Half-Done Work:** Tuyệt đối không commit nếu đang làm dở, học cách sử dụng `git stash`.
4. **Test Your Code Before You Commit:** Trước khi commit phải test lại cẩn thận, tránh những lỗi lặt vặt do bất cẩn.
5. **Write Good Commit Messages:** Commit message gồm 2 phần: Short Summary và Body. Short Summary chỉ nên nhỏ hơn 50 ký tự để miêu tả nội dung chính. Tham khảo thêm Formatting Rules bên dưới.
6. **Use Branches:** Sử dụng Branches để xử lý tách rời các vấn đề, ví dụ mỗi branche là 1 feature, bug fix, ..
7. **Agree on A Workflow:** Lựa chọn và tuân thủ một workflow nào đó, tránh sử dụng Git bừa bãi không theo tiêu chuẩn.

#### Formatting Rules
1. **Capitalized, short (50 chars or less) summary:** Viết hoa chữ cái đầu, tóm tắt ý chính trong vòng 50 ký tự.
2. **More detailed explanatory text, if necessary:** Phần chú giải cố gắng trong khoảng 72 ký tự. Phần chú giải không bắt buộc phải có.
3. **Always leave the second line blank:** Luôn luôn để trống dòng thứ 2 (để phân tách giữa `tóm tắt` và `chú giải`)
4.** Write your commit message in the imperative:** Viết câu ở dạng mệnh lệnh, ví dụ: Fix gì đó, Setup gì đó, Add gì đó, ...
5. **Further paragraphs come after blank lines:** Phần chú giải có thể Bullet points để diễn đạt các ý (sử dụng `-` hoặc `*`), lưu ý căn lề đầu dòng 2-4 spaces.
