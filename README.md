<!DOCTYPE html>
<html lang="uk">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Сучасна пекарня</title>
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;900&display=swap"
      rel="stylesheet"
    />
    <!-- Styles -->
    <link rel="stylesheet" href="./css/Styles.css" />
  </head>
  <body>
    <header class="header">
      <div class="container">
        <div class="header-container">
          <nav class="header-nav">
            <a href="Beginning.html">
              <img src="./Images/logo.svg" alt="Логотип сучасної пекарні" />
            </a>
            <ul class="header-menu">
              <li>
                <a class="link" href="#traditions-section">Наші традиції</a>
              </li>
              <li><a class="link" href="#chefs-section">Шеф-кухарі</a></li>
              <li><a class="link" href="#formats-section">Формати</a></li>
              <li><a class="link" href="#contacts-section">Контакти</a></li>
            </ul>
          </nav>
          <button class="button" type="button">Замовити дзвінок</button>
        </div>
      </div>
    </header>
    <main>
      <section class="hero-section">
        <div class="container">
          <h1 class="hero-title">
            <span class="accent">Сучасна</span> пекарня
          </h1>
        </div>
      </section>
      <section class="advantages-section">
        <div class="container">
          <h2 class="visually-hidden">Наші переваги</h2>
          <ul class="advantages-list">
            <li class="advantages-item">Доступні за бюджетом формати</li>
            <li class="advantages-item">Досвідчена управлінська команда</li>
            <li class="advantages-item">Великий попит на ринку</li>
          </ul>
        </div>
      </section>
      <section class="traditions-section section" id="traditions-section">
        <div class="container">
          <div class="tradition-container">
            <div class="tradition-content">
              <h2 class="tradition-title section-title">
                Новий формат традицій
              </h2>
              <p class="traditions-text">
                <span class="uppercase">shop bakery</span> — це пекарня, яка
                взяла все найкраще, і зберегла смак традиційної випічки та
                натуральність інгредієнтів.
              </p>
              <p class="traditions-text limited">
                Ми працюємо як найвідоміші мережі—
                <span class="brand">5 хвилин і замовлення готове.</span>
                А ще у наших пекарень стильний дизайн та висока якість
                обслуговування!
              </p>
            </div>
            <img
              src="./Images/Backeryman.jpg"
              alt="Чоловік пекар дивиться з посмішкою на батони"
            />
          </div>
        </div>
      </section>
      <section class="section" id="chefs-section">
        <div class="container">
          <h2 class="chefs-title section-title">
            Наші найкращі <span class="accent">шеф-кухарі</span>
          </h2>
          <ul>
            <li>
              <article>
                <h3 class="chef-title">Настя</h3>
                <p>Привіт, я Настя!</p>
                <p>Вже 10 років, я свтілюю у життя цікаві та смачні ідеї.</p>
                <p>Я випічу для вас найсмачніщі вироби!</p>
              </article>
            </li>
            <li>
              <article>
                <h3 class="chef-title">Влад</h3>
                <p>Привіт, я Влад!</p>
                <p>
                  Мій кодитерський стаж вже 18 років. SHOP BEKERY - це наша
                  любов, з якою ми ділимось кожен раз з Вами через нашу випічку!
                </p>
                <p>Я зроблю для вас унікальну начинку на будь який смак!</p>
              </article>
            </li>
          </ul>
        </div>
      </section>
      <section class="section" id="formats-section">
        <div class="container">
          <h2 class="formats-title section-title">Формати</h2>
          <ul class="format-list">
            <li class="format-item">
              <article class="format-card">
                <h3 class="format-title">Walrus</h3>
                <div class="format-text">
                  <p>Площа: до 120 м2</p>
                  <p>Меню: розширене меню</p>
                  <p>
                    Штат: 2 продавці-касири, 2 пекарі, 2 помічники пекаря, 2
                    офіціанти-різнороби
                  </p>
                  <p>Посадкові місця: є</p>
                </div>
              </article class="format-card">
            </li>
            <li class="format-item">
              <article>
                <h3 class="format-title">Horseshoe</h3>
                <div class="format-text">
                  <p>Площа: до 25 м2</p>
                  <p>Меню: найпопулярніші позиції меню</p>
                  <p>Штат: 2 продавці-касири, 2 пекарі, 1 помічник пекаря</p>
                  <p>Посадкові місця: відсутні</p>
                </div>
              </article>
            </li>
            <li class="format-item">
              <article class="format-card">
                <h3 class="format-title">Handlebar</h3>
                <div class="format-text">
                  <p>Площа: до 15 м2</p>
                  <p>Меню: найпопулярніші позиції меню</p>
                  <p>Штат: 1 продавець, 1 пекар, 1 помічник пекаря</p>
                  <p>Посадкові місця: відсутні</p>
                </div>
              </article>
            </li>
          </ul>
        </div>
      </section>
      <section class="section" id="contact-section">
        <div class="container">
          <h2 class="contact-title section-title">
            Приєднуйся до мережі пекарень
          </h2>
          <p>Заповни форму, щоб ми звʼязались з тобою!</p>
          <iframe
            src="https://maps.app.goo.gl/mjWwkDeYJMgSfQJa6"
            frameborder="0"
            width="603"
            height="595"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
      </section>
    </main>
    <footer>
      <div class="container">
        <nav>
          <a href="a">
            <img src="./Images/logo.svg" alt="Логотип сучасної пекарні" />
          </a>
          <ul>
            <li><a class="link" href="#">Наші традиції</a></li>
            <li><a class="link" href="#">Шеф-кухарі</a></li>
            <li><a class="link" href="#">Формати</a></li>
            <li><a class="link" href="#">Контакти</a></li>
          </ul>
        </nav>
        <address>
          <ul>
            <li>
              <a class="address-link" href="tel:+380960000007"
                >+ 38 (096) 000 00 07</a
              >
            </li>
            <li>
              <a class="address-link" href="mailto:shopbakery@gmail.com"
                >shopbakery@gmail.com</a
              >
            </li>
            <li>
              <a
                class="address-link"
                href="https://maps.app.goo.gl/P4e2wpjtsCcSokCW6"
                target="_blank"
                >Україна, м. Київ, вул. Січових Стрільців 54</a
              >
            </li>
            <li>
              <a href="f">
                <!-- facebook item -->
              </a>
            </li>
            <li>
              <a href="in">
                <!-- instugram item -->
              </a>
            </li>
          </ul>
          <a class="address-link" href="#" target="_blank"
            >Політика конфіденційності</a
          >
          <p class="address-copyright">&copy; 2022 Дані захищені</p>
        </address>
      </div>
    </footer>
  </body>
</html>
