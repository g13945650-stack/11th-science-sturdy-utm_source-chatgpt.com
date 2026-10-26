# 11th-science-sturdy-utm_source-chatgpt.com 
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#155eef">
  <meta name="description" content="11th Study Point - कक्षा 11वीं के विद्यार्थियों के लिए नोट्स, फॉर्मूले और अभ्यास।">
  <title>11th Study Point | Class 11 Science</title>

  <style>
    :root {
      --blue: #155eef;
      --dark: #123a75;
      --light: #f0f6ff;
      --text: #1d2939;
      --muted: #667085;
      --white: #ffffff;
      --border: #dce7f7;
      --shadow: 0 12px 35px rgba(21, 94, 239, .09);
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; scroll-padding-top: 85px; }

    body {
      font-family: system-ui, -apple-system, "Segoe UI", sans-serif;
      color: var(--text);
      background: #f8fbff;
      line-height: 1.6;
    }

    a { color: inherit; text-decoration: none; }
    button, input { font: inherit; }

    .container {
      width: min(1120px, 92%);
      margin: auto;
    }

    header {
      background: rgba(255,255,255,.96);
      border-bottom: 1px solid var(--border);
      position: sticky;
      top: 0;
      z-index: 10;
      backdrop-filter: blur(12px);
    }

    .navbar {
      min-height: 74px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 11px;
      color: var(--dark);
      font-size: 1.15rem;
      font-weight: 800;
    }

    .brand-icon {
      background: var(--blue);
      color: white;
      border-radius: 13px;
      padding: 9px 11px;
    }

    nav { display: flex; align-items: center; gap: 24px; }

    nav a {
      color: #475467;
      font-weight: 600;
      font-size: .94rem;
    }

    nav a:hover { color: var(--blue); }

    .hero {
      padding: 78px 0 65px;
      background:
        radial-gradient(ellipse at 90% 10%, #d7e7ff 0, transparent 40%),
        linear-gradient(135deg, #eef5ff, #ffffff 70%);
      border-bottom: 1px solid var(--border);
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.3fr .7fr;
      align-items: center;
      gap: 35px;
    }

    .tag {
      display: inline-block;
      padding: 7px 13px;
      border-radius: 30px;
      background: #dceaff;
      color: var(--blue);
      font-size: .85rem;
      font-weight: 750;
      margin-bottom: 18px;
    }

    h1 {
      color: var(--dark);
      font-size: clamp(2.3rem, 5vw, 4rem);
      line-height: 1.13;
      letter-spacing: -1.5px;
      margin-bottom: 20px;
    }

    h1 span { color: var(--blue); }

    .hero p {
      color: var(--muted);
      font-size: 1.08rem;
      max-width: 560px;
      margin-bottom: 26px;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      background: var(--blue);
      color: white;
      border: 0;
      border-radius: 11px;
      padding: 12px 20px;
      font-weight: 700;
      cursor: pointer;
      transition: .2s;
    }

    .btn:hover {
      background: #084acb;
      transform: translateY(-2px);
    }

    .hero-art {
      background: white;
      border: 1px solid var(--border);
      box-shadow: var(--shadow);
      border-radius: 28px;
      padding: 30px;
      text-align: center;
    }

    .hero-art .book { font-size: 5rem; margin-bottom: 8px; }

    .hero-art h2 { color: var(--dark); margin-bottom: 7px; }

    .hero-art p { margin: 0; font-size: .95rem; }

    .stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
      margin-top: 22px;
    }

    .stat {
      background: var(--light);
      padding: 13px 6px;
      border-radius: 12px;
    }

    .stat strong { display: block; color: var(--blue); }
    .stat span { font-size: .76rem; color: var(--muted); }

    section { padding: 68px 0; }

    .section-heading { text-align: center; margin-bottom: 30px; }

    .section-heading h2 {
      color: var(--dark);
      font-size: clamp(1.7rem, 3vw, 2.25rem);
      margin-bottom: 8px;
    }

    .section-heading p { color: var(--muted); }

    .search-wrap { max-width: 600px; margin: 0 auto 30px; }

    .search {
      width: 100%;
      padding: 15px 18px;
      border: 1px solid #cbd9ee;
      border-radius: 13px;
      background: white;
      outline: none;
      box-shadow: 0 4px 16px rgba(16, 24, 40, .04);
    }

    .search:focus {
      border-color: var(--blue);
      box-shadow: 0 0 0 3px #155eef20;
    }

    .subjects {
      display: grid;
      grid-template-columns: repeat(4, minmax(0, 1fr));
      gap: 18px;
    }

    .subject-card {
      background: white;
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 23px 18px;
      box-shadow: 0 4px 16px rgba(16,24,40,.025);
      transition: .22s;
    }

    .subject-card:hover {
      transform: translateY(-5px);
      border-color: #a8c7ff;
      box-shadow: var(--shadow);
    }

    .subject-icon {
      display: grid;
      place-items: center;
      width: 52px;
      height: 52px;
      border-radius: 15px;
      background: var(--light);
      font-size: 1.65rem;
      margin-bottom: 16px;
    }

    .subject-card h3 { color: var(--dark); margin-bottom: 7px; }
    .subject-card p { color: var(--muted); font-size: .9rem; }

    .subject-card .small-link {
      display: inline-block;
      color: var(--blue);
      font-weight: 700;
      font-size: .88rem;
      margin-top: 15px;
    }

    #noResults {
      display: none;
      text-align: center;
      color: var(--muted);
      padding: 25px;
    }

    .about-panel {
      display: grid;
      grid-template-columns: .8fr 1.2fr;
      gap: 30px;
      align-items: center;
      background: white;
      border: 1px solid var(--border);
      border-radius: 24px;
      padding: 35px;
      box-shadow: var(--shadow);
    }

    .about-icon {
      background: var(--light);
      border-radius: 20px;
      min-height: 190px;
      display: grid;
      place-items: center;
      font-size: 5rem;
    }

    .about-panel h2 { color: var(--dark); margin-bottom: 13px; }
    .about-panel p { color: var(--muted); margin-bottom: 10px; }

    .credits { background: #edf4ff; }

    .credit-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 18px;
    }

    .credit-card {
      background: white;
      border: 1px solid var(--border);
      border-radius: 17px;
      padding: 25px 15px;
      text-align: center;
    }

    .avatar {
      width: 58px;
      height: 58px;
      border-radius: 50%;
      margin: 0 auto 12px;
      display: grid;
      place-items: center;
      background: #dceaff;
      color: var(--blue);
      font-weight: 800;
      font-size: 1.2rem;
    }

    .credit-card h3 { color: var(--dark); font-size: 1.02rem; }
    .credit-card p { color: var(--muted); font-size: .86rem; margin-top: 5px; }

    .credit-card.featured {
      border: 2px solid var(--blue);
      box-shadow: var(--shadow);
    }

    .credit-card.featured .avatar {
      color: white;
      background: var(--blue);
    }

    footer {
      padding: 25px 0;
      text-align: center;
      background: #102e5b;
      color: #eaf1ff;
    }

    footer p + p { margin-top: 5px; font-size: .88rem; color: #c4d6f7; }

    @media (max-width: 850px) {
      .hero-grid { grid-template-columns: 1fr; }
      .hero-art { max-width: 500px; width: 100%; margin: auto; }
      .subjects { grid-template-columns: repeat(2, minmax(0, 1fr)); }
    }

    @media (max-width: 560px) {
      .navbar { padding: 13px 0; align-items: flex-start; flex-direction: column; gap: 12px; }
      nav { width: 100%; gap: 18px; flex-wrap: wrap; }
      nav a { font-size: .87rem; }
      .hero { padding: 48px 0; }
      section { padding: 48px 0; }
      .subjects { gap: 12px; }
      .subject-card { padding: 17px 13px; }
      .subject-card h3 { font-size: 1rem; }
      .about-panel { grid-template-columns: 1fr; padding: 22px; }
      .about-icon { min-height: 135px; }
      .credit-grid { grid-template-columns: 1fr; }
    }

    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after {
        scroll-behavior: auto !important;
        transition: none !important;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="container navbar">
      <a class="brand" href="#home" aria-label="11th Study Point Home">
        <span class="brand-icon">📘</span>
        <span>11th Study Point</span>
      </a>
      <nav aria-label="Main navigation">
        <a href="#home">होम</a>
        <a href="#subjects">विषय</a>
        <a href="#about">हमारे बारे में</a>
        <a href="#credits">Made by</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-grid">
        <div>
          <span class="tag">🎓 Class 11 • Science</span>
          <h1>पढ़ाई बने आसान,<br><span>सपने हों महान!</span></h1>
          <p>
            11th Study Point पर आपका स्वागत है।
            अपने विषय चुनें और नोट्स, फॉर्मूले व अभ्यास
            के साथ पढ़ाई को बेहतर बनाएं।
          </p>
          <a class="btn" href="#subjects">पढ़ाई शुरू करें →</a>
        </div>

        <div class="hero-art">
          <div class="book" aria-hidden="true">📚</div>
          <h2>Learn. Practice. Grow.</h2>
          <p>हर दिन कुछ नया सीखें और आगे बढ़ें।</p>
          <div class="stats">
            <div class="stat"><strong>11वीं</strong><span>कक्षा</span></div>
            <div class="stat"><strong>Science</strong><span>स्ट्रीम</span></div>
            <div class="stat"><strong>Learn</strong><span>हर दिन</span></div>
          </div>
        </div>
      </div>
    </section>

    <section id="subjects">
      <div class="container">
        <div class="section-heading">
          <h2>📚 हमारे विषय</h2>
          <p>अपना विषय चुनें या नीचे सर्च करके खोजें।</p>
        </div>

        <div class="search-wrap">
          <input
            class="search"
            id="subjectSearch"
            type="search"
            placeholder="🔍 विषय या अध्याय खोजें..."
            aria-label="विषय खोजें"
          >
        </div>

        <div class="subjects" id="subjectGrid">
          <article class="subject-card" data-search="physics भौतिक विज्ञान">
            <div class="subject-icon" aria-hidden="true">⚛️</div>
            <h3>Physics</h3>
            <p>भौतिक विज्ञान के सिद्धांत और फॉर्मूले।</p>
            <a class="small-link" href="#about">जानकारी देखें →</a>
          </article>

          <article class="subject-card" data-search="chemistry रसायन विज्ञान">
            <div class="subject-icon" aria-hidden="true">🧪</div>
            <h3>Chemistry</h3>
            <p>रासायनिक अभिक्रियाएँ और महत्वपूर्ण अवधारणाएँ।</p>
            <a class="small-link" href="#about">जानकारी देखें →</a>
          </article>

          <article class="subject-card" data-search="mathematics maths गणित">
            <div class="subject-icon" aria-hidden="true">📐</div>
            <h3>Mathematics</h3>
            <p>गणित के सूत्र, उदाहरण और अभ्यास।</p>
            <a class="small-link" href="#about">जानकारी देखें →</a>
          </article>

          <article class="subject-card" data-search="biology जीव विज्ञान">
            <div class="subject-icon" aria-hidden="true">🧬</div>
            <h3>Biology</h3>
            <p>जीव विज्ञान के विषय और महत्वपूर्ण प्रश्न।</p>
            <a class="small-link" href="#about">जानकारी देखें →</a>
          </article>
        </div>

        <p id="noResults" role="status">कोई विषय नहीं मिला। दूसरा नाम लिखकर देखें।</p>
      </div>
    </section>

    <section id="about">
      <div class="container">
        <div class="about-panel">
          <div class="about-icon" aria-hidden="true">🎓</div>
          <div>
            <h2>हमारे बारे में</h2>
            <p>
              <strong>11th Study Point</strong> कक्षा 11वीं के
              विद्यार्थियों के लिए बनाया गया एक अध्ययन मंच है।
            </p>
            <p>
              हमारा उद्देश्य आसान भाषा में पढ़ाई की जानकारी,
              नोट्स, फॉर्मूले और अभ्यास प्रश्न उपलब्ध कराने में
              विद्यार्थियों की मदद करना है।
            </p>
            <a class="btn" href="#subjects">विषय देखें</a>
          </div>
        </div>
      </div>
    </section>

    <section class="credits" id="credits">
      <div class="container">
        <div class="section-heading">
          <h2>✨ Made by</h2>
          <p>11th Study Point के निर्माता और सहयोगी</p>
        </div>

        <div class="credit-grid">
          <article class="credit-card">
            <div class="avatar" aria-hidden="true">NM</div>
            <h3>Mr. Narayan Mehta</h3>
            <p>Website contributor</p>
          </article>

          <article class="credit-card">
            <div class="avatar" aria-hidden="true">DS</div>
            <h3>Miss. Disha Sagitra</h3>
            <p>Website contributor</p>
          </article>

          <article class="credit-card featured">
            <div class="avatar" aria-hidden="true">VG</div>
            <h3>VIKAS GURJAR</h3>
            <p>Made by</p>
          </article>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>© <span id="year"></span> 11th Study Point | सीखो, समझो, आगे बढ़ो 🚀</p>
      <p>Made with ❤️ for Class 11 students</p>
    </div>
  </footer>

  <script>
    const searchInput = document.getElementById("subjectSearch");
    const cards = [...document.querySelectorAll(".subject-card")];
    const noResults = document.getElementById("noResults");

    searchInput.addEventListener("input", function () {
      const query = this.value.trim().toLocaleLowerCase("hi");
      let visibleCount = 0;

      cards.forEach(function (card) {
        const content = (
          card.innerText + " " + card.dataset.search
        ).toLocaleLowerCase("hi");

        const matches = content.includes(query);
        card.hidden = !matches;
        if (matches) visibleCount++;
      });

      noResults.style.display = visibleCount ? "none" : "block";
    });

    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>
</body>
</html>
