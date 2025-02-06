<!DOCTYPE html>
<html>
<head>
  <title>Dark Theme Button</title>
  <style>
    body {
      background-color: white;
      color: black;
      transition: background-color 0.5s;
    }

    .dark-theme {
      background-color: black;
      color: white;
    }

    .dark-theme:hover {
      background-color: #333;
    }

    .dark-theme:focus {
      outline: none;
    }
  </style>
</head>
<body>
  <h1>Dark Theme Button</h1>

  <button id="themeButton">Switch to Dark Theme</button>

  <script src="script.js"></script>
</body>
</html>