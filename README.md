<!DOCTYPE html>
<html>
<head>
  <style>
    body {
        background-image: url('wallhaven-jxvvx5.jpg');
      background-size: 2000px;
      font-family: Arial, sans-serif;
    }
   .container {
      width: 300px;
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
      margin: 50px auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    label {
      display: block;
      margin-bottom: 5px;
    }
    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    input[type="submit"] {
      background-color: #4CAF50;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      width: 100%;
    }
    input[type="submit"]:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Login</h2>
    <form action="/login" method="post">
      <label for="id">ID:</label>
      <input type="text" id="id" name="id" required>

      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>

      <input type="submit" value="Login">
    </form>
    <p>Don't have an account? <a href="T5_signup page.html">Sign up</a></p>
    <p><a href="forgetpassward.html">Forget Password?</a></p>
  </div>
</body>
</html>
