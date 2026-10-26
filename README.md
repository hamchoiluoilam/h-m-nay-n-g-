# 🍽️ Food Roulette - Ăn Gì Hôm Nay? (CF Edition & Vòng Quay 30 Món)

Ứng dụng web giải quyết câu hỏi muôn thuở **"Hôm nay ăn gì?"** dành cho nhóm bạn, cặp đôi và giới trẻ Gen Z. 

Lấy cảm hứng từ cơ chế **Lật Thẻ Báu Vật Đột Kích (CrossFire)** và **Vòng Quay 30 Món Phong Cách CRED/Zomato**, tích hợp kho dữ liệu **300 món ăn** phong phú cùng công cụ tra cứu hình ảnh chính xác chuẩn Google & Wikipedia.

---

## ✨ Tính Năng Nổi Bật

1. 🃏 **Lật 10 Thẻ Báu Vật Đột Kích (CF Style):**
   * Hiển thị cùng lúc 10 lá bài bí ẩn (lưới 5x2).
   * Hiệu ứng tráo bài xoay vòng 3D tốc độ cao.
   * Người chơi tự tay chạm chọn 1 lá bài: Thẻ bài lật 3D phát sáng ánh vàng VIP Gold, 9 lá bài còn lại tự động hé mở.
2. 🎡 **Vòng Quay 30 Món (Dynamic 30-Slice Roulette):**
   * Bánh xe 30 nan hoa đa màu sắc, tự động bốc 30 món ngẫu nhiên từ kho 300 món.
   * Nút *"Đổi 30 Món Khác"* để nạp mẻ món mới ngay lập tức.
3. 📸 **Hiện Hình Ảnh Chuẩn Khi Quay Xong (Image Matching):**
   * Popup chiến thắng hiển thị ảnh món ăn chất lượng cao chuẩn theo tên món.
   * Nút bấm 1-chạm: Tìm thêm hình ảnh trên **Google Images** và tìm quán gần nhất trên **Google Maps**.
4. 🗄️ **Database 300 Món Ăn Ngầm (Clean UI):**
   * 60 món Đồ Nước (Phở, bún, miến, hủ tiếu, bánh canh, lẩu...).
   * 60 món Cơm & Đồ Khô (Cơm tấm, cơm gà, bánh mì, bún đậu...).
   * 70 món Món Ngoại (Hàn, Nhật, Thái, Âu Mỹ, Trung...).
   * 70 món Ăn Vặt & Uống (Trà sữa, ốc, bánh tráng, xiên que...).
   * 40 món Healthy & Chay (Salad, poke bowl, cơm gạo lứt...).
5. 🔊 **Âm thanh Web Audio Synth & Hiệu ứng Pháo Hoa Confetti:**
   * Tiếng kim quay tạch tạch cơ khí, tiếng xáo bài và âm thanh chiến thắng không cần tải file ngoài.

---

## 🚀 Hướng Dẫn Chạy Cục Bộ (Local)

1. Mở file `index.html` trực tiếp trên bất kỳ trình duyệt nào (Chrome, Edge, Safari, Firefox).
2. Hoặc chạy local server bằng Node.js:
   ```bash
   npx serve .
   ```
   Sau đó truy cập: `http://localhost:3000`

---

## 🌐 Triển Khai Lên GitHub Pages (Miễn Phí)

1. Đẩy mã nguồn lên GitHub repository của bạn:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Food Roulette 300 dishes Web App"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
2. Trên GitHub, vào **Settings** > **Pages** > Chọn Branch `main` > Save.
3. Trang web sẽ trực tiếp hoạt động trực tuyến tại:
   `https://<your-username>.github.io/<your-repo-name>/`
