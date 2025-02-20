<h2>1. SQL Injection</h2>
<h3>Khai thác lỗ hổng:</h3>
<p><strong>Mô tả:</strong> SQL Injection xảy ra khi ứng dụng không kiểm tra hoặc làm sạch đầu vào của người dùng trước khi đưa vào câu truy vấn SQL.</p>
<h3>Cách xử lý lỗ hổng:</h3>
<ul>
  <li><strong>Sử dụng Prepared Statements/Parameterized Queries:</strong></li>
  <p>Sử dụng các tham số truy vấn thay vì nối chuỗi để ngăn chặn việc chèn mã độc.</p>
  <li><strong>Làm sạch đầu vào (Input Validation):</strong></li>
  <p>Kiểm tra và loại bỏ các ký tự đặc biệt không cần thiết.</p>
  <li><strong>Sử dụng ORM (Object-Relational Mapping):</strong></li>
  <p>Công cụ ORM thường có cơ chế tự động xử lý vấn đề này.</p>
   <li><strong>Quyền truy cập hạn chế:</strong></li>
  <p>Hạn chế quyền truy cập của tài khoản cơ sở dữ liệu dùng cho ứng dụng để giảm thiểu tác hại nếu bị tấn công.</p>
<ul>
