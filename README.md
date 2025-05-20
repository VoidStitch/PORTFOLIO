# PORTFOLIO
<!DOCTYPE html><html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Портфолио Пустотного</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }
    body {
      background-color: #121212;
      color: #e0e0e0;
      line-height: 1.6;
      animation: fadeInBody 1.2s ease-in;
    }
    @keyframes fadeInBody {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    header {
      background: #1f1f1f;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #333;
      animation: slideDown 1s ease;
    }
    @keyframes slideDown {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    header h1 {
      font-size: 2.5rem;
      color: #ffcc70;
      animation: fadeInText 1.5s ease;
    }
    nav {
      margin-top: 10px;
      animation: fadeInNav 1.5s ease;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #aaa;
      transition: color 0.3s;
      font-size: 1rem;
    }
    nav a:hover {
      color: #ffcc70;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .about {
      background-color: #1b1b1b;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 0 10px #000;
      animation: fadeUp 1.2s ease;
    }
    .about h2 {
      color: #ffcc70;
      margin-bottom: 20px;
    }
    .about p {
      animation: fadeUp 1.5s ease;
    }
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
      animation: fadeInGrid 1.2s ease-in-out;
    }
    @keyframes fadeInGrid {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
      border: 2px solid #333;
      object-fit: cover;
      height: 200px;
      transition: transform 0.3s, box-shadow 0.3s;
      animation: popIn 0.8s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 10px #ffcc70;
    }
    @keyframes popIn {
      from { transform: scale(0.9); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
    .contact {
      background-color: #1b1b1b;
      margin-top: 40px;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
      animation: fadeUp 1.2s ease;
    }
    .contact h2 {
      color: #ffcc70;
      margin-bottom: 15px;
    }
    .contact a.telegram-button {
      display: inline-block;
      margin-top: 10px;
      background: #0088cc;
      color: white;
      padding: 12px 25px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s, transform 0.3s;
      animation: popIn 0.9s ease;
    }
    .contact a.telegram-button:hover {
      background: #0075b0;
      transform: scale(1.05);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #1f1f1f;
      border-top: 2px solid #333;
      color: #777;
      animation: fadeInBody 1.2s ease-in;
    }@media (max-width: 768px) {
  header h1 {
    font-size: 2rem;
  }
  nav a {
    display: inline-block;
    margin: 5px;
    font-size: 0.95rem;
  }
  .gallery img {
    height: 150px;
  }
}

@media (max-width: 480px) {
  header h1 {
    font-size: 1.5rem;
  }
  nav a {
    font-size: 0.85rem;
  }
  .contact a.telegram-button {
    padding: 10px 20px;
    font-size: 0.9rem;
  }
}

  </style>
</head>
<body>
  <header>
    <h1>Портфолио Пустотного</h1>
    <nav>
      <a href="#about">Обо мне</a>
      <a href="#works">Мои работы</a>
      <a href="#contact">Связь</a>
    </nav>
  </header>  <section id="about" class="about">
    <h2>Обо мне</h2>
    <p>Привет! Меня зовут Пустотный. Я начинающий дизайнер и только начинаю свой путь в этой сфере. Параллельно я обучаюсь на химико-биологическом курсе, что помогает мне смотреть на вещи с разных сторон.</p>
    <p>Кроме дизайна, я увлекаюсь созданием Telegram-ботов — и могу помочь с этим, если нужно. Спасибо за интерес к моему портфолио!</p>
  </section>  <section id="works">
    <h2 style="color:#ffcc70; text-align:center; margin-bottom: 30px; animation: fadeIn 1s ease-in-out;">Мои работы</h2>
    <div class="gallery">
      <img src="work1.jpg" alt="Работа 1">
      <img src="work2.jpg" alt="Работа 2">
      <img src="work3.jpg" alt="Работа 3">
      <img src="work4.jpg" alt="Работа 4">
      <img src="work5.jpg" alt="Работа 5">
      <img src="work6.jpg" alt="Работа 6">
      <img src="work7.jpg" alt="Работа 7">
      <img src="work8.jpg" alt="Работа 8">
      <img src="work9.jpg" alt="Работа 9">
      <img src="work10.jpg" alt="Работа 10">
      <img src="work11.jpg" alt="Работа 11">
      <img src="work12.jpg" alt="Работа 12">
      <img src="work13.jpg" alt="Работа 13">
      <img src="work14.jpg" alt="Работа 14">
      <img src="work15.jpg" alt="Работа 15">
    </div>
  </section>  <section id="contact" class="contact">
    <h2>Связаться со мной</h2>
    <p>Можешь написать мне напрямую в Telegram:</p>
    <a href="https://t.me/CTYDEHTUK" class="telegram-button">@CTYDEHTUK</a>
    <a href="https://t.me/VoidStitch" class="telegram-button" style="margin-left:10px">@VoidStitch</a>
  </section>  <footer>
    <p>&copy; 2025 Пустотный — начинающий дизайнер</p>
  </footer>
</body>
</html>
