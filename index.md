<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <!-- Помнишь, для чего служит title? Он отображается в результатах поисковой выдачи в том же Гугле, ну или Эксплорере — не суть. Можешь погуглить ради интереса, что выдается по запросу 'Fairy Agency'. Погуглил? Молодец. А теперь допиши в title что-нибудь, чтобы было понятно, что мы сайты тут делаем. -->
  <title>Fairy Agency</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <meta content="" name="keywords">
  <meta content="" name="description">

  <!-- Favicons -->
  <!-- Знаешь, что такое фавикон? Погуглишь — разберешься, не маленький. Ладно, так уж и быть — объясню. Это та картинка, что отображается рядом с заголовком вкладки. Видишь 'B' в квадрате? Поищи в интернете и замени её на что-нибудь нормальное. В конце концов мы не бабочками торгуем, а сайты делаем. И про apple-touch-icon не забудь -->
  <link href="img/favicon.png" rel="icon">
  <link href="img/apple-touch-icon.png" rel="apple-touch-icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Montserrat:300,400,500,700|Open+Sans:300,300i,400,400i,700,700i" rel="stylesheet">

  <!-- Bootstrap -->
  <!-- Бутстрап — очень полезный CSS-фреймворк. Просто раскомментируй ссылку, и посмотри, как сайт преобразится. Это значительно упростит твою работу -->
   <link href="lib/bootstrap/css/bootstrap.min.css" rel="stylesheet"> 

  <!-- CSS-библиотеки -->
  <link href="lib/font-awesome/css/font-awesome.min.css" rel="stylesheet">
  <link href="lib/ionicons/css/ionicons.min.css" rel="stylesheet">
  <link href="lib/aos/aos.css" rel="stylesheet">
  <link href="lib/magnific-popup/magnific-popup.css" rel="stylesheet">


  <!-- Главный файл стилей -->
  <link href="css/style.css" rel="stylesheet">

</head>

