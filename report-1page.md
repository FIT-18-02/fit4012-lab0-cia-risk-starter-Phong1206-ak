# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu người dùng (tài khoản, mật khẩu, thông tin cá nhân)
- Cơ sở dữ liệu hệ thống (database lưu trữ thông tin)

**CIA mapping:**
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

**Phân tích sự cố B:**
- Threat: Hacker tấn công và thay đổi dữ liệu trái phép
- Vulnerability: Thiếu kiểm tra đầu vào, hệ thống phân quyền yếu
- Mitigation: Áp dụng validation dữ liệu, xác thực & phân quyền chặt chẽ, ghi log để phát hiện bất thường

### 4. Kết luận ngắn
Qua bài lab, em hiểu rõ hơn cách xác định các tài sản quan trọng trong hệ thống thông tin. Em cũng nắm được cách phân loại sự cố theo mô hình CIA và vai trò của từng yếu tố. Phần khó nhất là phân biệt giữa threat và vulnerability vì dễ bị nhầm lẫn. Tuy nhiên, khi phân tích theo từng bước, em đã hiểu rõ hơn mối liên hệ giữa chúng. Bài lab giúp em nhận thức được tầm quan trọng của bảo mật trong phát triển phần mềm và cách áp dụng vào thực tế.
