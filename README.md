# ThuatToanAES

**ThuatToanAES** là một ứng dụng web đơn giản giúp người dùng **mã hóa** và **giải mã** các tập tin dữ liệu bằng thuật toán **AES (Advanced Encryption Standard)** – một trong những chuẩn mã hóa dữ liệu phổ biến và an toàn nhất hiện nay.

Ứng dụng được xây dựng bằng **Python + Flask**, hỗ trợ giao diện web trực quan và dễ sử dụng, đồng thời có thể chạy trực tiếp trên **Google Colab** thông qua ngrok, rất tiện lợi cho việc demo hoặc học tập.

---

## ✨ Tính năng nổi bật

- ✅ **Mã hóa file (Encrypt):**
  - Người dùng có thể tải lên một tập tin bất kỳ.
  - Nhập một **khóa bảo mật gồm 16 ký tự** để mã hóa file đó bằng thuật toán AES-128.
  - File sau khi mã hóa sẽ được tự động tải về máy người dùng.

- ✅ **Giải mã file (Decrypt):**
  - Cho phép tải lên file đã được mã hóa bằng AES-128.
  - Người dùng nhập đúng **khóa gốc đã dùng để mã hóa**, hệ thống sẽ tiến hành giải mã và phục hồi nội dung ban đầu.

- ✅ **Giao diện người dùng (UI) thân thiện:**
  - Giao diện web HTML được chia thành 2 trang độc lập: **Encrypt** và **Decrypt**.
  - Người dùng dễ dàng thao tác chỉ với vài bước đơn giản: tải file → nhập khóa → nhấn nút.

- ✅ **Triển khai nhanh trên Google Colab:**
  - Với ngrok, bạn có thể khởi chạy server Flask trên Google Colab và truy cập qua một đường link công khai mà không cần cài đặt gì thêm trên máy tính cá nhân.

---

## 🖥️ Giao diện minh họa

### 🔐 Giao diện mã hóa:
![image](https://github.com/user-attachments/assets/c7f24057-40e6-4132-948c-5431e7d66290)
*Giao diện tải file cần mã hóa, nhập khóa, và thực hiện mã hóa.*

### 🔓 Giao diện giải mã:
![image](https://github.com/user-attachments/assets/f661203a-9789-426e-8c0a-4fbe08431b34)

*Giao diện tải file đã mã hóa, nhập khóa gốc và thực hiện giải mã.*

---
