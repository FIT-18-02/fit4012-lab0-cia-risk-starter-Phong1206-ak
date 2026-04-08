# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đinh Dương Phong

**MSSV:** 1871020451

**Lớp/Nhóm:** CNTT 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Dữ liệu người dùng (thông tin cá nhân, tài khoản, mật khẩu)
- Asset 2:Cơ sở dữ liệu hệ thống (database)
- Asset 3 (nếu có):Hệ thống máy chủ (server, API backend)

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Confidentiality (lộ dữ liệu, rò rỉ thông tin)
- Sự cố B ->Integrity (dữ liệu bị sửa đổi, sai lệch)
- Sự cố C ->Availability (hệ thống bị gián đoạn, không truy cập được)

---

## 3. Phân tích sự cố B
- Threat:Hacker tấn công và chỉnh sửa dữ liệu trái phép
- Vulnerability:Hệ thống không kiểm tra đầu vào (input validation yếu), thiếu xác thực/ phân quyền
- Mitigation:
Sử dụng kiểm tra dữ liệu đầu vào (validation, sanitize)
Áp dụng xác thực và phân quyền chặt chẽ (authentication & authorization)
Sử dụng mã hóa và log để phát hiện thay đổi bất thườ
---

## 4. Reflection
Viết 5-7 dòng.
Qua bài tập này, em hiểu rõ hơn về tầm quan trọng của bảo mật thông tin trong hệ thống phần mềm. Việc xác định tài sản cần bảo vệ giúp định hướng các biện pháp an ninh phù hợp. Mô hình CIA là nền tảng quan trọng để phân tích các rủi ro bảo mật. Ngoài ra, việc phân tích threat và vulnerability giúp nhận diện điểm yếu của hệ thống. Từ đó có thể đề xuất các giải pháp giảm thiểu hiệu quả. Đây là kiến thức rất cần thiết trong quá trình phát triển phần mềm an toàn.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:FIT4012{A-C-B-I-C-A}

