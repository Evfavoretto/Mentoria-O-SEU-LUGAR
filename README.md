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
      --green-900:#0c4d1f;--green-800:#0a3c16;--green-700:#145c27;--gold-500:#c6a75d;--stone-50:#fafafa;--stone-200:#e8e8e8;--stone-500:#5f5f5f;--white:#ffffff;--maxw:1120px;--radius:18px;--shadow:0 12px 34px rgba(0,0,0,.14)
    }
    *{box-sizing:border-box}
    html,body{margin:0}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;background:var(--white);line-height:1.5}
    .container{max-width:var(--maxw);margin:0 auto;padding:0 20px}
    
    /* HERO */
    header.hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;padding:56px 0 36px;text-align:center}
    .brand img{max-height:120px;width:auto;display:block;margin:0 auto}
    .hero h1{margin:18px 0 8px;font-size:40px;letter-spacing:.4px}
    .hero p{margin:0 auto 18px;max-width:70ch;color:#dff3e7}
    .btn{display:inline-block;border:0;border-radius:999px;padding:14px 24px;font-weight:800;cursor:pointer;text-decoration:none;transition:transform .04s ease,box-shadow .2s ease}
    .btn-primary{background:var(--gold-500);color:#181818;box-shadow:0 10px 26px rgba(198,167,93,.35)}
    .btn-outline{background:transparent;border:2px solid rgba(255,255,255,.5);color:#fff}

    /* Sections */
    .section{padding:56px 0}
    .section-title{font-size:32px;margin:0 0 16px;text-align:center}

    /* Quem conduz */
    .bio{display:grid;grid-template-columns:340px 1fr;gap:26px;align-items:center}
    .bio .photo{width:100%;aspect-ratio:1/1;border-radius:22px;overflow:hidden;box-shadow:var(--shadow)}
    .bio .photo img{width:100%;height:100%;object-fit:cover}

    /* Depoimentos */
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .card{background:var(--stone-50);border:1px solid var(--stone-200);border-radius:16px;padding:18px;box-shadow:var(--shadow)}
    .quote{font-size:16px}

    /* Form */
    #aplicacao{background:linear-gradient(180deg,#104c22,var(--green-900));color:#fff}
    .form-wrap{background:#fff;color:#0b0b0b;border-radius:22px;box-shadow:var(--shadow);padding:26px}
    form.app{display:grid;grid-template-columns:1fr 1fr;gap:16px}
    .field{display:flex;flex-direction:column;gap:8px}
    .field label{font-weight:700;font-size:14px}
    .field input,.field select,.field textarea{width:100%;padding:12px 14px;border:1px solid #d7d7d7;border-radius:12px;font-size:16px;background:#fff}
    .field textarea{min-height:120px;resize:vertical}
    .full{grid-column:1/-1}
    .consent{display:flex;gap:10px;align-items:flex-start}

    footer{background:#06290f;color:#dfeee6;padding:32px 0;margin-top:0;text-align:center}
    footer a{color:#dfeee6}
    @media (max-width:980px){.bio{grid-template-columns:1fr}.grid-3{grid-template-columns:1fr}form.app{grid-template-columns:1fr}.hero h1{font-size:34px}}
  </style>
</head>
<body>
  <header class="hero">
    <div class="brand">
      <img src="2.jpg" alt="Logo Mentoria O SEU LUGAR"/>
    </div>
    <h1>Mentoria O SEU LUGAR</h1>
    <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
    <a class="btn btn-primary" href="#aplicacao">Quero Me Candidatar</a>
    <div style="margin-top:16px"><img src="2.jpg" alt="Marca Mentoria O SEU LUGAR" style="max-height:80px"/></div>
  </header>

  <section id="quem-sou" class="section">
    <div class="container">
      <h3 class="section-title">Quem conduz a jornada</h3>
      <div class="bio">
        <div class="photo"><img src="D05501CF-A5E8-49C0-B116-7B8906497C92.jpeg" alt="Evandro Favoretto"/></div>
        <div>
          <p>Evandro Favoretto é graduado em Gestão Financeira, pós‑graduado em Neurociência, Psicologia e Saúde Mental, com formação em Constelação Familiar e Empresarial e em Numerologia. Também possui formação em Meditação e Respiração Terapêutica com renascimento. Atua como empresário, consultor e mentor de vida.</p>
          <ul>
            <li>Metodologia integrativa: emoção, sistêmico e ciência aplicada.</li>
            <li>Foco em resultados práticos: relações, carreira, finanças e bem‑estar.</li>
            <li>Processo seguro, respeitoso e confidencial.</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="depoimentos" class="section" style="background:var(--stone-50)">
    <div class="container">
      <h3 class="section-title">Transformações reais</h3>
      <div class="grid-3">
        <div class="card"><p class="quote">“Reconstrui minha vida com clareza e segurança. Liberei padrões ocultos e transformei desafios em crescimento.”</p><small>— Participante da Mentoria O SEU LUGAR</small></div>
        <div class="card"><p class="quote">“Melhorei meus relacionamentos e hoje vivo de forma mais leve e equilibrada.”</p><small>— Participante</small></div>
        <div class="card"><p class="quote">“Descobri meu verdadeiro lugar no mundo e passei a tomar decisões com confiança.”</p><small>— Participante</small></div>
      </div>
    </div>
  </section>

  <section id="aplicacao" class="section">
    <div class="container">
      <h3 class="section-title" style="color:#fff">Formulário de Aplicação — Mentoria O SEU LUGAR</h3>
      <div class="form-wrap">
        <form class="app" action="#" method="POST">
          <div class="field"><label for="nome">Nome completo</label><input id="nome" name="nome" type="text" required></div>
          <div class="field"><label for="email">E‑mail</label><input id="email" name="email" type="email" required></div>
          <div class="field"><label for="whats">WhatsApp (DDD + número)</label><input id="whats" name="whatsapp" type="tel" value="(49) 99811‑0445" required></div>
          <div class="field"><label for="cidade">Cidade/Estado</label><input id="cidade" name="cidade" type="text" placeholder="Ex.: Concórdia/SC"></div>
          <div class="field full"><label for="objetivo">Qual seu objetivo principal com a mentoria?</label><textarea id="objetivo" name="objetivo" required></textarea></div>
          <div class="field full"><label for="desafios">Quais desafios emocionais/sistêmicos você sente hoje?</label><textarea id="desafios" name="desafios" required></textarea></div>
          <div class="field"><label for="area">Área que mais deseja transformar</label><select id="area" name="area"><option value="relacionamentos">Relacionamentos</option><option value="emocional">Emocional/saúde</option><option value="carreira">Carreira/negócios</option><option value="financas">Finanças/prosperidade</option><option value="familia">Família/papéis sistêmicos</option></select></div>
          <div class="field"><label for="dispon">Disponibilidade (segundas 19h–22h)</label><select id="dispon" name="disponibilidade"><option value="ok">Tenho disponibilidade</option><option value="parcial">Consigo ajustar</option><option value="nao">Não consigo nesse horário</option></select></div>
          <div class="field"><label for="origem">Como soube da mentoria?</label><select id="origem" name="como_soube"><option>Instagram</option><option>WhatsApp/Indicação</option><option>YouTube</option><option>Evento/Aula</option><option>Outro</option></select></div>
          <div class="field"><label for="invest">Está ciente do investimento?</label><select id="invest" name="investimento"><option value="ciente">Sim, estou ciente do valor</option><option value="duvidas">Tenho dúvidas sobre formas de pagamento</option></select></div>
          <div class="field full consent"><input id="lgpd" type="checkbox" required><label for="lgpd">Autorizo o uso dos meus dados para análise da aplicação e contato (LGPD).</label></div>
          <div class="field full"><button class="btn btn-primary" type="submit">Enviar minha aplicação</button></div>
        </form>
      </div>
    </div>
  </section>

  <footer>
    <div>© <span id="y"></span> Mentoria O SEU LUGAR • Todos os direitos reservados</div>
    <div style="font-size:14px;opacity:.85">Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811‑0445</a></div>
  </footer>

  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html>
