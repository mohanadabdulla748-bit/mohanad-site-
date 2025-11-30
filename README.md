<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>مهند لصيانة الكهرباء والنظافة</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header class="site-header">
  <div class="container">
    <h1 class="logo">مهند لصيانة الكهرباء والنظافة</h1>
    <nav class="nav">
      <a href="index.html">الرئيسية</a>
      <a href="services.html">خدماتنا</a>
      <a href="contact.html">تواصل معنا</a>
    </nav>
  </div>
</header>
<main class="container main">
  <section class="hero">
    <h2>خدمات كهرباء وسباكة وتنظيف منازل ومكاتب بسرعة ومهارة</h2>
    <p>فريق محترف يقدم صيانة أعطال الكهرباء، تمديدات، تنظيف شامل، وصيانة عامة.</p>
    <a class="btn" href="tel:0126663438">اتصل الآن 0126663438</a>
    <a class="btn btn-outline" href="contact.html">أرسل رسالة</a>
  </section>
  <section class="features">
    <article>
      <h3>صيانة الكهرباء</h3>
      <p>إصلاح أعطال، تغيير مفاتيح ومآخذ، تمديدات كاملة.</p>
    </article>
    <article>
      <h3>السباكة والصيانة العامة</h3>
      <p>كشف تسريبات، تغيير مواسير، تركيب صنابير، وترميمات سريعة.</p>
    </article>
    <article>
      <h3>تنظيف منازل ومكاتب</h3>
      <p>تنظيف شامل، تنظيف عميق، تنظيف مفروشات وسجاد.</p>
    </article>
  </section>
</main>
<footer class="site-footer">
  <div class="container">
    <p>للتواصل: <a href="tel:0126663438">0126663438</a> ـ البريد: <a href="mailto:mohanadabdulla748@gmail.com">mohanadabdulla748@gmail.com</a></p>
    <p>© جميع الحقوق محفوظة — مهند لصيانة الكهرباء والنظافة</p>
  </div>
</footer>
</body>
</html>
:root{
  --accent:#ffcc00;
  --bg:#f5f6f8;
  --card:#ffffff;
  --dark:#111;
}
*{box-sizing:border-box}
body{font-family:Arial,sans-serif;background:var(--bg);margin:0;color:var(--dark);direction:rtl}
.container{max-width:1000px;margin:0 auto;padding:16px}
.site-header{background:#0b1220;color:white;padding:12px 0}
.logo{margin:0;font-size:20px;text-align:center}
.nav{display:flex;gap:12px;justify-content:center;margin-top:8px}
.nav a{color:#fff;text-decoration:none;padding:6px 10px;border-radius:6px}
.nav a:hover{background:rgba(255,255,255,0.06)}
.hero{background:linear-gradient(90deg,#ffffff 0%, #fafafa 100%);padding:24px;border-radius:10px;text-align:center;margin-top:16px}
.hero h2{margin:6px 0;font-size:22px}
.btn{display:inline-block;margin:8px 6px;padding:10px 18px;border-radius:8px;background:var(--accent);color:#000;text-decoration:none;font-weight:700}
.btn-outline{background:transparent;border:2px solid var(--accent);color:var(--dark)}
.features{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin-top:18px}
.features article{background:var(--card);padding:14px;border-radius:8px;box-shadow:0 2px 6px rgba(0,0,0,0.06)}
.about{background:var(--card);padding:14px;border-radius:8px;margin-top:18px}
.site-footer{background:#0b1220;color:white;padding:14px;margin-top:20px;text-align:center}
.service-list h3{margin-top:12px}
.contact-cards{display:flex;flex-wrap:wrap;gap:12px}
.card{background:var(--card);padding:12px;border-radius:8px;flex:1;min-width:200px}
.quick-form form{display:grid;gap:8px}
.quick-form input, .quick-form textarea{padding:8px;border:1px solid #ddd;border-radius:6px}
.note{font-size:12px;color:#666;margin-top:8px}
@media (max-width:600px){
  .nav{flex-direction:column}
  .logo{font-size:18px}
}
