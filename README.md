<style>
  :root{
    --green-900:#0c4d1f;
    --green-800:#0a3c16;
    --gold-500:#c6a75d;
    --yellow-canary:#fff176;
    --stone-200:#e7e7e7;
    --shadow:0 10px 28px rgba(0,0,0,.14);
  }
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;background:#eaf5ec}

  h1:first-of-type {display:none!important} /* esconde título azul */

  section{padding:60px 20px}

  .hero{
    background:linear-gradient(180deg,var(--green-900),var(--green-800));
    color:#fff;text-align:center;
    padding:100px 20px 80px;
  }

  .hero h1{
    font-size:60px;        /* bem grande */
    font-weight:900;       /* bem forte */
    text-transform:uppercase;
    color:#fff;            /* branco puro */
    margin-bottom:30px;
    letter-spacing:2px;    /* espaçamento para destacar */
  }

  .btn{display:inline-block;border-radius:999px;padding:14px 26px;font-weight:800;text-decoration:none;cursor:pointer;transition:.18s}
  .btn-yellow{background:var(--yellow-canary);color:#111;box-shadow:0 8px 22px rgba(0,0,0,.18)}
  .btn-yellow:hover{transform:translateY(-1px);filter:brightness(1.03)}
  .btn-gold{background:var(--gold-500);color:#fff;box-shadow:0 8px 22px rgba(0,0,0,.25)}
  .btn-gold:hover{transform:translateY(-1px);filter:brightness(1.05)}

  /* ...restante do CSS igual... */
</style>

<section class="hero">
  <h1>MENTORIA O SEU LUGAR</h1>
  <ul class="benefits">
    <li>🔹 Reconstrua sua vida com clareza e segurança.</li>
    <li>🔹 Libere padrões ocultos e transforme desafios em crescimento.</li>
    <li>🔹 Encontre equilíbrio emocional e tome decisões com confiança.</li>
    <li>🔹 Melhore seus relacionamentos, sua carreira e sua prosperidade.</li>
    <li>🔹 Liberte-se da ansiedade, do estresse e dos bloqueios que te impedem de avançar.</li>
    <li>🔹 Descubra seu verdadeiro lugar no mundo e viva com mais leveza e realização.</li>
  </ul>
  <p class="hero-kicker">Seu caminho para uma vida mais plena e alinhada com sua essência começa aqui!</p>
  <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank">Quero fazer parte</a>
</section>
