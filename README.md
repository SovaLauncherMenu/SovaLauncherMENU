<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SovaLauncher</title>
<style>
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
 margin:0;background:#101113;color:#f4f4f5;
 font-family:Arial,sans-serif;
}
header{
 padding:20px 7%;display:flex;
 justify-content:space-between;align-items:center;
 border-bottom:1px solid #303034;
}
.logo{font-size:23px;font-weight:bold}
.logo span{color:#92979f}
nav a{color:#bbb;text-decoration:none;margin-left:18px}
.hero{
 min-height:440px;padding:90px 20px;
 text-align:center;
 background:radial-gradient(ellipse,#303239 0%,#101113 70%);
}
.owl{font-size:65px}
h1{font-size:clamp(40px,8vw,72px);margin:15px 0}
h1 span{color:#92979f}
p{color:#b3b5bb;line-height:1.7}
.hero p{max-width:580px;margin:20px auto}
.btn{
 display:inline-block;padding:14px 23px;
 background:#e6e6e8;color:#111;
 border-radius:9px;text-decoration:none;
 font-weight:bold;margin:8px;
}
.btn.dark{background:#25262a;color:white;border:1px solid #444}
section{padding:55px 7%;text-align:center}
h2{font-size:30px}
.cards{
 display:grid;grid-template-columns:repeat(3,1fr);
 gap:18px;margin-top:30px;text-align:left;
}
.card{
 background:#1b1c20;border:1px solid #303136;
 border-radius:15px;padding:24px;
}
.card .icon{font-size:30px}
.card h3{margin-bottom:10px}
.card p{font-size:14px}
.download{
 max-width:650px;margin:25px auto;
 padding:25px;background:#1b1c20;
 border:1px solid #36373c;border-radius:15px;
}
footer{
 padding:25px;text-align:center;
 border-top:1px solid #303034;color:#85858c;
}
@media(max-width:650px){
 header{padding:16px 5%;flex-wrap:wrap;gap:12px}
 nav a{margin-left:8px;font-size:13px}
 .hero{padding:65px 16px}
 .cards{grid-template-columns:1fr}
 section{padding:40px 5%}
}
</style>
</head>
<body>

<header>
 <div class="logo">🦉 Sova<span>Launcher</span></div>
 <nav>
  <a href="#features">Возможности</a>
  <a href="#download">Скачать</a>
 </nav>
</header>

<main>
 <div class="hero">
  <div class="owl">🦉</div>
  <h1>Sova<span>Launcher</span></h1>
  <p>
   Твой Minecraft. Твои правила.
   Современный лаунчер с тёмным дизайном,
   сборками и удобным запуском игры.
  </p>
  <a class="btn" href="#download">Скачать лаунчер ↓</a>
  <a class="btn dark"
     href="https://github.com/SovaLauncherMenu">
     Мой GitHub ↗
  </a>
 </div>

 <section id="features">
  <h2>Возможности</h2>
  <p>Добро пожаловать в мир SovaLauncher</p>
  <div class="cards">
   <div class="card">
    <div class="icon">🌑</div>
    <h3>Тёмный дизайн</h3>
    <p>Стильный серый интерфейс и минималистичное оформление.</p>
   </div>
   <div class="card">
    <div class="icon">🎮</div>
    <h3>Сборки Minecraft</h3>
    <p>Добавляй информацию о своих сборках и игровых версиях.</p>
   </div>
   <div class="card">
    <div class="icon">🦉</div>
    <h3>Обновления</h3>
    <p>Следи за развитием проекта и новыми функциями.</p>
   </div>
  </div>
 </section>

 <section id="download">
  <h2>Скачать SovaLauncher</h2>
  <div class="download">
   <h3>Версия для Windows</h3>
   <p>
    Скоро здесь появится установщик SovaLauncher.
    Ссылка станет рабочей после публикации EXE.
   </p>
   <a class="btn"
      href="https://github.com/SovaLauncherMenu">
      Перейти на GitHub
   </a>
  </div>
 </section>
</main>

<footer>
 © 2026 SovaLauncher · SovaLauncherMenu
</footer>

</body>
</html>
