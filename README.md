<!-- Página com depoimentos reais -->
<style>
  :root{--green-900:#0c4d1f;--green-800:#0a3c16;--gold-500:#c6a75d;--stone-200:#e7e7e7;--white:#fff;--shadow:0 10px 28px rgba(0,0,0,.14);--radius:18px;--maxw:1120px}
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;line-height:1.5;background:var(--white)}
  .container{max-width:var(--maxw);margin:0 auto;padding:0 20px}

  /* HERO */
  .hero{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;text-align:center;padding:56px 20px 40px}
  .hero .brand img{max-height:120px}
  .hero h1{margin:14px 0 10px;font-size:40px}
  .hero p{max-width:70ch;margin:0 auto 20px;color:#dff3e7}
  .btn{display:inline-block;border:0;border-radius:999px;padding:14px 26px;font-weight:700;cursor:pointer;text-decoration:none}
  .btn-primary{background:var(--gold-500);color:#181818;box-shadow:0 8px 22px rgba(198,167,93,.35)}

  /* DEPOIMENTOS */
  section{padding:56px 0}
  .title{text-align:center;font-size:30px;margin-bottom:24px}
  .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
  .depo{background:var(--white);border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:22px;position:relative}
  .depo:before{content:'\201C';position:absolute;top:-12px;left:16px;font-size:52px;color:#cbb67a;opacity:.5}
  .depo p{margin:10px 0 12px;font-size:16px;font-style:italic}
  .depo small{display:block;color:#444;font-weight:600;text-align:right}

  /* FORM */
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
  <div class="brand"><img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/4gHYSUNDX1BST0ZJTEUAAQEAAAHIAAAAAAQwAABtbnRyUkdCIFhZWiAH4AABAAEAAAAAA..." alt="Logo Mentoria O SEU LUGAR"/></div>
  <h1>Mentoria O SEU LUGAR</h1>
  <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
  <a class="btn btn-primary" href="#aplicacao">Quero Me Candidatar</a>
</section>

<section id="depoimentos">
  <div class="container">
    <h3 class="title">Transformações Reais</h3>
    <div class="depos">
      <article class="depo">
        <p>“Participar da mentoria foi muito importante para mim. Tive resultados e despertares em várias áreas da minha vida — financeira, psicológica e principalmente emocional. Como é bom não ter medo de sentir! Hoje me sinto leve, tranquila e confiante, mais perto do meu sonho de cursar medicina.”</p>
        <small>Participante da Mentoria</small>
      </article>
      <article class="depo">
        <p>“Aprendi que o dinheiro não é apenas números, mas carrega emoções, histórias e vínculos. Quando olhado com equilíbrio, nos ensina sobre dar e receber e sobre honrar quem veio antes.”</p>
        <small>Alini De Paris</small>
      </article>
      <article class="depo">
        <p>“Cada dia que nasce é uma oportunidade de evoluir e ter consciência de como se quer viver, observando sentimentos e escolhendo o que terá mais importância. Mentoria Top!”</p>
        <small>Fernando Lovison</small>
      </article>
      <article class="depo">
        <p>“Aprendi que as emoções podem parecer ruins se não sentidas, mas fazem parte do nosso aprendizado e nos fortalecem para uma nova história.”</p>
        <small>Tonia Bohs</small>
      </article>
      <article class="depo">
        <p>“Aprendi que a gente pode ressignificar as emoções, transformando elas em aprendizado e força.”</p>
        <small>Mateus Battistela</small>
      </article>
      <article class="depo">
        <p>“Aprendi que somos capazes de ressignificar cada emoção, aprender a nos tornar mais resilientes e equilibrados.”</p>
        <small>Vania Alebrant</small>
      </article>
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

<section class="footer">
  © <span id="y"></span> Mentoria O SEU LUGAR • Dúvidas? WhatsApp: <a href="https://wa.me/5549998110445" target="_blank">(49) 99811‑0445</a>
</section>
<script>document.getElementById('y').textContent=new Date().getFullYear()</script>
