<template>
  <div>
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="ml-4" href="#">
          <img src="logo.png">
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
          <img src="4.jpg" alt="">
        </div>
      </div>
    </div>
    <div class="columns is-centered mx-4">
      <div class="column  is-three-quarters">
        <div class="box">
          <p class="has-text-centered is-size-4 has-text-weight-bold mt-4 has-background-white-ter py-1 around-the-title">خواص پنیر لیقوان</p>
          <div class="has-text-centered mt-5">
            <img src="shakhe.png" alt="">
          </div>
          <p class="has-text-right is-size-6 line-height-description mt-4 mb-6">

            پنیر از شیر گاو یا گاوهایی که در منطقه پرورش داده می‌شوند، تهیه می‌شود و دارای طعم و مزه خاصی است. آنچه پنیر
            لیقوان را از دیگر انواع پنیرها متمایز می‌کند، طعم غنی و ملایم آن است که به دلیل شرایط آب و هوایی و مراتع غنی
            این منطقه بوجود می‌آید.

            این پنیر معمولاً از شیر گاوهای محلی تهیه می‌شود که از چراگاه‌ها و مراتع اطراف لیقوان بهره می‌برند. پنیر
            لیقوان به صورت دستی و سنتی تولید می‌شود و برخی از کارخانه‌های محلی نیز در تولید آن نقش دارند. این پنیر
            معمولاً در قالب‌های بزرگ و استوانه‌ای تولید و به فروش می‌رسد.

            پنیر لیقوان به دلیل طعم خوشمزه، بافت نرم و ارزش غذایی بالا، مورد توجه بسیاری از علاقمندان به غذاهای ایرانی
            قرار دارد. این پنیر یکی از اصلی‌ترین مواد غذایی محسوب می‌شود که در تهیه انواع غذاهای ایرانی مورد استفاده
            قرار می‌گیرد و در ساندویچ‌ها، سالادها، پیتزاها و دیگر غذاها به عنوان یکی از مواد اصلی مورد استفاده قرار
            می‌گیرد.

            پنیر لیقوان به عنوان یک منبع خوب از پروتئین، کلسیم و سایر مواد مغذی مورد توجه است. این پنیر مفید برای رشد و
            تقویت استخوان‌ها و دندان‌ها است و در جبران نیازهای روزانه بدن به مواد مغذی مهم موثر است.

            تولید پنیر لیقوان در شهر لیقوان به عنوان یک فعالیت اقتصادی مهم شناخته می‌شود و به اشتغالزایی و رونق اقتصادی
            در این منطقه کمک می‌کند. این فعالیت تاثیر مهمی در اشتغال و رفاه اجتماعی مردم این منطقه داشته و به توسعه
            کشاورزی و دامداری در این منطقه کمک می‌کند.
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
          <p class="has-text-centered is-size-4 has-text-weight-bold mt-4 has-background-white-ter py-1 around-the-title">خواص پنیر شاهی</p>
          <div class="has-text-centered mt-5">
            <img src="shakhe.png" alt="">
          </div>
          <p class="has-text-right is-size-6 line-height-description mt-4 mb-6">

            پنیر شاهی یکی از نوع‌های محبوب پنیر در ایران است که از شیر گاو یا گاوهای محلی تولید می‌شود. این پنیر
            اصلی‌ترین محصول لبنی استان خراسان رضوی است و به دلیل ویژگی‌های خاص خود محبوبیت زیادی در بین مردم دارد. پنیر
            شاهی دارای طعم ملایم و خوشمزه‌ای است که به دلیل این ویژگی، در غذاهای مختلف مورد استفاده قرار می‌گیرد.

            این نوع پنیر معمولاً به صورت قطعات مربعی یا مستطیلی عرضه می‌شود و در بسته‌بندی‌های مختلف در بازارها و
            فروشگاه‌ها یافت می‌شود. تولید این پنیر اغلب به صورت سنتی و در واحدهای کوچک و خانگی انجام می‌شود، اما برخی
            کارخانه‌های بزرگ نیز اقدام به تولید آن کرده‌اند.

            پنیر شاهی دارای ارزش غذایی بالایی است و منبع خوبی از پروتئین، کلسیم و سایر مواد مغذی است. این پنیر به دلیل
            محتوای چربی مناسب خود، مناسب برای مصرف در سفره‌های ایرانی به شمار می‌آید و در تهیه انواع غذاهای محلی و
            معمولاً در فست فودهای ایرانی مورد استفاده قرار می‌گیرد.

            پنیر شاهی به دلیل طعم خوشایند و ملایم خود، معمولاً در ساندویچ‌ها، پیتزاها، سالادها و انواع غذاهای دیگر به
            عنوان یکی از اجزای اصلی مورد استفاده قرار می‌گیرد. همچنین، این پنیر به عنوان مکملی خوب برای تنقلات، برخی
            انواع خوراک‌ها و حتی در تهیه دسرها نیز مورد استفاده قرار می‌گیرد.

            پنیر شاهی به دلیل رونق دامداری در استان خراسان، ارزان قیمت و در دسترس بودن برای اکثر مردم است. این ویژگی
            باعث شده تا پنیر شاهی به عنوان یک گزینه مناسب و اقتصادی برای مصرف روزانه در خانواده‌ها به شمار آید.

            در طول تاریخ، پنیر شاهی نقش مهمی در فرهنگ و سنت غذایی ایرانی ایفا کرده است و همچنان ادامه تولید و مصرف آن به
            عنوان یکی از محصولات مهم لبنی در ایران ادامه دارد.
          </p>
        </div>
      </div>
    </div>
    <div class="columns is-centered mx-4 my-4 is-vcentered">
      <div class="column is-one-quarter">
        <div class="has-text-centered">
          <img src="2.jpg" alt="">
        </div>
      </div>
      <div class="column has-text-right is-two-thirds line-height-description">
        <p>
          لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون
          بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع
          با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و
          متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ
          پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط
          سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود
          طراحی اساسا مورد استفاده قرار گیرد.
        </p>
      </div>
    </div>
    <div class="columns is-centered mx-4 my-4 is-vcentered">
      <div class="column is-one-quarter">
        <div class="has-text-centered">
          <img src="3.jpg" alt="">
        </div>
      </div>
      <div class="column has-text-right is-two-thirds line-height-description">
        <p>
          لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون
          بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع
          با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و
          متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ
          پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط
          سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود
          طراحی اساسا مورد استفاده قرار گیرد.
        </p>
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
          <p class="has-text-white is-size-4"> فروشگاه اینترنتی دلیان</p>
        </div>
      </div>
      <div class="columns has-background-light mr-0 mb-0">
        <div class="column mx-6 mt-4 is-flex-direction-row-reverse is-flex">
          <div class="has-text-centered">
            <img src="starenamad.png" alt="">
          </div>
        </div>
        <div class="column mx-6 mt-4 is-flex-direction-row-reverse is-flex">
          <p class="has-text-weight-bold has-text-grey has-text-right">
            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ
          </p>
        </div>
      </div>
      <div class="has-background-grey-dark has-text-white py-2 has-text-centered subtitle is-7 has-text-weight-normal">
        استفاده از مطالب فروشگاه اینترنتی دلیان برای مقاصد غیرتجاری و با ذکر منبع بلامانع است.
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
