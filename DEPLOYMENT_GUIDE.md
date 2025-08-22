# 🚀 Hướng dẫn Deploy Portfolio Website

## 📋 Thông tin liên hệ đã cập nhật:
- **Email**: leanhtu16032003@gmail.com
- **GitHub**: https://github.com/leanhtu05

## 🌐 Các tùy chọn Deploy miễn phí:

### 1. **GitHub Pages (Khuyến nghị)**
```bash
# Bước 1: Tạo repository mới trên GitHub
# Tên repository: portfolio hoặc leanhtu05.github.io

# Bước 2: Upload code lên GitHub
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/leanhtu05/portfolio.git
git push -u origin main

# Bước 3: Kích hoạt GitHub Pages
# Vào Settings > Pages > Source: Deploy from a branch > Branch: main
```
**URL sẽ là**: `https://leanhtu05.github.io/portfolio/`

### 2. **Netlify (Dễ sử dụng nhất)**
1. Truy cập: https://netlify.com
2. Đăng ký tài khoản miễn phí
3. Kéo thả thư mục portfolio vào Netlify
4. Netlify sẽ tự động tạo URL ngẫu nhiên
5. Có thể đổi tên thành: `leanhttu-portfolio.netlify.app`

### 3. **Vercel (Hiệu suất cao)**
1. Truy cập: https://vercel.com
2. Đăng ký và kết nối GitHub
3. Import repository portfolio
4. Deploy tự động
**URL sẽ là**: `https://portfolio-leanhtu05.vercel.app`

### 4. **Firebase Hosting**
```bash
# Cài đặt Firebase CLI
npm install -g firebase-tools

# Đăng nhập Firebase
firebase login

# Khởi tạo project
firebase init hosting

# Deploy
firebase deploy
```

## 📱 Tạo QR Code cho Portfolio:

### Cách 1: Sử dụng công cụ online
1. Truy cập: https://qr-code-generator.com
2. Chọn "URL"
3. Nhập link website portfolio của bạn
4. Tùy chỉnh màu sắc (khuyến nghị: màu xanh #007bff)
5. Tải về định dạng PNG hoặc SVG

### Cách 2: Sử dụng Google Charts API
```html
<!-- QR Code tự động tạo -->
<img src="https://chart.googleapis.com/chart?chs=200x200&cht=qr&chl=https://leanhtu05.github.io/portfolio/" alt="Portfolio QR Code">
```

## 📄 Thông tin để điền vào CV:

### **Website Portfolio:**
```
🌐 Portfolio: https://leanhtu05.github.io/portfolio/
📧 Email: leanhtu16032003@gmail.com
💻 GitHub: https://github.com/leanhtu05
```

### **Mô tả ngắn cho CV:**
```
"Portfolio website showcasing modern front-end development skills with 
interactive demos including admin dashboard, e-commerce, and SaaS landing pages. 
Built with HTML5, CSS3, JavaScript, and responsive design principles."
```

## 🎯 Khuyến nghị Deploy:

### **Tùy chọn tốt nhất: GitHub Pages**
**Lý do:**
- ✅ Miễn phí mãi mãi
- ✅ Tích hợp với GitHub profile
- ✅ URL chuyên nghiệp
- ✅ SSL certificate tự động
- ✅ Dễ cập nhật (chỉ cần push code)

### **Các bước thực hiện:**

1. **Tạo repository GitHub:**
   - Tên: `portfolio`
   - Public repository
   - Thêm README.md

2. **Upload code:**
   ```bash
   git clone https://github.com/leanhtu05/portfolio.git
   cd portfolio
   # Copy tất cả file portfolio vào đây
   git add .
   git commit -m "Add portfolio website"
   git push origin main
   ```

3. **Kích hoạt GitHub Pages:**
   - Vào repository Settings
   - Scroll xuống phần "Pages"
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/ (root)"
   - Save

4. **Chờ 5-10 phút** để GitHub deploy

5. **Truy cập website:** `https://leanhtu05.github.io/portfolio/`

## 🔗 Custom Domain (Tùy chọn):

Nếu muốn domain riêng:
1. Mua domain (.com, .dev, .tech) từ Namecheap, GoDaddy
2. Cấu hình DNS trỏ về GitHub Pages
3. Thêm file `CNAME` với tên domain

## 📊 Theo dõi Analytics:

Thêm Google Analytics để theo dõi lượt truy cập:
```html
<!-- Thêm vào <head> của index.html -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## ✅ Checklist trước khi deploy:

- [ ] Cập nhật thông tin liên hệ
- [ ] Kiểm tra tất cả links hoạt động
- [ ] Test responsive trên mobile
- [ ] Tối ưu hóa hình ảnh
- [ ] Kiểm tra loading speed
- [ ] Test trên nhiều trình duyệt
- [ ] Chuẩn bị QR code
- [ ] Cập nhật CV với link website

---

**🎉 Chúc bạn thành công với portfolio website!**

Sau khi deploy xong, bạn sẽ có:
- ✅ Website portfolio chuyên nghiệp
- ✅ QR code để in trên CV
- ✅ Link để chia sẻ với nhà tuyển dụng
- ✅ Showcase kỹ năng front-end development
