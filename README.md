<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Meditação & Respiração Terapêutica</title>
  <meta name="description" content="Experiência de Meditação & Respiração Terapêutica — pratique presença, reduza estresse e reconecte corpo e mente." />
  <meta property="og:title" content="Meditação & Respiração Terapêutica" />
  <meta property="og:description" content="Vivência para equilíbrio, foco e bem-estar." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://via.placeholder.com/600x400" />
  <meta name="twitter:card" content="summary_large_image" />

  <style>
    :root{
      --rose:#C9376E;
      --rose-2:#FCE9F0;
      --blue:#3AAFA9;
      --blue-2:#E6F9F8;
      --ink:#0F172A;
      --soft:#667085;
      --line:#E9EEF5;
      --bg:#FFFFFF;
      --success:#10B981;
    }

    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);
      font-family:system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial}
    img{max-width:100%;display:block}
    a{text-decoration:none}

    /* Barra topo */
    .top-bar{
      background:var(--blue);
      color:#fff;
      text-align:center;
      padding:14px 10px;
      font-weight:900;
      font-size:clamp(20px,4.6vw,28px);
      letter-spacing:.04em;
    }

    /* Hero */
    .hero{padding:32px 20px;background:#fff}
    .wrap{max-width:1100px;margin:0 auto}
    .hero-card{
      background:#fff;border:1px solid var(--line);border-radius:20px;
      padding:28px;margin:0 auto;max-width:900px;
      box-shadow:0 14px 34px rgba(0,0,0,.06);text-align:center
    }
    .lead{color:var(--soft);font-size:20px;text-align:center;max-width:720px;margin:12px auto 0}
    .divider{height:10px;margin:22px auto;max-width:300px;border-radius:999px;
      background:linear-gradient(90deg,var(--rose),var(--blue))}
    .cta{margin-top:18px}
    .btn{display:inline-block;padding:14px 20px;border-radius:14px;font-weight:900;box-shadow:0 8px 18px rgba(0,0,0,.08)}
    .primary{background:var(--rose);color:#fff}
    .primary:hover{filter:brightness(1.05)}

    /* Seções */
    section{padding:56px 20px;border-bottom:1px solid var(--line)}
    .section-title{
      font-size:clamp(30px,4.2vw,42px);font-weight:900;margin:0 0 18px;
      background:linear-gradient(90deg,var(--rose),var(--blue));
      -webkit-background-clip:text;background-clip:text;color:transparent;text-align:center;
    }
    .grad-left{
      font-size:clamp(28px,4vw,38px);margin:0 0 12px;font-weight:900;
      background:linear-gradient(90deg,var(--rose),var(--blue));
      -webkit-background-clip:text;background-clip:text;color:transparent;text-align:left;
    }
    p{margin:8px 0 0;font-size:18px;color:var(--soft)}
    ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
    li{margin:8px 0}
    .list-check li{list-style:none;padding-left:28px;position:relative}
    .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:900}

    /* Cards */
    .grid{display:grid;gap:24px}
    .two{grid-template-columns:1fr}
    @media(min-width:860px){.two{grid-template-columns:1fr 1fr}}
    .card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)}
    .pink{background:var(--rose-2)}
    .blue{background:var(--blue-2)}

    /* Instrutor */
    .instrutor{text-align:center}
    .instrutor img{max-width:280px;border-radius:50%;box-shadow:0 10px 26px rgba(0,0,0,.08);margin:12px auto 16px}

    /* Preço */
    .price-card{text-align:center;padding:24px;border:1px solid var(--line);border-radius:18px;box-shadow:0 10px 28px rgba(0,0,0,.05);max-width:340px;margin:0 auto}
    .price{font-size:36px;font-weight:900;color:var(--rose);margin:10px 0}

    /* Depoimentos */
    .testimonials{display:grid;gap:18px}
    @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{border:1px solid var(--line);border-radius:16px;padding:16px 18px;box-shadow:0 8px 22px rgba(0,0,0,.05)}
    .t-name{font-weight:900;margin:0 0 6px;font-size:16px}

    /* FAQ */
    .faq{max-width:800px;margin:0 auto}
    .faq-item{margin:12px 0;border-radius:14px;overflow:hidden;box-shadow:0 6px 18px rgba(0,0,0,.06);border:1px solid var(--line)}
    .faq-q{width:100%;text-align:left;background:var(--rose);border:0;padding:16px 18px;font-size:18px;font-weight:900;color:#fff;cursor:pointer;display:flex;justify-content:space-between;align-items:center}
    .faq-q .mark{font-weight:900;color:#fff}
    .faq-a{max-height:0;overflow:hidden;transition:max-height .28s ease;background:var(--blue);color:#fff}
    .faq-a-inner{padding:16px 18px;font-size:16px;line-height:1.55}
    .faq-item.open .faq-a{max-height:320px}
    .faq-item.open .faq-q .mark{opacity:.9}

    /* Footer */
    footer{padding:28px 0;background:var(--blue);color:#fff;font-size:14px;text-align:center}
  </style>
</head>
<body>

  <!-- Topo -->
  <div class="top-bar">Meditação & Respiração Terapêutica</div>

  <!-- Hero -->
  <div class="hero">
    <div class="wrap">
      <div class="hero-card">
        <h1>Respire fundo. Viva leve.</h1>
        <p class="lead">Uma vivência prática para liberar tensões, equilibrar emoções e cultivar presença através da respiração consciente e meditação guiada.</p>
        <div class="divider"></div>
        <div class="cta">
          <a href="#inscricao" class="btn primary">Quero participar</a>
        </div>
      </div>
    </div>
  </div>

  <!-- O que é / Benefícios -->
  <section>
    <div class="wrap">
      <div class="grid two">
        <div class="card pink">
          <h2 class="grad-left">O que é</h2>
          <p>Uma jornada terapêutica de reconexão com o corpo e a mente. Técnicas de respiração, meditação guiada e exercícios de relaxamento profundo.</p>
        </div>
        <div class="card blue">
          <h2 class="grad-left">Benefícios</h2>
          <ul class="list-check">
            <li>Redução do estresse e ansiedade</li>
            <li>Melhora no foco e clareza mental</li>
            <li>Regulação emocional</li>
            <li>Maior conexão consigo mesmo</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Instrutor -->
  <section>
    <div class="wrap instrutor">
      <h2 class="section-title">Instrutor</h2>
      <img src="https://via.placeholder.com/300" alt="Instrutor da vivência">
      <p><strong>João Silva</strong> — terapeuta holístico especializado em respiração consciente, meditação e bem-estar emocional. Experiência com grupos e atendimentos individuais.</p>
    </div>
  </section>

  <!-- Preço -->
  <section id="inscricao">
    <div class="wrap">
      <h2 class="section-title">Investimento</h2>
      <div class="price-card">
        <div class="price">R$ 197,00</div>
        <p>Vagas limitadas</p>
        <a href="https://wa.me/5599999999999?text=Quero%20garantir%20minha%20vaga%20na%20Meditação%20Terapêutica" class="btn primary" target="_blank">Garantir minha vaga</a>
      </div>
    </div>
  </section>

  <!-- Depoimentos -->
  <section>
    <div class="wrap">
      <h2 class="section-title">Depoimentos</h2>
      <div class="testimonials">
        <div class="t-card"><p class="t-name">Ana</p><p>Saí da vivência muito mais calma e presente. A respiração mudou meu dia a dia.</p></div>
        <div class="t-card"><p class="t-name">Carlos</p><p>A clareza mental e a sensação de leveza foram incríveis. Recomendo a todos.</p></div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section>
    <div class="wrap">
      <h2 class="section-title">Perguntas Frequentes</h2>
      <div class="faq">
        <div class="faq-item">
          <button class="faq-q"><span>Preciso ter experiência prévia?</span><span class="mark">+</span></button>
          <div class="faq-a"><div class="faq-a-inner">Não. A prática é aberta a todos os níveis, desde iniciantes até praticantes avançados.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q"><span>O que devo levar?</span><span class="mark">+</span></button>
          <div class="faq-a"><div class="faq-a-inner">Roupas confortáveis, uma garrafa de água e, se desejar, seu próprio tapete ou almofada.</div></div>
        </div>
        <div class="faq-item">
          <button class="faq-q"><span>Quanto tempo dura?</span><span class="mark">+</span></button>
          <div class="faq-a"><div class="faq-a-inner">A vivência tem duração aproximada de 3 horas.</div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    © 2025 Meditação & Respiração Terapêutica — Todos os direitos reservados.
  </footer>

  <script>
    // FAQ toggle
    document.querySelectorAll('.faq-q').forEach(btn=>{
      btn.addEventListener('click', ()=>{
        const item = btn.parentElement;
        document.querySelectorAll('.faq-item').forEach(i=>{
          if(i!==item) i.classList.remove('open');
        });
        item.classList.toggle('open');
      });
    });
  </script>
</body>
</html>
