<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Приглашение на свадьбу</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f2f2f2;
      color: #333;
      overflow-x: hidden;
    }

    section {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 60px 20px;
      opacity: 0;
      transform: translateY(40px);
      transition: all 1s ease;
    }

    section.show {
      opacity: 1;
      transform: translateY(0);
    }

    .card {
      max-width: 900px;
      width: 100%;
      text-align: center;
    }

    /* 1 block */
    .hero {
      position: relative;
      background: url('https://vk.com/away.php?to=https%3A%2F%2Fsun9-39.userapi.com%2Fs%2Fv1%2Fig2%2F7Z1uaBwNBCQ7WtjMt9vriTJbjQFEOIP-SDWu7s7qftnWk1NhlfTPS-FszPgoGgMYSIsvSKHeUbP2CEVkujuEtXB6.jpg%3Fquality%3D95%26as%3D32x48%2C48x72%2C72x108%2C108x162%2C160x240%2C240x360%2C360x540%2C480x720%2C540x810%2C640x960%2C720x1080%2C1080x1620%2C1280x1920%2C1440x2160%2C1600x2400%26from%3Dbu%26u%3Dh3LnsgLuCPFP2nIkT4zHF8EPsv19ikBM39-inDOoa4Y%26cs%3D640x0&utf=1') center/cover fixed;
}

    .hero::after {
      content: '';
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.5);
    }

    .hero-content {
      position: relative;
      z-index: 2;
    }

    h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }

    p {
      font-size: 18px;
      line-height: 1.6;
    }

    /* countdown */
    .countdown {
      font-size: 32px;
      margin-top: 20px;
    }

    /* timeline */
    .timeline {
      display: flex;
      flex-direction: column;
      gap: 15px;
      font-size: 18px;
      align-items: center;
    }

    .timeline span {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    /* dress code circles */
    .colors {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin-top: 20px;
    }

    .color {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      border: 2px solid #333;
    }

    .pink { background: #f7c6d0; }
    .blue { background: #bcdffb; }
    .yellow { background: #fff3b0; }
    .green { background: #cfe8c9; }
    .olive { background: #a3b18a; }

    /* button */
    .btn {
      padding: 15px 25px;
      background: #333;
      color: white;
      border: none;
      cursor: pointer;
      margin-top: 20px;
      text-decoration: none;
      display: inline-block;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: none;
      margin-top: 20px;
    }

  </style>
</head>
<body>

<!-- 1 -->
<section class="hero show">
  <div class="hero-content">
    <h1>Дарья & Сергей</h1>
    <p>
      Дорогие наши родные и друзья!<br><br>
      Позвольте пригласить вас разделить с нами столь важный день - торжество посвященное нашему бракосочетанию.<br><br>
      Наша свадьба состоится:
    </p>
  </div>
</section>

<!-- 2 -->
<section>
  <div class="card">
    <h2>20 августа 2026</h2>
    <p>📍 Белгород</p>
    <div class="countdown" id="countdown"></div>
    <img src="https://vk.com/away.php?to=https%3A%2F%2Fsun9-39.userapi.com%2Fs%2Fv1%2Fig2%2F7Z1uaBwNBCQ7WtjMt9vriTJbjQFEOIP-SDWu7s7qftnWk1NhlfTPS-FszPgoGgMYSIsvSKHeUbP2CEVkujuEtXB6.jpg%3Fquality%3D95%26as%3D32x48%2C48x72%2C72x108%2C108x162%2C160x240%2C240x360%2C360x540%2C480x720%2C540x810%2C640x960%2C720x1080%2C1080x1620%2C1280x1920%2C1440x2160%2C1600x2400%26from%3Dbu%26u%3Dh3LnsgLuCPFP2nIkT4zHF8EPsv19ikBM39-inDOoa4Y%26cs%3D640x0&utf=1" style="width:100%; margin-top:20px; border-radius:10px;" />
  </div>
</section>

<!-- 3 timeline -->
<section>
  <div class="card">
    <h2>Тайминг мероприятия</h2>
    <div class="timeline">
      <span>12:00 → Церемония бракосочетания</span>
      <span>13:00 → Прогулка + фотосессия</span>
      <span>17:00 → Свадебный ужин</span>
      <span>23:00 → Завершение вечера</span>
    </div>
  </div>
</section>

<!-- 4 location -->
<section>
  <div class="card">
    <h2>Место проведения</h2>
    <p>Управление ЗАГС</p>
    <p>Белгород, улица Попова, 14</p>

    <iframe src="https://www.google.com/maps?q=Белгород%20Попова%2014&output=embed"></iframe>
  </div>
</section>

<!-- 5 dress code -->
<section class="hero">
  <div class="hero-content">
    <h2>Дресс-код</h2>
    <p>
      Мы очень ждём наше торжество и с удовольствием готовимся к этому незабываемому дню.<br><br>
      Нам было бы очень приятно, если бы вы выбрали наряды в этой цветовой гамме
    </p>

    <div class="colors">
      <div class="color pink"></div>
      <div class="color blue"></div>
      <div class="color yellow"></div>
      <div class="color green"></div>
      <div class="color olive"></div>
    </div>
  </div>
</section>

<!-- 6 RSVP -->
<section>
  <div class="card">
    <h2>Подтвердите присутствие</h2>
    <a class="btn" href="(https://forms.gle/wBGfkj6pEau3Drqj9)">Подтвердить участие</a>
  </div>
</section>

<!-- 7 end -->
<section>
  <div class="card">
    <h2>С нетерпением ждём вас!</h2>
  </div>
</section>

<script>
  // countdown
  const weddingDate = new Date("2026-08-20T00:00:00").getTime();

  const x = setInterval(function () {
    const now = new Date().getTime();
    const distance = weddingDate - now;

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    document.getElementById("countdown").innerHTML =
      days + "д " + hours + "ч " + minutes + "м " + seconds + "с ";

    if (distance < 0) {
      clearInterval(x);
      document.getElementById("countdown").innerHTML = "Свадьба началась!";
    }
  }, 1000);

  // scroll animation
  const sections = document.querySelectorAll("section");

  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add("show");
      }
    });
  }, { threshold: 0.2 });

  sections.forEach(sec => observer.observe(sec));
</script>

</body>
</html>

