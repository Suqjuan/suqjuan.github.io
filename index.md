---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:  "My Portfolio"
---
<html>
<head>
  <title>Clickable Pictures</title>
  <style>
    body{
        background-color: #CECECE;
    }
    .picture-container {
      position: relative;
      display: inline-block;
      width: 300px;
      height: 300px;
      margin: 10px;
    }
    .picture {
      display: block;
      width: 100%;
      height: 100%;
      background-color: #f1f1f1;
      background-size: cover;
      cursor: pointer;
    }
    .text-overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      font-size: 24px;
      font-weight: bold;
      text-align: center;
      width: 100%;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="picture-container">
      <a href="https://suqjuan.github.io/jekyll/update/2023/05/30/robotics.html">
        <div class="picture" style="background-image: url('https://suqjuan.github.io/docs/assets/img/scaraBefore.png');"></div>
        <div class="text-overlay">Robotics</div>
      </a>
    </div>
    <div class="picture-container">
      <a href="https://suqjuan.github.io/jekyll/update/2023/05/30/robotics.html">
        <div class="picture" style="background-image: url('https://suqjuan.github.io/docs/assets/img/scaraBefore.png');"></div>
        <div class="text-overlay">Embedded Systems</div>
      </a>
    </div>
    <div class="picture-container">
      <a href="https://suqjuan.github.io/jekyll/update/2023/05/30/robotics.html">
        <div class="picture" style="background-image: url('https://suqjuan.github.io/docs/assets/img/scaraBefore.png');"></div>
        <div class="text-overlay">Circuit Design</div>
      </a>
    </div>
    <div class="picture-container">
      <a href="https://suqjuan.github.io/jekyll/update/2023/05/30/robotics.html">
        <div class="picture" style="background-image: url('https://suqjuan.github.io/docs/assets/img/scaraBefore.png');"></div>
        <div class="text-overlay">Artifical Intelligence</div>
      </a>
    </div>
  </div>
</body>
</html>