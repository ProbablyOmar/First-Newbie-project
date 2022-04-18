<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">

  <title>Frontend Mentor | QR code component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    body{
      background-color: hsl(212, 45%, 89%);
    }
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
    .container{
      background-color: hsl(0, 0%, 100%);

      margin: auto;
      display:flex;
      justify-content: top;
      align-items: center;
      align-self: center;
      flex-direction: column;
      border-radius: 18px;
      width:275px;
      height:400px;
      font-family:Outfit;
    }
    img{
      height: 250px;
      width: 250px;
      margin: 15px;
      border-radius: 8px;
    }
    #im{
      font-style: normal;
      font-weight: 700;
      color:hsl(218, 44%, 22%);
      font-size: 18px;
      margin:4px;
      font-family:Outfit;

    }
    #limp{
      color:hsl(220, 15%, 55%);
      font-weight:400;
      font-size: 12pt;
      margin-top: 7px;
    }
    .center{
      display:flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height:700px;
    }
  </style>
</head>
<body>
  <div class="center">
    <div class="container">
      <div>
        <img src="images/image-qr-code.png" alt="QR CODE" >
      </div>
      <div style="text-align:center;">
        <p id="im">Improve your front-end skills by building projects</p>

        <p id="limp">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
      </div>
    <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="#">Omar Wassim</a>.
    </div>
  </div>
</body>
</html>
