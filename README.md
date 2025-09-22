# Mentoria O SEU LUGAR

   <!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>Mentoria O SEU LUGAR | Página de Vendas + Aplicação</title>
  <meta name="description" content="Mentoria O SEU LUGAR — clareza emocional, reconciliação com a história familiar, prosperidade e decisões com segurança. Inscreva-se passando pela aplicação."/>
  <meta name="theme-color" content="#0c4d1f"/>
  <style>
    :root{
      --green-900:#0c4d1f;
      --green-700:#145c27;
      --gold-500:#c6a75d;
      --stone-100:#f6f6f6;
      --stone-300:#e5e5e5;
      --stone-600:#565656;
      --white:#ffffff;
      --maxw:1100px;
      --radius:18px;
      --shadow:0 8px 30px rgba(0,0,0,.15);
    }
    body{margin:0;font-family:system-ui,sans-serif;background:var(--white);color:#0b0b0b}
    .container{max-width:var(--maxw);margin:0 auto;padding:0 22px}
    header.hero{background:linear-gradient(180deg, var(--green-900), #0a3c16 75%);color:var(--white);padding:48px 0 24px;text-align:center}
    .brand img{max-height:120px}
    .btn{border:0;border-radius:999px;padding:14px 22px;font-weight:700;cursor:pointer}
    .btn-primary{background:var(--gold-500);color:#1a1a1a}
    .btn-outline{background:transparent;color:var(--white);border:2px solid rgba(255,255,255,.45)}
    .section-title{font-size:30px;margin:0 0 16px;text-align:center}
    .grid-3{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
    .card{background:var(--white);border-radius:var(--radius);box-shadow:var(--shadow);padding:22px}
    footer{background:#06290f;color:#dfeee6;padding:32px 0;margin-top:40px;text-align:center}
    footer a{color:#dfeee6}
  </style>
</head>
<body>
  <header class="hero">
    <div class="brand">
      <!-- Logo oficial com fundo verde, GPS dourado e escrita branca -->
      <img src="2.jpg" alt="Logo Mentoria O SEU LUGAR" />
    </div>
    <h1>Mentoria O SEU LUGAR</h1>
    <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
    <a class="btn btn-primary" href="#aplicacao">Quero Me Candidatar</a>
    <div style="margin-top:16px">
      <img src="2.jpg" alt="Marca Mentoria O SEU LUGAR" style="max-height:80px"/>
    </div>
  </header>

  <section id="quem-sou">
    <div class="container">
      <h3 class="section-title">Quem conduz a jornada</h3>
      <div class="card">
        <!-- Foto pessoal de Evandro -->
        <img src="evandro.jpg" alt="Foto de Evandro Favoretto" style="width:200px;border-radius:50%;margin-bottom:16px"/>
        <p>Evandro Favoretto é graduado em Gestão Financeira, pós‑graduado em Neurociência, Psicologia e Saúde Mental, com formação em Constelação Familiar e Empresarial e em Numerologia. Também possui formação em Meditação e Respiração Terapêutica com renascimento. Atua como empresário, consultor e mentor de vida.</p>
      </div>
    </div>
  </section>

  <section id="depoimentos" style="background:var(--stone-100);padding:40px 0">
    <div class="container">
      <h3 class="section-title">Transformações (Depoimentos)</h3>
      <div class="grid-3">
        <div class="card"><p>“Reconstrui minha vida com clareza e segurança. Liberei padrões ocultos e transformei desafios em crescimento.”</p></div>
        <div class="card"><p>“Melhorei meus relacionamentos e hoje vivo de forma mais leve e equilibrada.”</p></div>
        <div class="card"><p>“Descobri meu verdadeiro lugar no mundo e passei a tomar decisões com confiança.”</p></div>
      </div>
    </div>
  </section>

  <section id="aplicacao" style="padding:40px 0">
    <div class="container">
      <h3 class="section-title">Formulário de Aplicação</h3>
      <form action="#" method="POST" class="card">
        <label>Nome completo<input type="text" name="nome" required></label>
        <label>Email<input type="email" name="email" required></label>
        <label>WhatsApp<input type="tel" name="whatsapp" value="(49) 99811 0445" required></label>
        <label>Objetivo<textarea name="objetivo" required></textarea></label>
        <button class="btn btn-primary" type="submit">Enviar aplicação</button>
      </form>
    </div>
  </section>

  <footer>
    <div>© <span id="y"></span> Mentoria O SEU LUGAR • Todos os direitos reservados</div>
    <div style="font-size:14px;opacity:.85">Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811 0445</a></div>
  </footer>

  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html>
