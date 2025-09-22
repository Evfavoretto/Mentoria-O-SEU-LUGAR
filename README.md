<!-- Página com FAQ accordion corrigido e sem título azul -->
<style>
  :root{--green-900:#0c4d1f;--green-800:#0a3c16;--gold-500:#c6a75d;--yellow-400:#FDE047;--stone-200:#e7e7e7;--white:#fff;--shadow:0 10px 28px rgba(0,0,0,.14);--radius:18px;--maxw:1120px}
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
.footer a{color:#dfeee6}
  /* Oculta título externo (ex.: GitHub Pages) */
  body>h1{display:none !important}
.footer a{color:#dfeee6}
  /* Oculta título externo (ex.: GitHub Pages) */
  body>h1{display:none !important}
</style>

<section class="hero">
  <h1>MENTORIA O SEU LUGAR</h1>
  <p>Reconstrua sua vida com clareza e segurança. Libere padrões ocultos. Prospere com leveza.</p>
  <a class="btn btn-yellow" href="#aplicacao">Quero fazer parte desse grupo</a>
</section>

<!-- resto do conteúdo da página permanece igual -->

<script>
// Countdown
function startCountdown(duration) {
  var timer = duration, minutes, seconds;
  var display = document.getElementById('countdown');
  setInterval(function () {
    minutes = parseInt(timer / 60, 10);
    seconds = parseInt(timer % 60, 10);
    minutes = minutes < 10 ? "0" + minutes : minutes;
    seconds = seconds < 10 ? "0" + seconds : seconds;
    display.textContent = minutes + ":" + seconds;
    if (--timer < 0) {
      display.textContent = "Tempo esgotado";
    }
  }, 1000);
}
window.onload = function () {
  var fifteenMinutes = 60 * 15;
  startCountdown(fifteenMinutes);
};

// FAQ Accordion toggle
const faqQuestions=document.querySelectorAll('.faq-question');
faqQuestions.forEach(q=>{
  q.addEventListener('click',()=>{
    q.parentElement.classList.toggle('active');
  });
});
// Countdown (já existente)
function startCountdown(duration) {
  var timer = duration, minutes, seconds;
  var display = document.getElementById('countdown');
  setInterval(function () {
    minutes = parseInt(timer / 60, 10);
    seconds = parseInt(timer % 60, 10);
    minutes = minutes < 10 ? "0" + minutes : minutes;
    seconds = seconds < 10 ? "0" + seconds : seconds;
    if(display){display.textContent = minutes + ":" + seconds;}
    if (--timer < 0 && display) { display.textContent = "Tempo esgotado"; }
  }, 1000);
}

// FAQ Accordion – abre/fecha respostas
(function(){
  var items = document.querySelectorAll('.faq-item');
  items.forEach(function(it){
    var q = it.querySelector('.faq-question');
    if(!q) return;
    q.addEventListener('click', function(){ it.classList.toggle('active'); });
  });
  // Abrir item via hash (ex.: #faq-parcelar)
  if(location.hash){
    var target = document.querySelector(location.hash);
    if(target && target.classList.contains('faq-item')){
      target.classList.add('active');
      setTimeout(function(){ target.scrollIntoView({behavior:'smooth', block:'start'}); }, 100);
    }
  }
})();

window.onload = function () {
  var fifteenMinutes = 60 * 15;
  startCountdown(fifteenMinutes);
};
// Countdown (já existente)
function startCountdown(duration) {
  var timer = duration, minutes, seconds;
  var display = document.getElementById('countdown');
  setInterval(function () {
    minutes = parseInt(timer / 60, 10);
    seconds = parseInt(timer % 60, 10);
    minutes = minutes < 10 ? "0" + minutes : minutes;
    seconds = seconds < 10 ? "0" + seconds : seconds;
    if(display){display.textContent = minutes + ":" + seconds;}
    if (--timer < 0 && display) { display.textContent = "Tempo esgotado"; }
  }, 1000);
}

// FAQ Accordion – abre/fecha respostas
(function(){
  var items = document.querySelectorAll('.faq-item');
  items.forEach(function(it){
    var q = it.querySelector('.faq-question');
    if(!q) return;
    q.addEventListener('click', function(){ it.classList.toggle('active'); });
  });
})();

window.onload = function () {
  var fifteenMinutes = 60 * 15;
  startCountdown(fifteenMinutes);
};
</script>
