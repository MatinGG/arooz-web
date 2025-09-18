<template>
    <title>سایت رسمی محسن رضوی</title>
  <link rel="stylesheet" href="../../assets/css/main.css">
      <header id="siteHeader">
    <div class="container nav">
      <a href="./index.html" class="logo">
        <span class="logo-box">
          <img src="./Pics/logo.webp" alt="لوگو">
        </span>
        <span class="headtext">محسن رضوی</span>
      </a>

      <nav aria-label="منو اصلی">
        <ul>
          <li><a href="#home">خانه</a></li>
          <li><a href="#about">درباره من</a></li>
          <li><a href="#contact">تماس</a></li>
        </ul>
      </nav>
      <div class="nav-actions">
        <a class="btn ghost" href="#contact">ورود | ثبت نام</a>
        <button class="hamburger" id="menuBtn" aria-label="منو"><span></span></button>
      </div>
    </div>
    <div id="mobileMenu" class="container" aria-label="منو موبایل">
      <a href="#home">خانه</a>
      <a href="#about">درباره من</a>
      <a href="#contact">تماس</a>
    </div>
  </header>
 <!-- Hero -->
  <main id="home" class="hero">
    <div class="container content">
      <h1 class="title">سایت رسمی محسن رضوی</h1>
      <p class="subtitle">من محسن هستم، خوشحال می‌شوم فعالیت‌های من را مشاهده کنید:</p>
      <div class="hero-cta">
        <a class="btn" href="#about">بیشتر بدانید</a>
      </div>
      <div class="stats">
        <div class="stat"><div class="num">1</div><div class="lbl">مدال طلای المپیاد ادبی</div></div>
        <div class="stat"><div class="num">+10 سال</div><div class="lbl">تحربه تدریس</div></div>
      </div>
    </div>
  </main>

<!-- About -->
<section id="about" class="about">
  <div class="container">
    <h2 class="section-title">درباره محسن رضوی</h2>
    <p class="section-sub">ترکیب خلاقیت، هنر و تجربه</p>
    <div class="panel reveal">
      <div>
        <p>من محسن رضوی هستم؛ علاقه‌مند به ادبیات، طراحی و خلاقیت. تلاش می‌کنم در هر پروژه‌ای ارزش واقعی را به کارفرما منتقل کنم و با دیدگاهی تازه، تجربه‌ای متفاوت رقم بزنم.</p>
        <ul>
          <li>تجربه کار با برندهای معتبر</li>
          <li>ترکیب هنر سنتی و مدرن</li>
          <li>توجه ویژه به جزئیات</li>
        </ul>
      </div>
    </div>
  </div>
</section>


  <!-- Footer -->
  <footer>
    <div class="container foot">
      <div>
        <div class="logo" style="margin-bottom:8px"><i></i><span>محسن رضوی</span></div>
        <p style="margin:0 0 10px; color:#cbd5e1">هنر، خلاقیت و تعهد در یک قاب.</p>
        <div class="sub"><span id="year"></span> ساخته شده با ❤️ در ایران </div>
      </div>
      <div>
        <h5>لینک‌ها</h5>
        <a href="#about">درباره من</a>
        <a href="#contact">تماس</a>
      </div>
      <div>
        <h5>قوانین</h5>
        <a href="#">حریم خصوصی</a>
        <a href="#">شرایط استفاده</a>
      </div>
    </div>
  </footer>
  <a id="toTop" class="btn" href="#home" aria-label="بازگشت به بالا">⬆️ بالا</a>

</template>