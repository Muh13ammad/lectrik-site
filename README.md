<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Профессиональный электрик</title>
  <style>
    /* Сброс стилей */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    header {
      background: #333;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
    }
    nav ul li {
      margin: 0 1rem;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .banner {
      background: url('https://via.placeholder.com/1500x500') no-repeat center center/cover;
      height: 500px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
    }
    .banner h1 {
      font-size: 3rem;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 2rem;
    }
    section {
      margin-bottom: 2rem;
    }
    h2 {
      margin-bottom: 1rem;
      color: #333;
    }
    .services .service-item {
      background: #f4f4f4;
      padding: 1rem;
      margin-bottom: 1rem;
      border-radius: 5px;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
    @media (min-width: 768px) {
      .services {
        display: flex;
        gap: 1rem;
      }
      .services .service-item {
        flex: 1;
      }
    }
  </style>
</head>
<body>
  <!-- Шапка сайта -->
  <header>
    <nav>
      <ul>
        <li><a href="#home">Главная</a></li>
        <li><a href="#about">О мастере</a></li>
        <li><a href="#services">Услуги</a></li>
        <li><a href="#contact">Контакты</a></li>
      </ul>
    </nav>
  </header>

  <!-- Баннер -->
  <section id="home" class="banner">
    <h1>Профессиональный электрик</h1>
  </section>

  <div class="container">
    <!-- О мастере -->
    <section id="about">
      <h2>О мастере</h2>
      <p>Здравствуйте! Я профессиональный электрик с многолетним опытом. Гарантирую высокое качество обслуживания, соблюдение сроков и разумные цены.</p>
    </section>

    <!-- Услуги -->
    <section id="services">
      <h2>Услуги</h2>
      <div class="service-item">
        <h3>Электромонтаж</h3>
        <p>Выполняю монтаж и ремонт электропроводки в квартирах, домах и коммерческих объектах.</p>
      </div>
      <div class="service-item">
        <h3>Диагностика и ремонт</h3>
        <p>Провожу диагностику и устранение неисправностей в электросистемах.</p>
      </div>
      <div class="service-item">
        <h3>Установка осветительного оборудования</h3>
        <p>Подберу и установлю осветительные приборы для вашего дома или офиса.</p>
      </div>
    </section>

    <!-- Контакты -->
    <section id="contact">
      <h2>Контакты</h2>
      <p>Свяжитесь со мной для консультации и заказа услуг:</p>
      <ul>
        <li>Телефон: <a href="tel:+71234567890">+7 (123) 456-78-90</a></li>
        <li>Email: <a href="mailto:elektrik@example.com">elektrik@example.com</a></li>
      </ul>
      <p>Или отправьте сообщение через форму ниже:</p>
      <form action="#" method="post">
        <label for="name">Имя:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Сообщение:</label><br>
        <textarea id="message" name="message" rows="4" required></textarea><br><br>
        <button type="submit">Отправить</button>
      </form>
    </section>
  </div>

  <!-- Футер -->
  <footer>
    <p>&copy; 2025 Электрик. Все права защищены.</p>
  </footer>
</body>
</html>
