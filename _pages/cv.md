---
layout: none
title: "CV"
permalink: /cv/
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CV | {{ site.title }}</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
    }
    #pdf-container {
      flex: 1;
      border: none;
    }
    .download-bar {
      background-color: #f8f9fa;
      text-align: right;
      padding: 10px 20px;
      border-bottom: 1px solid #ddd;
    }
    .download-bar a {
      text-decoration: none;
      color: #007bff;
      font-weight: bold;
    }
    .download-bar a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="download-bar">
    <a href="/files/CV.pdf" download>⬇ Download CV (PDF)</a>
  </div>
  <embed id="pdf-container" src="/files/CV.pdf" type="application/pdf" width="100%" height="100%">
</body>
</html>
