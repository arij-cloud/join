
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Me</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }
    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #4facfe, #a18cd1);
    }
    .container {
      background: rgba(255, 255, 255, 0.15);
      padding: 40px;
      border-radius: 20px;
      backdrop-filter: blur(10px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
      text-align: center;
      width: 300px;
    }
    h1 {
      color: white;
      margin-bottom: 20px;
    }
    input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 10px;
      outline: none;
    }
    input::placeholder {
      color: #777;
    }
    button {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 10px;
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: white;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      transform: scale(1.05);
      opacity: 0.9;
    }
    .footer {
      margin-top: 15px;
      font-size: 12px;
      color: #eee;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Join Me 💜</h1>
    <form action="https://formspree.io/f/YOUR_ID" method="POST">
      <input type="text" name="name" placeholder="Your name" required>
      <input type="email" name="email" placeholder="Your email" required>
      <button type="submit">Send ✨</button>
    </form>
    <div class="footer">
      Made with 💙
    </div>
  </div>
</body>
</html>
