<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Mentoria O SEU LUGAR — Página de Vendas</title>
<style>
  :root{
    --green-900:#0c4d1f;    /* verde profundo */
    --green-800:#0a3c16;    /* verde escuro */
    --green-light:#eaf5ec;  /* fundo claro da página */
    --gold-500:#c6a75d;     /* dourado CTA */
    --yellow-canary:#fff176;
    --stone-200:#e7e7e7;
    --shadow:0 10px 28px rgba(0,0,0,.14);
    --maxw:1120px;
  }

  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;line-height:1.55;background:var(--green-light)}
  section{padding:60px 20px}
  .container{max-width:var(--maxw);margin:0 auto;padding:0 20px}

  /* Oculta apenas o título azul padrão do GitHub Pages (se existir) */
  body > h1:first-child{display:none !important;}

  /* HERO */
  .hero{
    background:linear-gradient(180deg,var(--green-900),var(--green-800));
    color:#fff;text-align:center;padding:80px 20px
  }
  .hero-title{
    font-size:clamp(36px,6vw,68px);
    font-weight:900;
    letter-spacing:1.5px;
    text-transform:uppercase;
    color:#fff;
    margin:0 0 16px;
  }
  .hero ul.benefits{
    list-style:none;max-width:880px;margin:0 auto 10px;padding:0;text-align:left
  }
  .hero ul.benefits li{margin:6px 0;font-size:16px;color:#e6f7ef;font-weight:500}
  .hero .hero-kicker{max-width:880px;margin:12px auto 0;color:#dff3e7;font-weight:600;font-size:16px}

  /* Botões */
  .btn{display:inline-block;border-radius:999px;padding:14px 26px;font-weight:800;text-decoration:none;cursor:pointer;transition:.18s}
  .btn-yellow{background:var(--yellow-canary);color:#111;box-shadow:0 8px 22px rgba(0,0,0,.18)}
  .btn-yellow:hover{transform:translateY(-1px);filter:brightness(1.04)}
  .btn-gold{background:var(--gold-500);color:#fff;box-shadow:0 8px 22px rgba(0,0,0,.25)}
  .btn-gold:hover{transform:translateY(-1px);filter:brightness(1.05)}

  /* Títulos de seção */
  .title{font-size:34px;text-align:center;margin:0 0 24px;font-weight:900;color:#0b0b0b}

  /* Objetivos */
  .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
  .objective{border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center}
  .objective.green{background:var(--green-900);color:#fff}
  .objective.white{background:#fff;border:1px solid var(--stone-200);color:#0b0b0b}
  .objective h4{margin-bottom:8px;font-size:18px}
  .objective p{font-size:16px;line-height:1.5;word-break:normal;overflow-wrap:anywhere}

  /* Bio */
  .bio{max-width:860px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:16px;box-shadow:var(--shadow);padding:28px;text-align:center}
  .bio h3{font-size:28px;margin-bottom:10px}
  .bio p{font-size:17px}

  /* Depoimentos */
  .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
  .depo{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:26px;position:relative;font-size:17px}
  .depo:before{content:'\\201C';position:absolute;top:-12px;left:16px;font-size:54px;color:#cbb67a;opacity:.5}
  .depo p{margin:8px 0 12px;font-style:italic}
  .depo small{display:block;color:#444;font-weight:600;text-align:right}

  /* Seção link do formulário */
  #aplicacao{background:linear-gradient(180deg,#104c22,var(--green-900));color:#fff}
  .form-wrap{background:#fff;color:#0b0b0b;border-radius:22px;box-shadow:var(--shadow);padding:28px;text-align:center}
  .cta-stack{display:flex;flex-direction:column;gap:16px;align-items:center}
  .cta-stack .btn{min-width:320px}

  /* Rodapé */
  .footer{background:#06290f;color:#dfeee6;text-align:center;padding:22px;font-size:14px}
  .footer a{color:#dfeee6}

  /* Mobile */
  @media (max-width: 640px){
    section{padding:38px 14px}
    .hero{padding:46px 14px 34px}
    .hero ul.benefits li,.hero .hero-kicker{font-size:15px}
    .btn{width:100%;max-width:520px}
    .objectives{grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:12px}
    .objective h4{font-size:16px}
    .objective p{font-size:15px}
    .depos{grid-template-columns:1fr;gap:14px}
    .depo{font-size:16px;padding:20px}
    .bio{padding:22px}
  }
</style>
</head>
<body>

  <!-- HERO -->
  <section class="hero">
    <h2 class="hero-title">Mentoria O SEU LUGAR</h2>
    <ul class="benefits">
      <li>🔹 Reconstrua sua vida com clareza e segurança.</li>
      <li>🔹 Libere padrões ocultos e transforme desafios em crescimento.</li>
      <li>🔹 Encontre equilíbrio emocional e tome decisões com confiança.</li>
      <li>🔹 Melhore seus relacionamentos, sua carreira e sua prosperidade.</li>
      <li>🔹 Liberte-se da ansiedade, do estresse e dos bloqueios que te impedem de avançar.</li>
      <li>🔹 Descubra seu verdadeiro lugar no mundo e viva com mais leveza e realização.</li>
    </ul>
    <p class="hero-kicker">Seu caminho para uma vida mais plena e alinhada com sua essência começa aqui!</p>
    <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank" rel="noopener">Quero fazer parte</a>
  </section>

  <!-- OBJETIVOS -->
  <section>
    <div class="container">
      <h3 class="title">Objetivos da Mentoria</h3>
      <div class="objectives">
        <div class="objective green"><h4>Libertação</h4><p>Libertação de padrões familiares limitados.</p></div>
        <div class="objective green"><h4>Relacionamentos</h4><p>Relacionamentos mais saudáveis e harmoniosos.</p></div>
        <div class="objective green"><h4>Reconciliação</h4><p>Reconciliação com a história da sua família.</p></div>
        <div class="objective white"><h4>Prosperidade</h4><p>Prosperidade e abundância financeira.</p></div>
        <div class="objective white"><h4>Autoconfiança</h4><p>Autoconfiança e empoderamento pessoal.</p></div>
        <div class="objective white"><h4>Equilíbrio</h4><p>Equilíbrio emocional e mental.</p></div>
        <div class="objective green"><h4>Alívio</h4><p>Alívio de estresse, ansiedade e sintomas psicossomáticos.</p></div>
        <div class="objective green"><h4>Família</h4><p>Restauração do papel dos pais e filhos.</p></div>
        <div class="objective green"><h4>Liberação</h4><p>Liberação de cargas emocionais do passado.</p></div>
        <div class="objective white"><h4>Segurança</h4><p>Segurança e clareza para mudanças e decisões.</p></div>
      </div>
    </div>
  </section>

  <!-- BIO -->
  <section>
    <div class="container">
      <div class="bio">
        <h3>Conheça o seu mentor</h3>
        <p><strong>Evandro Favoretto</strong> — Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
      </div>
    </div>
  </section>

  <!-- DEPOIMENTOS -->
  <section id="depoimentos">
    <div class="container">
      <h3 class="title">Transformações Reais</h3>
      <div class="depos">
        <article class="depo"><p>“Participar da mentoria foi muito importante para mim. Tive resultados e despertares em várias áreas da minha vida — financeira, psicológica e principalmente emocional. Como é bom não ter medo de sentir! Hoje me sinto leve, tranquila e confiante, mais perto do meu sonho de cursar medicina.”</p><small>Participante da Mentoria</small></article>
        <article class="depo"><p>“Aprendi que o dinheiro não é apenas números, mas carrega emoções, histórias e vínculos. Quando olhado com equilíbrio, nos ensina sobre dar e receber e sobre honrar quem veio antes.”</p><small>Alini De Paris</small></article>
        <article class="depo"><p>“Cada dia que nasce é uma oportunidade de evoluir e ter consciência de como se quer viver, observando sentimentos e escolhendo o que terá mais importância. Mentoria Top!”</p><small>Fernando Lovison</small></article>
        <article class="depo"><p>“Aprendi que as emoções podem parecer ruins se não sentidas, mas fazem parte do nosso aprendizado e nos fortalecem para uma nova história.”</p><small>Tonia Bohs</small></article>
        <article class="depo"><p>“Aprendi que a gente pode ressignificar as emoções, transformando elas em aprendizado e força.”</p><small>Mateus Battistela</small></article>
        <article class="depo"><p>“Aprendi que somos capazes de ressignificar cada emoção, aprender a nos tornar mais resilientes e equilibrados.”</p><small>Vania Alebrant</small></article>
      </div>
      <div style="text-align:center;margin-top:40px">
        <a class="btn btn-gold" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank" rel="noopener">
          Já tomei minha decisão — Quero me inscrever agora
        </a>
      </div>
    </div>
  </section>

  <!-- CTA final / link do formulário (opcional manter) -->
  <section id="aplicacao">
    <div class="container">
      <h3 class="title" style="color:#fff">Formulário de Aplicação — Mentoria O SEU LUGAR</h3>
      <div class="form-wrap">
        <p style="margin:0 0 18px;">Clique no botão abaixo para abrir o formulário oficial em nova aba:</p>
        <div class="cta-stack">
          <a class="btn btn-yellow"
             href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform"
             target="_blank" rel="noopener">Enviar minha aplicação</a>
        </div>
      </div>
    </div>
  </section>

  <!-- RODAPÉ -->
  <section class="footer">
    © 2025 Mentoria O SEU LUGAR • Dúvidas? WhatsApp:
    <a href="https://wa.me/5549998110445" target="_blank" rel="noopener">(49) 99811-0445</a>
  </section>

</body>
</html>
