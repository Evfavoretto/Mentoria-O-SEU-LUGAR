<!-- Página com FAQ e fundos verdes -->
<style>
  :root{--green-900:#0c4d1f;--green-800:#0a3c16;--gold-500:#c6a75d;--stone-200:#e7e7e7;--white:#fff;--shadow:0 10px 28px rgba(0,0,0,.14);--radius:18px;--maxw:1120px}
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;line-height:1.5;background:var(--white)}
  .container{max-width:var(--maxw);margin:0 auto;padding:0 20px}

  .hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;text-align:center;padding:56px 20px 40px}
  .hero h1{margin:14px 0 10px;font-size:40px}
  .hero p{max-width:72ch;margin:0 auto 18px;color:#dff3e7}
  .btn{display:inline-block;border:0;border-radius:999px;padding:14px 26px;font-weight:700;cursor:pointer;text-decoration:none}
  .btn-primary{background:var(--gold-500);color:#181818;box-shadow:0 8px 22px rgba(198,167,93,.35)}

  section{padding:56px 0}
  .title{text-align:center;font-size:30px;margin-bottom:24px}

  .green-section{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff}
  .green-section .title{color:#fff}
  .green-box{background:rgba(255,255,255,0.08);border-radius:14px;padding:20px;box-shadow:var(--shadow)}

  .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
  .objective{padding:12px;font-size:16px}

  .bio{max-width:860px;margin:0 auto;font-size:17px;line-height:1.6}

  .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
  .depo{background:rgba(255,255,255,0.08);border-radius:16px;padding:22px;position:relative}
  .depo:before{content:'\201C';position:absolute;top:-12px;left:16px;font-size:52px;color:#cbb67a;opacity:.7}
  .depo p{margin:10px 0 12px;font-size:16px;font-style:italic}
  .depo small{display:block;color:#eee;font-weight:600;text-align:right}

  #aplicacao{background:linear-gradient(180deg,#104c22,var(--green-900));color:#fff}
  .form-wrap{background:#fff;color:#0b0b0b;border-radius:22px;box-shadow:var(--shadow);padding:28px}
  form.app{display:grid;grid-template-columns:1fr 1fr;gap:16px}
  .field{display:flex;flex-direction:column;gap:6px}
  .field label{font-weight:600;font-size:14px}
  .field input,.field select,.field textarea{padding:12px 14px;border:1px solid #ccc;border-radius:12px;font-size:15px}
  .field textarea{min-height:110px;resize:vertical}
  .full{grid-column:1/-1}
  .consent{display:flex;gap:10px;align-items:flex-start}

  .faq-item{background:#fff;border-radius:12px;box-shadow:var(--shadow);margin-bottom:14px;padding:18px}
  .faq-item h4{margin-bottom:8px;color:var(--green-900)}

  .footer{background:#06290f;color:#dfeee6;text-align:center;padding:26px 12px;font-size:14px}
  .footer a{color:#dfeee6}
</style>

<section class="hero">
  <h1>Mentoria O SEU LUGAR</h1>
  <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
  <a class="btn btn-primary" href="#aplicacao">Quero Me Candidatar</a>
</section>

<section class="green-section">
  <div class="container">
    <h3 class="title">Objetivos da Mentoria</h3>
    <div class="objectives">
      <div class="objective">Libertação de padrões familiares limitados</div>
      <div class="objective">Relacionamentos mais saudáveis e harmoniosos</div>
      <div class="objective">Reconciliação com a história da sua família</div>
      <div class="objective">Prosperidade e abundância financeira</div>
      <div class="objective">Autoconfiança e empoderamento pessoal</div>
      <div class="objective">Equilíbrio emocional e mental</div>
      <div class="objective">Alívio de estresse, ansiedade e sintomas psicossomáticos</div>
      <div class="objective">Restauração do papel dos pais e filhos</div>
      <div class="objective">Liberação de cargas emocionais do passado</div>
      <div class="objective">Segurança e clareza para mudanças e decisões</div>
    </div>
  </div>
</section>

<section class="green-section">
  <div class="container">
    <h3 class="title">Quem Conduz</h3>
    <div class="green-box bio">
      <p><strong>Evandro Favoretto</strong> — Graduado em Gestão Financeira, pós‑graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
    </div>
  </div>
</section>

<section id="depoimentos" class="green-section">
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

<!-- FAQ -->
<section class="green-section">
  <div class="container">
    <h3 class="title">Perguntas Frequentes</h3>
    <div class="faq-item">
      <h4>Qual a duração da mentoria?</h4>
      <p>A mentoria acontece em encontros semanais de 3 horas, ao longo de 3 meses, com possibilidade de extensão conforme necessidade.</p>
    </div>
    <div class="faq-item">
      <h4>Preciso ter conhecimento prévio?</h4>
      <p>Não. O processo foi desenvolvido para qualquer pessoa que deseje clareza, equilíbrio e prosperidade.</p>
    </div>
    <div class="faq-item">
      <h4>Posso parcelar o valor?</h4>
      <p>Sim. Existem opções de parcelamento e condições especiais de pagamento.</p>
    </div>
    <div class="faq-item">
      <h4>Os encontros são online ou presenciais?</h4>
      <p>Os encontros podem ocorrer online ao vivo ou presenciais em datas específicas anunciadas.</p>
    </div>
    <div class="faq-item">
      <h4>Existe suporte fora dos encontros?</h4>
      <p>Sim. Você terá acesso a grupo exclusivo e suporte direto durante o período da mentoria.</p>
    </div>
  </div>
</section>

<section class="footer">
  © <span id="y"></span> Mentoria O SEU LUGAR • Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811‑0445</a>
</section>
<script>document.getElementById('y').textContent=new Date().getFullYear()</script>
