<template>
    <!-- <div class="w-full bg-red flex gap-2 items-between justify-around">

        <NuxtLink to="/"> Home </NuxtLink>
        <NuxtLink to="/register"> Register </NuxtLink>
        <NuxtLink to="/contact"> Contact </NuxtLink>
        <NuxtLink to="/about"> About </NuxtLink>

    </div> -->



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



</template>