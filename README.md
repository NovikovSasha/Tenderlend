# Tenderlend

```html
    <!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <link href="https://fonts.googleapis.com/css?family=PT+Serif:400,700|Roboto:400,500&amp;subset=cyrillic"
    rel="stylesheet">
  <link rel="stylesheet" href="css/normalize.css">
  <!-- Подключение шрифтов -->
  <link rel="stylesheet" href="css/fonts.css">
  <link rel="stylesheet" href="css/jquery.fancybox.min.css">
  <link rel="stylesheet" href="css/slick.css">
  <!-- Визуальное оформление элементов форм -->
  <link rel="stylesheet" href="css/jquery.formstyler.css">
  <!-- Поключение основных стилей -->
  <link rel="stylesheet" href="css/style.css">
  <!-- Подключение стилей для адаптиной вёрстки -->
  <link rel="stylesheet" href="css/media.css">
</head>

<body>

  <!-- Вёрстка шапки -->
  <header class="header">

    <!-- Контактная часть шапки -->
    <div class="header__top">

      <!-- Ограничение всех элементо по ширине -->
      <div class="container">

        <!-- Контактные данные -->
        <div class="header__contacts">
          <!-- Номер телефона -->
          <a class="header__phone" href="tel:380963092145">8 800 555 35 35</a>
          <!-- Адресс электронной почты -->
          <a class="header__email" href="#">mmott23.melnikov@yandex.ru</a>
          <!-- Кнопка бесплатная консультация -->
          <a class="header__btn" href="#">Бесплатная
            консультация</a>
        </div>

      </div>

    </div>

    <!-- Осноная часть шапки -->
    <div class="header__content">

      <!-- Ограничение всех эл-ов осноной части шапки по ширине -->
      <div class="container">

        <!-- Обединение всех эл-ов осноной части шапки в одном блоке  -->
        <div class="header__content-inner">
          
          <!-- Логотип -->
          <div class="header__logo">
            <a href="#">
              <img src="img/logo.png" alt="Логотип">
            </a>
          </div>

          <!--  Гланое меню -->
          <nav class="menu">

        
            <!-- Списки меню -->
            <ul>
              <li><a href="#">Главная</a></li>
              <li><a href="#">О компании</a></li>
              <li><a href="#">Услуги</a></li>
              <li><a href="#">Контакты</a></li>
            </ul>

          </nav>
        </div>

      </div>
    </div>

  </header>

  <!-- Вёрстка слайдера -->
  <section class="slider">
    <!-- Ограничение всех эл-ов осноной части слайдера по ширине -->
    <div class="container">
      <!-- Обединение всех эл-ов контента слайдера в одном блоке  -->
      <div class="slider__inner">
        <!-- Вёрстка контента первой части слайдера -->
        <div class="slider__item">
          <!-- Объединение первой части  один блок -->
          <div class="slider__item-content">
            <!-- Заголовок контента -->
            <div class="slider__title">
              КОМПЛЕКСНОЕ ЗАКРЫТИЕ ПРЕДПРИЯТИЯ
            </div>
            <!-- Контент --> 
            <div class="slider__text">
              Полное прекращение существования юридического лица с сохранением легальности всей предыдущей деятельности.
            </div>
            <!-- Кнопка оставить заявку -->
            <a data-fancybox data-src="#modal" href="javascript:;" class="slider__btn default-btn">
              Оставить заявку
            </a>
          </div>
        </div>
        <!-- Вёрстка контента второй части слайдера -->
        <div class="slider__item">
          <!-- Объединение второй части  один блок -->
          <div class="slider__item-content">
            <!-- Заголовок контента -->
            <div class="slider__title">
              КОМПЛЕКСНОЕ ЗАКРЫТИЕ ПРЕДПРИЯТИЯ
            </div>
            <!-- Контент --> 
            <div class="slider__text">
              Полное прекращение существования юридического лица с сохранением легальности всей предыдущей деятельности.
            </div>
            <!-- Кнопка оставить заявку -->
            <a data-fancybox data-src="#modal" href="javascript:;" class="slider__btn default-btn">
              Оставить заявку
            </a>
          </div>
        </div>
        <!-- Вёрстка контента третьей части слайдера -->
        <div class="slider__item">
          <!-- Объединение третьей части  один блок -->
          <div class="slider__item-content">
            <!-- Заголовок контента -->
            <div class="slider__title">
              КОМПЛЕКСНОЕ ЗАКРЫТИЕ ПРЕДПРИЯТИЯ
            </div>
            <!-- Контент --> 
            <div class="slider__text">
              Полное прекращение существования юридического лица с сохранением легальности всей предыдущей деятельности.
            </div>
            <!-- Кнопка оставить заявку -->
            <a data-fancybox data-src="#modal" href="javascript:;" class="slider__btn default-btn">
              Оставить заявку
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Вёрстка услуг -->
  <section class="services">
    <!-- Ограничение всех элементо по ширине -->
    <div class="container">
      <!-- Верхняя часть блока услуги   -->
      <div class="services__top">
        <div class="services__title-box">
          <!-- Заголовок -->
          <div class="services__title">
            Наши Услуги
          </div>
          <div class="services__text">
            Комплексный подход к вашему вопросу, своевременная правовую помощь, представление интересов во всех судебных
            инстанциях.
          </div>
        </div>
        <!-- Кнопка показать услуги -->
        <div class="services__btn">
          <a href="#">
            Показать все услуги
          </a>
        </div>
      </div>
      <!-- Обединение услуг в один блок  -->
      <div class="services__items">
       <!--  Услуга банкротство и ликвидация -->
        <div class="services__item">
          <!-- Логотип услуги -->
          <img src="img/about-1.png" alt="">
          <!-- Заголовок  -->
          <div class="services__item-title">
            Банкротство и ликвидация
          </div>
          <!-- Описание услуги -->
          <div class="services__item-text">
            Полное прекращение существования юридического лица с сохранением легальности всей предыдущей деятельности
          </div>
          <!-- Кнопки -->
          <div class="services__item-btn">
            <!-- Кнопка подробнее -->
            <a class="services__item-link" href="#">Подробнее</a>
            <!-- Кнопка заказать -->
            <a data-fancybox data-src="#modal" href="javascript:;" class="default-btn">
              Заказать
            </a>
          </div>
        </div>
        <!--  Услуга адвокатское сопровождение -->
        <div class="services__item">
          <!-- Логотип услуги -->
          <img src="img/about-2.png" alt="">
          <!-- Заголовок  -->
          <div class="services__item-title">
            Адвокатское сопровождение
          </div>
          <!-- Описание услуги -->
          <div class="services__item-text">
            Мы гарантируем полное профессиональное обслуживание клиентов в заявленных сферах деятельности и соблюдение
            конфиденциальности.
          </div>
          <!-- Кнопки -->
          <div class="services__item-btn">
            <!-- Кнопка подробнее -->
            <a class="services__item-link" href="#">Подробнее</a>
            <!-- Кнопка заказать -->
            <a data-fancybox data-src="#modal" href="javascript:;" class="default-btn">
              Заказать
            </a>
          </div>
        </div>
        <!--  Услуга налоговый аудит -->
        <div class="services__item">
          <!-- Логотип услуги -->
          <img src="img/about-3.png" alt="">
          <!-- Заголовок  -->
          <div class="services__item-title">
            Налоговый аудит
          </div>
          <!-- Описание услуги -->
          <div class="services__item-text">
            Налоговый аудит проводят перед проведением налоговых проверок; при оценке возможных налоговых рисков; при
            оптимизации налогообложения.
          </div>
          <!-- Кнопки -->
          <div class="services__item-btn">
            <!-- Кнопка подробнее -->
            <a class="services__item-link" href="#">Подробнее</a>
            <!-- Кнопка заказать -->
            <a data-fancybox data-src="#modal" href="javascript:;" class="default-btn">
              Заказать
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Вёрстка информации о компании -->
  <section class="about">
    <!-- Ограничение всех элементо по ширине -->
    <div class="container">
      <!-- Обединение всех эл-ов контента информации о компании в одном блоке  -->
      <div class="about__inner">
        <!-- Заголовок -->
        <div class="about__title">
          О компании
        </div>
        <!-- Описание компании -->
        <div class="about__text">
          Компания специализируется на оказании услуг в сфере корпоративного права, налогового консалтинга,
          представительства в судах, ликвидации и банкротства предприятий. На сегодняшний день, коллектив компании
          объединяет
          высокопрофессиональных экспертов имеющих
          специализации в отдельных областях права.
        </div>
        <!-- Кнопка узнать больше -->
        <a href="#" class="about__btn default-btn">
          Узнать больше
        </a>
      </div>
    </div>
  </section>
  
  <!-- Вёрстка формы консультации клиента -->
  <section class="form">
    <!-- Ограничение всех элементо по ширине -->
    <div class="container">
      <div class="form__inner">
        <div class="form__content">
          <!-- Верхняя часть формы -->
          <div class="form__title-box">
            <!--  Заголовок -->
            <div class="form__title">
              Получить Консультацию
            </div>
            <div class="form__text">
              Комплексный подход к вашему вопросу, своевременная правовую помощь, представление интересов во всех
              судебных инстанциях.
            </div>
          </div>
          <!--  Форма заполнения данных клиентом -->
          <div class="form__box">
            <form>
              <div class="form__box-inner">
                <!-- Объединение всех полей для заполнения в одном блоке  -->
                <div class="form__box-left">
                  <!-- Поле для заполнения E-mail  -->
                  <label>
                    E-mail
                    <input type="text">
                  </label>
                  <!-- Поле для заполнения контактного телефона  -->
                  <label>
                    Контактный телефон
                    <input type="text">
                  </label>
                  <!-- Поле для заполнения ФИО -->
                  <label>
                    ФИО
                    <input type="text">
                  </label>
                  <!-- Выпадаюий список вопросов -->
                  <label>
                    Тема вопроса
                    <select>
                      <option>-------------</option>
                      <option>-------------</option>
                      <option>-------------</option>
                      <option>-------------</option>
                    </select>
                  </label>
                </div>
                <div class="form__box-right">
                  <!-- Многострочное текстовое поле -->
                  <label>
                    Сообщение
                    <textarea></textarea>
                  </label>
                  <!-- Кнопка получить консультацию -->
                  <button class="default-btn" type="submit">Получить консультацию</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Вёрстка достижений  -->
  <section class="advantages">
    <!-- Ограничение всех элементо по ширине -->
    <div class="container">
      <div class="advantages__inner">
        <!-- Первое достижение -->
        <div class="advantages-item">
          <!-- Заголовок -->
          <div class="advantages__title">
            Десятки добровольных ликвидаций ежемесячно
          </div>
          <!-- Описание достижения -->
          <div class="advantages__text">
            Мы умеем минимизировать все риски в процессе добровольной ликвидации юридических лиц.
          </div>
        </div>
        <!-- Второе достижение -->
        <div class="advantages-item">
          <!-- Заголовок -->
          <div class="advantages__title">
            Отличное знание законов в сфере банкротства
          </div>
          <!-- Описание достижения -->
          <div class="advantages__text">
            Позволяют нам эффективно отстаивать как интересы кредиторов, так и интересы собственников проблемной
            организации.
          </div>
        </div>
        <!-- Третье достижение -->
        <div class="advantages-item">
          <!-- Заголовок -->
          <div class="advantages__title">
            Большой опыт сопровождения банкротства
          </div>
          <!-- Описание достижения -->
          <div class="advantages__text">
            Мы обладаем большим опытом сопровождения процедур банкротства предприятий.
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Вёрстка новостей  -->
  <section class="news">
    <!-- Ограничение всех элементо по ширине -->
    <div class="container">
      <!-- Верхняя часть блока новостей -->
      <div class="news__top">
        <div class="news__title-box">
          <!-- Заголовок -->
          <div class="news__title">
            Новости Компании
          </div>
          <div class="news__text">
            Комплексный подход к вашему вопросу, своевременная правовую помощь, представление интересов во всех судебных
            инстанциях.
          </div>
        </div>
        <!--  Кнопка открыть все новости -->
        <div class="news__btn">
          <a href="#">
            Открыть все новости
          </a>
        </div>
      </div>
      <div class="news__inner">
        <!-- Слайдер новостей -->
        <div class="news__slider">
          <div class="news__slider-inner">
            <!-- Статья 1 -->
            <div class="news__slider-item">
              <!-- Заголовок -->
              <div class="news__slider-title">
                Банкротство и ликвидация предприятия в Украине
              </div>
              <!-- Контент -->
              <div class="news__slider-text">
                «На сегодняшний день, коллектив компании объединяет высокопрофессиональных экспертов имеющих
                специализации в отдельных областях права. На сегодняшний день, коллектив компании объединяет
                высокопрофессиональных экспертов имеющих специализации в отдельных областях права. На сегодняшний день,
                коллектив компании объединяет высокопрофессиональных экспертов имеющих специализации в отдельных
                областях права...»
              </div>
              <div class="news__slider-author">
                Андрей Ворошилов, генеральный директор компании Bankom
              </div>
            </div>
            <!-- Статья 2 -->
            <div class="news__slider-item">
              <!-- Заголовок -->
              <div class="news__slider-title">
                Банкротство и ликвидация предприятия в Украине
              </div>
              <!-- Контент -->
              <div class="news__slider-text">
                «На сегодняшний день, коллектив компании объединяет высокопрофессиональных экспертов имеющих
                специализации в отдельных областях права. На сегодняшний день, коллектив компании объединяет
                высокопрофессиональных экспертов имеющих специализации в отдельных областях права. На сегодняшний день,
                коллектив компании объединяет высокопрофессиональных экспертов имеющих специализации в отдельных
                областях права...»
              </div>
              <div class="news__slider-author">
                Андрей Ворошилов, генеральный д иректор компании Bankom
              </div>
            </div>
            <!-- Статья 3 -->
            <div class="news__slider-item">
              <!-- Заголовок -->
              <div class="news__slider-title">
                Банкротство и ликвидация предприятия в Украине
              </div>
              <!-- Контент -->
              <div class="news__slider-text">
                «На сегодняшний день, коллектив компании объединяет высокопрофессиональных экспертов имеющих
                специализации в отдельных областях права. На сегодняшний день, коллектив компании объединяет
                высокопрофессиональных экспертов имеющих специализации в отдельных областях права. На сегодняшний день,
                коллектив компании объединяет высокопрофессиональных экспертов имеющих специализации в отдельных
                областях права...»
              </div>
              <div class="news__slider-author">
                Андрей Ворошилов, генеральный д иректор компании Bankom
              </div>
            </div>
          </div>
        </div>
        <!-- Ссылка на новость 1 -->
        <a href="#" class="news__blog">
          <!-- Изображение 1 новости -->
          <div class="news__images">
            <img src="img/news-1.jpg" alt="">
            <div class="news__date">03.04</div>
          </div>
          <!-- Заголок -->
          <div class="news__blog-title">
            Новость компании
          </div>
          <!-- Контент -->
          <div class="news__blog-text">
            На сегодняшний день, коллектив компании объединяет высокопрофессиональных экспертов имеющих специализации в
            отдельных областях права...»
          </div>
        </a>
        <!-- Ссылка на новость 1 -->
        <a href="#" class="news__blog">
          <!-- Изображение 2 новости -->
          <div class="news__images">
            <img src="img/news-2.jpg" alt="">
            <div class="news__date">03.04</div>
          </div>
          <!-- Заголок -->
          <div class="news__blog-title">
            Новость компании
          </div>
          <!-- Контент -->
          <div class="news__blog-text">
            На сегодняшний день, коллектив компании объединяет высокопрофессиональных экспертов имеющих специализации в
            отдельных областях права...»
          </div>
        </a>
      </div>
    </div>
  </section>

  <!-- Вёрстка футера -->
  <footer class="footer">
    <div class="footer__content">
      <!-- Ограничение всех элементо по ширине -->
      <div class="container">
        <!-- Объединение сех контактных данных компании в обном блоке -->
        <div class="footer__inner">
          <!-- Контакты компании -->
          <div class="footer__info">
            <div class="footer__title">
              Комплексное закрытие предприятия
            </div>
            <div class="footer__text">
              Полное прекращение существования юридического лица с сохранением легальности всей предыдущей деятельности.
            </div>
            <!-- Кнопка бесплатная консультация -->
            <a data-fancybox data-src="#modal" href="javascript:;" class="header__btn" href="#">
              Бесплатная консультация
            </a>
            <!-- Список контактных данных компании -->
            <ul class="footer__list">
              <!-- Номер телефона -->
              <li><a class="footer__phone" href="tel:380963092145">+38 (096) 309 21 45</a></li>
              <!-- Адресс электронной почты -->
              <li><a href="#">layout585@gmail.com</a></li>
              <!-- Адресс -->
              <li><a class="footer__adress" href="#">Киев, ул.Пушиной, 13</a></li>
            </ul>
          </div>
          <!-- Гугл карта -->
          <div class="footer__map">
            <iframe height="250px" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2540.124391996489!2d30.364922015731644!3d50.457408279476354!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40d4cc919501b4ef%3A0x71a476f68f4c8246!2z0YPQuy4g0KTQtdC-0LTQvtGA0Ysg0J_Rg9GI0LjQvdC-0LksIDEzLCDQmtC40LXQsiwgMDIwMDA!5e0!3m2!1sru!2sua!4v1555013165886!5m2!1sru!2sua" frameborder="0" style="border:0" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </div>
    <!-- Копирайт -->
    <div class="footer__copy">
      <!-- Ограничение всех элементо по ширине -->
      <div class="container">
        <div class="copy__text">
          © 2020 Template by Anastasia Shaposhnyk. Все права защищены.
        </div>
      </div>
    </div>
  </footer> 

  <!-- Модальное окно при нажатии на кнопку бесплантная консультация -->
  <div id="modal">
    <form>
      <input type="text" placeholder="Ваше имя">
      <input type="text" placeholder="Ваш телефон">
      <input type="submit" value="Отправить">
    </form>
  </div>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="js/jquery.fancybox.min.js"></script>
  <script src="js/slick.min.js"></script>
  <script src="js/jquery.formstyler.min.js"></script>
  <script src="js/main.js"></script>

</body>

</html>
```
