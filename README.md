# Dự Án Portfolio Cá Nhân - Vũ Minh Hưng

Dự án trang web Portfolio cá nhân của **Vũ Minh Hưng** (Bài 1: Cấu trúc hóa Bản sắc Cá nhân bằng Semantic HTML5). Trang web tập trung vào việc áp dụng đúng chuẩn các thẻ ngữ nghĩa (**Semantic HTML5**), tối ưu hóa cấu trúc nội dung, khả năng tiếp cận (Accessibility - a11y) và thân thiện với SEO.

---

## 👤 Thông Tin Cá Nhân

- **Họ và tên:** Vũ Minh Hưng
- **Địa chỉ:** Đồng Nai, Việt Nam
- **Điện thoại:** [0987712170](tel:0987712170)
- **GitHub:** [https://github.com/MinhHung309](https://github.com/MinhHung309)
- **LinkedIn:** [http://linkedin.com/in/MinhHung309](http://linkedin.com/in/MinhHung309)
- **Định hướng:** Đang học tập và phát triển kỹ năng trong lĩnh vực Công nghệ Thông tin & Lập trình Web.

---

## 📁 Cấu Trúc Thư Mục

```text
ex1-semantic-portfolio/
├── css/
│   └── style.css      # CSS phân tầng, bố cục Grid/Flexbox và responsive cơ bản
├── index.html         # Trang portfolio chính sử dụng chuẩn Semantic HTML5
├── README.md          # Tài liệu giới thiệu dự án và thông tin cá nhân
├── prompt.md          # Ghi lại prompt gốc yêu cầu tạo dự án
└── prompt_log.md      # Lịch sử các bước thực hiện và cập nhật
```

---

## 🎯 Mục Tiêu & Điểm Nổi Bật Kỹ Thuật

1. **Semantic HTML5 Chuẩn Mực:**
   - `<header>`: Chứa tên cá nhân (logo) và khối menu điều hướng `<nav>` với thuộc tính `aria-label`.
   - `<main>`: Bao bọc toàn bộ nội dung chính của trang.
   - `<section>`: Phân chia các khu vực logic rõ ràng (`#hero`, `#about`, `#skills`, `#projects`, `#contact`). Mỗi section đều có thẻ tiêu đề `<h2>` đại diện.
   - `<article>`: Sử dụng cho các đơn vị nội dung độc lập như từng bài tập học tập (`.project-card`), các nhóm kỹ năng (`.skill-category`), và phần giới thiệu (`.about-bio`).
   - `<figure>` & `<figcaption>`: Trình bày hình ảnh minh họa bài thực hành kèm chú thích ngữ nghĩa.
   - `<address>`: Bao bọc thông tin liên hệ chính thức theo chuẩn HTML5.
   - `<footer>`: Chứa thông tin bản quyền và ghi chú dự án.

2. **Thứ Bậc Tiêu Đề Hợp Lý (Heading Hierarchy):**
   - Duy nhất một thẻ `<h1>` tại Hero Section cho tên chủ nhân website (**Vũ Minh Hưng**).
   - Thẻ `<h2>` cho tên các khu vực chính (Về Bản Thân, Kỹ Năng Đang Rèn Luyện, Dự Án Học Tập, Thông Tin Liên Hệ).
   - Thẻ `<h3>` cho các nhóm con hoặc tiêu đề từng bài thực hành, kỹ năng.

3. **SEO & Accessibility (Khả năng tiếp cận):**
   - Thẻ `<meta name="description">` và `<meta name="viewport">` đầy đủ.
   - Sử dụng SVG placeholder avatar trung tính làm hình giữ chỗ cho đại diện cá nhân.
   - Các liên kết văn bản mang ý nghĩa rõ ràng, đúng chuẩn `tel:` và `https://` / `http://`.

4. **CSS Tinh Gọn & Thích Ứng (Responsive):**
   - Thiết kế sạch sẽ, dễ đọc với font hệ thống mượt mà.
   - Bố cục linh hoạt sử dụng CSS Flexbox và CSS Grid (`auto-fit`, `minmax`).
   - Tương thích tốt trên cả thiết bị di động (Mobile) lẫn máy tính để bàn (Desktop).

---

## 🚀 Hướng Dẫn Xem Dự Án

1. Mở trực tiếp file `index.html` bằng trình duyệt bất kỳ (Chrome, Edge, Firefox, Safari).
2. Hoặc sử dụng tiện ích mở rộng **Live Server** trên VS Code để xem với chế độ tự động tải lại khi chỉnh sửa.
