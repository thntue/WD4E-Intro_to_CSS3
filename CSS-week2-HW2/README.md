# CSS-week2-HW2: Introduction to CSS3 - Homework 2

Trang web hoàn thành bài tập Tuần 2 (Homework 2) cho khóa học **Introduction to CSS3** (Đại học Michigan / Coursera - Web Design for Everybody).

## Các yêu cầu đã hoàn thành

1. **Bản sao mới**: Tạo từ bài tập HW1 với cấu trúc thư mục hoàn chỉnh (`index.html`, `neighborhood.html`, `parks.html`, `css/style.css`, `images/`).
2. **Khả năng tiếp cận (Accessibility - WAVE)**:
   - Thêm liên kết hoạt động `Skip to Main Content` (`<a class="skip-link" href="#main">Skip to Main Content</a>`) vào ngay đầu thẻ `<body>` của cả 3 trang.
   - Thêm thuộc tính `id="main"` vào thẻ `<main>` tương ứng trên cả 3 trang.
   - Định dạng kiểu dáng cho `.skip-link` với độ tương phản cao, hỗ trợ điều hướng bàn phím.
3. **Comment out styling phần tử `li`**:
   - Vô hiệu hóa quy tắc CSS cũ của `li` bằng `/* ... */`.
4. **Định dạng thanh điều hướng `nav`**:
   - Sử dụng `display: inline-block;` và `width: 80%;`.
5. **Bộ chọn hậu duệ cho hình ảnh trong điều hướng / header**:
   - Sử dụng bộ chọn `header img, nav img { width: 10%; }` giúp hình ảnh hiển thị cạnh `nav` trên cùng một hàng.
6. **Định dạng lớp `.grid` (trang Neighborhood Walks)**:
   - Áp dụng `display: grid;` với lưới 2 cột `grid-template-columns: 40% 40%;`.
   - Kết hợp các thuộc tính `justify-content: space-around;`, `align-items: center;`, và `row-gap: 20px;`.
7. **Bộ chọn hậu duệ cho hình ảnh trong `.grid`**:
   - `.grid img { width: 100%; }` giúp ảnh mở rộng vừa khít mỗi cột lưới 40%.
   - Không ảnh hưởng đến hình ảnh của lớp `.flex` ở trang `parks.html`.
8. **Định dạng lớp `.flex` (trang Walks in the Park)**:
   - Áp dụng `display: flex;` với `flex-wrap: wrap;` và `justify-content: space-around;`.
9. **Kiểm tra WAVE & W3C**:
   - Đảm bảo độ tương phản màu sắc đạt chuẩn WCAG AA/AAA.
   - Tất cả hình ảnh có văn bản thay thế `alt`.