# web-for-dog-study
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Giới Thiệu Về Tổ 4</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background: linear-gradient(to right, #ff9966, #ff5e62);
      color: white;
    }
    .navbar {
      background: rgba(0, 0, 0, 0.8);
      padding: 15px 0;
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      z-index: 1000;
    }
    .navbar a {
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      margin: 0 10px;
      font-size: 18px;
      transition: background 0.3s;
    }
    .navbar a:hover {
      background: rgba(255, 255, 255, 0.2);
      border-radius: 5px;
    }
    .container {
      max-width: 1000px;
      margin: 80px auto 20px;
      padding: 20px;
      background: rgba(255, 255, 255, 0.9);
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      color: black;
    }
    h1 {
      color: #333;
    }
    .team {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .member {
      width: 200px;
      margin: 15px;
      padding: 15px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      text-align: center;
      transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
    }
    .member:hover {
      transform: scale(1.1);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }
    .member img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      transition: transform 0.3s;
    }
    .member:hover img {
      transform: rotate(10deg);
    }
    .member h3 {
      margin: 10px 0 5px;
      font-size: 18px;
      color: #333;
    }
    .member p {
      font-size: 14px;
      color: #666;
      text-align: left;
    }
  </style>
</head>
<body>
  <div class="navbar">
    <a href="#">Trang chủ</a>
    <a href="#team">Nhóm</a>
    <a href="#contact">Liên hệ</a>
  </div>

  <div class="container" id="team">
    <h1>Giới Thiệu Nhóm</h1>
    <div class="team">
  <!-- Thành viên 1 -->
  <div class="member">
    <img src="https://cdn.glitch.global/f00da8d9-199b-4090-95e6-f12611e595db/xuan%20khoa.jpg?v=1744127541154" />
    <h3>Nguyễn Xuân Khoa</h3>
    <p>Thành viên</p>
    <p><strong>Sở thích:</strong> Ngủ và ngủ.</p>
    <p><strong>Ngày sinh:</strong> 18/09/2007</p>
    <p><strong>Giới tính:</strong> Nam</p>
    <p><strong>Quê quán:</strong> Nam Định.</p>
    <p><strong>Số điện thoại:</strong> 0823676999</p>
    <p><strong>Bản nhạc yêu thích:</strong> 2 phút hơn Funk</p>
    <p><strong>Câu Slogan:</strong> Ngủ là cách healing tốt nhất</p>
    <p><strong>Facebook:</strong> <a href='https://www.facebook.com/share/15jgfeQV7W/' target="_blank">Nguyễn Khoa</a></p>
  </div>
      
  <!-- Thành viên 6 -->
  <div class="member">
    <img src="https://cdn.glitch.global/f00da8d9-199b-4090-95e6-f12611e595db/anh%20hi%E1%BA%BFu.jpg?v=1744127211248" />
    <h3>Đặng Nguyễn Anh Hiếu</h3>
    <p>Nô lệ</p>
    <p><strong>Sở thích:</strong> ăn, ngủ, nghe nhạc, chơi thể thao, chơi game</p>
    <p><strong>Ngày sinh:</strong> 31/05/2007</p>
    <p><strong>Giới tính:</strong> Nam</p>
    <p><strong>Quê quán:</strong> Thanh Hoá</p>
    <p><strong>Số điện thoại:</strong> 0347427742</p>
    <p><strong>Bản nhạc yêu thích:</strong> From the start</p>
    <p><strong>Câu Slogan:</strong> Tung tung tung tung tung Sahour</p>
    <p><strong>Facebook:</strong> <a href="https://www.facebook.com/share/15KoeA9kWR/?mibextid=wwXIfr" target="_blank">Đặng Hiếu</a></p>
  </div>

  <!-- Thành viên 7 -->
  <div class="member">
    <img src="https://cdn.glitch.global/f00da8d9-199b-4090-95e6-f12611e595db/l%C3%A2m.jpg?v=1744127188826" />
    <h3>Nguyễn Lâm Anh</h3>
    <p>Quân Sư</p>
    <p><strong>Sở thích:</strong> xem phim, nghe nhạc, chơi game</p>
    <p><strong>Ngày sinh:</strong> 21/05/2007</p>
    <p><strong>Giới tính:</strong> Nam</p>
    <p><strong>Quê quán:</strong> Nam Định</p>
    <p><strong>Số điện thoại:</strong> 0856210507</p>
    <p><strong>Bản nhạc yêu thích:</strong> Đường tôi chở em về</p>
    <p><strong>Câu Slogan:</strong> Có chí ắt làm nên</p>
    <p><strong>Facebook:</strong> <a href="https://www.facebook.com/lam.146625" target="_blank">Lâm</a></p>
  </div>

  <!-- Thành viên 8 -->
  <div class="member">
    <img src="https://cdn.glitch.global/f00da8d9-199b-4090-95e6-f12611e595db/ChatGPT%20Image%2021_55_29%201%20thg%204%2C%202025.png?v=1744127225851" />
    <h3>Nguyễn Lê Đức Huy</h3>
    <p>Hỗ trợ khách hàng</p>
    <p><strong>Sở thích:</strong> Đá bóng, suy nghĩ, đọc sách</p>
    <p><strong>Ngày sinh:</strong> 29/09/2007</p>
    <p><strong>Giới tính:</strong> Nam</p>
    <p><strong>Quê quán:</strong> Trực Ninh - Nam Định</p>
    <p><strong>Số điện thoại:</strong> 9999999999</p>
    <p><strong>Bản nhạc yêu thích:</strong> Outside</p>
    <p><strong>Câu Slogan:</strong> Không có phiên toà nào hoàn hảo dành cho nhân loại</p>
    <p><strong>Facebook:</strong> <a href="https://www.facebook.com/nguyen.uc.huy.682932" target="_blank">Nguyễn Đức Huy</a></p>
  </div>
</div>


  <section id="contact">
    <h2>Liên Hệ</h2>
    <p>
      Để biết thêm chi tiết hoặc liên hệ với chúng tôi, vui lòng gửi email
      tới: <a href="mailto:leduchuy2992007@gmail.com">leduchuy2992007@gmail.com</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Tổ 4 gương mẫu</p>
  </footer>
</body>
</html>
