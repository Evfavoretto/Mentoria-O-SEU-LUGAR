
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mentoria O SEU LUGAR</title>
  <style>
    header, .page-header, .site-header, .project-name, .project-tagline {
      display: none !important;
    }

    :root{
      --green-900:#0c4d1f;
      --green-800:#0a3c16;
      --green-soft:#e6f3ea;
      --gold-500:#c6a75d;
      --yellow-canary:#ffeb3b;
      --stone-200:#e7e7e7;
      --shadow:0 10px 28px rgba(0,0,0,.14);
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;background:#eaf5ec}
    .container{max-width:1120px;margin:0 auto;padding:0 20px}
    section{padding:60px 20px}

    /* HERO no topo */
    .hero{
      background:linear-gradient(180deg,var(--green-900),var(--green-800));
      color:#fff;text-align:center;padding:120px 20px 80px;margin-top:0
    }
    .hero h1 {
      font-size: 68px;       /* diminuído de 80px */
      letter-spacing: .5px;
      text-transform: uppercase;
      margin-bottom: 40px;   /* espaço antes da lista */
      font-weight: 900;
    }
    @media (min-width:992px){
      .hero h1{font-size: 80px;}  /* em telas grandes */
    }
    @media (max-width:480px){
      .hero h1{font-size: 36px;}  /* no celular */
    }
    .hero ul.benefits{list-style:none;max-width:880px;margin:10px auto 6px;padding:0;text-align:left}
    .hero ul.benefits li{margin:6px 0}
    .hero .hero-kicker{
      max-width:880px;
      margin:30px auto 30px;
      color:#e8f7ef;
      font-weight:600;
      text-align:center
    }

    /* Botões */
    .btn{display:inline-block;border-radius:999px;padding:16px 30px;font-weight:800;text-decoration:none;cursor:pointer;transition:.18s;font-size:16px}
    .btn-yellow{background:var(--yellow-canary);color:#111;box-shadow:0 8px 22px rgba(0,0,0,.18)}
    .btn-yellow:hover{transform:translateY(-2px);filter:brightness(1.05)}

    /* Títulos de seção */
    .title{font-size:42px;text-align:center;margin:0 0 28px;font-weight:900;color:#0b0b0b}

    /* Objetivos */
    .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
    .objective{border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center}
    .objective.green{background:var(--green-900);color:#fff}
    .objective.white{background:#fff;border:1px solid var(--stone-200);color:#0b0b0b}
    .objective h4{margin-bottom:8px}

    /* Bio */
    .bio{max-width:860px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:16px;box-shadow:var(--shadow);padding:28px;text-align:center}
    .bio h3{font-size:30px;margin-bottom:10px}

    /* Depoimentos */
    .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
    .depo{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:26px;position:relative;font-size:18px}
    .depo:before{content:'\201C';position:absolute;top:-12px;left:16px;font-size:54px;color:#cbb67a;opacity:.5}
    .depo p{margin:8px 0 12px;font-style:italic}
    .depo small{display:block;color:#444;font-weight:600;text-align:right}

    .final-buttons{margin-top:40px;text-align:center;display:flex;flex-direction:column;gap:16px;align-items:center}

    /* Investimento */
    #investimento{background:var(--green-soft);text-align:center}
    #investimento h2{font-size:42px;color:var(--gold-500);margin-bottom:30px;font-weight:900}
    #investimento .tabela{font-size:24px;color:#111;margin-bottom:14px}
    #investimento .tabela span{text-decoration:line-through;color:#444}
    #investimento .promo{font-size:32px;color:var(--gold-500);font-weight:900;margin-bottom:26px}
    #investimento .carga{font-size:22px;color:var(--green-900);margin-bottom:12px}
    #investimento .bonus{font-size:22px;color:#b90000;font-weight:700}

    /* Rodapé */
    .footer{background:#06290f;color:#dfeee6;text-align:center;padding:30px 20px;font-size:14px}
    .footer a{color:#dfeee6}
  </style>
</head>
<body>

<section class="hero">
  <h1>MENTORIA O SEU LUGAR</h1>
  <ul class="benefits">
    <li>🔹 Reconstrua sua vida com clareza e segurança.</li>
    <li>🔹 Libere padrões ocultos e transforme desafios em crescimento.</li>
    <li>🔹 Encontre equilíbrio emocional e tome decisões com confiança.</li>
    <li>🔹 Melhore seus relacionamentos, sua carreira e sua prosperidade.</li>
    <li>🔹 Liberte-se da ansiedade, do estresse e dos bloqueios que te impedem de avançar.</li>
    <li>🔹 Descubra seu verdadeiro lugar no mundo e viva com mais leveza e realização.</li>
  </ul>
  <p class="hero-kicker">Seu caminho para uma vida mais plena e alinhada com sua essência começa aqui!</p>
  <div style="margin-top:30px;">
    <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank">Quero fazer parte</a>
  </div>
</section>

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

<section>
  <div class="container">
    <div class="bio">
      <h3>Conheça o seu mentor</h3>
      <p><strong>Evandro Favoretto</strong> — Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
    </div>
  </div>
</section>

<section id="depoimentos">
  <div class="container">
    <h3 class="title" style="color:var(--green-900)">Transformações Reais</h3>
    <div class="depos">
      <article class="depo"><p>“Participar da mentoria foi muito importante para mim. Tive resultados e despertares em várias áreas da minha vida — financeira, psicológica e principalmente emocional. Como é bom não ter medo de sentir! Hoje me sinto leve, tranquila e confiante, mais perto do meu sonho de cursar medicina.”</p><small>Participante da Mentoria</small></article>
      <article class="depo"><p>“Aprendi que o dinheiro não é apenas números, mas carrega emoções, histórias e vínculos. Quando olhado com equilíbrio, nos ensina sobre dar e receber e sobre honrar quem veio antes.”</p><small>Alini De Paris</small></article>
      <article class="depo"><p>“Cada dia que nasce é uma oportunidade de evoluir e ter consciência de como se quer viver, observando sentimentos e escolhendo o que terá mais importância. Mentoria Top!”</p><small>Fernando Lovison</small></article>
      <article class="depo"><p>“Aprendi que as emoções podem parecer ruins se não sentidas, mas fazem parte do nosso aprendizado e nos fortalecem para uma nova história.”</p><small>Tonia Bohs</small></article>
      <article class="depo"><p>“Aprendi que a gente pode ressignificar as emoções, transformando elas em aprendizado e força.”</p><small>Mateus Battistela</small></article>
      <article class="depo"><p>“Aprendi que somos capazes de ressignificar cada emoção, aprender a nos tornar mais resilientes e equilibrados.”</p><small>Vania Alebrant</small></article>
    </div>

    <div class="final-buttons">
      <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank">Já tomei minha decisão — Quero me inscrever agora</a>
      <a class="btn btn-yellow" href="https://wa.me/5549998110445" target="_blank">Ainda estou com dúvida — Preciso de mais informações</a>
    </div>
  </div>
</section>

<!-- Investimento -->
<section id="investimento" style="background:#fff;padding:60px 20px;text-align:center">
  <h2 style="font-size:42px;color:#c6a75d;margin-bottom:30px;font-weight:900;">Investimento</h2>
  <p style="font-size:24px;color:#111;margin-bottom:14px;">
    <span style="text-decoration:line-through;color:#444;">Tabela: R$ 3.500,00</span>
  </p>
  <p style="font-size:32px;color:#c6a75d;font-weight:900;margin-bottom:26px;">
    POR: R$ 1.970,00
  </p>
  <p style="font-size:22px;color:#0c4d1f;margin-bottom:12px;">
    <strong>12 semanas</strong> (toda segunda-feira) — <strong>19h às 22h</strong>
  </p>
  <p style="font-size:22px;color:#b90000;font-weight:700;">
    BÔNUS: 4 ENCONTROS individuais on-line
  </p>
  <div style="margin-top:40px;">
    <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank">
      Quero garantir minha vaga
    </a>
  </div>
</section>

<section class="footer">
  © 2025 Mentoria O SEU LUGAR • Todos os direitos reservados •
</section>

</body>
</html>
