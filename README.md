<!-- Landing Page – Mentoria O SEU LUGAR -->
<style>
  :root{--green-900:#0c4d1f;--green-800:#0a3c16;--gold-500:#c6a75d;--yellow-400:#FDE047;--yellow-100:#FEF9C3;--stone-200:#e7e7e7;--white:#fff;--shadow:0 10px 28px rgba(0,0,0,.14);--radius:18px;--maxw:1120px}
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;line-height:1.5;background:var(--white)}
  .container{max-width:var(--maxw);margin:0 auto;padding:0 20px}

  .hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;text-align:center;padding:56px 20px 40px}
  .hero h1{margin:14px 0 10px;font-size:48px;letter-spacing:1px}
  .hero p{max-width:72ch;margin:0 auto 18px;color:#dff3e7}
  .btn{display:inline-block;border:0;border-radius:999px;padding:14px 26px;font-weight:700;cursor:pointer;text-decoration:none}
  .btn-yellow{background:var(--yellow-400);color:#1a1a1a;box-shadow:0 8px 22px rgba(253,224,71,.45)}

  section{padding:56px 0}
  .title{text-align:center;font-size:34px;margin-bottom:24px}

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

  /* FAQ Accordion */
  .faq-item{background:#fff;border-radius:12px;box-shadow:var(--shadow);margin-bottom:14px;overflow:hidden}
  .faq-question{padding:16px;cursor:pointer;display:flex;justify-content:space-between;align-items:center;font-weight:600;color:#0c4d1f}
  .faq-answer{padding:0 16px 16px;display:none;color:#0b0b0b}
  .faq-item.active .faq-answer{display:block}
  .faq-item svg{transition:transform .3s}
  .faq-item.active svg{transform:rotate(90deg)}

  .footer{background:#06290f;color:#dfeee6;text-align:center;padding:26px 12px;font-size:14px}
  .footer a{color:#dfeee6}
</style>

<section class="hero">
  <h1>MENTORIA O SEU LUGAR</h1>
  <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
  <a class="btn btn-yellow" href="#aplicacao">Quero fazer parte desse grupo</a>
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
    <h3 class="title">Conheça o Seu Mentor</h3>
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

<section>
  <div class="container">
    <h3 class="title" style="font-size:38px">INVESTIMENTO & ESTRUTURA</h3>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:18px;align-items:stretch">
      <div style="background:radial-gradient(1200px 400px at 10% -10%, #1a6a33, #0c4d1f);color:#fff;border-radius:16px;box-shadow:0 18px 38px rgba(0,0,0,.25);padding:24px;position:relative;overflow:hidden">
        <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap">
          <span style="display:inline-block;background:#063019;padding:6px 12px;border-radius:999px;font-size:12px;font-weight:800;letter-spacing:.4px">TURMA AO VIVO</span>
          <span style="display:inline-block;background:#063019;padding:6px 12px;border-radius:999px;font-size:12px;font-weight:800;letter-spacing:.4px">12 SEMANAS</span>
          <span style="display:inline-block;background:#063019;padding:6px 12px;border-radius:999px;font-size:12px;font-weight:800;letter-spacing:.4px">SEGUNDAS 19H–22H</span>
        </div>
        <div style="margin-top:14px">
          <div style="font-size:16px;opacity:.95">Investimento</div>
          <div style="font-size:44px;font-weight:900;line-height:1.1;margin-top:2px"><span style="text-decoration:line-through;opacity:.65">R$ 3.500,00</span> <span style="display:inline-block;background:var(--yellow-400);color:#1a1a1a;padding:2px 8px;border-radius:10px;margin-left:6px">por R$ 1.970,00</span></div>
          <div style="margin-top:6px;font-size:15px;opacity:.9">Você economiza <strong>R$ 1.530,00</strong></div>
        </div>
        <div style="margin-top:16px;display:flex;gap:12px;flex-wrap:wrap">
          <a class="btn btn-yellow" href="#aplicacao">Já tomei minha decisão e quero fazer parte</a>
        </div>
      </div>
      <div style="background:var(--yellow-100);border:1px solid #efe3a6;border-radius:16px;box-shadow:0 10px 28px rgba(0,0,0,.12);padding:22px">
        <h4 style="margin:0 0 10px;color:#0c4d1f;background:rgba(253,224,71,.6);display:inline-block;padding:4px 10px;border-radius:10px">BÔNUS</h4>
        <ul style="margin:0;padding-left:18px;line-height:1.7;color:#0b0b0b;font-weight:600">
          <li><strong>4 encontros individuais online</strong> para acelerar a sua integração</li>
          <li>Materiais e tarefas de integração entre encontros</li>
          <li>Suporte no grupo durante o período da mentoria</li>
        </ul>
      </div>
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
        <div class="field full"><button class="btn btn-yellow" type="submit">Enviar minha aplicação</button></div>
      </form>
    </div>
  </div>
</section>

<section class="green-section">
  <div class="container">
    <h3 class="title">Perguntas Frequentes</h3>
    <div class="faq-item">
      <div class="faq-question">Qual a duração da mentoria?<svg width="16" height="16" fill="currentColor"><path d="M6 4l4 4-4 4"/></svg></div>
      <div class="faq-answer"><p>A mentoria acontece em encontros semanais de 3 horas, ao longo de 3 meses, com possibilidade de extensão conforme necessidade.</p></div>
    </div>
    <div class="faq-item">
      <div class="faq-question">Preciso ter conhecimento prévio?<svg width="16" height="16" fill="currentColor"><path d="M6 4l4 4-4 4"/></svg></div>
      <div class="faq-answer"><p>Não. O processo foi desenvolvido para qualquer pessoa que deseje clareza, equilíbrio e prosperidade.</p></div>
    </div>
    <div class="faq-item">
      <div class="faq-question">Posso parcelar o valor?<svg width="16" height="16" fill="currentColor"><path d="M6 4l4 4-4 4"/></svg></div>
      <div class="faq-answer"><p>Sim. Existem opções de parcelamento e condições especiais de pagamento.</p></div>
    </div>
    <div class="faq-item">
      <div class="faq-question">Os encontros são online ou presenciais?<svg width="16" height="16" fill="currentColor"><path d="M6 4l4 4-4 4"/></svg></div>
      <div class="faq-answer"><p>Os encontros podem ocorrer online ao vivo ou presenciais em datas específicas anunciadas.</p></div>
    </div>
    <div class="faq-item">
      <div class="faq-question">Existe suporte fora dos encontros?<svg width="16" height="16" fill="currentColor"><path d="M6 4l4 4-4 4"/></svg></div>
      <div class="faq-answer"><p>Sim. Você terá acesso a grupo exclusivo e suporte direto durante o período da mentoria.</p></div>
    </div>
  </div>
</section>

<section class="footer">
  Direitos Autorais • Mentoria O SEU LUGAR © 2025
</section>

<script>
// FAQ acordeão: uma aberta por vez
(function(){
  var items = document.querySelectorAll('.faq-item');
  items.forEach(function(item){
    var q = item.querySelector('.faq-question');
    if(!q) return;
    q.addEventListener('click', function(){
      items.forEach(function(other){ if(other!==item) other.classList.remove('active'); });
      item.classList.toggle('active');
    });
  });
})();
</script>
