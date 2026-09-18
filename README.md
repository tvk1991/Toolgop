# 📱 Ứng Dụng Tính Toán Trả Góp & Rút Tiền Tín Dụng

Ứng dụng web di động được thiết kế tối ưu riêng cho trình duyệt **Safari trên các dòng iPhone (từ iPhone 10 đến 18 Pro Max)**. Giao diện phong cách kính mờ (Glassmorphism) hiện đại, gọn gàng, giúp người dùng dễ dàng tính toán chi phí trả góp, tiền lãi, phí rút tiền và phí tất toán trước hạn một cách nhanh chóng và chính xác.

---

## ✨ Tính Năng Nổi Bật

- **Tối ưu tuyệt đối cho Safari iPhone:** Giao diện mượt mà, không bị tràn màn hình, không bị lỗi tự động zoom khi chạm vào ô nhập liệu (cỡ chữ chuẩn 15px - 16px).
- **Quản lý đa khách hàng (Tabs):** Cho phép tạo, lưu và chuyển đổi giữa nhiều khách hàng/danh mục khác nhau. Dữ liệu được lưu trữ tự động trên trình duyệt thiết bị (`LocalStorage`).
- **Tùy chỉnh thông số linh hoạt:** 
  - Tự động định dạng số tiền rút có dấu chấm ngăn cách hàng nghìn giúp dễ nhìn (ví dụ: `38.000.000 VNĐ`).
  - Hỗ trợ nhập số thập phân linh hoạt cho Lãi suất và Phí rút (nhập được cả dấu chấm `.` và dấu phẩy `,`, ví dụ: `0,5%` hoặc `0.5%`).
- **Hỗ trợ 5 kỳ hạn phổ biến:** Lựa chọn nhanh các kỳ hạn **3 tháng, 6 tháng, 12 tháng, 24 tháng và 36 tháng**.
- **Công thức tính toán tự động chuẩn xác:**
  - Tiền gốc/tháng & Tiền lãi/tháng.
  - Tổng tiền hàng tháng (Gốc + Lãi).
  - Tổng cả kỳ & Chênh lãi.
  - Phí tất toán trước hạn (Tự động tính 3% dư nợ gốc còn lại khi $\ge 6$ tháng và 2% khi $< 6$ tháng).

---

## 🚀 Hướng Dẫn Đưa Lên GitHub Pages

Để sử dụng ứng dụng mọi lúc mọi nơi trực tiếp trên Safari iPhone dưới dạng một web app, bạn có thể triển khai lên **GitHub Pages** theo các bước sau:

1. **Tạo Repository mới trên GitHub:**
   - Truy cập [GitHub](https://github.com) và đăng nhập vào tài khoản của bạn.
   - Nhấn nút **New** (hoặc dấu `+` góc trên bên phải) để tạo một Repository mới.
   - Đặt tên repository (ví dụ: `credit-calculator`).
   - Chọn chế độ **Public** (Công khai).
   - Nhấn **Create repository**.

2. **Tải file lên:**
   - Tại trang repository vừa tạo, nhấn vào dòng chữ **"creating a new file"**.
   - Đặt tên file chính xác là **`index.html`**.
   - Dán toàn bộ mã nguồn ứng dụng vào khung soạn thảo.
   - Kéo xuống dưới, nhấn nút **Commit changes...** để lưu lại.

3. **Kích hoạt GitHub Pages:**
   - Chuyển sang tab **Settings** ở thanh menu phía trên của repository.
   - Ở cột menu bên trái, tìm và chọn mục **Pages**.
   - Tại mục **Build and deployment** -> **Branch**:
     - Chọn nhánh là `main` (hoặc `master`).
     - Chọn thư mục là `/ (root)`.
   - Nhấn **Save**.

4. **Hoàn tất:**
   - Chờ khoảng 1-2 phút, GitHub sẽ cung cấp cho bạn một đường link website (dạng `https://tentaikhoan.github.io/ten-repo/`).
   - Hãy mở đường link đó trên **Safari của iPhone**, bạn có thể bấm nút chia sẻ trong Safari và chọn **"Thêm vào Màn hình chính" (Add to Home Screen)** để biến nó thành một ứng dụng độc lập như app native!

---

## 🛠️ Công Nghệ Sử Dụng
- HTML5 / CSS3 / JavaScript (Vanilla JS)
- Tailwind CSS (via CDN)
- FontAwesome Icons
- Apple SF Pro Display Font System
