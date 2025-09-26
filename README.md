
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mentoria O SEU LUGAR</title>
  <style>
    header, .page-header, .site-header, .project-name, .project-tagline {
      display: none !important;
    }

    :root{
      --green-900:#0c4d1f;
      --green-800:#0a3c16;
      --green-soft:#e6f3ea;
      --gold-500:#c6a75d;
      --yellow-canary:#ffeb3b;
      --stone-200:#e7e7e7;
      --red-700:#c62828;
      --shadow:0 10px 28px rgba(0,0,0,.14);
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:#0b0b0b;background:#eaf5ec}
    .container{max-width:1120px;margin:0 auto;padding:0 20px}
    section{padding:60px 20px}

    /* HERO no topo */
    .hero{
      background:linear-gradient(180deg,var(--green-900),var(--green-800));
      color:#fff;text-align:center;padding:120px 20px 80px;margin-top:0
    }
    .hero h1 {
      font-size: 68px;
      letter-spacing: .5px;
      text-transform: uppercase;
      margin-bottom: 40px;
      font-weight: 900;
    }
    @media (min-width:992px){.hero h1{font-size: 80px}}
    @media (max-width:480px){.hero h1{font-size: 36px}}
    .hero ul.benefits{list-style:none;max-width:880px;margin:10px auto 6px;padding:0;text-align:left}
    .hero ul.benefits li{margin:6px 0}
    .hero .hero-kicker{max-width:880px;margin:30px auto 30px;color:#e8f7ef;font-weight:600;text-align:center}

    /* Botões */
    .btn{display:inline-block;border-radius:999px;padding:16px 30px;font-weight:800;text-decoration:none;cursor:pointer;transition:.18s;font-size:16px}
    .btn-yellow{background:var(--yellow-canary);color:#111;box-shadow:0 8px 22px rgba(0,0,0,.18)}
    .btn-yellow:hover{transform:translateY(-2px);filter:brightness(1.05)}

    /* Títulos de seção */
    .title{font-size:42px;text-align:center;margin:0 0 28px;font-weight:900;color:#0b0b0b}

    /* Trustbar */
    .trustbar{background:#fff;padding:18px 0;border-top:1px solid var(--stone-200);border-bottom:1px solid var(--stone-200)}
    .trust{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:10px;align-items:center;text-align:center}
    .trust-item{background:#f8fbf9;border:1px solid var(--stone-200);border-radius:999px;padding:10px 14px;font-weight:700;color:var(--green-900)}

    /* Objetivos */
    .objectives{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
    .objective{border-radius:16px;box-shadow:var(--shadow);padding:18px;text-align:center}
    .objective.green{background:var(--green-900);color:#fff}
    .objective.white{background:#fff;border:1px solid var(--stone-200);color:#0b0b0b}
    .objective h4{margin-bottom:8px}

    /* Bio */
    .bio{max-width:860px;margin:0 auto;background:var(--green-900);color:#fff;border-radius:16px;box-shadow:var(--shadow);padding:28px;text-align:center}
    .bio h3{font-size:30px;margin-bottom:10px}

    /* Depoimentos */
    .depos{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
    .depo{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:26px;position:relative;font-size:18px}
    .depo:before{content:'\201C';position:absolute;top:-12px;left:16px;font-size:54px;color:#cbb67a;opacity:.5}
    .depo p{margin:8px 0 12px;font-style:italic}
    .depo small{display:block;color:#444;font-weight:600;text-align:right}
    .depo-footer{display:flex;gap:10px;align-items:center;justify-content:flex-end}
    .avatar{width:32px;height:32px;border-radius:50%;object-fit:cover;border:1px solid var(--stone-200)}

    .final-buttons{margin-top:40px;text-align:center;display:flex;flex-direction:column;gap:16px;align-items:center}

    /* Passo a passo */
    #como-funciona .steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
    #como-funciona .step{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:18px}
    #como-funciona .step .num{width:36px;height:36px;border-radius:50%;background:var(--green-900);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:900;margin-bottom:10px}
    #como-funciona h4{margin:4px 0 6px;font-size:18px;color:var(--green-900)}

    /* FAQ (fundo verde; perguntas em verde forte; respostas brancas) */
    #faq{background:linear-gradient(180deg,var(--green-900),var(--green-800));color:#fff;padding-top:60px;padding-bottom:60px}
    #faq .title{color:#fff}
    .faq{max-width:900px;margin:0 auto;display:flex;flex-direction:column;gap:12px}
    .faq-item{border:1px solid rgba(255,255,255,.15);border-radius:14px;background:#fff;box-shadow:var(--shadow);overflow:hidden}
    .faq-q{width:100%;text-align:left;background:#fff;padding:16px 18px;font-weight:900;font-size:18px;cursor:pointer;display:flex;align-items:center;justify-content:space-between;color:var(--green-900)}
    .faq-q:hover{background:#fffde7}
    .faq-q span{flex:1;color:var(--green-900)}
    .faq-q::after{content:'▸';font-size:18px;transition:.18s;margin-left:14px;color:#111}
    .faq-item.active .faq-q::after{transform:rotate(90deg)}
    .faq-a{display:none;padding:0 18px 18px 18px;color:#2c2c2c;font-size:16px;line-height:1.6;background:#fff}
    .faq-item.active .faq-a{display:block}

    /* Investimento — vermelho/verde */
    #investimento{background:var(--green-soft);text-align:center}
    #investimento h2{font-size:42px;color:var(--red-700);margin-bottom:30px;font-weight:900}
    #investimento .tabela{font-size:28px;color:#111;margin-bottom:14px}
    #investimento .tabela span{text-decoration:line-through;color:var(--green-900);font-weight:900}
    #investimento .promo{font-size:36px;color:var(--red-700);font-weight:900;margin-bottom:26px}
    #investimento .carga{font-size:22px;color:var(--green-900);margin-bottom:12px}
    #investimento .bonus{font-size:22px;color:#b90000;font-weight:700}

    /* Garantia / Transparência */
    #garantia .guarantee-card{background:#fff;border:1px solid var(--stone-200);border-radius:16px;box-shadow:var(--shadow);padding:24px;max-width:880px;margin:0 auto;text-align:center}
    #garantia h3{color:var(--green-900);margin-bottom:10px}
    #garantia small{display:block;margin-top:10px;color:#444}

    /* Rodapé */
    .footer{background:#06290f;color:#dfeee6;text-align:center;padding:30px 20px;font-size:14px}
    .footer a{color:#dfeee6}
  </style>
</head>
<body>

<!-- HERO -->
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
  <div style="margin-top:30px;">
    <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank">Quero fazer parte</a>
  </div>
</section>

<!-- TRUSTBAR -->
<section class="trustbar">
  <div class="container trust">
    <div class="trust-item">🔒 Dados protegidos (LGPD)</div>
    <div class="trust-item">✅ Seleção por aplicação (sem cobrança agora)</div>
    <div class="trust-item">🎯 Metodologia prática e humana</div>
    <div class="trust-item">📞 Suporte no WhatsApp</div>
  </div>
</section>

<!-- OBJETIVOS -->
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

<!-- BIO -->
<section>
  <div class="container">
    <div class="bio">
      <h3>Conheça o seu mentor</h3>
      <p><strong>Evandro Favoretto</strong> — Graduado em Gestão Financeira, pós-graduado em Neurociência, Psicologia e Saúde Mental. Formação em Constelação Familiar e Empresarial, formação em Numerologia, empresário, consultor e mentor de vida. Também possui formação em Meditação e Respiração Terapêutica com renascimento.</p>
    </div>
  </div>
</section>

<!-- DEPOIMENTOS -->
<section id="depoimentos">
  <div class="container">
    <h3 class="title" style="color:var(--green-900)">Transformações Reais</h3>
    <div class="depos">
      <article class="depo"><p>“Participar da mentoria foi muito importante para mim. Tive resultados e despertares em várias áreas da minha vida — financeira, psicológica e principalmente emocional. Como é bom não ter medo de sentir! Hoje me sinto leve, tranquila e confiante, mais perto do meu sonho de cursar medicina.”</p><small>Diego</small></article>
      <article class="depo"><p>“Aprendi que o dinheiro não é apenas números, mas carrega emoções, histórias e vínculos. Quando olhado com equilíbrio, nos ensina sobre dar e receber e sobre honrar quem veio antes.”</p><small>Alini De Paris</small></article>
      <article class="depo"><p>“Cada dia que nasce é uma oportunidade de evoluir e ter consciência de como se quer viver, observando sentimentos e escolhendo o que terá mais importância. Mentoria Top!”</p><small>Fernando Lovison</small></article>
      <article class="depo"><p>“Aprendi que as emoções podem parecer ruins se não sentidas, mas fazem parte do nosso aprendizado e nos fortalecem para uma nova história.”</p><small>Tonia Bohs</small></article>
      <article class="depo"><p>“Aprendi que a gente pode ressignificar as emoções, transformando elas em aprendizado e força.”</p><small>Mateus Battistela</small></article>
      <article class="depo"><p>“Aprendi que somos capazes de ressignificar cada emoção, aprender a nos tornar mais resilientes e equilibrados.”</p><small>Vania Alebrant</small></article>
    </div>

    <div class="final-buttons">
      <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank">Já tomei minha decisão — Quero me inscrever agora</a>
      <a class="btn btn-yellow" href="https://wa.me/5549998110445" target="_blank">Ainda estou com dúvida — Preciso de mais informações</a>
    </div>
  </div>
</section>

<!-- COMO FUNCIONA -->
<section id="como-funciona">
  <div class="container">
    <h3 class="title">Como vai funcionar depois que você aplicar</h3>
    <div class="steps">
      <div class="step">
        <div class="num">1</div>
        <h4>Envie a aplicação</h4>
        <p>Leva de 3 a 5 minutos. Suas respostas nos ajudam a entender seu momento.</p>
      </div>
      <div class="step">
        <div class="num">2</div>
        <h4>Retorno pelo WhatsApp</h4>
        <p>Entraremos em contato para alinhar objetivos, tirar dúvidas e confirmar o encaixe.</p>
      </div>
      <div class="step">
        <div class="num">3</div>
        <h4>Confirmação da vaga</h4>
        <p>Você recebe as instruções de início e pagamento <strong>somente após aprovação</strong>.</p>
      </div>
      <div class="step">
        <div class="num">4</div>
        <h4>Primeiro encontro</h4>
        <p>Segundas, 19h–22h. Começamos com objetivos e um plano de integração simples.</p>
      </div>
    </div>
  </div>
</section>

<!-- FAQ -->
<section id="faq">
  <div class="container">
    <h3 class="title">Perguntas Frequentes</h3>
    <div class="faq" role="tablist" aria-label="Perguntas Frequentes">
      <div class="faq-item active">
        <button class="faq-q" role="tab" aria-expanded="true"><span>Para quem é a Mentoria O SEU LUGAR?</span></button>
        <div class="faq-a" role="region">
          A mentoria é para quem quer ter uma vida mais leve e feliz. É para você que sente que carrega pesos emocionais/sistêmicos que impactam relacionamentos, decisões e prosperidade. Para você que sente que carrega o mundo nas costas, para quem sente dores e não aparece em exame algum. Ideal para quem busca leveza, clareza e um caminho prático de mudança com base em constelação familiar/empresarial, Psicologia, Neurociência, Psicanálise, Saúde Mental e integração emocional.
        </div>
      </div>

      <div class="faq-item">
        <button class="faq-q" role="tab" aria-expanded="false"><span>Como funciona na prática?</span></button>
        <div class="faq-a" role="region">
          São <strong>12 semanas</strong>, encontros em grupo às <strong>segundas, 19h–22h</strong>, com tarefas de integração entre encontros. Você terá também <strong>4 encontros individuais on-line (bônus)</strong> para aprofundar temas específicos.
        </div>
      </div>

      <div class="faq-item">
        <button class="faq-q" role="tab" aria-expanded="false"><span>Qual é o investimento?</span></button>
        <div class="faq-a" role="region">
          De <s>R$ 3.500,00</s> por <strong>R$ 1.970,00</strong>. Condições e formas de pagamento são alinhadas após a aplicação aprovada.
        </div>
      </div>

      <div class="faq-item">
        <button class="faq-q" role="tab" aria-expanded="false"><span>Como faço minha inscrição?</span></button>
        <div class="faq-a" role="region">
          Clique em <strong>“Quero me inscrever agora”</strong>. Você será direcionado ao <strong>Formulário de Aplicação</strong> no Google Forms. Após enviar, entraremos em contato pelo WhatsApp para os próximos passos.
        </div>
      </div>

      <div class="faq-item">
        <button class="faq-q" role="tab" aria-expanded="false"><span>E se eu tiver dúvidas antes de aplicar?</span></button>
        <div class="faq-a" role="region">
          Sem problema. Use o botão <strong>“Preciso de mais informações”</strong> para falar comigo no WhatsApp: <a href="https://wa.me/5549998110445" target="_blank" style="color:#0c4d1f;font-weight:700;">(49) 99811-0445</a>.
        </div>
      </div>

      <div class="faq-item">
        <button class="faq-q" role="tab" aria-expanded="false"><span>Há suporte entre os encontros?</span></button>
        <div class="faq-a" role="region">
          Sim. Você contará com orientação no grupo da mentoria durante o período do programa, além das tarefas de integração para consolidar o aprendizado.
        </div>
      </div>
    </div>
  </div>
</section>

<!-- INVESTIMENTO -->
<section id="investimento">
  <h2>Investimento</h2>
  <p class="tabela">
    <span>Tabela: R$ 3.500,00</span>
  </p>
  <p class="promo">POR: R$ 1.970,00</p>
  <p class="carga"><strong>12 semanas</strong> (toda segunda-feira) — <strong>19h às 22h</strong></p>
  <p class="bonus">BÔNUS: 4 ENCONTROS individuais on-line</p>
  <div style="margin-top:40px;">
    <a class="btn btn-yellow" href="https://docs.google.com/forms/d/e/1FAIpQLScOxe1PnumYWjnWFqyRKV2Bh2d58vuKwlacx8ZjvSODdvEQVw/viewform" target="_blank">
      Quero garantir minha vaga
    </a>
    <p style="margin-top:10px;color:#444;font-size:14px;">
      🔒 Seus dados são usados apenas para contato e análise da aplicação (LGPD).
    </p>
  </div>
</section>

<!-- GARANTIA / TRANSPARÊNCIA -->
<section id="garantia">
  <div class="container">
    <div class="guarantee-card">
      <h3>Transparência & Compromisso</h3>
      <p>O pagamento só acontece após a aprovação da sua aplicação e alinhamento pelo WhatsApp. Você entra com segurança e no seu tempo.</p>
      <!-- Se tiver garantia específica, descomente e edite:
      <p><strong>Garantia 7 dias:</strong> caso você perceba que não é para você, cancelamos sua participação.</p>
      -->
      <small>Seus dados são usados apenas para análise e contato (LGPD). Nunca compartilhamos com terceiros.</small>
    </div>
  </div>
</section>

<!-- FIT: É / NÃO É PARA VOCÊ -->
<section id="fit">
  <div class="container">
    <h3 class="title">É para você se...</h3>
    <div class="objectives">
      <div class="objective white"><p>Quer clareza emocional e sistêmica para decidir com segurança.</p></div>
      <div class="objective white"><p>Está pronto(a) para praticar integração entre encontros.</p></div>
      <div class="objective white"><p>Busca um processo guiado, humano e direto ao ponto.</p></div>
    </div>

    <h3 class="title" style="margin-top:28px">Não é para você se...</h3>
    <div class="objectives">
      <div class="objective green"><p>Procura fórmula mágica sem envolvimento pessoal.</p></div>
      <div class="objective green"><p>Quer resultado sem abrir espaço para sentir e compreender.</p></div>
      <div class="objective green"><p>Não pretende reservar 3h semanais + pequenas práticas.</p></div>
    </div>
  </div>
</section>

<!-- RODAPÉ -->
<section class="footer">
  © 2025 Mentoria O SEU LUGAR • Todos os direitos reservados • Dúvidas? <a href="https://wa.me/5549998110445" target="_blank">WhatsApp</a>
</section>

<script>
  // FAQ: abre uma pergunta por vez
  document.querySelectorAll('.faq-q').forEach(function(btn){
    btn.addEventListener('click', function(){
      const item = btn.parentElement;
      const list = item.parentElement.querySelectorAll('.faq-item');
      list.forEach(i => {
        if(i !== item){ 
          i.classList.remove('active');
          i.querySelector('.faq-q').setAttribute('aria-expanded','false');
        }
      });
      const isActive = item.classList.toggle('active');
      btn.setAttribute('aria-expanded', isActive ? 'true' : 'false');
    });
  });
</script>

</body>
</html>
