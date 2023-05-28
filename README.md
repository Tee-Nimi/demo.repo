# landing-page-float
This file contains both the html and the css attached to the <head>. Here, I used float to align the html mackup for the browser.
  
 <!DOCTYPE html>
<!-- saved from url=(0101)file:///C:/Users/Nkechi%20Nemine-Ekaye/Desktop/HTML-CSS%20course/css-courses/floats/landing-page.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Landing Page</title>
  <link rel="preconnect" href="https://fonts.googleapis.com/">
<link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;500;600;700&amp;family=Roboto:wght@400;500;700&amp;family=UnifrakturMaguntia&amp;display=swap" rel="stylesheet">

  <style>
    * {
      margin-top: 70px;
      padding: 0;
      font-family: Oswald, Roboto, sans-serif;
    }

    .windows-page {
      width: 600px;
      height: 650px;
      margin: 0 auto;
    }

    ul {
      list-style-type: none;
      margin-top: 80px;
      margin-bottom: 50px;
      font-size: medium;
      font-weight: bold;
    }

    li {
      display: inline;
      margin-right: 3px;
    }

    div.logo {
      float: left;
      margin-right: 150px;
      margin-left: 20px;
      padding: 3px 30px;
      border: 3px solid black;
      letter-spacing: 2px;
    }

    .not-logo {
      margin-right: 20px;
      float: right;
      margin-bottom: 65px;
      letter-spacing: 1.5px;
    }

    .content {
      clear: both;
      text-align: center;
    }

    .lorem {
      clear: both;
      text-align: center;
    }

    .landing, .page {
      font-size: 52px;
      font-weight: bold;
      letter-spacing: 1.75px;
      margin-top: 0;
    }
    
    .simple {
      clear: both;
      font-size: 22px;
      font-weight: 500;
      margin-bottom: 0;
      letter-spacing: 2px;
    }

    .lorem {
      margin-top: 65px;
      font-size: 18px;
      font-weight: normal;
    }
    .tempor {
      margin-top: -5px;
      margin-bottom: 35px;
    }

    div.learning {
      width: 140px;
      height: 30px;
      padding: 3px;
      font-size: 18px;
      font-weight: 500;
      text-align: center;
      margin: 5px auto;
      border: 1px solid black;
      box-shadow: 1.5px 1.5px rgba(138, 138, 138, 0.834);
    }

    body {
      background-color: rgba(199, 194, 194, 0.216);
    }

  </style>
</head>
<body>
  
  <div class="windows-page">
    <div class="list">
      <ul class="unordered-list">
        <div class="logo">
          <li>LOGO</li>
        </div>
        <div class="not-logo">
          <li>HOME</li>
          <li>ABOUT</li>
          <li>SERVICES</li>
          <li>CONTACT</li>
        </div>
      </ul>
    </div>

    <div class="content">
      <div class="simple">SIMPLE/BEAUTIFUL</div>
      <div class="landing">LANDING</div>
      <div class="page">PAGE</div>
    </div>

    <div class="lorem">
      <p>LOREM IPSUM DOLOR SIT AMET, CONSECTETUR ADIPISICING ELIT, SED DO EIUSMOD</p>
      <p class="tempor">TEMPOR INCIDIDUNT UT LABORE ET DOLORE MAGNA ALIQUA.</p>
    </div>

    <div class="learning">START LEARNING</div>

  </div>

</body>
</html> 
