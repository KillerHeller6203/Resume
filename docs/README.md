<!DOCTYPE html>
<html>
<head>
  <title>My Resume</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
    }
    header {
      background: #24292e;
      color: white;
      padding: 10px;
      text-align: center;
    }
    iframe {
      flex: 1;
      border: none;
    }
    .download-btn {
      background: #2da44e;
      color: white;
      padding: 8px 15px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h2>My Resume</h2>
    <a class="download-btn" href="Resume.pdf" download>Download PDF</a>
  </header>
  <iframe src="Resume.pdf"></iframe>
</body>
</html>
