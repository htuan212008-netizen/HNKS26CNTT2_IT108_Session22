# Bài 6: Ứng dụng AI trong khắc phục lỗi Git Permission Denied
## 1. Công thức Prompt 3 Thành phần nhờ AI giải thích lỗi
- Bối cảnh/Vai trò: Chuyên gia hướng dẫn lập trình cho sinh viên năm nhất.
- Nhiệm vụ: Giải thích bình dân lỗi error: open(".git/FETCH_HEAD"): Permission denied và hướng dẫn cách fix trên Windows.
- Định dạng: Ngắn gọn, dễ hiểu, bước thực hiện rõ ràng.
## 2. Xử lý lỗi & Chụp ảnh minh họa
- Nguyên nhân: Thư mục ẩn .git bị khóa quyền ghi.
- Cách fix: Đóng Terminal/VS Code cũ => Mở lại bằng quyền Run as Administrator.
- Mẹo chụp màn hình: Khoanh vùng đỏ dòng lỗi và che thông tin cá nhân.
## 3. Mẫu Bug Report nhờ Giảng viên
- Context: Windows 11, VS Code, Git git push origin main.
- Expected: Đẩy code lên GitHub thành công.
- Actual: Vẫn báo lỗi Permission denied dù đã chạy quyền Admin.
- Đã thử nghiệm: Đã dùng quyền Administrator nhưng chưa được, nhờ thầy/cô hỗ trợ phân quyền thư mục .git.
