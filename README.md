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
      --green-900:#0c4d1f;--green-800:#0a3c16;--gold-500:#c6a75d;--stone-50:#fafafa;--stone-200:#e8e8e8;--white:#ffffff;--shadow:0 12px 34px rgba(0,0,0,.14)
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;background:var(--white);line-height:1.5}
    .container{max-width:1100px;margin:0 auto;padding:0 20px}

    header.hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;padding:60px 20px;text-align:center}
    .brand img{max-height:120px;width:auto}
    .hero h1{margin:20px 0 10px;font-size:42px;letter-spacing:.5px}
    .hero p{max-width:70ch;margin:0 auto 20px;color:#e6f5ec}
    .btn{display:inline-block;border:0;border-radius:999px;padding:14px 26px;font-weight:700;cursor:pointer;text-decoration:none}
    .btn-primary{background:var(--gold-500);color:#181818;box-shadow:0 10px 26px rgba(198,167,93,.35)}

    .section{padding:56px 0}
    .section-title{font-size:30px;text-align:center;margin-bottom:24px}

    /* Depoimentos */
    .depo-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
    .depo-card{background:var(--white);border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:22px;display:flex;flex-direction:column;align-items:center;text-align:center}
    .depo-card p{font-size:16px;font-style:italic;margin-bottom:10px}
    .depo-card small{color:#555;font-weight:600}

    /* Form */
    #aplicacao{background:linear-gradient(180deg,#104c22,var(--green-900));color:#fff}
    .form-wrap{background:#fff;color:#0b0b0b;border-radius:22px;box-shadow:var(--shadow);padding:28px}
    form.app{display:grid;grid-template-columns:1fr 1fr;gap:16px}
    .field{display:flex;flex-direction:column;gap:6px}
    .field label{font-weight:600;font-size:14px}
    .field input,.field select,.field textarea{padding:12px 14px;border:1px solid #ccc;border-radius:12px;font-size:15px}
    .field textarea{min-height:110px;resize:vertical}
    .full{grid-column:1/-1}
    .consent{display:flex;gap:10px;align-items:flex-start}

    footer{background:#06290f;color:#dfeee6;padding:28px 0;text-align:center;font-size:14px}
    footer a{color:#dfeee6}
    @media(max-width:900px){form.app{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header class="hero">
    <div class="brand"><img src="2.jpg" alt="Logo Mentoria O SEU LUGAR"/></div>
    <h1>Mentoria O SEU LUGAR</h1>
    <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
    <a class="btn btn-primary" href="#aplicacao">Quero Me Candidatar</a>
    <div style="margin-top:18px"><img src="2.jpg" alt="Marca Mentoria O SEU LUGAR" style="max-height:70px"/></div>
  </header>

  <section id="depoimentos" class="section" style="background:var(--stone-50)">
    <div class="container">
      <h3 class="section-title">Transformações Reais</h3>
      <div class="depo-grid">
        <div class="depo-card">
          <p>“Minha ansiedade diminuiu e voltei a ter energia para a vida. Consegui organizar as relações em casa e no trabalho.”</p>
          <small>Participante da Mentoria</small>
        </div>
        <div class="depo-card">
          <p>“Destravei as finanças e tomei decisões que eu adiava há anos. A clareza que encontrei aqui mudou tudo.”</p>
          <small>Participante da Mentoria</small>
        </div>
        <div class="depo-card">
          <p>“Ressignifiquei dores antigas da minha família e consegui reconectar com meus pais com leveza e respeito.”</p>
          <small>Participante da Mentoria</small>
        </div>
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
          <div class="field"><label for="cidade">Cidade/Estado</label><input id="cidade" name="cidade" type="text"></div>
          <div class="field full"><label for="objetivo">Qual seu objetivo principal com a mentoria?</label><textarea id="objetivo" name="objetivo" required></textarea></div>
          <div class="field full"><label for="desafios">Quais desafios emocionais/sistêmicos você sente hoje?</label><textarea id="desafios" name="desafios" required></textarea></div>
          <div class="field"><label for="area">Área que mais deseja transformar</label><select id="area" name="area"><option>Relacionamentos</option><option>Emocional/saúde</option><option>Carreira/negócios</option><option>Finanças/prosperidade</option><option>Família/papéis sistêmicos</option></select></div>
          <div class="field"><label for="dispon">Disponibilidade (segundas 19h–22h)</label><select id="dispon" name="disponibilidade"><option>Tenho disponibilidade</option><option>Consigo ajustar</option><option>Não consigo nesse horário</option></select></div>
          <div class="field"><label for="origem">Como soube da mentoria?</label><select id="origem" name="como_soube"><option>Instagram</option><option>WhatsApp/Indicação</option><option>YouTube</option><option>Evento/Aula</option><option>Outro</option></select></div>
          <div class="field"><label for="invest">Está ciente do investimento?</label><select id="invest" name="investimento"><option>Sim, estou ciente do valor</option><option>Tenho dúvidas sobre formas de pagamento</option></select></div>
          <div class="field full consent"><input id="lgpd" type="checkbox" required><label for="lgpd">Autorizo o uso dos meus dados para análise da aplicação e contato (LGPD).</label></div>
          <div class="field full"><button class="btn btn-primary" type="submit">Enviar minha aplicação</button></div>
        </form>
      </div>
    </div>
  </section>

  <footer>
    <div>© <span id="y"></span> Mentoria O SEU LUGAR • Todos os direitos reservados</div>
    <div>Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811‑0445</a></div>
  </footer>

  <script>document.getElementById('y').textContent=new Date().getFullYear()</script>
</body>
</html>