<body>

  <!--==========================
    Хедер
  ============================-->
  <header id="header">
    <!-- Я тут нашел очень странную багу. Сейчас расскажу тебе, как воспроизвести. Перейди по ссылке с заглушкой или просто допиши # в конец адресной строки (как на скрине), пролистай примерно до середины сайта и обнови страницу. С фоном хедера творится что-то неладное. Если заказчик узнает, он меня убьет: https://capella.pics/7a82ef24-d382-4c51-9150-36f4422b7656.jpg -->
    <div class="container">

      <div id="logo" class="pull-left">
        <h1><a href="#intro" class="scrollto">Fairy Agency</a></h1>
        <!-- Вместо названия компании здесь должен быть логотип. Поищи какой-нибудь в интернете симпатичный с прозрачным фоном или нарисуй сам. Авторчкие права — дело тонкое, ты понимаешь. Я тебе уже сделал заготовку — просто раскомментируй строку ниже и вставь нужную картинку. Не благодари. -->
        <!-- <a href="#intro"><img src="img/logo.png" alt="" title="" /></img></a> -->
      </div>

      <nav id="nav-menu-container">
        <ul class="nav-menu">
          <li class="menu-active"><a href="#intro">Главная</a></li>
          <li><a href="#about">О нас</a></li>
          <!-- Я не знаю, как ты с этим справишься, но нужно сделать выпадающее меня второго уровня по ширине таким же, как первого. Слишком длинные названия должны обрезаться и скрываться многоточием:
          https://capella.pics/a47581f9-829f-47fc-adac-5af3d822b429.jpg -->
          <li class="menu-has-children"><a href="">Меню</a>
            <ul>
              <li><a href="#">О продвижении</a></li>
              <li class="menu-has-children"><a href="#">Front-end блог</a>
                <ul>
                  <li><a href="#">Зачем нам нужен JavaScript</a></li>
                  <li><a href="#">Node.js или Я у Мамы Бэкендер</a></li>
                  <li><a href="#">Почему нужно учить фреймворки</a></li>
                  <li><a href="#">Системы сборки за и против</a></li>
                  <li><a href="#">Скажи мне, какой препроцессор используешь</a></li>
                </ul>
              </li>
              <li><a href="#">Наша история</a></li>
              <li><a href="#">События мира Web</a></li>
              <li><a href="#">Тренды 2k18</a></li>
            </ul>
          <li><a href="#features">Преимущества</a></li>
          <li><a href="#pricing">Цены</a></li>
          <!-- Хей, кажется эта ссылка никуда не ведет. Сможешь пофиксить? -->
          <li><a href="#komanda">Команда</a></li>
          <li><a href="#gallery">Портфолио</a></li>
          </li>
          <li><a href="#contact">Контакты</a></li>
        </ul>
      </nav><!-- #nav-menu-container -->
    </div>
  </header><!-- #header -->

  <!--==========================
    Intro Section
  ============================-->
  <section id="intro">

    <div class="intro-text">
      <h2>Мы Fairy Agency</h2>
      <p>Создаем сайты, которые нравятся людям</p>
      <!-- Эта ссылка должна переходить на секцию "О нас". Но она просто выбрасывает с сайта. Сможешь пофиксить? -->
      <a href=".about" class="btn-get-started scrollto">Узнать больше</a>
    </div>
    <!-- Кажется, одно из изображений наезжает на кнопку "Узнать больше".
    Смекаешь, что так быть не должно? Разберись с этим:
    https://capella.pics/7496b62f-de81-4b6d-a725-5205c273cf50.jpg -->
    <div class="product-screens">

      <div class="product-screen-1" data-aos="fade-up" data-aos-delay="400" >
        <img src="img/product-screen-1.png" alt="">
      </div>

      <div class="product-screen-2" data-aos="fade-up" data-aos-delay="200">
        <img src="img/product-screen-2.png" alt="">
      </div>

      <div class="product-screen-3" data-aos="fade-up" data-aos-delay="200">
        <img src="img/product-screen-3.png" alt="">
      </div>

    </div>

  </section><!-- #intro -->

  <main id="main">

    <!--==========================
      Секция о нас
    ============================-->
    <section id="about" class="section-bg">
      <div class="container-fluid">
        <div class="section-header">
          <h3 class="section-title">О нас</h3>
          <span class="section-divider"></span>
          <p class="section-description">
            За 10 лет на рынке мы помогли более чем 220 компаниям увеличить продажи с помощью сайта.<br>
            Среди наших клиентов Misty Princess, ElectroCat и Nervous Salamandra.
          </p>
        </div>

        <div class="row">
          <div class="col-lg-6 about-img" data-aos="fade-right">
            <img src="img/about-img.jpg" alt="">
          </div>

          <div class="col-lg-6 content" data-aos="fade-left">
            <h2>Мы знаем, что нравится вашим клиентам</h2>
            <h3>В 21 веке люди ценят мобильность и удобство. Клиент с удовольствием сделает заказ в два клика, не отрываясь от своих дел.</h3>
            <p>
              Можете мысленно описать сайт, на котором вам было приятно находиться? Мы не умеем читать мысли, но готовы поспорить, вы сейчас подумали:
            </p>

            <ul>
              <li><i class="ion-android-checkmark-circle"></i> На нем легко найти нужную информацию</li>
              <li><i class="ion-android-checkmark-circle"></i> Хорошо проработаны элементы интерфейса</li>
              <li><i class="ion-android-checkmark-circle"></i> Он быстро грузится</li>
            </ul>

            <p>
              Мы можем сделать такой сайт с учетом ваших пожеланий. Сайт, который поможет достичь ваших целей.
            </p>
          </div>
        </div>

      </div>
    </section><!-- #about -->

    <!--==========================
      Секция преимущества продукта
    ============================-->
    <section id="features">
      <div class="container">

        <div class="row">

          <div class="col-lg-8 offset-lg-4">
            <div class="section-header" data-aos="fade" data-aos-duration="1000">
              <h3 class="section-title">Преимущества работы с нами</h3>
              <span class="section-divider"></span>
            </div>
          </div>

          <div class="col-lg-4 col-md-5 features-img">
            <img src="img/product-features.png" alt="" data-aos="fade-right" data-aos-easing="ease-out-back">
          </div>

          <div class="col-lg-8 col-md-7 ">

            <div class="row">

              <div class="col-lg-6 col-md-6 box" data-aos="fade-left">
                <div class="icon"><i class="ion-ios-analytics-outline"></i></div>
                <h4 class="title"><a href="">Гарантия качества</a></h4>
                <p class="description">Мы будем согласовывать с вами каждый этап. Это сделает процесс разработки прозрачным для вас, и вы будете знать, что получите в конце.</p>
              </div>
              <div class="col-lg-6 col-md-6 box" data-aos="fade-left" data-aos-delay="100">
                <div class="icon"><i class="ion-ios-flask-outline"></i></div>
                <h4 class="title"><a href="">Комплексный подход</a></h4>
                <p class="description">Помимо разработки сайта мы можем предложить вам услуги SEO-специалиста, копирайтера и маркетолога.</p>
              </div>
              <div class="col-lg-6 col-md-6 box" data-aos="fade-left" data-aos-delay="200">
                <div class="icon"><i class="ion-social-buffer-outline"></i></div>
                <h4 class="title"><a href="">Гибкая политика цен</a></h4>
                <p class="description">У нас есть разные тарифы. Воспользуйтесь услугой бесплатной консультации и выберите только то, что вам нужно.</p>
              </div>
              <div class="col-lg-6 col-md-6 box" data-aos="fade-left" data-aos-delay="300">
                <div class="icon"><i class="ion-ios-speedometer-outline"></i></div>
                <h4 class="title"><a href="">Точно в срок</a></h4>
                <p class="description">Мы ценим время наших клиентов. Будет составлен план работ и обозначено время завершения каждого этапа.</p>
              </div>
            </div>

          </div>

        </div>

      </div>

    </section><!-- #features -->

    <!--==========================
      Детальное описание преимуществ
    ============================-->
    <section id="advanced-features">

      <div class="features-row section-bg">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <img class="advanced-feature-img-right" src="img/advanced-feature-1.jpg" alt="" data-aos="fade-left">
              <div data-aos="fade-right">
                <h2>Услуги SEO-оптимизации</h2>
                <h3>Знаете, как находят вас клиенты? Наши специалисты смогут дать ответ на этот вопрос.</h3>
                <p>Мы проанализируем запросы поисковиков и изучим ваших конкурентов. Составим портрет целевой аудитории и поможем новым клиентам узнать о вас.</p>
                <p>Обсудим ваши цели SEO-продвижения. Определим, на каких страницах ваши клиенты проводят больше всего времени.</p>
                <p>Оптимизируем сайт и поможем подняться на верхние позиции в результатах выдачи поисковых систем</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="features-row">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <img class="advanced-feature-img-left" src="img/advanced-feature-2.jpg" alt="">
              <div data-aos="fade-left">
                <h2>Проработка интерфейса</h2>
                <i class="ion-ios-paper-outline" data-aos="fade-left"></i>
                <p data-aos="fade-left">Задача любого сайта — сделать так, чтобы посетитель быстро нашел нужную ему информацию. Если интерфейс непонятен, вы рискуете потерять клиента</p>
                <i class="ion-ios-color-filter-outline" data-aos="fade-left" data-aos-delay="200"></i>
                <p data-aos="fade-left" data-aos-delay="200">Наши креативные специалисты разработают максимально удобный и легкий для восприятия вашей целевой аудитории дизайн.</p>
                <i class="ion-ios-barcode-outline" data-aos="fade-left" data-aos-delay="400"></i>
                <p data-aos="fade-left" data-aos-delay="400">Струкура сайта будет логично организована, а элементы интерфейса выдержаны в едином стиле. Ваш сайт будет отлично смотреться на любых мобильных устройствах.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="features-row section-bg">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <img class="advanced-feature-img-right" src="img/advanced-feature-3.jpg" alt="" data-aos="fade-left">
              <div data-aos="fade-right">
                <h2>Цифры говорят сами за себя</h2>
                <h3>Наши сайты помогают продавать.</h3>
                <p>Мы работаем с компаниями, занятыми в совершенно разных отраслях. Среди наших клиентов представители малого и среднего бизнеса, владельцы салонов красоты, производители техники и электроники, операторы связи. Все они отмечают повышение уровня продаж после заказа сайта.</p>
                <i class="ion-ios-albums-outline"></i>
                <p>Мы не знаем, что у вас за компания, поэтому пока не можем сказать, какое решение подойдет именно вам. Приходите к нам в офис — обсудим за чашечкой кофе.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section><!-- #advanced-features -->

    <!--==========================
      Call To Action Section
    ============================-->
    <section id="call-to-action">
      <div class="container">
        <div class="row">
          <div class="col-lg-9 text-center text-lg-left">
            <h3 class="cta-title">Начните с сайта</h3>
            <p class="cta-text">Давно хотели поднять свой бизнес на новый уровень? Сделайте первый шаг — закажите бесплатную консультацию по созданию сайта.</p>
          </div>
          <div class="col-lg-3 cta-btn-container text-center">
            <a class="cta-btn align-middle" href="#">Заказать сайт</a>
          </div>
        </div>

      </div>
    </section><!-- #call-to-action -->

    <!--==========================
      Секция дополнительные преимущества
    ============================-->
    <section id="more-features" class="section-bg">
      <div class="container">

        <div class="section-header">
          <h3 class="section-title">Почему стоит выбрать нас</h3>
          <span class="section-divider"></span>
          <p class="section-description">Если вы дочитали до этой секции, похоже, вы заинтересованы. Позвольте рассказать вам больше.</p>
        </div>

        <div class="row">

          <div class="col-lg-6">
            <div class="box" data-aos="fade-right">
              <div class="icon"><i class="ion-ios-analytics-outline"></i></div>
              <h4 class="title"><a href="">Разработка фирменного стиля</a></h4>
              <p class="description">Наш креативный специалист поможет разработать корпоративную символику, благодаря которой ваша компания станет более узнаваемой.</p>
            </div>
          </div>

          <div class="col-lg-6">
            <div class="box" data-aos="fade-left">
              <div class="icon"><i class="ion-ios-bookmarks-outline"></i></div>
              <h4 class="title"><a href="">Система бонусов</a></h4>
              <p class="description">Расскажите о нас вашим знакомым, получите существенную скидку на услуги технической поддержки для вашего сайта.</p>
            </div>
          </div>

          <div class="col-lg-6">
            <div class="box" data-aos="fade-right">
              <div class="icon"><i class="ion-ios-stopwatch-outline"></i></div>
              <h4 class="title"><a href="">Ценим ваше время</a></h4>
              <p class="description">Нет времени наполнять сайт? Наши копирайтеры напишут тексты, а контент-менеджер добавит на сайт нужные материалы.</p>
            </div>
          </div>

          <div class="col-lg-6">
            <div class="box" data-aos="fade-left">
              <div class="icon"><i class="ion-ios-heart-outline"></i></div>
              <h4 class="title"><a href="">Нам доверяют</a></h4>
              <p class="description">Клиентам нравится, как мы работаем, они рекомендуют нас знакомым и возвращаются к нам снова.</p>
            </div>
          </div>

        </div>
      </div>
    </section><!-- #more-features -->

    <!--==========================
      Секция клиенты
    ============================-->
    <section id="clients">
      <div class="container">

        <div class="row">

          <div class="col-md-2">
            <img src="img/clients/client-1.png" alt=""  data-aos="fade-up">
          </div>

          <div class="col-md-2">
            <img src="img/clients/client-2.png" alt=""  data-aos="fade-up">
          </div>

          <div class="col-md-2">
            <img src="img/clients/client-3.png" alt=""  data-aos="fade-up">
          </div>

          <div class="col-md-2">
            <img src="img/clients/client-4.png" alt=""  data-aos="fade-up">
          </div>

          <div class="col-md-2">
            <img src="img/clients/client-5.png" alt=""  data-aos="fade-up">
          </div>

          <div class="col-md-2">
            <img src="img/clients/client-6.png" alt=""  data-aos="fade-up">
          </div>

        </div>
      </div>
    </section><!-- #more-features -->

    <!--==========================
      Секция цены
    ============================-->
    <section id="pricing" class="section-bg">
      <div class="container">

        <div class="section-header">
          <h3 class="section-title">Наши цены</h3>
          <span class="section-divider"></span>
          <p class="section-description">Приведенные на сайте цены предварительные. Они могут измениться как в большую, так и в меньшую сторону, после того как вы расскажете о вашей компании.</p>
        </div>

        <div class="row">
          <!-- Тексты на русском языке, а цены в долларах? Возьми-ка калькулятор, дружок, и исправь. -->
          <div class="col-lg-4 col-md-6">
            <div class="box" data-aos="fade-right">
              <h3>Стартовый</h3>
              <h4><sup>$</sup>500<span> месяц</span></h4>
              <ul>
                <li><i class="ion-android-checkmark-circle"></i> Составление плана работ</li>
                <li><i class="ion-android-checkmark-circle"></i> Анализ целевой аудитории</li>
                <li><i class="ion-android-checkmark-circle"></i> Проработка интерфейса</li>
                <li><i class="ion-android-checkmark-circle"></i> Отрисовка макетов</li>
                <li><i class="ion-android-checkmark-circle"></i> Работы по верстке и настройке</li>
              </ul>
              <a href="#" class="get-started-btn">Начать</a>
            </div>
          </div>

          <div class="col-lg-4 col-md-6">
            <!-- В тариф "бизнес" больше не входит настройка SSL-сертификатов. Однако, если убрать этот пункт, блоки становятся разной высоты. Заказчик не портерпит такого на своем сайте. Однако, и обманывать людей за их же деньги нехорошо. Поправишь? https://capella.pics/938def0d-7dd8-41b0-ba3d-108c21ddc078.jpg -->
            <div height = "500px" class="box featured" data-aos="fade-up">
              <h3>Бизнес</h3>
              <h4><sup>$</sup>700<span> месяц</span></h4>
              <ul>
                <li><i class="ion-android-checkmark-circle"></i> Все опции пакета "Стартовый"</li>
                <li><i class="ion-android-checkmark-circle"></i> Работа SEO-специалиста</li>
                
                <li><i class="ion-android-checkmark-circle"></i> Анализ конкурентов</li>
                <li><i class="ion-android-checkmark-circle"></i> Аудит вашего старого сайта</li>
              </ul>
              <a href="#" class="get-started-btn">Начать</a>
            </div>
          </div>

          <div class="col-lg-4 col-md-6">
            <div class="box" data-aos="fade-left">
              <h3>Всё включено</h3>
              <h4><sup>$</sup>1000<span> месяц</span></h4>
              <ul>
                <li><i class="ion-android-checkmark-circle"></i> Все опции пакета "Бизнес"</li>
                <li><i class="ion-android-checkmark-circle"></i> Услуги копирайтера</li>
                <li><i class="ion-android-checkmark-circle"></i> Услуги контент-менеджера</li>
                <li><i class="ion-android-checkmark-circle"></i> Тех.поддержка вашего сайта</li>
                <li><i class="ion-android-checkmark-circle"></i> Консультация маркетолога</li>
              </ul>
              <a href="#" class="get-started-btn">Начать</a>
            </div>
          </div>

        </div>
      </div>
    </section><!-- #pricing -->

    <!--==========================
      Секция часто задаваемые вопросы
    ============================-->
    <section id="faq">
      <div class="container">

        <div class="section-header">
          <h3 class="section-title">Часто задаваемые вопросы</h3>
          <span class="section-divider"></span>
          <p class="section-description">Здесь приведены ответы на наиболее распространенные вопросы наших клиентов</p>
        </div>

        <ul id="faq-list" data-aos="fade-up">
          <li>
            <a data-toggle="collapse" class="collapsed" href="#faq1">Сколько по времени занимает разработка сайта? <i class="ion-android-remove"></i></a>
            <div id="faq1" class="collapse" data-parent="#faq-list">
              <p>
                Все зависит от сложности вашей идеи и специфики бизнеса. В среднем от 2 до 4 месяцев.
              </p>
            </div>
          </li>

          <li>
            <a data-toggle="collapse" href="#faq2" class="collapsed">У меня есть старый сайт. Сколько стоит заказать его редизайн?<i class="ion-android-remove"></i></a>
            <div id="faq2" class="collapse" data-parent="#faq-list">
              <p>
                Для начала нам нужно ознакомиться с вашим сайтом. Приходите к нам в офис на бесплатную консультацию.
              </p>
            </div>
          </li>

          <li>
            <a data-toggle="collapse" href="#faq3" class="collapsed">Если я порекомендую вас знакомым, и они закажут у вас сайт, сколько составит моя скидка?<i class="ion-android-remove"></i></a>
            <div id="faq3" class="collapse" data-parent="#faq-list">
              <p>
                Скидка на наши услуги составит 10%
              </p>
            </div>
          </li>

          <li>
            <a data-toggle="collapse" href="#faq4" class="collapsed">В стоимость ваших услуг уже входит покупка доменного имени?<i class="ion-android-remove"></i></a>
            <div id="faq4" class="collapse" data-parent="#faq-list">
              <p>
                Нет, не входит. Мы вместе с вами выбираем доменное имя для вашего сайта, и вы оплачиваете покупку домена отдельно.
              </p>
            </div>
          </li>

          <li>
            <a data-toggle="collapse" href="#faq5" class="collapsed">Можно ли отдельно заказать у вас услуги тех.поддержки без создания сайта?<i class="ion-android-remove"></i></a>
            <div id="faq5" class="collapse" data-parent="#faq-list">
              <p>
                Нет, мы занимаемся поддержкой только сайтов, созданных нами.
              </p>
            </div>
          </li>

          <li>
            <a data-toggle="collapse" href="#faq6" class="collapsed">Можно ли у вас заказать услуги копирайтера и/или SEO-специалиста без создания сайта?<i class="ion-android-remove"></i></a>
            <div id="faq6" class="collapse" data-parent="#faq-list">
              <p>
                Да, можно.
              </p>
            </div>
          </li>

        </ul>

      </div>
    </section><!-- #faq -->

    <!--==========================
      Секция наша команда
    ============================-->
    <section id="team" class="section-bg">
      <div class="container">
        <div class="section-header">
          <h3 class="section-title">Команда</h3>
          <span class="section-divider"></span>
          <p class="section-description">Эти люди будут участвовать в разработке сайта, который поднимет ваш бизнес на новый уровень.</p>
        </div>
        <!-- В идеале фотографии должны выглядеть так: https://capella.pics/c75ad454-20f7-44cb-bcc1-a21c66dbb628.jpg
        Сможешь избавиться от этого ужасного скролла? -->
        <div class="row" data-aos="fade-up">
          <div class="col-lg-3 col-md-6">
            <div class="member">
              <div  ><img width = "200px" height = "200px" src="img/team/team-1.jpg" alt=""></div>
              <h4>Михаил Белкин</h4>
              <span>Web-программист</span>
              <div class="social">
                <a href=""><i class="fa fa-twitter"></i></a>
                <a href=""><i class="fa fa-facebook"></i></a>
                <a href=""><i class="fa fa-google-plus"></i></a>
                <a href=""><i class="fa fa-linkedin"></i></a>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member">
              <div class="pic"><img src="img/team/team-2.jpg" alt=""></div>
              <h4>Сара Джонс</h4>
              <span>Копирайтер</span>
              <div class="social">
                <a href=""><i class="fa fa-twitter"></i></a>
                <a href=""><i class="fa fa-facebook"></i></a>
                <a href=""><i class="fa fa-google-plus"></i></a>
                <a href=""><i class="fa fa-linkedin"></i></a>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member">
              <div class="pic"><img src="img/team/team-3.jpg" alt=""></div>
              <h4>Федор Сахно</h4>
              <span>SEO-специалист</span>
              <div class="social">
                <a href=""><i class="fa fa-twitter"></i></a>
                <a href=""><i class="fa fa-facebook"></i></a>
                <a href=""><i class="fa fa-google-plus"></i></a>
                <a href=""><i class="fa fa-linkedin"></i></a>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member">
              <div class="pic"><img src="img/team/team-4.jpg" alt=""></div>
              <h4>Анастасия Цветкова</h4>
              <span>Дизайнер</span>
              <div class="social">
                <a href=""><i class="fa fa-twitter"></i></a>
                <a href=""><i class="fa fa-facebook"></i></a>
                <a href=""><i class="fa fa-google-plus"></i></a>
                <a href=""><i class="fa fa-linkedin"></i></a>
              </div>
            </div>
          </div>
        </div>

      </div>
    </section><!-- #team -->

    <!--==========================
      Секция галерея
    ============================-->
    <section id="gallery">
      <div class="container-fluid">
        <div class="section-header">
          <h3 class="section-title">Портфолио</h3>
          <span class="section-divider"></span>
          <p class="section-description">Примеры наших работ, среди которых корпоративные сайты, посадочные страницы и сайты-визитки.</p>
        </div>

        <div class="row no-gutters">
          <!-- У меня тут пара картинок куда-то задевалась. Они должны быть в папке. Наверное, что-то с путями -->
          <div class="col-lg-4 col-md-6">
            <div class="gallery-item" data-aos="fade-up">
              <a href="img/gallery/gallery-1.jpg" class="gallery-popup">
                <img src="img/gallery/gallery-1.jpg" alt="">
              </a>
            </div>
          </div>

          <div class="col-lg-4 col-md-6">
            <div class="gallery-item" data-aos="fade-up">
              <a href="img/gallery/gallery-2.jpg" class="gallery-popup">
                <img src="img/gallery/gallery-2.jpg" alt="">
              </a>
            </div>
          </div>

          <div class="col-lg-4 col-md-6">
            <div class="gallery-item" data-aos="fade-up">
              <a href="img/gallery/gallery-3.jpg" class="gallery-popup">
                <img src="../../img/gallery/gallery-3.jpg" alt="">
              </a>
            </div>
          </div>

          <div class="col-lg-4 col-md-6">
            <div class="gallery-item" data-aos="fade-up">
              <a href="img/gallery/gallery-4.jpg" class="gallery-popup">
                <img src="../img/gallery/gallery-4.jpg" alt="">
              </a>
            </div>
          </div>

          <div class="col-lg-4 col-md-6">
            <div class="gallery-item" data-aos="fade-up">
              <a href="img/gallery/gallery-5.jpg" class="gallery-popup">
                <img src="img/gallery/gallery-5.jpg" alt="">
              </a>
            </div>
          </div>

          <div class="col-lg-4 col-md-6">
            <div class="gallery-item" data-aos="fade-up">
              <a href="img/gallery/gallery-6.jpg" class="gallery-popup">
                <img src="img/gallery/gallery-6.jpg" alt="">
              </a>
            </div>
          </div>

        </div>

      </div>
    </section><!-- #gallery -->

    <!--==========================
      Contact Section
    ============================-->
    <section id="contact">
      <div class="container">
        <div class="row" data-aos="fade-up">

          <div class="col-lg-4 col-md-4">
            <div class="contact-about">
              <h3>Fairy Agency</h3>
              <p>Закажите у нас сайт, который поднимет ваш бизнес на новый уровень.</p>
              <div class="social-links">
                <a href="#" class="twitter"><i class="fa fa-twitter"></i></a>
                <a href="#" class="facebook"><i class="fa fa-facebook"></i></a>
                <a href="#" class="instagram"><i class="fa fa-instagram"></i></a>
                <a href="#" class="google-plus"><i class="fa fa-google-plus"></i></a>
                <a href="#" class="linkedin"><i class="fa fa-linkedin"></i></a>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="info">
              <div>
                <i class="ion-ios-location-outline"></i>
                <p>Цветочная улица, дом 10<br>Нью Йорк, 535022</p>
              </div>

              <div>
                <i class="ion-ios-email-outline"></i>
                <p>order@fairyagency.com</p>
              </div>

              <div>
                <i class="ion-ios-telephone-outline"></i>
                <p>+2-7756-55468-59</p>
              </div>

            </div>
          </div>

          <div class="col-lg-5 col-md-8">
            <div class="form">
              <div id="sendmessage">Ваше сообщение отправлено. Спасибо!</div>
              <div id="errormessage"></div>
              <form action="" method="post" role="form" class="contactForm">
                <div class="form-row">
                  <div class="form-group col-lg-6">
                    <input type="text" name="name" class="form-control" id="name" placeholder="Ваше имя" data-rule="minlen:4" data-msg="В вашем имени должно быть как минимум 4 буквы" />
                    <div class="validation"></div>
                  </div>
                  <div class="form-group col-lg-6">
                    <input type="email" class="form-control" name="email" id="email" placeholder="Ваш Email" data-rule="email" data-msg="Введите корректный email" />
                    <div class="validation"></div>
                  </div>
                </div>
                <div class="form-group">
                  <input type="text" class="form-control" name="subject" id="subject" placeholder="Тема" data-rule="minlen:4" data-msg="Тема сообщения должна быть как минимум длиной 8 символов" />
                  <div class="validation"></div>
                </div>
                <div class="form-group">
                  <textarea class="form-control" name="message" rows="5" data-rule="required" data-msg="Напишите что-нибудь нам" placeholder="Ваше сообщение"></textarea>
                  <div class="validation"></div>
                </div>
                <div class="text-center"><button type="submit" title="Send Message">Отправить</button></div>
              </form>
            </div>
          </div>

        </div>

      </div>
    </section><!-- #contact -->

  </main>

  <!--==========================
    Footer
  ============================-->
  <footer id="footer">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 text-lg-left text-center">
          <div class="copyright">
            &copy; Copyright <strong>Fairy Agency</strong>. Все права защищены
          </div>
        </div>
        <div class="col-lg-6">
          <nav class="footer-links text-lg-right text-center pt-2 pt-lg-0">
            <a href="#intro" class="scrollto">На главную</a>
            <a href="#about" class="scrollto">О нас</a>
            <a href="#">Политика конфиденциальности</a>
          </nav>
        </div>
      </div>
      </div>
    </div>
  </footer><!-- #footer -->

  <a href="#" class="back-to-top"><i class="fa fa-chevron-up"></i></a>

  <!-- JavaScript Libraries -->
  <script src="lib/jquery/jquery.min.js"></script>
  <script src="lib/jquery/jquery-migrate.min.js"></script>
  <script src="lib/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="lib/easing/easing.min.js"></script>
  <script src="lib/aos/aos.js"></script>
  <script src="lib/superfish/hoverIntent.js"></script>
  <script src="lib/superfish/superfish.min.js"></script>
  <script src="lib/magnific-popup/magnific-popup.min.js"></script>

  <!-- Contact Form JavaScript File -->
  <script src="contactform/contactform.js"></script>

  <!-- Template Main Javascript File -->
  <script src="js/main.js"></script>

</body>
</html>
