<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP&display=swap" rel="stylesheet">
  </head>

  <header>
    <img src="./assets/img/txt_logo01_pc.png" alt="">
    <div class="header-nav__wrap">
      <img src="./assets/img/txt_phone_changed_pc.png" alt="" class="header-nav__img-tel">
      <a href="" class="header-reservation__btn">→無料相談予約はこちら</a>
      <img class="header-nav__img-menu" src="./assets/img/btn_menu01_pc.png" alt="">
    </div>
  </header>

  <main>
    <section class="fv">
      <img src="./assets/img/img_main01-sp.png" alt="" class="fv-img__img">
      <img src="./assets/img/txt_copy01_pc.png" alt="" class="fv-text__img">
    </section>
    <section class="intro">
        <img class="intro__heading" src="./assets/img/bg_intro01-pc.png" alt="">
      <div class="intro-wrap">
        <div class="intro-photo__box"></div>
        <div class="intro-information">
          <img src="./assets/img/txt_intro01.png" alt="" class="intro_information__img">
          <p class="intro-information__main-text">お二人だけの<br>スペシャルな結婚式を実現します</p>
          <p class="intro-information__sub-text">WEDDING GRACEは、1日1組限定でハワイウェディングをプロデュースします。1日1組限定としているのは、弊社プランナーが挙式日の早朝からその日の終わりまで付き添うからです。それは、お客様一人一人のこだわりに細かく丁寧に対応し、特別な1日にしていただくためです。大切な挙式当日を迎えるまでは、日本で直接お会いして準備を進めていきましょう。</p>
          <a href="" class="intro-btn">→WEDDING GRACEについて</a>
        </div>
        <div class="sec01-photo-sub"></div>
      </div>
    </section>
    <section class="gallery">
      <div class="gallery-title">
        <div class="gallery-title__wrap">
          <h2 class="gallery-title__heading">Gallery</h2>
          <p class="gallery-title__sub-heading">お客様の挙式紹介</p>
        </div>
        <p class="gallery-title__text">これまでにWEDDING GRACEが手掛けたお客様のそれぞれのこだわりの挙式をご紹介します。お客様が挙げられた実際の結婚式を参考にしてください。</p>
      </div>
      <div class="gallery-card">
        <div class="gallery-card__wrap">
          <p class="gallery-card__number">01</p>
          <img src="./assets/img/asano0390-670x471.jpg" alt="" class="gallery-card__img">
          <p class="gallery-card__text">A様カップルWEDDING</p>
          <img src="./assets/img/bg_gallery02.png" alt="" class="gallery-card__img-left">
        </div>
        <div class="gallery-card__wrap">
              <p class="gallery-card__number">02</p>
              <img src="./assets/img/20190615-196-670x471.jpg" alt="" class="gallery-card__img">
              <p class="gallery-card__text">M様カップルWEDDING</p>
        </div>
        <div class="gallery-card__wrap">
          <p class="gallery-card__number">03</p>
          <img src="./assets/img/km0295-670x471.jpg" alt="" class="gallery-card__img">
          <p class="gallery-card__text">T様カップルWEDDING</p>
        </div>
        <div class="gallery-card__wrap">
          <p class="gallery-card__number">04</p>
          <img src="./assets/img/022218-tsuboi0663-670x471.jpg" alt="" class="gallery-card__img">
          <p class="gallery-card__text">T様カップルWEDDING</p>
          <img src="./assets/img/bg_gallery02.png" alt="" class="gallery-card__img-right">
        </div>
      </div>
      <a href="" class="gallery-list__btn">→ギャラリーをもっと見る</a>
    </section>
  </main>
</template>

<style scoped>

</style>
