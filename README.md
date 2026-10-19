# Trang Web Giới Thiệu Sách (Book Landing Page)

Dự án trang web tĩnh giới thiệu về sách sử dụng **HTML5, CSS3, Bootstrap 4.6 và jQuery**, đáp ứng đầy đủ tiêu chuẩn Responsive trên mọi thiết bị di động, tablet và desktop.

---

## 1. Cấu trúc 7 phần theo yêu cầu
Trang web được thiết kế theo đúng yêu cầu bài tập và mẫu thiết kế tham khảo từ [bootstrap-demo](https://github.com/hoanv7169/bootstrap-demo):

1. **Header & Book Overview**:
   - Thanh điều hướng (Navbar) với logo thương hiệu `Books`, menu điều hướng nhanh và nút Toggle Menu trên di động.
   - Banner mở đầu (Hero Section) với tiêu đề sách *EXCITING ADVENTURE*, thông tin tác giả, lời tựa hấp dẫn, nút mua nhanh (*Buy now for $5.99*) và hình ảnh bìa sách nổi bật.
2. **Author (Tác giả)**:
   - Giới thiệu chân dung tác giả `Mr. Devid Smith`, tiểu sử sự nghiệp và thông điệp gửi gắm tới độc giả qua khung thông tin xếp lớp (overlapping panel).
3. **Features & Numbers (Đặc điểm nổi bật & Số liệu)**:
   - Các điểm đặc sắc của cuốn sách kèm 4 khối số liệu thống kê tự động nhảy số khi cuộn chuột (*2345 Happy Clients, 6784 Books Sold, 1056 Reviews, 9152 Total Readers*).
4. **Prices (Bảng giá các ấn bản)**:
   - 3 gói ấn bản linh hoạt: **PDF Edition** ($77.99), **E-Book** ($99.99), và **Print Copy bìa cứng** ($58.99).
5. **Download (Tải ứng dụng đa nền tảng)**:
   - Khối tải ứng dụng đọc sách trên nền tảng **Desktop** (Website/PC) và **Mobile** (App Store/Google Play).
6. **Reader’s Say (Cảm nhận của độc giả)**:
   - Đánh giá từ các độc giả tiêu biểu với ảnh đại diện, chức danh và khối chuyển động Carousel phản hồi tự động.
7. **Footer (Chân trang)**:
   - Thông tin giới thiệu *About us*, form đăng ký nhận bản tin *Newsletter* và các liên kết mạng xã hội (*Facebook, Instagram, Twitter, YouTube*).

---

## 2. Công nghệ sử dụng
- **HTML5 & Semantic Elements**
- **Bootstrap 4.6 Grid System & Components** (Navbar, Cards, Carousel, Forms, Flex utilities)
- **Font Awesome 5** (Icon hệ thống)
- **Custom CSS & Mobile Media Queries** (`style.css` và `mobile.css` tối ưu responsive)
- **jQuery & Custom Animation** (`main.js` xử lý hiệu ứng đếm số tự động và Navbar Sticky khi cuộn chuột)

---

## 3. Cấu trúc thư mục
```
book-landing-page/
├── assets/                  # Toàn bộ hình ảnh tác giả, bìa sách, avatar độc giả
├── css/
│   ├── style.css            # Định dạng chính của trang web
│   └── mobile.css           # Quy tắc Responsive Media Query cho điện thoại và tablet
├── js/
│   └── main.js              # Xử lý hiệu ứng đếm số (counter) và sticky navbar
├── src/
│   └── index.html           # Bản sao index trong thư mục src
├── index.html               # Trang web chính tại thư mục gốc
└── README.md                # Tài liệu hướng dẫn dự án
```

---

## 4. Hướng dẫn chạy thử
Mở trực tiếp file [index.html](file:///c:/Users/admin/Downloads/responsive-grid-master/book-landing-page/index.html) bằng bất kỳ trình duyệt web nào (Chrome, Edge, Firefox) hoặc dùng Live Server trong VS Code.
