<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Happy Birthday Manisha 🎂</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 16px;
      background: radial-gradient(circle at top, #ffe0f0, #fbc2eb, #a18cd1);
      color: #fff;
    }

    .wrapper {
      text-align: center;
      max-width: 800px;
      width: 100%;
    }

    h1 {
      font-size: 2.4rem;
      margin-bottom: 10px;
      text-shadow: 0 3px 8px rgba(0, 0, 0, 0.35);
    }

    .name {
      color: #ffe082;
    }

    .subtitle {
      font-size: 1rem;
      margin-bottom: 20px;
      opacity: 0.9;
    }

    /* CAKE ANIMATION */
    .cake-area {
      display: flex;
      justify-content: center;
      margin-bottom: 30px;
    }

    .cake {
      position: relative;
      width: 160px;
      height: 160px;
      animation: floatCake 3s ease-in-out infinite;
    }

    @keyframes floatCake {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-8px); }
    }

    .cake-base {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 140px;
      height: 55px;
      background: #ff9eb5;
      border-radius: 18px 18px 10px 10px;
      box-shadow: 0 8px 18px rgba(0, 0, 0, 0.35);
    }

    .cake-layer {
      position: absolute;
      bottom: 40px;
      left: 50%;
      transform: translateX(-50%);
      width: 130px;
      height: 45px;
      background: #ffe4f2;
      border-radius: 18px 18px 14px 14px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.25);
    }

    .icing {
      position: absolute;
      bottom: 70px;
      left: 50%;
      transform: translateX(-50%);
      width: 120px;
      height: 26px;
      background: #fff2fa;
      border-radius: 18px;
      overflow: hidden;
    }

    .icing::before,
    .icing::after {
      content: "";
      position: absolute;
      width: 28px;
      height: 28px;
      background: #ffd1ec;
      border-radius: 50%;
      top: 10px;
    }

    .icing::before {
      left: 15px;
    }
    .icing::after {
      right: 15px;
    }

    .sprinkles span {
      position: absolute;
      width: 6px;
      height: 3px;
      border-radius: 3px;
      background: #ff6f9c;
    }

    .sprinkles span:nth-child(1) { top: 6px; left: 18px; }
    .sprinkles span:nth-child(2) { top: 4px; left: 40px; }
    .sprinkles span:nth-child(3) { top: 8px; left: 62px; }
    .sprinkles span:nth-child(4) { top: 6px; left: 84px; }
    .sprinkles span:nth-child(5) { top: 4px; left: 100px; }

    .candle {
      position: absolute;
      bottom: 92px;
      left: 50%;
      transform: translateX(-50%);
      width: 10px;
      height: 35px;
      background: repeating-linear-gradient(
        to bottom,
        #ff9eb5,
        #ff9eb5 5px,
        #fff 5px,
        #fff 10px
      );
      border-radius: 5px;
    }

    .flame {
      position: absolute;
      top: -14px;
      left: 50%;
      transform: translateX(-50%);
      width: 16px;
      height: 24px;
      background: radial-gradient(circle at 50% 20%, #fff7a0, #ffb347);
      border-radius: 50% 50% 50% 50%;
      box-shadow: 0 0 12px rgba(255, 215, 130, 0.9);
      animation: flicker 0.6s infinite alternate;
    }

    @keyframes flicker {
      0% { transform: translateX(-50%) scale(1); opacity: 0.9; }
      100% { transform: translateX(-48%) scale(1.08); opacity: 1; }
    }

    /* PHOTO GALLERY */
    .gallery-title {
      margin-bottom: 10px;
      font-size: 1.1rem;
      font-weight: 500;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 14px;
      margin-top: 10px;
    }

    .photo {
      position: relative;
      border-radius: 14px;
      overflow: hidden;
      box-shadow: 0 6px 16px rgba(0, 0, 0, 0.3);
      border: 2px solid rgba(255, 255, 255, 0.6);
      background: rgba(255, 255, 255, 0.15);
    }

    .photo img {
      width: 100%;
      height: 170px;
      object-fit: cover;
      display: block;
      transition: transform 0.25s ease;
    }

    .photo:hover img {
      transform: scale(1.05);
    }

    .photo-tag {
      position: absolute;
      bottom: 6px;
      left: 8px;
      right: 8px;
      font-size: 0.75rem;
      padding: 3px 6px;
      border-radius: 999px;
      background: rgba(0, 0, 0, 0.4);
      text-align: center;
    }
  </style>
</head>
<body>

  <div class="wrapper">
    <h1>Happy Birthday <span class="name">Manisha</span> 🎉</h1>
    <div class="subtitle">Wishing you a day as beautiful as your smile.</div>

    <!-- CAKE ANIMATION -->
    <div class="cake-area">
      <div class="cake">
        <div class="cake-base"></div>
        <div class="cake-layer"></div>
        <div class="icing">
          <div class="sprinkles">
            <span></span><span></span><span></span><span></span><span></span>
          </div>
        </div>
        <div class="candle">
          <div class="flame"></div>
        </div>
      </div>
    </div>

    <!-- PHOTO GALLERY -->
    <div class="gallery-title">Some beautiful moments of Manisha 💖</div>
    <div class="gallery">
      <!-- Replace image sources with her real photos -->
      <div class="photo">
        <img src="manisha1.jpg" alt="Manisha Photo 1">
        <div class="photo-tag">Manisha ✨</div>
      </div>
      <div class="photo">
        <img src="manisha2.jpg" alt="Manisha Photo 2">
        <div class="photo-tag">That cute smile 💕</div>
      </div>
      <div class="photo">
        <img src="manisha3.jpg" alt="Manisha Photo 3">
        <div class="photo-tag">Unforgettable moment 📸</div>
      </div>
      <div class="photo">
        <img src="manisha4.jpg" alt="Manisha Photo 4">
        <div class="photo-tag">Always shining 🌟</div>
      </div>
    </div>
  </div>

</body>
</html>
