<h2>3. Cross-site Request Forgery (CSRF)</h2>
<h3>Khai thác lỗ hổng:</h3>
<p><strong>Mô tả:</strong> CSRF xảy ra khi một trang web độc hại ép trình duyệt của người dùng gửi một yêu cầu đến ứng dụng web mà người dùng đã đăng nhập, dẫn đến hành động trái phép.</p>
<h3>Cách xử lý lỗ hổng:</h3>
<ul>
  <li><strong>Token chống CSRF:</strong></li>
  <p>Sử dụng token ngẫu nhiên được gắn vào mỗi form và kiểm tra token này khi nhận yêu cầu.</p>
  <li><strong>Kiểm tra Referer Header:</strong></li>
  <p>Đảm bảo yêu cầu đến từ trang web đáng tin cậy.</p>
  <li><strong>Sử dụng SameSite Cookies:</strong></li>
  <p>Thiết lập thuộc tính SameSite cho cookie để hạn chế gửi cookie qua các yêu cầu cross-site.</p>
</ul>
