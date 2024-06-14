<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Software Engineer</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f1f1f1;
      font-family: Arial, sans-serif;
    }

    .personal-card {
      background-color: white;
      box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.1);
      padding: 40px;
      border-radius: 15px;
      text-align: center;
      max-width: 400px;
      width: 100%;
    }

    h2 {
      margin-bottom: 5px;
      font-size: 24px;
    }

    p {
      margin-top: 0;
      color: #666;
      font-size: 16px;
    }

    .social-links {
      margin-top: 20px;
      display: flex;
      justify-content: center;
    }

    .social-links a {
      display: inline-block;
      margin: 0 15px;
      font-size: 24px;
      transition: color 0.3s;
      text-decoration: none;
      color: #333;
    }

    .social-links a:hover {
      color: #007bff;
    }

    .x-link {
      font-weight: bold;
      color: #333;
    }

    .email-link {
      margin-top: 20px;
      color: #333;
    }

    .email-link a {
      color: #333;
      text-decoration: none;
      font-size: 16px;
    }

    .greeting {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .greeting span {
      font-family: monospace;
      color: #333;
    }
  </style>
</head>
<body>
  <div class="personal-card">
    <div class="greeting">
      <span>👋 Hi, I'm</span> Rayan Alghamdi
    </div>
    <div class="social-links">
      <a href="https://www.instagram.com/ry.i?igsh=MXMxYW41ZWs4MTIzYQ%3D%3D&utm_source=qr" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://x.com/iiqdn?s=21" target="_blank" class="x-link">X</a>
      <a href="https://www.tiktok.com/@.rrr?_t=8nBRalZgVs2&_r=1" target="_blank"><i class="fab fa-tiktok"></i></a>
    </div>
    <div class="email-link">
      <a href="mailto:6abotalal@gmail.com">6abotalal@gmail.com</a>
    </div>
  </div>
</body>
</html>
