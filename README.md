<!-- Página ajustada com destaques nos objetivos e depoimentos -->
<style>
  :root{
    --green-900:#0c4d1f; /* verde profundo da sua marca */
    --green-800:#0a3c16; /* verde escuro para degradê/segundo plano */
    --gold-500:#c6a75d; /* dourado da marca (detalhes) */
    --yellow-canary:#fff176; /* amarelo canário dos CTAs/FAQ */
    --stone-200:#e7e7e7;
    --shadow:0 10px 28px rgba(0,0,0,.14);
  }
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;background:#fff}
  section{padding:60px 20px}

  /* HERO com o degradê original verde e título em caixa alta */
  .hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;text-align:center;padding:80px 20px}
  .hero h1{font-size:46px;letter-spacing:.5px;text-transform:uppercase}
  .btn{display:inline-block;border-radius:999px;padding:14px 26px;font-weight:800;text-decoration:none;cursor:pointer;transition:.18s}
  .btn-yellow{background:var(--yellow-canary);color:#111;box-shadow:0 8px 22px rgba(0,0,0,.18)}
  .btn-yellow:hover{transform:translateY(-1px);filter:brightness(1.03)}

  /* Títulos maiores conforme pedido */
  h2.title, .title{font-size:34px;text-align:center;margin:0 0 24px;font-weight:900;color:#0b0b0b}

  /* OBJETIVOS com cards verdes/brancos alternados (controle manual por classe) */
  .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
  .objective{border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center}
  .objective.green{background:var(--green-900);color:#fff}
  .objective.white{background:#fff;border:1px solid var(--stone-200);color:#0b0b0b}
  .objective h4{margin-bottom:8px}

  /* BLOCO BIO em verde com tipografia branca */
  .bio{max-width:860px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:16px;box-shadow:var(--shadow);padding:28px;text-align:center}
  .bio h3{font-size:28px;margin-bottom:10px}

  /* DEPOIMENTOS com tipografia maior e aspas douradas suaves */
  .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
  .depo{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:26px;position:relative;font-size:18px}
  .depo:before{content:'C';position:absolute;top:-12px;left:16px;font-size:54px;color:#cbb67a;opacity:.5}
  .depo p{margin:8px 0 12px;font-style:italic}
  .depo small{display:block;color:#444;font-weight:600;text-align:right}

  /* INVESTIMENTO & BÔNUS (verdes com texto branco) */
  .investment{background:radial-gradient(1200px 400px at 10% -10%, #1a6a33, var(--green-900));color:#fff;border-radius:18px;max-width:880px;margin:0 auto;padding:32px;text-align:center;box-shadow:0 18px 38px rgba(0,0,0,.25)}
  .bonus{background:radial-gradient(1200px 400px at 10% -10%, #145a2a, var(--green-800));color:#fff;border-radius:14px;padding:18px;margin-top:18px}

  /* FAQ em amarelo canário com setinhas nativas */
  details{background:var(--yellow-canary);margin:0 auto 10px;max-width:880px;padding:14px;border-radius:12px;box-shadow:var(--shadow)}
  details summary{cursor:pointer;font-weight:800;color:#111}
  details p{margin-top:10px}

  /* FORM: inputs arredondados e grade 2 colunas */
  form{display:grid;grid-template-columns:1fr 1fr;gap:16px;max-width:880px;margin:0 auto}
  form .full{grid-column:1/-1}
  form input,form textarea,form select{padding:12px;border-radius:12px;border:1px solid #ccc;font-size:16px}

  .footer{background:#06290f;color:#dfeee6;text-align:center;padding:22px;font-size:14px}
  /* Benefícios no hero */
  .hero ul.benefits{list-style:none;max-width:880px;margin:10px auto 6px;padding:0;text-align:left}
  .hero ul.benefits li{margin:6px 0}
  .hero .hero-kicker{max-width:880px;margin:10px auto 0;color:#e8f7ef;font-weight:600}
</style>

<section class="hero">
  <h1><span class='logo-icon'>📍</span> MENTORIA O SEU LUGAR<\/h1>
  <ul class="benefits">
    <li>🔹 Reconstrua sua vida com clareza e segurança.</li>
    <li>🔹 Libere padrões ocultos e transforme desafios em crescimento.</li>
    <li>🔹 Encontre equilíbrio emocional e tome decisões com confiança.</li>
    <li>🔹 Melhore seus relacionamentos, sua carreira e sua prosperidade.</li>
    <li>🔹 Liberte-se da ansiedade, do estresse e dos bloqueios que te impedem de avançar.</li>
    <li>🔹 Descubra seu verdadeiro lugar no mundo e viva com mais leveza e realização.</li>
  </ul>
  <p class="hero-kicker">Seu caminho para uma vida mais plena e alinhada com sua essência começa aqui!</p>
  <a class="btn btn-yellow" href="#aplicacao">Já decidi e quero fazer parte</a>
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
      <form class="app" action="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/formResponse" method="POST" target="hidden_iframe" onsubmit="submitted=true;">
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
        <div class="field full"><button class="btn btn-yellow" type="submit">Enviar minha aplicação</button></div>
        <!-- Campos ocultos necessários para o Google Forms -->
        <input type="hidden" name="fvv" value="1">
        <input type="hidden" name="pageHistory" value="0">
        <input type="hidden" name="fbzx" id="fbzx" value="">
        <!-- Ocultos necessários / compatibilidade Google Forms -->
        <input type="hidden" name="fvv" value="1">
        <input type="hidden" name="pageHistory" value="0">
        <input type="hidden" name="fbzx" id="fbzx" value="">
        
        <!-- Perguntas obrigatórias fixas do seu Form (defaults) -->
        <input type="hidden" name="entry.1363258938" value="Sim, estou pronto(a)">
        <input type="hidden" name="entry.1159568625" value="Sim">
        <input type="hidden" name="entry.1258011610" value="Sim, me comprometo">
        <input type="hidden" name="entry.361069271" value="1.970,00">
        <input type="hidden" name="entry.687114195" value="1">
        <input type="hidden" name="entry.94360950" value="1">

        <iframe name="hidden_iframe" id="hidden_iframe" style="display:none;"></iframe>
      </form>
    </div>
  </div>
</section>

<section class="footer">
  © 2025 Mentoria O SEU LUGAR • Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811-0445</a>
</section>

<script>
  // Envio silencioso para o Google Forms + redirecionamento para Obrigado
  var submitted = false;

  // Gera fbzx dinâmico (boa prática)
  (function(){
    var i = document.getElementById('fbzx');
    if (i) { i.value = String(Math.random()).slice(2) + Date.now(); }
  })();

  var iframe = document.getElementById('hidden_iframe');
  if (iframe) {
    iframe.addEventListener('load', function(){
      if (submitted) { window.location.href = 'obrigado.html'; }
    });
  }
</script>

  ©️ 2025 Mentoria O SEU LUGAR • Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811-0445</a>
</section>
