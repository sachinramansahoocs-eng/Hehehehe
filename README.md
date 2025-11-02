<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday 💖 Sthitilragna</title>
  <style>
    /* ========== BASIC STYLE ========== */
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffb6c1, #ffe6f0);
      text-align: center;
      padding: 0;
      margin: 0;
      color: #333;
      overflow-x: hidden;
    }

    header {
      background-color: rgba(255, 255, 255, 0.5);
      padding: 25px 10px;
      border-radius: 0 0 25px 25px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    h1 {
      color: #d63384;
      font-size: 2.4em;
      margin: 0;
      text-shadow: 1px 1px 2px #fff;
    }

    /* ========== IMAGES ========== */
    img {
      width: 90%;
      max-width: 350px;
      border-radius: 15px;
      margin: 15px auto;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      display: block;
    }

    /* ========== MESSAGE BOX ========== */
    .message {
      background: #fff;
      border-radius: 20px;
      padding: 20px;
      margin: 20px auto;
      max-width: 400px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      line-height: 1.6;
      font-size: 1.1em;
      animation: fadeIn 1.2s ease forwards;
    }

    /* ========== BUTTON ========== */
    button {
      background-color: #ff5fa2;
      color: white;
      border: none;
      border-radius: 25px;
      padding: 10px 25px;
      font-size: 1em;
      margin-top: 15px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background-color: #d63384;
    }

    /* ========== FOOTER ========== */
    .footer {
      margin-top: 30px;
      font-style: italic;
      color: #555;
      padding-bottom: 30px;
    }

    /* ========== ANIMATIONS ========== */
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(30px);}
      to {opacity: 1; transform: translateY(0);}
    }

    header, img, .footer {
      animation: fadeIn 1.5s ease forwards;
    }

    /* ========== CONFETTI (OPTIONAL) ========== */
    .confetti {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      overflow: hidden;
      z-index: 999;
    }

    .confetti span {
      position: absolute;
      width: 10px;
      height: 10px;
      background: #ff5fa2;
      opacity: 0.8;
      animation: fall 4s infinite;
    }

    @keyframes fall {
      0% {transform: translateY(-10px) rotate(0deg);}
      100% {transform: translateY(110vh) rotate(720deg);}
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <h1>💖 Happy Birthday, Sthitilragna 💖</h1>
  </header>

  <!-- MAIN IMAGE -->
  <img src="IMG-20251102-WA0009.jpg" alt="Main Photo">

  <!-- MESSAGE BOX -->
  <div class="message">
    <p><b>To mo dhana 💋, Happy Birthday💋!</b></p>
    <p>Thank you for being my partner, my best friend, and my greatest adventure.  
       I cherish every moment we've shared and I'm so excited for all the ones to come.  
       God bless you always 💖</p>
  </div>

  <!-- FUNNY IMAGES -->
  <img src="IMG-20251102-WA0010.jpg" alt="Funny Photo 1">
  <img src="IMG-20251102-WA0011.jpg" alt="Funny Photo 2">

  <!-- FOOTER -->
  <div class="footer">
    <p>With love, always 💞<br>— Yours, Sachin 💫</p>
  </div>

  <!-- CONFETTI EFFECT -->
  <div class="confetti"></div>

  <script>
    // Generate falling confetti hearts
    const confettiContainer = document.querySelector('.confetti');
    for (let i = 0; i < 25; i++) {
      const confetti = document.createElement('span');
      confetti.style.left = Math.random() * 100 + 'vw';
      confetti.style.background = ['#ff5fa2', '#ff9ec4', '#ffd6e0'][Math.floor(Math.random()*3)];
      confetti.style.animationDelay = Math.random() * 3 + 's';
      confettiContainer.appendChild(confetti);
    }
  </script>

</body>
</html>
