# Lịch Sử Thực Hiện & Cập Nhật (Prompt Log)

## [2026-10-24] - Khởi tạo dự án Bài 1: Cấu trúc hóa Bản sắc Cá nhân bằng Semantic HTML5

### 1. Nội dung yêu cầu thực hiện
- Khởi tạo dự án Portfolio cá nhân tập trung vào Semantic HTML5.
- Tạo cấu trúc file: `index.html`, `css/style.css`, `README.md`, `prompt.md`, `prompt_log.md`.
- Áp dụng các thẻ ngữ nghĩa HTML5: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<address>`, `<footer>`.
- Các khu vực nội dung: Header (menu điều hướng), Hero (giới thiệu ngắn gọn), About Me (tiểu sử & thông tin cơ bản), Skills (kỹ năng kỹ thuật & kỹ năng mềm), Projects (3 dự án mẫu), Contact (thông tin liên hệ chuẩn ngữ nghĩa), Footer (bản quyền).
- Tối ưu SEO và trợ năng (a11y): Thẻ tiêu đề phân cấp hợp lý (`h1` -> `h2` -> `h3`), `alt` cho ảnh, liên kết có ý nghĩa.
- CSS: Bố cục sạch sẽ, đọc tốt, responsive cho mobile và desktop, không dùng JavaScript, dark mode hoặc animation phức tạp.
- Toàn bộ nội dung bằng tiếng Việt, thông tin mẫu dễ thay thế.

### 2. Các file đã tạo
- [index.html](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/index.html): Cấu trúc ngữ nghĩa HTML5 hoàn chỉnh.
- [css/style.css](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/css/style.css): Bố cục Flexbox/Grid, màu sắc hài hòa, chuẩn responsive.
- [prompt.md](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/prompt.md): Lưu trữ nguyên vẹn câu lệnh prompt gốc từ người dùng.
- [README.md](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/README.md): Hướng dẫn dự án, giải thích cấu trúc Semantic và hướng dẫn tùy biến.
- [prompt_log.md](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/prompt_log.md): Nhật ký triển khai và cập nhật.


## [2026-10-24] - Cập nhật thông tin cá nhân thật (Vũ Minh Hưng)

### 1. Nội dung yêu cầu thực hiện
- Cập nhật toàn bộ thông tin cá nhân của người dùng vào trang Portfolio:
  - Họ và tên: Vũ Minh Hưng
  - Địa chỉ: Đồng Nai, Việt Nam
  - Điện thoại: 0987712170 (hỗ trợ liên kết `tel:0987712170`)
  - GitHub: https://github.com/MinhHung309
  - LinkedIn: http://linkedin.com/in/MinhHung309
- Header & Hero: Cập nhật tên và tiêu đề thể hiện đang học tập, phát triển kỹ năng trong ngành CNTT.
- About Me: Viết lời giới thiệu tự nhiên, chân thực, không tự bịa trường lớp hay thành tích không có thật.
- Contact: Hiển thị đầy đủ địa chỉ, số điện thoại, link GitHub và LinkedIn có thể nhấp được.
- Skills & Projects: Giữ ở mức kỹ năng đang học và dự án học tập thực tế (bài thực hành Semantic HTML5 và bố cục văn bản).
- Ảnh đại diện: Thay ảnh người mẫu cũ bằng hình đại diện trung tính (SVG placeholder avatar) để người dùng thay thế ảnh thật sau này.
- Loại bỏ hoàn toàn thông tin mẫu của "Nguyễn Văn A" và email/thông tin liên hệ giả định.
- Cập nhật tài liệu `README.md` với thông tin cá nhân mới.

### 2. Các file đã chỉnh sửa
- [index.html](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/index.html): Cập nhật thông tin thật của Vũ Minh Hưng, loại bỏ toàn bộ dữ liệu mẫu.
- [css/style.css](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/css/style.css): Bổ sung hỗ trợ kiểu hiển thị cho SVG placeholder avatar.
- [README.md](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/README.md): Cập nhật thông tin cá nhân và định hướng học tập của Vũ Minh Hưng.
- [prompt_log.md](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/prompt_log.md): Ghi chép lịch sử cập nhật.


## [2026-10-24] - Cập nhật ảnh đại diện cá nhân thực tế

### 1. Nội dung yêu cầu thực hiện
- Tìm kiếm ảnh cá nhân người dùng đã thêm vào dự án trong thư mục `assets/`.
- Phát hiện file ảnh duy nhất: `assets/img/Hung_ava.jpg.jpg`.
- Thay thế đoạn SVG placeholder avatar trong Hero Section bằng thẻ `<img>` trỏ chính xác đến `assets/img/Hung_ava.jpg.jpg`.
- Giữ nguyên class `placeholder-avatar` và thêm thuộc tính `alt="Ảnh đại diện của Vũ Minh Hưng"`.
- Bổ sung cấu hình CSS (`width: 260px; height: 260px; object-fit: cover; border-radius: 50%`) để ảnh hiển thị chuẩn tỉ lệ vuông tròn, không bị méo và co giãn tốt trên màn hình điện thoại.

### 2. Các file đã chỉnh sửa
- [index.html](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/index.html): Thay thế thẻ SVG giữ chỗ bằng thẻ `<img>` ảnh đại diện thật của Vũ Minh Hưng.
- [css/style.css](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/css/style.css): Cập nhật kích thước cố định 260x260px và `object-fit: cover` cho avatar.
- [prompt_log.md](file:///c:/Users/Admin/OneDrive/Desktop/Web/ex1-semantic-portfolio/prompt_log.md): Ghi chép cập nhật.
