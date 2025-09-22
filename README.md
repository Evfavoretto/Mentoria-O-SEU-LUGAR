<!-- Página ajustada -->
<style>
  :root{--green-900:#0c4d1f;--green-800:#0a3c16;--gold-500:#c6a75d;--stone-200:#e7e7e7;--white:#fff;--shadow:0 10px 28px rgba(0,0,0,.14);--radius:18px;--maxw:1120px;--yellow-50:#FEF9C3}
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;line-height:1.5;background:var(--white)}
  .container{max-width:var(--maxw);margin:0 auto;padding:0 20px}

  .hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;text-align:center;padding:56px 20px 40px}
  .hero h1{margin:14px 0 10px;font-size:40px}
  .hero p{max-width:72ch;margin:0 auto 18px;color:#dff3e7}
  .btn{display:inline-block;border:0;border-radius:999px;padding:14px 26px;font-weight:700;cursor:pointer;text-decoration:none}
  .btn-primary{background:var(--gold-500);color:#181818;box-shadow:0 8px 22px rgba(198,167,93,.35)}
  .btn-yellow{background:#facc15;color:#181818;box-shadow:0 8px 22px rgba(250,204,21,.35)}

  section{padding:56px 0}
  .title{text-align:center;font-size:30px;margin-bottom:24px}

  .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
  .objective{background:var(--white);border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center}
  .objective h4{margin-bottom:8px;color:var(--green-900)}

  .bio{background:var(--white);border-radius:16px;box-shadow:var(--shadow);padding:26px;max-width:860px;margin:0 auto}
  .bio h3{margin-bottom:12px;font-size:26px;color:var(--green-900)}
  .bio p{margin-bottom:8px}

  .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
  .depo{background:var(--white);border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:22px;position:relative}
  .depo:before{content:'\201C';position:absolute;top:-12px;left:16px;font-size:52px;color:#cbb67a;opacity:.5}
  .depo p{margin:10px 0 12px;font-size:16px;font-style:italic}
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

  .bonus-card{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;border:1px solid #0a3c16;border-radius:16px;box-shadow:0 10px 28px rgba(0,0,0,.25);padding:22px}
  .bonus-card h4{margin:0 0 10px;color:#fff;background:rgba(253,224,71,.6);display:inline-block;padding:4px 10px;border-radius:10px}
  .bonus-card ul{margin:0;padding-left:18px;line-height:1.7;color:#fff}
  /* FAQ base (garante abertura/fechamento visível) */
  .faq-item{background:#fff;border-radius:12px;box-shadow:var(--shadow);margin-bottom:14px;overflow:hidden}
  .faq-question{padding:16px;cursor:pointer;display:flex;justify-content:space-between;align-items:center;font-weight:700;color:var(--green-900)}
  .faq-answer{padding:0 16px 16px;display:none;color:#0b0b0b}
  .faq-item.active .faq-answer{display:block}
</style>

<section class="hero">
  <h1>MENTORIA O SEU LUGAR</h1>
  <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
  <a class="btn btn-yellow" href="#aplicacao">Quero fazer parte desse grupo</a>
</section>

<!-- Conteúdo omitido para brevidade -->

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
          <div style="font-size:46px;font-weight:900;line-height:1.1;margin-top:2px"><span style="text-decoration:line-through;opacity:.65">R$ 3.500,00</span> <span style="display:inline-block;background:var(--yellow-50);color:#1a1a1a;padding:2px 8px;border-radius:10px;margin-left:6px">por R$ 1.970,00</span></div>
          <div style="margin-top:6px;font-size:15px;opacity:.9">Você economiza <strong>R$ 1.530,00</strong></div>
        </div>
        <div style="margin-top:16px;display:flex;gap:12px;flex-wrap:wrap">
          <a class="btn btn-yellow" href="#aplicacao">Já tomei minha decisão e quero fazer parte</a>
        </div>
      </div>
      <div class="bonus-card">
        <h4>BÔNUS</h4>
        <ul>
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
        <div class="field"><label for="whats">WhatsApp (DDD + número)</label><input id="whats" name="whatsapp" type="tel" placeholder="(DDD) número" required></div>
        <div class="field"><label for="cidade">Cidade/Estado</label><input id="cidade" name="cidade" type="text"></div>
        <div class="field full"><label for="objetivo">Qual seu objetivo principal com a mentoria?</label><textarea id="objetivo" name="objetivo" required></textarea></div>
        <div class="field full"><label for="desafios">Quais desafios emocionais/sistêmicos você sente hoje?</label><textarea id="desafios" name="desafios" required></textarea></div>
        <div class="field"><label for="area">Área que mais deseja transformar</label><select id="area" name="area"><option>Relacionamentos</option><option>Emocional/saúde</option><option>Carreira/negócios</option><option>Finanças/prosperidade</option><option>Família/papéis sistêmicos</option></select></div>
        <div class="field"><label for="dispon">Disponibilidade (segundas 19h–22h)</label><select id="dispon" name="disponibilidade"><option>Tenho disponibilidade</option><option>Consigo ajustar</option><option>Não consigo nesse horário</option></select></div>
        <div class="field"><label for="origem">Como soube da mentoria?</label><select id="origem" name="como_soube"><option>Instagram</option><option>WhatsApp/Indicação</option><option>YouTube</option><option>Evento/Aula</option><option>Outro</option></select></div>
        <div class="field"><label for="invest">Está ciente do investimento?</label><select id="invest" name="investimento"><option>Sim, estou ciente do valor</option><option>Tenho dúvidas sobre formas de pagamento</option></select></div>
        <div class="field full consent"><input id="lgpd" type="checkbox" required><label for="lgpd">Autorizo o uso dos meus dados para análise da aplicação e contato (LGPD).</label></div>
        <div class="field full" style="display:flex;gap:12px;flex-wrap:wrap;align-items:center">
          <button class="btn btn-yellow" type="submit">Enviar minha aplicação</button>
          <a class="btn btn-yellow" href="https://docs.google.com/forms/d/1mb_cQIEqf2mneyYHMwp_ijb98wwKdtghKM_ZJrDtNYk/viewform" target="_blank" rel="noopener">Abrir formulário em nova aba</a>
        </div>
      </form>
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
