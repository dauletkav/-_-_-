<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ерден Нығметұлы Әзірбаев — өмірбаян</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=Noto+Serif+Display:wght@500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b1020;
      --card: #121a33;
      --muted: #a6b0cf;
      --text: #e7ecff;
      --accent: #7aa2ff;
      --accent-2: #9be0b9;
      --border: #243055;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius: 18px;
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      background: radial-gradient(1200px 600px at 20% -10%, rgba(122,162,255,.15), transparent),
                  radial-gradient(1000px 500px at 110% 10%, rgba(155,224,185,.14), transparent),
                  var(--bg);
      color: var(--text);
      font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, "Noto Sans", Arial, sans-serif;
      line-height: 1.65;
    }
    .wrap {
      max-width: 900px;
      margin: 48px auto;
      padding: 0 20px 80px;
    }
    header.hero {
      background: linear-gradient(180deg, rgba(122,162,255,.12), rgba(18,26,51,.7));
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 28px 28px 24px;
      box-shadow: var(--shadow);
      position: relative;
      overflow: hidden;
    }
    header.hero:after {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(600px 200px at 80% -10%, rgba(155,224,185,.18), transparent);
      pointer-events: none;
    }
    h1.title {
      font-family: "Noto Serif Display", serif;
      font-weight: 700;
      letter-spacing: .3px;
      margin: 4px 0 10px;
      font-size: clamp(28px, 4vw, 44px);
      line-height: 1.15;
      text-wrap: balance;
    }
    .subtitle {
      color: var(--muted);
      font-weight: 500;
      margin-bottom: 14px;
    }
    .badges { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 8px; }
    .badge {
      border: 1px solid var(--border);
      background: rgba(18,26,51,.6);
      padding: 6px 10px;
      border-radius: 999px;
      font-size: 13px;
      color: var(--muted);
      backdrop-filter: blur(3px);
    }
    main {
      margin-top: 28px;
      display: grid;
      gap: 18px;
    }
    section.card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 22px;
      box-shadow: var(--shadow);
    }
    section.card h2 {
      margin: 0 0 10px;
      font-size: 20px;
      letter-spacing: .2px;
    }
    .lead {
      font-size: 17px;
      color: #dbe4ff;
    }
    ul.timeline {
      list-style: none;
      margin: 0; padding: 0;
      display: grid; gap: 10px;
    }
    .timeline li {
      display: grid;
      grid-template-columns: 140px 1fr;
      gap: 16px;
      align-items: start;
      padding: 12px 14px;
      border: 1px dashed var(--border);
      border-radius: 14px;
      background: rgba(255,255,255,.02);
    }
    .timeline .when { color: var(--accent); font-weight: 600; }
    .timeline .what { color: var(--text); }

    .awards, .works { display: grid; gap: 8px; margin: 0; padding-left: 18px; }
    .awards li::marker, .works li::marker { color: var(--accent-2); }

    .footer {
      display: flex; gap: 12px; flex-wrap: wrap; align-items: center; justify-content: space-between; margin-top: 16px; color: var(--muted);
    }
    .btn {
      appearance: none; border: 1px solid var(--border); background: rgba(122,162,255,.12);
      color: var(--text); padding: 10px 14px; border-radius: 999px; cursor: pointer; font-weight: 600;
    }
    .btn:hover { filter: brightness(1.05); }
    .btn:active { transform: translateY(1px); }

    @media (max-width: 560px) {
      .timeline li { grid-template-columns: 1fr; }
    }
    /* Басып шығару үшін */
    @media print {
      body { background: #fff; color: #111; }
      header.hero, section.card { box-shadow: none; background: #fff; border-color: #ddd; }
      .btn { display: none; }
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header class="hero">
      <div class="subtitle">Ғалым • Органикалық химия • Қазақстан</div>
      <h1 class="title">Ерден Нығметұлы Әзірбаев</h1>
      <div class="badges">
        <span class="badge">1912 ж. 12 шілде — 1975 ж. 14 қаңтар</span>
        <span class="badge">Химия ғылымдарының докторы (1961)</span>
        <span class="badge">Профессор (1962)</span>
        <span class="badge">ҚазҒА корр. мүшесі (1962)</span>
        <span class="badge">Қазақ КСР еңбек сіңірген ғылым қайраткері (1969)</span>
      </div>
    </header>

    <main>
      <section class="card">
        <h2>Қысқаша өмірбаян</h2>
        <p class="lead">
          Ерден  Нығметұлы  Әзірбаев (12.7.1912, Батыс Қазақстан облысы, Жәнібек ауданы, Сайқын станция – 14.1.1975, Алматы қаласы) – химия ғылымдарының докторы (1961), профессор (1962), Қазақстан Ғылым Академиясының корресподент мүшесі (1962), Қазақ КСР-інің еңбек сіңірген ғылым қайраткері (1969).
        </p>
      </section>

      <section class="card">
        <h2>Білімі</h2>
        <ul class="timeline">
          <li>
            <div class="when">1933</div>
            <div class="what">Саратов университетін бітірген.</div>
          </li>
          <li>
            <div class="when">1937–1940</div>
            <div class="what">Ленинград университетінің аспирантурасын аяқтады.</div>
          </li>
        </ul>
      </section>

      <section class="card">
        <h2>Еңбек жолы</h2>
        <ul class="timeline">
          <li>
            <div class="when">1933–1934</div>
            <div class="what">Саратов крекинг зауытында жұмыс істеді.</div>
          </li>
          <li>
            <div class="when">1934–1935</div>
            <div class="what">Орал педагогикалық институтында қызмет атқарып, химиялық кафедрасын ұйымдастырды.</div>
          </li>
          <li>
            <div class="when">1935–1954</div>
            <div class="what">ҚазМУ-да (қазіргі ҚазҰУ) ассистент, доцент, кафедра меңгерушісі, декан (1940–1954).</div>
          </li>
          <li>
            <div class="when">1954–1958; 1964–1975</div>
            <div class="what">Химия ғылымдары институтында лаборатория және бөлім меңгерушісі.</div>
          </li>
          <li>
            <div class="when">1958–1964</div>
            <div class="what">Қазақстан Ғылым Академиясының Химия-металлургия институтының директоры.</div>
          </li>
        </ul>
      </section>

      <section class="card">
        <h2>Ғылыми үлесі</h2>
        <ul class="works">
          <li>Негізгі ғылыми еңбектері көмір, мұнай, ацетилен, органикалық қосылыстар, физиологиялық активті заттар химиясына, нәзік органикалық қосылыстар синтезіне арналған.</li>
          <li>Органика синтез саласында ацетиленнің жаңа туындыларын және оның изомерлерін зерттеді.</li>
          <li>Алғаш Қарағанды көмірінен кокс алу мүмкіндігін анықтады.</li>
          <li>Медицинада ісікке қарсы «Глиофен», ауыл шаруашылығында өсімдік өсуін тездететін «Ақпинол», «Фоспинол» препараттарын тапты.</li>
          <li>81 авторлық куәлік алған.</li>
        </ul>
      </section>

      <section class="card">
        <h2>Марапаттар</h2>
        <ul class="awards">
          <li>Еңбек Қызыл Ту ордені.</li>
          <li>«Құрмет Белгісі» ордені (1945).</li>
          <li>Медальдар.</li>
        </ul>
        <div class="footer">
          <span>Құжатты басып шығару немесе PDF сақтап алу үшін батырманы басыңыз.</span>
          <button class="btn" onclick="window.print()">Басып шығару / PDF</button>
        </div>
      </section>
    </main>
  </div>
</body>
</html>
