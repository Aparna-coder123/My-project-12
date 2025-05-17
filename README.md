<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Webpage</title>
  <style>
    body {
      background-color: #f0f0f0;
      font-family: Arial, sans-serif;
      color: #333;
      padding: 20px;
    }

    h1 {
      color: #0066cc;
      text-align: center;
    }

    p {
      text-align: center;
    }

    img {
      display: block;
      margin: 20px auto;
    }

    a {
      display: block;
      text-align: center;
      margin: 10px;
      color: #0066cc;
    }

    button {
      display: block;
      margin: 20px auto;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Welcome to My Webpage</h1>
  <p>This is a paragraph about my website.</p>
  <img src="https://via.placeholder.com/150" alt="Placeholder Image">
  <a href="https://example.com" target="_blank">Visit Example</a>

  <button onclick="showMessage()">Click Me</button>

  <script>
    function showMessage() {
      alert("Hello! This is a JavaScript alert.");
    }
  </script>
</body>
</html>
