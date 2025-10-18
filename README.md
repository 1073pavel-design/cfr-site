<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Центр Финансовых Решений — кредиты, РКО, страхование</title>
  <meta name="description" content="Финансовый брокер: кредиты для физлиц и ИП/ООО, РКО, страхование и консультации. Помогаем получить одобрение даже с плохой КИ.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#ffffff;
      --muted:#6b7280;
      --accent:#0b63d4;
      --accent-dark:#084aa0;
      --card:#f8fbff;
      --radius:14px;
      --maxw:1100px;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;background:var(--bg);color:#0f1724;line-height:1.45;-webkit-font-smoothing:antialiased;
    }
    .container{max-width:var(--maxw);margin:0 auto;padding:28px}
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 0}
    .brand{display:flex;gap:14px;align-items:center}
    .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(180deg,var(--accent),var(--accent-dark));display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:18px}
    h1{margin:0;font-size:24px}
    .tag{color:var(--muted);font-size:13px}
    nav a{margin-left:18px;color:var(--accent);text-decoration:none;font-weight:600}

    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;padding:28px 0}
    .hero h2{font-size:32px;margin:0 0 12px}
    .hero p{color:var(--muted);margin:0 0 18px}
    .actions{display:flex;gap:12px}
    .btn{background:var(--accent);color:white;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:600;display:inline-block}
    .btn.secondary{background:transparent;color:var(--accent);border:1px solid rgba(11,99,212,0.12)}

    .card{background:var(--card);padding:18px;border-radius:var(--radius);box-shadow:0 6px 20px rgba(11,99,212,0.06)}
    .services{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:22px 0}
    .service{padding:16px;border-radius:12px;background:white;border:1px solid #eef6ff}
    .service h3{margin:6px 0 4px;font-size:16px}
    .service p{margin:0;color:var(--muted);font-size:14px}

    .testimonials{margin-top:12px;display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .t{background:white;padding:16px;border-radius:12px;border:1px solid #eef3fb}
    .author{font-weight:700}
    .muted{color:var(--muted);font-size:13px}

    footer{margin-top:36px;padding:28px 0;border-top:1px solid #eef3fb}
    .contacts{display:flex;gap:16px;flex-direction:column}

    /* responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .services{grid-template-columns:repeat(2,1fr)}
      .testimonials{grid-template-columns:1fr}
    }
    @media (max-width:520px){
      .services{grid-template-columns:1fr}
      .logo{width:48px;height:48px;font-size:16px}
      h1{font-size:18px}
      .hero h2{font-size:22px}
    }

    /* small utility */
    .small{font-size:13px;color:var(--muted)}
    .pill{display:inline-block;padding:6px 10px;background:#f1f8ff;border-radius:999px;color:var(--accent);font-weight:600;font-size:13px}
    .meta{display:flex;gap:8px;align-items:center}
    .phone{font-weight:700;color:var(--accent-dark)}
    form input, form textarea{width:100%;padding:10px;border-radius:8px;border:1px solid #e6efff;margin-top:8px}
    form button{margin-top:10px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">CFR</div>
        <div>
          <h1>Центр Финансовых Решений</h1>
          <div class="tag">Кредиты, РКО, страхование — помощь в выборе и оформлении</div>
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
          <div class="pill">Финансовый брокер • Работаем с частными лицами и бизнесом</div>
          <h2>Подберём кредит, РКО и страхование — быстро и прозрачно</h2>
          <p>Помогаем получить одобрение даже при сложной кредитной истории. Подбираем банки и страховые решения под вашу задачу, сопровождаем оформление от заявки до получения средств.</p>
          <div class="actions">
            <a class="btn" href="#contact">Оставить заявку</a>
            <a class="btn secondary" href="#cases">Наши кейсы</a>
          </div>

          <div style="margin-top:18px;display:flex;gap:14px;align-items:center;flex-wrap:wrap">
            <div class="card small">
              <div class="meta"><strong>Контакт</strong><span class="muted">+7 (996) 828‑58‑34</span></div>
              <div class="meta"><strong>Telegram</strong><span class="muted">@PavelFinanceB</span></div>
              <div class="meta"><strong>Email</strong><span class="muted">pavel.itel0802@gmail.com</span></div>
            </div>
            <div class="card small">
              <div><strong>Гарантия</strong></div>
              <div class="muted">Консультация — бесплатно. Работаем по результату и по договору.</div>
            </div>
          </div>
        </div>

        <aside class="card">
          <h3 style="margin-top:0">Быстрая заявка</h3>
          <form action="#" onsubmit="alert('Заявка отправлена — телефон: '+document.getElementById('phone').value);return false;">
            <label class="small">Имя</label>
            <input type="text" id="name" placeholder="Иван" required>
            <label class="small">Телефон</label>
            <input type="tel" id="phone" placeholder="+7 (___) ___-__-__" required>
            <label class="small">Что нужно</label>
            <select style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6efff;margin-top:8px">
              <option>Кредит физлицу</option>
              <option>РКО для бизнеса</option>
              <option>Кредит ИП/ООО</option>
              <option>Страхование</option>
              <option>Консультация</option>
            </select>
            <button class="btn" type="submit">Отправить заявку</button>
            <div class="small" style="margin-top:8px;color:var(--muted)">Или напишите в Telegram: <a href="https://t.me/PavelFinanceB" target="_blank">@PavelFinanceB</a></div>
          </form>
        </aside>
      </section>

      <section id="services">
        <h3>Наши услуги</h3>
        <div class="services">
          <div class="service">
            <strong>Кредиты для физлиц</strong>
            <h3>Подбор оптимального предложения</h3>
            <p>Проверим доступные варианты по вашему профилю, поможем подготовить документы и отправим заявки в подходящие банки.</p>
          </div>
          <div class="service">
            <strong>РКО для бизнеса</strong>
            <h3>Расчётно‑кассовое обслуживание</h3>
            <p>Подберём тарифы с низкими комиссиями, поможем с подключением онлайн‑банкинга и тарифными льготами на старте.</p>
          </div>
          <div class="service">
            <strong>Кредиты для ИП/ООО</strong>
            <h3>Бизнес‑решения и оборотный капитал</h3>
            <p>Работаем с продуктами для ИП и ООО, помогаем с документами и сопровождением сделок.</p>
          </div>
          <div class="service">
            <strong>Страхование</strong>
            <h3>Защита бизнеса и имущества</h3>
            <p>Подберём коммерческие и личные программы страхования под риски клиента.</p>
          </div>
          <div class="service">
            <strong>Кредитные карты</strong>
            <h3>Карты с выгодными кешбэками и лимитами</h3>
            <p>Поможем подобрать карту под ваши расходы и оформить её быстро.</p>
          </div>
          <div class="service">
            <strong>Финансовые консультации</strong>
            <h3>Анализ и рекомендации</h3>
            <p>Разберём вашу ситуацию и предложим план действий для улучшения КИ и повышения шансов на одобрение.</p>
          </div>
        </div>
      </section>

      <section id="cases">
        <h3>Реальные кейсы клиентов</h3>
        <p class="small">Ниже — отрывки реальных историй клиентов. Конфиденциальность сохранена.</p>
        <div class="testimonials">
          <div class="t">
            <div class="author">Сергей П., Москва</div>
            <div class="muted">Ситуация: испорченная КИ после развода, множественные отказы</div>
            <p>После анализа БКИ помогли закрыть часть просрочек, подобрали банки с лояльной политикой и отправили корректные заявки. В итоге — одобрение на 500 000 ₽ под приемлемый процент. Быстро и по делу.</p>
          </div>
          <div class="t">
            <div class="author">Анна Р., Новосибирск</div>
            <div class="muted">Ситуация: 8 микрозаймов, просрочки</div>
            <p>Оформлена реструктуризация и единый кредит для закрытия МФО. Сейчас один удобный платёж вместо восьми — это реально помогло восстановить бюджет.</p>
          </div>
          <div class="t">
            <div class="author">Роман Д., Тверь</div>
            <div class="muted">Ситуация: самозанятый, нестабильный доход</div>
            <p>Подобрали продукт, принимающий выписки и налоговые отчёты вместо справок 2‑НДФЛ — одобрили 400 000 ₽. Всё дистанционно и без лишних требований.</p>
          </div>
          <div class="t">
            <div class="author">Екатерина М., Воронеж</div>
            <div class="muted">Ситуация: низкий рейтинг, оформили под залог</div>
            <p>Предложили вариант под залог авто и помогли с документами. Получила 350 000 ₽ — условия прозрачно прописаны в договоре.</p>
          </div>
        </div>
      </section>

      <section id="about" style="margin-top:22px">
        <h3>Почему выбирают нас</h3>
        <ul class="small">
          <li>Персональный подход — оцениваем ситуацию и предлагаем только рабочие решения.</li>
          <li>Работаем с несколькими банками и страховыми партнёрами.</li>
          <li>Прозрачные условия и сопровождение до результата.</li>
        </ul>
      </section>

    </main>

    <footer id="contact">
      <div style="display:flex;gap:24px;flex-wrap:wrap;justify-content:space-between;align-items:flex-start">
        <div style="flex:1;min-width:260px">
          <h3>Контакты</h3>
          <div class="contacts small">
            <div>Телефон: <a class="phone" href="tel:+79968285834">+7 (996) 828‑58‑34</a></div>
            <div>Telegram: <a href="https://t.me/PavelFinanceB" target="_blank">@PavelFinanceB</a></div>
            <div>Email: <a href="mailto:pavel.itel0802@gmail.com">pavel.itel0802@gmail.com</a></div>
            <div class="muted">График: пн–пт 09:00–19:00 (по договорённости в выходные)</div>
          </div>
        </div>

        <div style="flex-basis:360px;min-width:260px">
          <div class="card">
            <h4 style="margin-top:0">Оставить заявку</h4>
            <form action="#" onsubmit="alert('Спасибо! Мы свяжемся с вами в течение рабочего дня.');return false;">
              <input placeholder="Имя" required>
              <input placeholder="Телефон" required>
              <textarea placeholder="Коротко опишите задачу" rows="3"></textarea>
              <button class="btn" type="submit">Отправить</button>
              <div class="small" style="margin-top:10px">Или напишите в Telegram: <a href="https://t.me/PavelFinanceB">@PavelFinanceB</a></div>
            </form>
          </div>
        </div>
      </div>

      <div style="margin-top:18px;text-align:center" class="small muted">© Центр Финансовых Решений — Все права защищены</div>
    </footer>
  </div>
</body>
</html>
