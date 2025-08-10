<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ورود VIPZEXNET</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Vazirmatn&display=swap');

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      background: linear-gradient(135deg, #00c853, #00796b);
      font-family: 'Vazirmatn', Tahoma, sans-serif;
      color: #f0f0f0;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
      direction: rtl;
    }

    /* ----- Login styles ----- */

    #login-container {
      background: rgba(0, 0, 0, 0.75);
      border-radius: 16px;
      max-width: 400px;
      width: 100%;
      padding: 30px 25px;
      box-shadow: 0 0 20px rgba(0, 200, 83, 0.7);
      text-align: center;
    }

    h1 {
      margin-bottom: 1rem;
      font-weight: 700;
      color: #00e676;
      user-select: none;
    }

    p {
      margin: 0.6rem 0 1.2rem 0;
      font-size: 1rem;
      line-height: 1.4;
    }

    input[type="email"],
    input[type="text"] {
      width: 100%;
      padding: 12px 15px;
      font-size: 1rem;
      border-radius: 8px;
      border: none;
      outline: none;
      margin-bottom: 15px;
      transition: box-shadow 0.3s ease;
      background-color: #1b1b1b;
      color: #d0ffd8;
    }

    input[type="email"]:focus,
    input[type="text"]:focus {
      box-shadow: 0 0 8px #00e676;
    }

    button {
      background-color: #00c853;
      border: none;
      color: white;
      font-weight: 700;
      font-size: 1rem;
      padding: 12px 0;
      width: 100%;
      border-radius: 10px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      user-select: none;
    }

    button:hover {
      background-color: #00b14f;
    }

    .message {
      min-height: 22px;
      margin-bottom: 15px;
      font-size: 0.9rem;
      color: #ffccbc;
      user-select: none;
    }

    .message.success {
      color: #a5d6a7;
    }

    .hidden {
      display: none;
    }

    /* ----- VIPZEXNET page styles ----- */

    #vipzexnet-container {
      display: none;
      max-width: 800px;
      width: 100%;
      font-family: 'Tahoma', sans-serif;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #ffffff;
      line-height: 1.7;
      border-radius: 10px;
      padding: 1rem 2rem 2rem 2rem;
      box-shadow: 0 0 30px rgba(0, 200, 83, 0.8);
    }

    #vipzexnet-container header {
      background-color: rgba(0,0,0,0.7);
      padding: 1rem;
      text-align: center;
      border-radius: 10px 10px 0 0;
    }

    #vipzexnet-container header h1 {
      margin: 0;
      font-size: 1.8rem;
      user-select: none;
    }

    #vipzexnet-container header p {
      margin: 0.3rem 0 0 0;
    }

    main {
      padding: 2rem 0;
      background-color: rgba(0,0,0,0.6);
      border-radius: 0 0 10px 10px;
    }

    .config-card {
      background-color: rgba(0,0,0,0.5);
      padding: 1rem;
      margin-bottom: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(255,255,255,0.05);
    }

    .config-card h2 {
      margin-top: 0;
      font-size: 1.3rem;
      user-select: none;
    }

    .buy-btn {
      background-color: #00c853;
      color: white;
      padding: 0.5rem 1rem;
      font-size: 0.95rem;
      text-decoration: none;
      border-radius: 6px;
      display: inline-block;
      margin-top: 1rem;
      text-align: center;
      font-weight: bold;
      user-select: none;
    }

    .info {
      background-color: rgba(0,0,0,0.5);
      padding: 1rem;
      border-radius: 10px;
      margin-bottom: 2rem;
      font-size: 1rem;
      user-select: none;
    }

    footer {
      background-color: rgba(0,0,0,0.7);
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      margin-top: 3rem;
      user-select: none;
      border-radius: 10px;
    }

    .social-icons {
      text-align: center;
      margin: 2rem 0;
    }

    .social-icons a {
      margin: 0 10px;
      display: inline-block;
    }

    .social-icons img {
      width: 48px;
      height: 48px;
      border-radius: 12px;
    }

    section.education {
      background-color: rgba(0,0,0,0.6);
      padding: 1.5rem;
      border-radius: 10px;
      margin: 2rem auto;
      text-align: center;
      user-select: none;
    }

    section.education h2 {
      color: #00c853;
      margin-bottom: 1rem;
    }

    section.education p {
      margin-bottom: 1rem;
    }

    section.education a {
      background: #00c853;
      color: #fff;
      padding: 0.7rem 1.5rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      user-select: none;
    }

    @media (max-width: 450px) {
      #login-container {
        padding: 25px 20px;
      }
      input[type="email"], input[type="text"], button {
        font-size: 0.95rem;
        padding: 10px;
      }
      h1 {
        font-size: 1.5rem;
      }
      #vipzexnet-container {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- Login page -->
  <div id="login-container">
    <h1>ورود به VIPZEXNET</h1>

    <div id="email-section">
      <p>ایمیل خود را وارد کنید تا کد تایید برای شما ارسال شود:</p>
      <input type="email" id="email-input" placeholder="example@gmail.com" autocomplete="email" required />
      <button id="send-code-btn">ارسال کد تایید</button>
      <div id="email-msg" class="message"></div>
    </div>

    <div id="code-section" class="hidden">
      <p>کد تایید ارسال شده به ایمیل خود را وارد کنید:</p>
      <input type="text" id="code-input" placeholder="کد تایید ۶ رقمی" maxlength="6" autocomplete="one-time-code" />
      <button id="verify-code-btn">تایید کد</button>
      <div id="code-msg" class="message"></div>
    </div>
  </div>

  <!-- VIPZEXNET main page -->
  <div id="vipzexnet-container" lang="fa" dir="rtl">
    <header>
      <h1>🔋با VIPZEXNET بهترین سرعت VPN را تجربه کنید - بدون قطعی</h1>
      <p>اتصال پرسرعت، پایدار، بدون محدودیت و قابل استفاده در تمامی دستگاه‌ها</p>
    </header>
    <main>
      <div class="info">
        <p>🌍 لوکیشن‌ها: 🇩🇪 🇦🇪 🇹🇷 🇸🇪 🇫🇷 🇬🇧 🇺🇸</p>
        <p>📱 دستگاه‌ها: اندروید، iOS، ویندوز</p>
        <p>🎯 مناسب برای: اینستاگرام، یوتیوب، گیم و موارد دیگر</p>
        <p>🇮🇷 لذت یک V.P.N پرسرعت و با کیفیت را با ما تجربه کنید 🇮🇷</p>
      </div>
      <div class="config-card">
        <h2>⭐️ نامحدود تک‌کاربر</h2>
        <p>قیمت: ۱۰۰ هزار تومان</p>
        <a class="buy-btn" href="https://rubika.ir/Mahdi_shami89" target="_blank">خرید</a>
      </div>
      <div class="config-card">
        <h2>⭐️ نامحدود دوکاربر</h2>
        <p>قیمت: ۵۰ هزار تومان</p>
        <a class="buy-btn" href="https://rubika.ir/Mahdi_shami89" target="_blank">خرید</a>
      </div>
      <div class="config-card">
        <h2>⭐️ نامحدود سه‌کاربر</h2>
        <p>قیمت: ۳۰ هزار تومان</p>
        <a class="buy-btn" href="https://rubika.ir/Mahdi_shami89" target="_blank">خرید</a>
      </div>
    </main>
    <h2 style="text-align:center; color:#00c853;">برای اطلاع از خبرهای VIPZEXNET ما را در شبکه‌های اجتماعی دنبال کنید 🌐</h2>
    <div class="social-icons">
      <div style="display:inline-block; text-align:center; margin: 0 10px;">
        <a href="https://t.me/VIPZEXNET" target="_blank">
          <img src="https://img.icons8.com/fluency/48/telegram-app.png" alt="Telegram">
        </a>
        <div style="color:#fff; font-size:0.85rem; margin-top:0.3rem;">کانال VIPZEXNET در تلگرام</div>
      </div>
      <div style="display:inline-block; text-align:center; margin: 0 10px;">
        <a href="https://rubika.ir/VIPZEXNET" target="_blank">
          <img src="https://upload.wikimedia.org/wikipedia/commons/6/66/Rubika_app_logo.png" alt="Rubika">
        </a>
        <div style="color:#fff; font-size:0.85rem; margin-top:0.3rem;">کانال VIPZEXNET در روبیکا</div>
      </div>
    </div>
    <section class="education">
      <h2>🎓 آموزش وارد کردن کانفیگ</h2>
      <p>برای یادگیری نحوه وارد کردن کانفیگ VPN، روی دکمه زیر کلیک کنید:</p>
      <a href="https://www.aparat.com/playlist/21562118" target="_blank">مشاهده آموزش در آپارات</a>
    </section>
    <footer>
      <p>پشتیبانی در تلگرام: <a href="https://t.me/Mahdi_shami" style="color:#4caf50" target="_blank">@Mahdi_shami</a></
