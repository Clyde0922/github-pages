<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zaira App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .login-box {
      background: white;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .login-box input {
      display: block;
      width: 100%;
      margin: 10px 0;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .login-box button {
      background: #007bff;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
    .message {
      margin-top: 20px;
      font-weight: bold;
      color: #ff0066;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <h2>Login to Zaira App</h2>
    <input type="text" placeholder="Email">
    <input type="password" placeholder="Password">
    <button onclick="showMessage()">Login</button>
    <div class="message" id="message"></div>
  </div>

  <script>
    function showMessage() {
      document.getElementById('message').innerText = "I miss you, iyot na tayo.";
    }
  </script>
</body>
</html>
