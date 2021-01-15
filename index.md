<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Purelogic. Research and development</title>
    <link rel="stylesheet" href="styles/fonts.css" />
    <link rel="stylesheet" href="styles/global.css" />
    <link rel="stylesheet" href="styles/style.css" />
  </head>
  <body class="page">
    <div class="page-menu">
      <nav class="menu-nav">
        <div class="menu-nav__logo-wrapper">
          <a class="menu-nav__logo" aria-label="Purelogic">
            <img
              class="menu-nav__logo-icon"
              src="img/logo-mobile.svg"
              alt="Логотип сайта Purelogic"
          /></a>
        </div>
        <ul class="menu-list">
          <li class="menu-navigation__item menu-navigation__link--machine-tool">
            <a class="menu-navigation__link" href="#">Станки с ЧПУ DIY</a>
          </li>
          <li
            class="menu-navigation__item menu-navigation__link--mechantronics"
          >
            <a class="menu-navigation__link" href="#">Мехатроника</a>
          </li>
          <li
            class="menu-navigation__item menu-navigation__link--mechantronics"
          >
            <a class="menu-navigation__link" href="#">Термическая резка</a>
          </li>
          <li
            class="menu-navigation__item menu-navigation__link--mechantronics"
          >
            <a class="menu-navigation__link" href="#">Наборы ЧПУ</a>
          </li>
        </ul>
      </nav>
    </div>
    <header class="page-header">
      <div class="user-nav">
        <ul class="menu-items">
          <li class="menu-items-link menu-items-link__opened about">
            <a class="menu-items-link__title" href="#">О компании</a>
          </li>
          <li class="menu-items-link menu-items-link__opened buyer">
            <a class="menu-items-link__title" href="#">Покупателю</a>
          </li>
          <li class="menu-items-link sale">
            <a class="menu-items-link__title" href="#">Акции</a>
          </li>
          <li class="menu-items-link support">
            <a class="menu-items-link__title" href="#">Поддержка и сервис</a>
          </li>
          <li class="menu-items-link contacts">
            <a class="menu-items-link__title" href="#">Контакты</a>
          </li>
        </ul>
        <div class="search-container">
          <form>
            <input
              type="text"
              placeholder="Что вы ищете..."
              name="search"
              class="search-container__input"
            />
            <button class="search-container__button" type="submit">
              Поиск
            </button>
          </form>
        </div>
      </div>
      <div class="flex-box">
      <div class="user-menu">
        <ul class="user-items">
          <li class="user-items-link">
            <a class="user-items-link__title about-icon" href="#">
              <span>Кабинет</span></a
            >
          </li>
          <li class="user-items-link">
            <a class="user-items-link__title favorite-icon" href="#">
              <span>Избранное</span></a
            >
          </li>
          <li class="user-items-link">
            <a class="user-items-link__title compare-icon" href="#">
              <span>Сравнение</span></a
            >
          </li>
          <li class="user-items-link">
            <a class="user-items-link__title basket-icon" href="#">
              <span>Корзина</span></a
            >
          </li>
        </ul>
      </div>
      <div class="info">
        <span class="info__title">Бесплатно по РФ</span>
        <a class="info__tel" href="tel:8 800 555-63-74">8 800 555-63-74</a>
        <a href="tel:8 800 555-63-74" class="info__location"><u>Москва</u></a>
      </div>
      <div class="call">
        <button
          class="call__button"
          id="call-button"
          type="button"
          aria-label="Заказать консультацию"
        >
            Запросить <br> консультацию
        </button>
      </div>
    </div>
    </header>
    <header class="page-header__mobile">
      <nav class="main-nav">
        <div class="main-nav__logo-wrapper">
          <a class="main-nav__logo header-logo" aria-label="Purelogic">
            <img
              class="header-logo__image"
              src="img/logo-mobile.svg"
              width="143"
              height="25"
              alt="Логотип сайта Purelogic" /></a
          ><button
            class="main-nav__toggle main-nav__toggle--off"
            id="toggle-button"
            type="button"
            aria-label="Меню"
          ></button>
        </div>
        <ul class="main-nav__user-list">
          <li class="user-navigation__item">
            <a
              class="user-navigation__link user-navigation__link--search"
              href="#"
              ><svg
                class="user-navigation__link-image"
                width="19"
                height="19"
              ></svg
            ></a>
          </li>
          <li class="user-navigation__item">
            <a
              class="user-navigation__link user-navigation__link--account"
              href="#"
              ><svg
                class="user-navigation__link-image"
                width="18"
                height="20"
              ></svg
            ></a>
          </li>
          <li class="user-navigation__item">
            <a
              class="user-navigation__link user-navigation__link--favorite"
              href="#"
              ><svg
                class="user-navigation__link-image"
                width="14"
                height="21"
              ></svg
            ></a>
          </li>
          <li class="user-navigation__item">
            <a
              class="user-navigation__link user-navigation__link--compare"
              href="#"
              ><svg
                class="user-navigation__link-image"
                width="16"
                height="21"
              ></svg
            ></a>
          </li>
          <li class="user-navigation__item">
            <a
              class="user-navigation__link user-navigation__link--basket"
              href="#"
              ><svg
                class="user-navigation__link-image"
                width="20"
                height="19"
              ></svg
            ></a>
          </li>
          <li class="user-navigation__item">
            <button
              class="main-nav__button"
              id="consultation-button"
              type="button"
              aria-label="Заказать консультацию"
            >
              Консультация
            </button>
          </li>
        </ul>
      </nav>
    </header>
    <script src="js/index.js"></script>
  </body>
</html>
