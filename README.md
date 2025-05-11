<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="صفحه رسمی صدرا کاستوم - مسابقه Call of Duty Mobile با جوایز CP و نقدی!" />
  <title>صدرا کاستوم | مسابقه کالاف دیوتی</title>

  <!-- استایل عمومی -->
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #000;
      color: #fff;
      line-height: 1.6;
      scroll-behavior: smooth;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    img {
      max-width: 100%;
      height: auto;
      border: none;
    }

    header {
      background: linear-gradient(90deg, #e50914, #ff4c4c);
      padding: 20px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
      letter-spacing: 2px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      position: relative;
      overflow: hidden;
    }

    header::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: -100%;
      width: 200%;
      height: 4px;
      background: linear-gradient(90deg, transparent, #e50914, transparent);
      animation: shine 3s infinite;
    }

    @keyframes shine {
      0% { left: -100%; }
      50% { left: 100%; }
      100% { left: 100%; }
    }

    nav {
      background-color: #111;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
      font-size: 1.1em;
      border-bottom: 1px solid #333;
    }

    nav a:hover {
      color: #e50914;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1601653530703-6b0a3e9e6a0d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
      height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      flex-direction: column;
      position: relative;
    }

    .hero::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.6);
    }

    .hero h1 {
      font-size: 3.5em;
      margin-bottom: 15px;
      text-shadow: 3px 3px 8px #000;
      z-index: 2;
    }

    .hero p {
      font-size: 1.3em;
      max-width: 700px;
      z-index: 2;
      background-color: rgba(0,0,0,0.6);
      padding: 20px;
      border-radius: 12px;
    }

    .section {
      padding: 60px 20px;
      text-align: center;
      background-color: #0f0f0f;
    }

    .section h2 {
      font-size: 2.2em;
      margin-bottom: 25px;
      color: #0f0;
      text-shadow: 0 0 5px #0f0;
    }

    .section p {
      font-size: 1.2em;
      max-width: 800px;
      margin: auto;
      line-height: 1.7;
      color: #ccc;
    }

    .contest {
      background-color: #1a1a1a;
      padding: 50px 20px;
      border-top: 2px dashed #e50914;
      border-bottom: 2px dashed #e50914;
    }

    .contest h2 {
      color: #0f0;
      margin-bottom: 20px;
      font-size: 2em;
    }

    .contest p {
      font-size: 1.3em;
      margin-bottom: 30px;
    }

    .prize {
      font-size: 1.4em;
      color: gold;
      margin-top: 20px;
      font-weight: bold;
    }

    .btn {
      background-color: #e50914;
      color: white;
      padding: 15px 35px;
      font-size: 1.3em;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      box-shadow: 0 0 10px #e50914;
      transition: all 0.3s ease;
    }

    .btn:hover {
      background-color: #c20711;
      box-shadow: 0 0 20px #c20711;
    }

    .result {
      margin-top: 25px;
      font-size: 1.3em;
      color: #0f0;
      font-weight: bold;
    }

    footer {
      background-color: #000;
      color: #666;
      text-align: center;
      padding: 20px 0;
      font-size: 0.9em;
      border-top: 1px solid #333;
    }

    .game-logo {
      width: 120px;
      height: 120px;
      margin: 20px auto;
      border-radius: 50%;
      border: 3px solid #e50914;
      box-shadow: 0 0 15px #e50914;
    }
  </style>
</head>
<body>

  <header>صدرا کاستوم</header>

  <nav>
    <a href="#about">درباره ما</a>
    <a href="#contest">مسابقه</a>
    <a href="#contact">تماس بگیرید</a>
  </nav>

  <div class="hero">
    <h1>مسابقه کالاف دیوتی</h1>
    <p>بزرگترین رقابت‌های دیوتی موبایل با جوایز نقدی و CP!</p>
  </div>

  <section class="section" id="about">
    <img src="https://cdn-icons-png.flaticon.com/512/1163/1163661.png" alt="لوگو بازی دیوتی" class="game-logo">
    <h2>درباره مسابقات صدرا کاستوم</h2>
    <p>
      صدرا کاستوم فقط برای طراحان نیست! ما روم های آنلاین دیوتی موبایل برگزار میکنیم تا گیمرها با هم به رقابت بپردازن.<br/>
      در این مسابقات شما قهرمان میدونی، MVP میشی و جایزه میگیری!
    </p>
  </section>

  <section class="contest" id="contest">
    <h2>مسابقه خفن دیوتی موبایل</h2>
    <p>
      🎯 روم بازی دیوتی موبایل<br/>
      🔥 هر هفته چندین دور مسابقه برگزار میشه!<br/>
      💰 جایزه MVP هر دور: ۸۰ عدد CP (هدیه داخل بازی)<br/>
      🏆 روزی چندتا نفر برتر جایزه میگیرن!<br/>
      📱 همه چیز رایگان است! فقط ثبت نام کن و شروع کن.
    </p>
    <button class="btn" onclick="enterContest()">ثبت‌نام در مسابقه</button>
    <div class="result" id="result"></div>
  </section>

  <section class="section" id="contact">
    <h2>تماس با ما</h2>
    <p>
      📩 ایمیل: sadra.custom@example.com<br/>
      📱 اینستاگرام: @sadra.custom<br/>
      📌 تمامی حقوق مادی و معنوی این وبسایت متعلق به صدرا کاستوم است.
    </p>
  </section>

  <footer>
    &copy; 2025 صدرا کاستوم | تمامی حقوق محفوظ است.
  </footer>

  <script>
    function enterContest() {
      const result = document.getElementById("result");
      const messages = [
        "ثبت نام شما با موفقیت انجام شد! منتظر لینک روم باشید 🎮",
        "خب الان توی لیست شرکت کننده‌ها هستی، آماده باش! 😎",
        "خفن‌ترین گیمرها امسال اینجا جمع شدن... ممنون که با ما هستی! 💪"
      ];
      const randomMessage = messages[Math.floor(Math.random() * messages.length)];
      result.textContent = randomMessage;
    }
  </script>

</body>
</html>