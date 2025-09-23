<!-- Página ajustada com destaques nos objetivos e depoimentos -->
<style>
  :root{--green-900:#0c4d1f;--green-800:#0a3c16;--gold-500:#c6a75d;--yellow-300:#fff176;--stone-200:#e7e7e7;--white:#fff;--shadow:0 10px 28px rgba(0,0,0,.14);--radius:18px;--maxw:1120px}
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;line-height:1.5;background:var(--white)}
  .container{max-width:var(--maxw);margin:0 auto;padding:0 20px}

  .hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;text-align:center;padding:56px 20px 40px}
  .hero h1{margin:14px 0 10px;font-size:42px;letter-spacing:1px}
  .hero p{max-width:72ch;margin:0 auto 18px;color:#dff3e7}
  .btn{display:inline-block;border:0;border-radius:999px;padding:14px 26px;font-weight:700;cursor:pointer;text-decoration:none;transition:.2s}
  .btn-primary{background:var(--yellow-300);color:#181818;box-shadow:0 8px 22px rgba(198,167,93,.35)}
  .btn-primary:hover{filter:brightness(1.05)}

  section{padding:56px 0}
  .title{text-align:center;font-size:34px;margin-bottom:28px;font-weight:800}

  .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
  .objective{border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center;font-size:18px;font-weight:600}
  .objective.white{background:var(--white);border:1px solid var(--stone-200);color:var(--green-900)}
  .objective.green{background:var(--green-900);color:#fff}
  .objective h4{margin-bottom:8px}

  .bio{background:var(--green-900);color:#fff;border-radius:16px;box-shadow:var(--shadow);padding:26px;max-width:860px;margin:0 auto}
  .bio h3{margin-bottom:12px;font-size:28px;color:#fff}
  .bio p{margin-bottom:8px}

  .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
  .depo{background:var(--white);border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:28px;position:relative;font-size:18px}
  .depo:before{content:'\201C';position:absolute;top:-12px;left:16px;font-size:52px;color:#cbb67a;opacity:.5}
  .depo p{margin:10px 0 12px;font-style:italic}
  .depo small{display:block;color:#444;font-weight:600;text-align:right}

  #aplicacao{background:linear-gradient(180deg,#104c22,var(--green-900));color:#fff}
  .form-wrap{background:#fff;color:#0b0b0b;border-radius:22px;box-shadow:var(--shadow);padding:28px}
  form.app{display:grid;grid-template-columns:1fr 1fr;gap:16px}
  .field{display:flex;flex-direction:column;gap:6px}
  .field label{font-weight:600;font-size:14px}
  .field input,.field select,.field textarea{padding:12px 14px;border:1px solid #ccc;border-radius:12px;font-size:15px}
  .field textarea{min-height:110px;resize:vertical}
  .full{grid-column:1/-1}
  .consent{display:flex;gap:10px;align-items:flex-start}

  .footer{background:#06290f;color:#dfeee6;text-align:center;padding:26px 12px;font-size:14px}
  .footer a{color:#dfeee6}
</style>

<section class="hero">
  <h1>MENTORIA O SEU LUGAR</h1>
  <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
  <a class="btn btn-primary" href="#aplicacao">Já decidi e quero fazer parte</a>
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
    <h3 class="title">Transformações Reais</h3>
    <div class="depos">
      <article class="depo"><p>“Participar da mentoria foi muito importante para mim. Tive resultados e despertares em várias áreas da minha vida — financeira, psicológica e principalmente emocional. Como é bom não ter medo de sentir! Hoje me sinto leve, tranquila e confiante, mais perto do meu sonho de cursar medicina.”</p><small>Participante da Mentoria</small></article>
      <article class="depo"><p>“Aprendi que o dinheiro não é apenas números, mas carrega emoções, histórias e vínculos. Quando olhado com equilíbrio, nos ensina sobre dar e receber e sobre honrar quem veio antes.”</p><small>Alini De Paris</small></article>
      <article class="depo"><p>“Cada dia que nasce é uma oportunidade de evoluir e ter consciência de como se quer viver, observando sentimentos e escolhendo o que terá mais importância. Mentoria Top!”</p><small>Fernando Lovison</small></article>
      <article class="depo"><p>“Aprendi que as emoções podem parecer ruins se não sentidas, mas fazem parte do nosso aprendizado e nos fortalecem para uma nova história.”</p><small>Tonia Bohs</small></article>
      <article class="depo"><p>“Aprendi que a gente pode ressignificar as emoções, transformando elas em aprendizado e força.”</p><small>Mateus Battistela</small></article>
      <article class="depo"><p>“Aprendi que somos capazes de ressignificar cada emoção, aprender a nos tornar mais resilientes e equilibrados.”</p><small>Vania Alebrant</small></article>
    </div>
  </div>
</section>

<section id="aplicacao">
  <div class="container">
    <h3 class="title" style="color:#fff">Formulário de Aplicação — Mentoria O SEU LUGAR</h3>
    <div class="form-wrap">
      <form class="app" action="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/formResponse" method="POST" target="hidden_iframe" onsubmit="return handleSubmit();">
        <div class="field"><label for="nome">Nome completo</label><input id="nome" name="entry.1179648702" type="text" required></div>
        <div class="field"><label for="email">E-mail</label><input id="email" name="entry.1143030303" type="email" required></div>
        <div class="field"><label for="whats">WhatsApp (DDD + número)</label><input id="whats" name="entry.2915256" type="tel" required></div>
        <div class="field"><label for="cidade">Cidade/Estado</label><input id="cidade" name="entry.861399822" type="text"></div>
        <div class="field full"><label for="objetivo">Qual seu objetivo principal com a mentoria?</label><textarea id="objetivo" name="entry.1280192492" required></textarea></div>
        <div class="field full"><label for="desafios">Quais desafios emocionais/sistêmicos você sente hoje?</label><textarea id="desafios" name="entry.667930364" required></textarea></div>
        <div class="field"><label for="area">Área que mais deseja transformar</label><select id="area" name="entry.1748955800"><option>Relacionamentos</option><option>Emocional/saúde</option><option>Carreira/negócios</option><option>Finanças/prosperidade</option><option>Família/papéis sistêmicos</option></select></div>
        <div class="field"><label for="dispon">Disponibilidade (segundas 19h–22h)</label><select id="dispon" name="entry.787425964"><option>Tenho disponibilidade</option><option>Consigo ajustar</option><option>Não consigo nesse horário</option></select></div>
        <div class="field"><label for="origem">Como soube da mentoria?</label><select id="origem" name="entry.1556807345"><option>Instagram</option><option>WhatsApp/Indicação</option><option>YouTube</option><option>Evento/Aula</option><option>Outro</option></select></div>
        <div class="field"><label for="invest">Está ciente do investimento?</label><select id="invest" name="entry.159333129"><option>Sim, estou ciente do valor</option><option>Tenho dúvidas sobre formas de pagamento</option></select></div>
        <div class="field full consent"><input id="lgpd" type="checkbox" required><label for="lgpd">Autorizo o uso dos meus dados para análise da aplicação e contato (LGPD).</label></div>
        <div class="field full"><button class="btn btn-primary" type="submit">Enviar minha aplicação</button></div>
        <iframe name="hidden_iframe" id="hidden_iframe" style="display:none;"></iframe>
      </form>
    </div>
  </div>
</section>

<section class="footer">
  © 2025 Mentoria O SEU LUGAR • Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811-0445</a>
</section>

<script>
  var submitted = false;
  var iframe = document.getElementById('hidden_iframe');
  if (iframe) {
    iframe.addEventListener('load', function(){
      if (submitted) { window.location.href = 'obrigado.html'; }
    });
  }
  var submitted = false;
  var lastPayload = '';
  function handleSubmit(){
    submitted = true;
    var f = document.querySelector('#aplicacao form.app');
    if(f){
      var nome = f.querySelector('#nome')?.value || '';
      var email = f.querySelector('#email')?.value || '';
      var whats = f.querySelector('#whats')?.value || '';
      var cidade = f.querySelector('#cidade')?.value || '';
      var objetivo = f.querySelector('#objetivo')?.value || '';
      var desafios = f.querySelector('#desafios')?.value || '';
      var area = f.querySelector('#area')?.value || '';
      var dispon = f.querySelector('#dispon')?.value || '';
      var origem = f.querySelector('#origem')?.value || '';
      var invest = f.querySelector('#invest')?.value || '';
      var msg = `Olá, Evandro! Quero aplicar para a Mentoria O SEU LUGAR.%0A%0A`+
                `Nome: ${nome}%0A`+
                `E-mail: ${email}%0A`+
                `WhatsApp: ${whats}%0A`+
                `Cidade/Estado: ${cidade}%0A`+
                `Objetivo: ${objetivo}%0A`+
                `Desafios: ${desafios}%0A`+
                `Área: ${area}%0A`+
                `Disponibilidade: ${dispon}%0A`+
                `Como soube: ${origem}%0A`+
                `Investimento: ${invest}`;
      lastPayload = msg;
      // Abre o WhatsApp em nova aba com a mensagem pronta
      var wa = 'https://wa.me/5549998110445?text=' + msg;
      window.open(wa, '_blank');
    }
    return true; // continua o submit para o Google Forms (iframe)
  }
  var iframe = document.getElementById('hidden_iframe');
  if (iframe) {
    iframe.addEventListener('load', function(){
      if (submitted) { window.location.href = 'obrigado.html'; }
    });
  }
</script>
