<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mentoria O SEU LUGAR</title>
  <style>
    :root{
      --green-900:#0c4d1f;
      --green-800:#0a3c16;
      --gold-500:#c6a75d;
      --yellow-200:#fff68f;
      --stone-200:#e7e7e7;
      --shadow:0 10px 28px rgba(0,0,0,.14);
    }
    body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;background:#fff}
    section{padding:60px 20px}
    h1,h2,h3{margin:0 0 16px}
    .hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;text-align:center;padding:80px 20px}
    .hero h1{font-size:42px;text-transform:uppercase}
    .btn{display:inline-block;border-radius:999px;padding:14px 26px;font-weight:700;text-decoration:none;cursor:pointer}
    .btn-yellow{background:var(--yellow-200);color:#000}
    .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
    .objective{border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center}
    .objective.green{background:var(--green-900);color:#fff}
    .objective.white{background:#fff;border:1px solid var(--stone-200)}
    .bio{max-width:800px;margin:0 auto;text-align:center}
    .bio h3{font-size:28px;color:var(--green-900)}
    .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
    .depo{background:#fff;border-radius:16px;box-shadow:var(--shadow);padding:20px;position:relative}
    .depo:before{content:'“';position:absolute;top:-12px;left:12px;font-size:48px;color:#cbb67a;opacity:.5}
    .investment{background:var(--green-900);color:#fff;border-radius:18px;max-width:800px;margin:0 auto;padding:30px;text-align:center}
    .bonus{background:var(--green-800);color:#fff;border-radius:14px;padding:16px;margin-top:16px}
    details{background:var(--yellow-200);margin-bottom:10px;padding:14px;border-radius:10px}
    details summary{cursor:pointer;font-weight:600}
    form{display:grid;grid-template-columns:1fr 1fr;gap:16px;max-width:800px;margin:0 auto}
    form .full{grid-column:1/-1}
    form input,form textarea,form select{padding:12px;border-radius:12px;border:1px solid #ccc}
    .footer{background:#06290f;color:#dfeee6;text-align:center;padding:20px;font-size:14px}
  </style>
</head>
<body>

<section class="hero">
  <h1>Mentoria O SEU LUGAR</h1>
  <p>Reconstrua sua vida com clareza, segurança e prosperidade emocional.</p>
  <a class="btn btn-yellow" href="#formulario">Já decidi e quero fazer parte</a>
</section>

<section>
  <h2 style="text-align:center">Objetivos da Mentoria</h2>
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
</section>

<section>
  <div class="bio">
    <h3>Conheça o seu mentor</h3>
    <p><strong>Evandro Favoretto</strong> — Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
  </div>
</section>

<section>
  <h2 style="text-align:center">Transformações Reais</h2>
  <div class="depos">
    <div class="depo"><p>“Participar da mentoria foi muito importante para mim. Tive resultados em várias áreas da vida — financeira, psicológica e emocional. Hoje me sinto leve, tranquila e confiante.”</p><small>Participante</small></div>
    <div class="depo"><p>“Aprendi que o dinheiro carrega emoções, histórias e vínculos. Quando olhado com equilíbrio, nos ensina sobre dar e receber.”</p><small>Alini De Paris</small></div>
    <div class="depo"><p>“Cada dia que nasce é uma oportunidade de evoluir e ter consciência de como se quer viver. Mentoria Top!”</p><small>Fernando Lovison</small></div>
    <div class="depo"><p>“Aprendi que as emoções fazem parte do aprendizado e nos fortalecem para uma nova história.”</p><small>Tonia Bohs</small></div>
  </div>
</section>

<section>
  <div class="investment">
    <h2>Investimento & Estrutura</h2>
    <p><del>R$3.500</del> <strong>por apenas R$1.970</strong><br>
    12 semanas — segundas-feiras, das 19h às 22h</p>
    <div class="bonus">
      <h3>🎁 Bônus Exclusivos</h3>
      <ul style="text-align:left;max-width:500px;margin:0 auto">
        <li>4 encontros individuais online</li>
        <li>Materiais e tarefas de integração</li>
        <li>Suporte no grupo durante a mentoria</li>
      </ul>
    </div>
  </div>
</section>

<section>
  <h2 style="text-align:center">Perguntas Frequentes</h2>
  <div style="max-width:800px;margin:0 auto">
    <details>
      <summary>Como funciona a mentoria?</summary>
      <p>São 12 encontros semanais em grupo, via Zoom, além de 4 encontros individuais e suporte durante todo o processo.</p>
    </details>
    <details>
      <summary>Preciso ter experiência anterior?</summary>
      <p>Não. A mentoria foi desenhada para qualquer pessoa em busca de clareza, equilíbrio e prosperidade.</p>
    </details>
    <details>
      <summary>Como é feito o pagamento?</summary>
      <p>Você pode pagar à vista ou parcelado no cartão de crédito. Mais detalhes serão enviados após sua aplicação.</p>
    </details>
  </div>
</section>

<section id="formulario">
  <h2 style="text-align:center">Formulário de Aplicação</h2>
  <iframe name="hidden_iframe" style="display:none;"></iframe>
  <form id="appForm"
    action="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/formResponse"
    method="POST" target="hidden_iframe">

    <input class="full" type="text" name="entry.1179648702" placeholder="Nome completo" required>
    <input type="email" name="entry.1143030303" placeholder="E-mail" required>
    <input type="tel" name="entry.2915256" placeholder="WhatsApp (DDD + número)" required>
    <input type="text" name="entry.861399822" placeholder="Cidade/Estado">

    <textarea class="full" name="entry.1280192492" placeholder="Qual seu objetivo principal?" required></textarea>
    <textarea class="full" name="entry.667930364" placeholder="Quais desafios emocionais/sistêmicos você sente hoje?" required></textarea>

    <select name="entry.1748955800" class="full">
      <option>Relacionamentos</option>
      <option>Emocional/saúde</option>
      <option>Carreira/negócios</option>
      <option>Finanças/prosperidade</option>
      <option>Família/papéis sistêmicos</option>
    </select>

    <select name="entry.787425964" class="full">
      <option>Tenho disponibilidade</option>
      <option>Consigo ajustar</option>
      <option>Não consigo nesse horário</option>
    </select>

    <select name="entry.1556807345" class="full">
      <option>Instagram</option>
      <option>WhatsApp/Indicação</option>
      <option>YouTube</option>
      <option>Evento/Aula</option>
      <option>Outro</option>
    </select>

    <select name="entry.1363258938" class="full">
      <option>Sim, estou ciente do valor</option>
      <option>Tenho dúvidas sobre formas de pagamento</option>
    </select>

    <button type="submit" class="btn btn-yellow full">Enviar minha aplicação</button>
  </form>
</section>

<section class="footer">
  © 2025 Mentoria O SEU LUGAR • Todos os direitos reservados
</section>

<script>
  document.getElementById("appForm").addEventListener("submit", function() {
    setTimeout(function() {
      window.location.href = "/obrigado.html"; 
    }, 1000);
  });
</script>

</body>
</html>
