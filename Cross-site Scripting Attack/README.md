<h2>2. Cross-site Scripting (XSS) Attack</h2>
<h3>Khai thác lỗ hổng:</h3>
<p><strong>Mô tả:</strong> XSS xảy ra khi một ứng dụng web không làm sạch đầu vào của người dùng và hiển thị chúng lên trình duyệt, cho phép kẻ tấn công chèn mã JavaScript độc hại.</p>
<h3>Cách xử lý lỗ hổng:</h3>
<ul>
  <li><strong>Escape Output:</strong></li>
  <p>Sử dụng các hàm escape để đảm bảo rằng dữ liệu đầu ra không được thực thi dưới dạng HTML hay JavaScript.</p>
  <li><strong>Content Security Policy (CSP):</strong></li>
  <p>Áp dụng CSP để hạn chế các nguồn tài nguyên và ngăn chặn việc thực thi mã độc.</p>
  <li><strong>Input Validation:</strong></li>
  <p>Kiểm tra và loại bỏ các mã độc từ đầu vào.</p>
</ul>
