<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>VidNova - Video Gallery</title>
  <style>
    body {
      font-family: sans-serif;
      background: #111;
      color: #fff;
      text-align: center;
      padding: 30px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 20px;
    }
    .video-box {
      background: #222;
      border-radius: 12px;
      margin: 15px auto;
      padding: 20px;
      max-width: 500px;
      box-shadow: 0 0 10px rgba(255,255,255,0.1);
    }
    .download-button {
      margin-top: 15px;
      padding: 10px 20px;
      background: #ff5722;
      color: white;
      border: none;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
    }
    .download-button:hover {
      background: #e64a19;
    }
  </style>
</head>
<body>
  <h1>VidNova</h1>
  <p>Download Your Favorite Videos</p>

  <div class="video-box">
    <h3>Video 1: Football Highlights</h3>
    <a href="https://drive.google.com/uc?export=download&id=YOUR_VIDEO_ID" class="download-button">Download</a>
  </div>

  <div class="video-box">
    <h3>Video 2: Travel Vlog</h3>
    <a href="https://drive.google.com/uc?export=download&id=YOUR_VIDEO_ID" class="download-button">Download</a>
  </div>
</body>
</html>
