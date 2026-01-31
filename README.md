# Website Công Ty Juteng Vietnam

Website chính thức của Công ty TNHH Công Nghệ Điện Tử Juteng (Việt Nam)

## Thông Tin Website

- **URL**: https://jutengvietnam.github.io
- **Công ty**: Công ty TNHH Công Nghệ Điện Tử Juteng (Việt Nam)
- **Lĩnh vực**: Sản xuất và kinh doanh laptop, máy in, linh kiện ô tô điện tử

## Tính Năng

- ✅ Thiết kế responsive (tương thích mọi thiết bị)
- ✅ Giao diện hiện đại với màu sắc thương hiệu (xanh - vàng - đen)
- ✅ Giới thiệu công ty chi tiết
- ✅ Danh sách sản phẩm/dịch vụ
- ✅ Form liên hệ
- ✅ Hiệu ứng chuyển động mượt mà
- ✅ SEO-friendly

## Cấu Trúc File

```
jutengvietnam.github.io/
│
├── index.html          # Trang chủ
├── style.css          # CSS styling
├── script.js          # JavaScript
├── logo.png           # Logo công ty (cần thêm)
└── README.md          # File hướng dẫn này
```

## Hướng Dẫn Deploy Lên GitHub Pages

### Bước 1: Upload Files
1. Vào repository: https://github.com/jutengvietnam/jutengvietnam.github.io
2. Nhấn nút "Add file" → "Upload files"
3. Kéo thả các file: index.html, style.css, script.js vào
4. Nhấn "Commit changes"

### Bước 2: Thêm Logo (Tùy chọn)
1. Chuẩn bị file logo.png (nền trong suốt)
2. Upload vào repository
3. Logo sẽ tự động hiển thị trên website

### Bước 3: Kích Hoạt GitHub Pages
1. Vào Settings của repository
2. Chọn "Pages" ở menu bên trái
3. Trong "Source", chọn "main" branch
4. Nhấn "Save"
5. Đợi 1-2 phút, website sẽ online tại: https://jutengvietnam.github.io

## Tùy Chỉnh Nội Dung

### Thay Đổi Thông Tin Liên Hệ
Mở file `index.html` và tìm section với id="contact", chỉnh sửa:
- Địa chỉ
- Số điện thoại
- Email
- Giờ làm việc

### Thêm/Sửa Sản Phẩm
Trong file `index.html`, tìm section với id="products", sửa hoặc thêm:
```html
<div class="product-card">
    <div class="product-image">
        <img src="URL_HÌNH_ẢNH" alt="Tên sản phẩm">
    </div>
    <div class="product-content">
        <h3>Tên Sản Phẩm</h3>
        <p>Mô tả sản phẩm...</p>
    </div>
</div>
```

### Thay Đổi Màu Sắc
Trong file `style.css`, tìm phần `:root` và chỉnh sửa:
```css
:root {
    --primary-blue: #0066cc;      /* Màu xanh chính */
    --accent-yellow: #ffcc00;     /* Màu vàng nhấn */
    --dark-black: #1a1a1a;        /* Màu đen */
}
```

## Bảo Trì & Cập Nhật

### Cập Nhật Nội Dung
1. Vào repository trên GitHub
2. Nhấn vào file cần sửa (index.html, style.css, script.js)
3. Nhấn biểu tượng bút chì (Edit)
4. Chỉnh sửa nội dung
5. Nhấn "Commit changes"
6. Website sẽ tự động cập nhật sau vài giây

### Thêm Hình Ảnh Mới
1. Upload hình ảnh lên repository
2. Sử dụng đường dẫn: `./tên-file.jpg` trong HTML
3. Hoặc sử dụng URL hình ảnh từ nguồn khác

## Hỗ Trợ

Nếu cần hỗ trợ kỹ thuật, vui lòng liên hệ:
- Email: info@jutengvietnam.com
- Điện thoại: 0238.651.8888

## Giấy Phép

© 2025 Juteng Vietnam. All rights reserved.

---

**Lưu ý**: Đây là website tĩnh (static website), không có backend. Form liên hệ hiện tại chỉ hiển thị thông báo. Để có chức năng gửi email thực sự, cần tích hợp dịch vụ như:
- FormSpree
- EmailJS
- Netlify Forms
- Google Forms

**Bảo mật**: Không lưu trữ thông tin nhạy cảm hoặc API keys trực tiếp trong code.
