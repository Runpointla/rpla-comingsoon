<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>RunPointLA Coming Soon</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background: black;
      overflow: hidden;
      font-family: Arial, sans-serif;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .spotlight {
      position: absolute;
      top: 0;
      left: 0;
      width: 200%;
      height: 100%;
      background: radial-gradient(circle at 0% 50%, rgba(255, 255, 255, 0.1) 0%, transparent 25%);
      animation: moveSpotlight 5s linear infinite;
      pointer-events: none;
    }

    @keyframes moveSpotlight {
      from {
        background-position: 0% 50%;
      }
      to {
        background-position: 100% 50%;
      }
    }

    .content {
      z-index: 1;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.3em;
    }

    .email {
      font-size: 0.9em;
      margin-bottom: 1em;
      color: #ccc;
    }

    .tagline {
      font-size: 1.2em;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="spotlight"></div>
  <div class="content">
    <h1>RunPointLA Coming Soon!</h1>
    <div class="email">brandon@runpointLA.com</div>
    <div class="tagline">Brands + Entertainers = Awesome Campaigns</div>
  </div>
</body>
</html>
