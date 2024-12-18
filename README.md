<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hacker Login Screen</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      font-family: monospace;
      background: black;
      overflow: hidden;
    }
    .split {
      width: 50%;
      height: 100%;
      position: relative;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .white-hat {
      background: linear-gradient(to bottom, #0f0, #060);
      color: white;
    }
    .black-hat {
      background: linear-gradient(to bottom, #300, #900);
      color: black;
    }
    h1 {
      margin: 0;
      font-size: 2rem;
      text-transform: uppercase;
      text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
    }
    .login-form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input {
      padding: 10px;
      border: none;
      font-size: 1rem;
      background: rgba(0, 0, 0, 0.5);
      color: white;
      outline: none;
    }
    .white-hat input {
      color: #0f0;
    }
    .black-hat input {
      color: #f00;
    }
    button {
      padding: 10px 20px;
      font-size: 1rem;
      border: none;
      cursor: pointer;
    }
    .white-hat button {
      background: #0f0;
      color: black;
    }
    .black-hat button {
      background: #f00;
      color: white;
    }
  </style>
</head>
<body>
  <div class="split white-hat">
    <h1>White Hat Login</h1>
    <form class="login-form">
      <input type="text" placeholder="Username">
      <input type="password" placeholder="Password">
      <button type="submit">Login</button>
    </form>
  </div>
  <div class="split black-hat">
    <h1>Black Hat Login</h1>
    <form class="login-form">
      <input type="text" placeholder="Username">
      <input type="password" placeholder="Password">
      <button type="submit">Login</button>
    </form>
  </div>
</body>
</html>
