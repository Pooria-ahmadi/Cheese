<template>
  <div>
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="ml-4" href="#">
          <img src="zeytunshop-white-logo.png">
        </a>
        <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" @click="toggleMenu">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div id="navbarBasicExample" class="navbar-menu" :class="{ 'is-active': isMobileMenuOpen }">
        <div class="navbar-end has-text-right mr-6">
          <a href="#" class="navbar-item">
            پنیر لیقوان
          </a>
          <a href="#" class="navbar-item">
            پنیر شاهی
          </a>
          <a href="#" class="navbar-item">
            خرید آنلاین
          </a>
        </div>
      </div>
    </nav>
    <img src="Cheese.jpg" alt="Cheese-poster" style="width: 100%;">
    <div class="columns is-centered mx-4 my-4 is-vcentered">
      <div class="column has-text-right is-two-thirds line-height-description">
        <p>
          پنیر یکی از فرآورده‌های لبنی است که به‌صورت روزانه در وعده‌های غذایی مختلف توسط عموم مردم مصرف می‌شود و
          باتوجه‌به اینکه ماده اولیه آن شیر است خواص آن نیز از شیر فرآوری شده تبعیت می‌کند. پنیر لیقوان نیز از این قاعده
          مستثنی نیست و خواص پنیر لیقوان فرآوری شده از شیر تازه گوسفندی بیش از سایر انواع پنیر است.
          یکی از خواص اختصاصی خرید پنیر لیقوان نسبت به سایر پنیرها این است که در فرایند تولید پنیر از باکتری‌های
          تولیدکننده پروبیوتیک استفاده می‌شود؛ بنابراین کسانی که دچار سوءهاضمه هستند و نمی‌توانند لبنیات مصرف کنند
          می‌توانند خرید پنیر لیقوان را در برنامه غذایی خود قرار دهند.
        </p>
      </div>
      <div class="column is-one-quarter">
        <div class="has-text-centered">
          <img src="lighvan-chees-1.jpg" alt="">
        </div>
      </div>
    </div>
    <div class="columns is-centered mx-4">
      <div class="column  is-three-quarters">
        <div class="box">
          <p class="has-text-centered is-size-4 has-text-weight-bold mt-4">خواص پنیر لیقوان</p>
          <p class="has-text-right is-size-6 line-height-description mt-6">
            بسیاری از شرکت‌های صنعتی و کارگاه‌های تولید پنیر از اسم لیقوان سوءاستفاده کرده و پنیر تولیدی خود را به نام
            خرید پنیر لیقوان به فروش می‌رسانند ولی جالب است بدانید که پنیر اصل لیقوان صرفاً پنیری است که به روش سنتی در
            دهکده توریستی لیقوان تولید می‌شود و اگر پنیری توسط دستگاه‌های صنعتی تولید شده باشد یا به‌صورت دستی در شهری
            غیر از لیقوان به‌عمل‌آمده باشد پنیر اصل لیقوان نخواهد بود و طعم اصیل این پنیر را با خود به همراه نخواهد
            داشت.اما چگونه پنیر اصل لیقوان را از پنیر تقلبی تشخیص دهیم؟ در اینجا تفاوت‌های پنیر اصل لیقوان با سایر
            پنیرها را از زبان کریم شاهد یکی از تولیدکنندگان برتر پنیر اصیل سنتی در لیقوان، خواهیم شنید:
          </p>
          <p class="has-text-right has-text-weight-bold my-6 line-height-description">
            پنیر لیقوان به دلیل اینکه از شیر تازه گوسفند یا بز تهیه می‌شود و چربی آن نیز گرفته نمی‌شود دارای رنگی کاملا
            سفید و نرم است. همچنین بر روی پنیر اصل لیقوان سوراخ‌هایی دیده می‌شود که در زمان به عمل آمدن پنیر بوجود می
            آید. یکی از نکات مهم برای خرید پنیر اصیل لیقوان توجه به برند تولید کننده است. بهتر است قبل از خرید از خوشنام
            بودن و اصیل بودن برند تولید کننده پنیر آگاهی یابید. برندهای مشهور صنعتی تولید کننده پنیر به‌هیچ‌وجه پنیر اصل
            و سنتی لیقوانی ارائه نمی‌کنند.
          </p>
        </div>
      </div>
    </div>
    <div class="has-text-centered mx-6">
      <video controls poster="lighvan-chees-1.jpg">
        <source src="Cheese.mp4" type="video/mp4">
      </video>
    </div>
    <div class="columns is-centered mx-4 my-4 is-vcentered">
      <div class="column has-text-right is-two-thirds line-height-description">
        <p>
          پنیر یکی از فرآورده‌های لبنی است که به‌صورت روزانه در وعده‌های غذایی مختلف توسط عموم مردم مصرف می‌شود و
          باتوجه‌به اینکه ماده اولیه آن شیر است خواص آن نیز از شیر فرآوری شده تبعیت می‌کند. پنیر لیقوان نیز از این قاعده
          مستثنی نیست و خواص پنیر لیقوان فرآوری شده از شیر تازه گوسفندی بیش از سایر انواع پنیر است.
          یکی از خواص اختصاصی خرید پنیر لیقوان نسبت به سایر پنیرها این است که در فرایند تولید پنیر از باکتری‌های
          تولیدکننده پروبیوتیک استفاده می‌شود؛ بنابراین کسانی که دچار سوءهاضمه هستند و نمی‌توانند لبنیات مصرف کنند
          می‌توانند خرید پنیر لیقوان را در برنامه غذایی خود قرار دهند.
        </p>
      </div>
      <div class="column is-one-quarter">
        <div class="has-text-centered">
          <img src="lighvan-chees-1.jpg" alt="">
        </div>
      </div>
    </div>
    <div class="columns is-centered mx-4">
      <div class="column  is-three-quarters">
        <div class="box">
          <p class="has-text-centered is-size-4 has-text-weight-bold mt-4">خواص پنیر شاهی</p>
          <p class="has-text-right is-size-6 my-6 line-height-description">
            درصد بالای کلسیم موجود در پنیر لیقوان و توجه به این نکته که کلسیم به نقش قابل توجهی در سلامت بدن و جلوگیری
            از پوکی استخوان و سلامت دندان دارد و همچنین سهم 20 درصدی پروتین در جدول ارزش غذایی پنیر لیقوان که ترکیبی از
            پروتین وی و پروتیین کاذئین است و نقشی که پروتئین وی در ترمیم عضلات و کنترل سوخت و ساز بدن دارد.

            ازسوی دیگر، خاصیت پروبیوتیک پنیر که سیستم دفاعی بدن را در برابر امراض و انواع باکتری ها تقویت میکند و همچنین
            عدم امکان افزودن مواد غیر معمول از قبیل روغن پالم ، نگهدارنده های صنعتی و ترکیبات شیمیایی به پنیر لیقوان سبب
            این شده است که پنیر لیقوان در زمره محصولات ارگانیک و طبیعی با شاخصه های سلامتی بالا قرار گیرد.
            پنیر لیقوان شاهی تبریز خانواده نسبت به دیگر پنیر ها دارای خاصیت های اختصاصی تری بوده به طوری که در تولید این
            نوع از پنیر از باکتری‌های پروبیوتیک استفاده می‌شود.

            که این باکتری‌های پروبیوتیک موجود در این پنیر باعث بهبود عملکرد دستگاه گوارش و هضم بهتر مواد غذایی می‌شود.

            یکی از ویژگی‌های مهم پنیر لیقوان دارا بودن پروتئین بیش از حد آن است که آن را در دسته محصولات گوشتی قرار
            می‌دهند.

            در صورتی که می‌خواهید پروتئین نیاز بدن خود را دریافت کنید به شما پیشنهاد می‌کنیم این نوع پنیر را تهیه کنید.

            جهت تامین مقادیر مورد نیاز فسفر بدن خود می توانید از این نوع پنیر استفاده کنید که نقش بسزایی هم برای جذب
            کلسیم در استخوان ها و حتی دندان ها دارد.
          </p>
        </div>
      </div>
    </div>
    <section>
      <hr>
      <div class="columns has-text-right has-background-light mr-0">
        <div class="column mx-6 mt-4">
          <p class="has-text-success-dark"> دسترسی سریع</p>
          <ul>
            <li class="my-4">
              <a href="#" class="pr-4">تماس با ما</a>
            </li>
            <li class="my-4">
              <a href="#" class="pr-4"> درباره ما </a>
            </li>
          </ul>
        </div>
        <div class="column mx-6 mt-4">
          <p class="has-text-success-dark"> راهنمای سایت </p>
          <ul>
            <li class="my-4">
              <a href="#" class="pr-4"> گارانتی محصول </a>
            </li>
            <li class="my-4">
              <a href="#" class="pr-4"> قوانین و مقررات </a>
            </li>
          </ul>
        </div>
        <div class="column mx-6 mt-4">
          <p class="has-text-success-dark"> تماس با ما </p>
          <ul>
            <li class="my-4">
              <a href="#" class="pr-4"> تلفن : 123456789</a>
            </li>
            <li class="my-4">
              <a href="#" class="pr-4"> واتس آپ</a>
            </li>
          </ul>
        </div>
        <div class="column mx-6 my-4">
          <p class="has-text-success-dark"> ادرس : </p>
        </div>
      </div>
      <div class="columns has-background-grey-dark mb-0 mr-0">
        <div class="column pr-6 has-text-white is-flex pt-0 is-flex-direction-row-reverse">
          <a href="#">
            <img src="instagram.png" alt="">
          </a>
          <a href="#">
            <img src="whatsapp.png" alt="">
          </a>
        </div>
        <div class="column is-flex-direction-row-reverse is-flex ">
          <p class="has-text-white is-size-4"> فروشگاه اینترنتی پنیر</p>
        </div>
      </div>
      <div class="columns has-background-light mr-0 mb-0">
        <div class="column mx-6 mt-4 is-flex-direction-row-reverse is-flex">
          <div class="has-text-centered">
            <img src="starenamad.png" alt="">
          </div>
        </div>
        <div class="column mx-6 mt-4 is-flex-direction-row-reverse is-flex">
          <p class="has-text-weight-bold has-text-grey">
            فروشگاه اینترنتی
          </p>
        </div>
      </div>
      <div class="has-background-grey-dark has-text-white py-2 has-text-centered subtitle is-7 has-text-weight-normal">
        استفاده از مطالب فروشگاه اینترنتی  برای مقاصد غیرتجاری و با ذکر منبع بلامانع است.
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMobileMenuOpen: false
    };
  },
  methods: {
    toggleMenu() {
      this.isMobileMenuOpen = !this.isMobileMenuOpen;
    }
  }
}
</script>
