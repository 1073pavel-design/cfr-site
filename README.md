<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Центр Финансовых Решений — кредиты, РКО, страхование</title>
  <meta name="description" content="Финансовый брокер: кредиты для физлиц и ИП/ООО, РКО, страхование и консультации. Помогаем получить одобрение даже с плохой КИ.">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #ffffff;
      --muted: #6b7280;
      --accent: #0b63d4;
      --accent-dark: #084aa0;
      --card: #f8fbff;
      --radius: 14px;
      --maxw: 1100px;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, Arial;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: var(--bg);
      color: #0f1724;
      line-height: 1.45;
      -webkit-font-smoothing: antialiased;
    }
    .container { max-width: var(--maxw); margin: 0 auto; padding: 28px; }
    header { display: flex; align-items: center; justify-content: space-between; padding: 18px 0; }
    .brand { display: flex; gap: 14px; align-items: center; }
    .logo {
      width: 56px; height: 56px;
      border-radius: 10px;
      background: linear-gradient(180deg,var(--accent),var(--accent-dark));
      display: flex; align-items: center; justify-content: center;
      color: white; font-weight: 700; font-size: 18px;
    }
    h1 { margin: 0; font-size: 24px; }
    nav a { margin-left: 18px; color: var(--accent); text-decoration: none; font-weight: 600; }

    .hero { display: grid; grid-template-columns: 1fr 420px; gap: 28px; align-items: center; padding: 28px 0; }
    .hero h2 { font-size: 32px; margin: 0 0 12px; }
    .hero p { color: var(--muted); margin: 0 0 18px; }
    .actions { display: flex; gap: 12px; }
    .btn { background: var(--accent); color: white; padding: 12px 18px; border-radius: 10px; text-decoration: none; font-weight: 600; display: inline-block; border: none; cursor: pointer; }
    .btn.secondary { background: transparent; color: var(--accent); border: 1px solid rgba(11,99,212,0.12); }

    .card { background: var(--card); padding: 18px; border-radius: var(--radius); box-shadow: 0 6px 20px rgba(11,99,212,0.06); }
    .services { display: grid; grid-template-columns: repeat(3,1fr); gap: 16px; margin: 22px 0; }
    .service { padding: 16px; border-radius: 12px; background: white; border: 1px solid #eef6ff; }
    .service h3 { margin: 6px 0 4px; font-size: 16px; }
    .service p { margin: 0; color: var(--muted); font-size: 14px; }

    .testimonials { margin-top: 12px; display: grid; grid-template-columns: repeat(2,1fr); gap: 12px; }
    .t { background: white; padding: 16px; border-radius: 12px; border: 1px solid #eef3fb; }
    .author { font-weight: 700; }
    .muted { color: var(--muted); font-size: 13px; }

    footer { margin-top: 36px; padding: 28px 0; border-top: 1px solid #eef3fb; }
    .contacts { display: flex; gap: 16px; flex-direction: column; }

    @media (max-width:900px){
      .hero { grid-template-columns: 1fr; }
      .services { grid-template-columns: repeat(2,1fr); }
      .testimonials { grid-template-columns: 1fr; }
    }
    @media (max-width:520px){
      .services { grid-template-columns: 1fr; }
      .logo { width: 48px; height: 48px; font-size: 16px; }
      h1 { font-size: 18px; }
      .hero h2 { font-size: 22px; }
    }

    .small { font-size: 13px; color: var(--muted); }
    form input, form select, form textarea { width: 100%; padding: 10px; border-radius: 8px; border: 1px solid #e6efff; margin-top: 8px; }
  </style>
</head>
<body>

<!-- убираем лишний заголовок GitHub Pages -->
<style>h1:first-of-type, header + h1 {display:none!important}</style>

<div class="container">
  <header>
    <div class="brand">
      <div class="logo">CFR</div>
      <div>
        <h1>Центр Финансовых Решений</h1>
        <div class="small">Кредиты, РКО, страхование — помощь в выборе и оформлении</div>
      </div>
    </div>
    <nav>
      <a href="#services">Услуги</a>
      <a href="#cases">Кейсы</a>
      <a href="#contact">Контакты</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div>
        <div class="small" style="color:var(--accent);font-weight:600;">Финансовый брокер • Работаем с частными лицами и бизнесом</div>
        <h2>Подберём кредит, РКО и страхование — быстро и прозрачно</h2>
        <p>Помогаем получить одобрение даже при сложной кредитной истории. Подбираем банки и страховые решения под вашу задачу.</p>
        <div class="actions">
          <a class="btn" href="#contact">Оставить заявку</a>
          <a class="btn secondary" href="#cases">Наши кейсы</a>
        </div>
      </div>

      <aside class="card">
        <h3 style="margin-top:0;">Быстрая заявка</h3>
        <form id="quickForm">
          <input type="text" name="name" placeholder="Имя" required>
          <input type="tel" name="phone" placeholder="+7 (___) ___-__-__" required>
          <select name="type">
            <option>Кредит физлицу</option>
            <option>РКО для бизнеса</option>
            <option>Кредит ИП/ООО</option>
            <option>Страхование</option>
            <option>Консультация</option>
          </select>
          <button class="btn" type="submit">Отправить заявку</button>
        </form>
      </aside>
    </section>

    <section id="services">
      <h3>Наши услуги</h3>
      <div class="services">
        <div class="service"><h3>Кредиты для физлиц</h3><p>Подбор оптимального предложения и помощь в одобрении даже при плохой КИ.</p></div>
        <div class="service"><h3>РКО для бизнеса</h3><p>Подберём банк с выгодными тарифами и подключим онлайн-банкинг.</p></div>
        <div class="service"><h3>Кредиты для ИП/ООО</h3><p>Бизнес-решения, оборотный капитал, сопровождение сделки.</p></div>
        <div class="service"><h3>Страхование</h3><p>Подбор программ страхования для частных и корпоративных клиентов.</p></div>
        <div class="service"><h3>Кредитные карты</h3><p>Поможем подобрать карту с выгодными условиями и кешбэком.</p></div>
        <div class="service"><h3>Финансовые консультации</h3><p>Анализ, стратегия и помощь в улучшении кредитной истории.</p></div>
      </div>
    </section>

    <section id="cases">
      <h3>Реальные кейсы клиентов</h3>
      <div class="testimonials">
        <div class="t"><div class="author">Сергей П., Москва</div><p>Испорченная КИ после развода, одобрение 500 000 ₽ после анализа и сопровождения.</p></div>
        <div class="t"><div class="author">Анна Р., Новосибирск</div><p>8 микрозаймов — оформили единый кредит, закрыли все просрочки.</p></div>
        <div class="t"><div class="author">Роман Д., Тверь</div><p>Самозанятый, нестабильный доход — одобрено 400 000 ₽ без 2-НДФЛ.</p></div>
        <div class="t"><div class="author">Екатерина М., Воронеж</div><p>Кредит под залог авто, сумма 350 000 ₽, прозрачные условия.</p></div>
      </div>
    </section>

    <footer id="contact">
      <h3>Контакты</h3>
      <div class="contacts small">
        <div>📞 <a href="tel:+79968285834" class="phone">+7 (996) 828-58-34</a></div>
        <div>💬 Telegram: <a href="https://t.me/PavelFinanceB" target="_blank">@PavelFinanceB</a></div>
        <div>✉️ Email: <a href="mailto:pavel.itel0802@gmail.com">pavel.itel0802@gmail.com</a></div>
      </div>
      <div style="margin-top:18px;text-align:center" class="small muted">© Центр Финансовых Решений — Все права защищены</div>
    </footer>
  </main>
</div>

<script>
document.querySelector("#quickForm").addEventListener("submit", function(e) {
  e.preventDefault();

  const name = e.target.querySelector('input[name="name"]').value;
  const phone = e.target.querySelector('input[name="phone"]').value;
  const type = e.target.querySelector('select[name="type"]').value;

  const token = "7815097627:AAFK-dwK9_Efq2lvVsDMwmkHQuQDZoKb9io";
  const chatId = "6926310935";
  const message = `📩 Новая заявка с сайта CFR:\n\n👤 Имя: ${name}\n📞 Телефон: ${phone}\n💼 Услуга: ${type}`;

  fetch(`https://api.telegram.org/bot${token}/sendMessage`, {
    method: "POST",
    headers: { "Content-Type": "application/json" },
    body: JSON.stringify({ chat_id: chatId, text: message })
  })
  .then(res => {
    if (res.ok) {
      alert("✅ Заявка успешно отправлена!");
      e.target.reset();
    } else {
      alert("❌ Ошибка при отправке. Проверьте данные.");
    }
  })
  .catch(err => alert("⚠️ Ошибка соединения: " + err));
});
</script>

</body>
</html>
