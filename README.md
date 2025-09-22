# Mentoria O SEU LUGAR
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>Mentoria O SEU LUGAR | Página de Vendas + Aplicação</title>
  <meta name="description" content="Mentoria O SEU LUGAR — clareza emocional, reconciliação com a história familiar, prosperidade e decisões com segurança. Inscreva-se passando pela aplicação."/>
  <meta name="theme-color" content="#0c4d1f"/>
  <!-- OG -->
  <meta property="og:title" content="Mentoria O SEU LUGAR"/>
  <meta property="og:description" content="Reconstrua sua vida com clareza e segurança. Libere padrões ocultos, cure relações e prospere."/>
  <meta property="og:type" content="website"/>

  <style>
    :root{
      --green-900:#0c4d1f; /* fundo principal (verde escuro do branding) */
      --green-700:#145c27;
      --green-600:#1b6b30;
      --gold-500:#c6a75d; /* dourado do símbolo */
      --gold-600:#b18f3f;
      --stone-100:#f6f6f6;
      --stone-300:#e5e5e5;
      --stone-600:#565656;
      --white:#ffffff;
      --maxw:1100px;
      --radius:18px;
      --shadow:0 8px 30px rgba(0,0,0,.15);
    }
    html,body{margin:0;height:100%;font-family: system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial, 'Noto Sans', 'Liberation Sans', sans-serif;color:#0b0b0b;background:var(--white);}    
    .container{max-width:var(--maxw);margin:0 auto;padding:0 22px;}
    header.hero{background:linear-gradient(180deg, var(--green-900), #0a3c16 75%);color:var(--white);padding:48px 0 24px;}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:16px;}
    .brand{display:flex;align-items:center;gap:14px;}
    .brand img{height:52px;width:auto;border-radius:10px;}
    .brand h1{font-size:22px;margin:0;font-weight:700;letter-spacing:.6px}
    .cta-top{display:flex;gap:12px;flex-wrap:wrap}
    .btn{appearance:none;border:0;border-radius:999px;padding:14px 22px;font-weight:700;cursor:pointer;transition:transform .04s ease, box-shadow .2s ease;}
    .btn:active{transform:translateY(1px)}
    .btn-primary{background:var(--gold-500);color:#1a1a1a;box-shadow:0 6px 18px rgba(198,167,93,.35)}
    .btn-outline{background:transparent;color:var(--white);border:2px solid rgba(255,255,255,.45)}

    .split{display:grid;grid-template-columns: 1.1fr .9fr;gap:32px;align-items:center;padding:28px 0 40px}
    .headline{font-size:42px;line-height:1.1;margin:16px 0 16px}
    .eyebrow{display:inline-block;background:rgba(255,255,255,.12);padding:6px 12px;border-radius:999px;font-size:13px;letter-spacing:.3px}
    .sub{font-size:18px;color:#e9f7ee;max-width:58ch}
    .card{background:var(--white);border-radius:var(--radius);box-shadow:var(--shadow);padding:26px}

    /* BENEFÍCIOS */
    section{padding:54px 0}
    .section-title{font-size:30px;margin:0 0 16px}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .benefit{background:var(--stone-100);border-radius:16px;padding:18px;border:1px solid var(--stone-300)}
    .benefit h4{margin:0 0 8px;font-size:18px}
    .benefit p{margin:0;color:#333}

    /* QUEM SOU */
    .bio{display:grid;grid-template-columns: .95fr 1.05fr;gap:26px;align-items:center}
    .bio ul{margin:0;padding-left:18px}

    /* PREÇO E BÔNUS */
    .price-wrap{display:grid;grid-template-columns:1fr 1fr;gap:22px}
    .price-card{border:2px solid var(--green-700)}
    .price{font-size:40px;color:var(--green-700);margin:10px 0}
    .strike{color:#888;text-decoration:line-through}
    .tag{display:inline-block;background:var(--green-900);color:var(--white);padding:4px 10px;border-radius:999px;font-weight:700;font-size:12px}
    .bonus li{margin-bottom:8px}

    /* FORMULÁRIO */
    #aplicacao{background:linear-gradient(180deg, #0f5a24, var(--green-900));color:var(--white)}
    .form-card{background:var(--white);color:#0b0b0b;border-radius:22px;box-shadow:var(--shadow);padding:26px}
    form{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    form .full{grid-column:1/-1}
    label{display:block;font-weight:700;font-size:13px;margin:6px 0}
    input,select,textarea{width:100%;padding:12px 14px;border:1px solid #d7d7d7;border-radius:12px;font-size:16px;background:#fff}
    textarea{min-height:110px;resize:vertical}
    .consent{display:flex;gap:10px;align-items:flex-start}
    .submit{grid-column:1/-1;display:flex;gap:12px;flex-wrap:wrap}

    /* FAQ */
    details{background:var(--stone-100);border:1px solid var(--stone-300);border-radius:14px;padding:14px}
    details+details{margin-top:10px}
    summary{cursor:pointer;font-weight:700}

    footer{background:#06290f;color:#dfeee6;padding:32px 0;margin-top:40px}
    footer a{color:#dfeee6}

    @media (max-width: 980px){
      .split, .grid-3, .bio, .price-wrap{grid-template-columns:1fr}
      form{grid-template-columns:1fr}
      .headline{font-size:34px}
    }
  </style>
</head>
<body>
  <header class="hero">
    <div class="container">
      <div class="nav">
        <div class="brand">
          <!-- Substitua o src pelo caminho do seu arquivo: coloque 2.jpg na mesma pasta do HTML -->
          <img src="2.jpg" alt="Logo Mentoria O SEU LUGAR" />
          <h1>Mentoria O SEU LUGAR</h1>
        </div>
        <div class="cta-top">
          <a class="btn btn-outline" href="#beneficios">Como funciona</a>
          <a class="btn btn-primary" href="#aplicacao">Quero aplicar</a>
        </div>
      </div>

      <div class="split">
        <div>
          <span class="eyebrow">Transformação sistêmica com base emocional</span>
          <h2 class="headline">Reconstrua sua vida com clareza e segurança.<br/> Libere padrões ocultos. Prospere com leveza.</h2>
          <p class="sub">Uma jornada guiada para curar relações, ressignificar traumas, equilibrar o emocional e tomar decisões com confiança. Processo em grupo com encontros semanais + bônus de acompanhamento individual.</p>
          <div style="display:flex;gap:12px;margin-top:16px">
            <a class="btn btn-primary" href="#aplicacao">Preencher aplicação</a>
            <a class="btn btn-outline" href="#faq">Tirar dúvidas</a>
          </div>
        </div>
        <div class="card">
          <strong style="display:block;color:var(--green-700);text-transform:uppercase;letter-spacing:.8px">Resumo</strong>
          <ul>
            <li>12 semanas • segundas, 19h–22h (ao vivo online)</li>
            <li>Bônus: 4 encontros individuais online</li>
            <li>Turma com vagas limitadas mediante aplicação</li>
          </ul>
          <div style="margin-top:12px">
            <span class="tag">INVESTIMENTO</span>
            <p class="price"><span class="strike">R$ 3.500,00</span>  <strong>por R$ 1.970,00</strong></p>
          </div>
        </div>
      </div>
    </div>
  </header>

  <section id="beneficios">
    <div class="container">
      <h3 class="section-title">Por que essa mentoria funciona</h3>
      <p style="max-width:70ch;color:var(--stone-600)">Resultados esperados pelos participantes ao longo do processo:</p>
      <div class="grid-3" style="margin-top:14px">
        <div class="benefit"><h4>Libertação de padrões familiares</h4><p>Identifique e transforme crenças herdadas que bloqueiam sua vida e seus resultados.</p></div>
        <div class="benefit"><h4>Relacionamentos mais saudáveis</h4><p>Cure laços familiares, afetivos e profissionais para criar conexões autênticas e equilibradas.</p></div>
        <div class="benefit"><h4>Reconciliação com a história</h4><p>Ressignifique traumas e conflitos que impactam suas escolhas e emoções.</p></div>
        <div class="benefit"><h4>Prosperidade e abundância</h4><p>Desbloqueie padrões inconscientes que impedem o fluxo do dinheiro e a realização profissional.</p></div>
        <div class="benefit"><h4>Autoconfiança e clareza</h4><p>Conecte-se com sua força interior para decidir com segurança no presente.</p></div>
        <div class="benefit"><h4>Equilíbrio emocional</h4><p>Libere medos, inseguranças e dores emocionais que afetam sua paz e felicidade.</p></div>
        <div class="benefit"><h4>Alívio de estresse e sintomas</h4><p>Entenda a origem emocional de sintomas físicos/mentais e promova bem‑estar.</p></div>
        <div class="benefit"><h4>Ordem sistêmica</h4><p>Harmonize papéis de pais e filhos, trazendo leveza para a vida.</p></div>
        <div class="benefit"><h4>Segurança para decisões</h4><p>Descubra o seu lugar e siga em frente com confiança e propósito.</p></div>
      </div>
      <div style="margin-top:24px">
        <a href="#aplicacao" class="btn btn-primary">Quero me candidatar</a>
      </div>
    </div>
  </section>

  <section id="quem-sou">
    <div class="container bio">
      <div>
        <img src="2.jpg" alt="Marca Mentoria O SEU LUGAR" style="width:100%;max-width:360px;border-radius:18px;box-shadow:var(--shadow)"/>
      </div>
      <div>
        <h3 class="section-title">Quem conduz a jornada</h3>
        <p>Evandro Favoretto é graduado em Gestão Financeira, pós‑graduado em Neurociência, Psicologia e Saúde Mental, com formação em Constelação Familiar e Empresarial e em Numerologia, além de formação em Meditação e Respiração Terapêutica com renascimento. Atua como empresário, consultor e mentor de vida.</p>
        <ul>
          <li>Metodologia integrativa: emoção, sistêmico, ciência aplicada ao cotidiano.</li>
          <li>Foco em resultados práticos: relações, carreira, finanças e bem‑estar.</li>
          <li>Processo seguro, respeitoso e confidencial.</li>
        </ul>
        <div style="margin-top:16px"><a class="btn btn-outline" href="#aplicacao">Aplicar para a próxima turma</a></div>
      </div>
    </div>
  </section>

  <section id="oferta">
    <div class="container price-wrap">
      <div class="card price-card">
        <h3 style="margin:0 0 6px">Estrutura da Mentoria</h3>
        <ul>
          <li>12 encontros semanais em grupo (ao vivo, online) • segundas 19h–22h</li>
          <li>Comunidade e materiais de apoio</li>
          <li>Acompanhamento por tarefas de integração</li>
        </ul>
        <p class="price"><span class="strike">R$ 3.500,00</span> <strong>por R$ 1.970,00</strong></p>
        <a class="btn btn-primary" href="#aplicacao">Quero aplicar agora</a>
      </div>
      <div class="card">
        <h3 style="margin:0 0 6px">Bônus</h3>
        <ul class="bonus">
          <li>4 encontros individuais on‑line para acelerar sua integração</li>
          <li>Plano pessoal de práticas para equilíbrio emocional</li>
          <li>Prioridade nas vagas de vivências presenciais</li>
        </ul>
        <p style="margin-top:10px;color:var(--stone-600)">* Vagas limitadas mediante aprovação da aplicação.</p>
      </div>
    </div>
  </section>

  <section id="depoimentos" style="background:var(--stone-100)">
    <div class="container">
      <h3 class="section-title">Transformações (depoimentos)</h3>
      <p style="color:var(--stone-600)">Insira aqui prints ou vídeos curtos de clientes (carrossel ou 3 cards). Exemplos: alívio de dores, clareza para decisões, melhoria em relações e finanças.</p>
      <div class="grid-3" style="margin-top:14px">
        <div class="card" style="min-height:140px">[Vídeo/Print 1]</div>
        <div class="card" style="min-height:140px">[Vídeo/Print 2]</div>
        <div class="card" style="min-height:140px">[Vídeo/Print 3]</div>
      </div>
    </div>
  </section>

  <!-- FORMULÁRIO DE APLICAÇÃO -->
  <section id="aplicacao">
    <div class="container">
      <h3 class="section-title" style="color:#fff">Formulário de Aplicação — Mentoria O SEU LUGAR</h3>
      <p style="max-width:75ch;color:#d9f2e3;margin-top:-6px">Preencha com sinceridade. Usaremos suas respostas para entender seu momento, confirmar o encaixe com a mentoria e liberar a matrícula.</p>

      <div class="form-card">
        <!-- IMPORTANTE: Substitua o atributo action abaixo pelo seu endpoint (ex.: Formspree, HubSpot, MailerLite, Google Apps Script).-->
        <!-- Exemplo com Formspree: action="https://formspree.io/f/SEU_ID" method="POST" -->
        <form action="#" method="POST">
          <div>
            <label for="nome">Nome completo</label>
            <input id="nome" name="nome" type="text" required>
          </div>
          <div>
            <label for="email">E‑mail</label>
            <input id="email" name="email" type="email" required>
          </div>
          <div>
            <label for="whats">WhatsApp (DDD + número)</label>
            <input id="whats" name="whatsapp" type="tel" placeholder="(49) 99811-0445" required>
          </div>
          <div>
            <label for="cidade">Cidade/Estado</label>
            <input id="cidade" name="cidade" type="text" placeholder="Ex.: Concórdia/SC">
          </div>
          <div class="full">
            <label for="objetivo">Qual seu objetivo principal com a mentoria?</label>
            <textarea id="objetivo" name="objetivo" required></textarea>
          </div>
          <div class="full">
            <label for="desafios">Quais desafios emocionais/sistêmicos você sente hoje? (ex.: ansiedade, conflitos familiares, finanças travadas)</label>
            <textarea id="desafios" name="desafios" required></textarea>
          </div>
          <div>
            <label for="area">Área que mais deseja transformar</label>
            <select id="area" name="area">
              <option value="relacionamentos">Relacionamentos</option>
              <option value="emocional">Emocional/saúde</option>
              <option value="carreira">Carreira/negócios</option>
              <option value="financas">Finanças/prosperidade</option>
              <option value="familia">Família/papéis sistêmicos</option>
            </select>
          </div>
          <div>
            <label for="horario">Disponibilidade (segundas 19h–22h)</label>
            <select id="horario" name="disponibilidade">
              <option value="ok">Tenho disponibilidade</option>
              <option value="parcial">Consigo ajustar</option>
              <option value="nao">Não consigo nesse horário</option>
            </select>
          </div>
          <div>
            <label for="como-soube">Como soube da mentoria?</label>
            <select id="como-soube" name="como_soube">
              <option>Instagram</option>
              <option>WhatsApp/Indicação</option>
              <option>YouTube</option>
              <option>Evento/Aula</option>
              <option>Outro</option>
            </select>
          </div>
          <div>
            <label for="ticket">Está ciente do investimento?</label>
            <select id="ticket" name="investimento">
              <option value="ciente">Sim, estou ciente do valor</option>
              <option value="duvidas">Tenho dúvidas sobre formas de pagamento</option>
            </select>
          </div>
          <div class="full consent">
            <input id="lgpd" type="checkbox" name="lgpd" required>
            <label for="lgpd">Autorizo o tratamento dos meus dados para análise da aplicação e contato sobre a Mentoria O SEU LUGAR (LGPD). Declaro estar ciente de que vagas são limitadas e dependem de aprovação.</label>
          </div>
          <div class="submit">
            <button class="btn btn-primary" type="submit">Enviar minha aplicação</button>
            <span style="align-self:center;color:#6b6b6b">Tempo estimado: 2–3 minutos</span>
          </div>
        </form>
      </div>
    </div>
  </section>

  <section id="faq">
    <div class="container">
      <h3 class="section-title">Perguntas Frequentes</h3>
      <details>
        <summary>Como são os encontros?</summary>
        <p>Online e ao vivo, via plataforma de videoconferência. A gravação pode ser disponibilizada em casos específicos.</p>
      </details>
      <details>
        <summary>Qual a duração total?</summary>
        <p>12 semanas, com encontros às segundas das 19h às 22h (horário de Brasília).</p>
      </details>
      <details>
        <summary>Como funciona a aprovação?</summary>
        <p>Após enviar sua aplicação, nossa equipe avalia o encaixe e entra em contato para os próximos passos da matrícula.</p>
      </details>
      <details>
        <summary>Existe suporte individual?</summary>
        <p>Sim. Além dos encontros em grupo, você recebe <strong>4 sessões individuais online</strong> como bônus.</p>
      </details>
      <div style="margin-top:18px">
        <a class="btn btn-primary" href="#aplicacao">Quero aplicar</a>
      </div>
    </div>
  </section>

  <footer>
    <div class="container" style="display:flex;flex-direction:column;gap:10px">
      <div>© <span id="y"></span> Mentoria O SEU LUGAR • Todos os direitos reservados</div>
      <div style="font-size:14px;opacity:.85">Dúvidas? Fale no WhatsApp: <a href="https://wa.me/55" target="_blank" rel="noopener">(coloque seu número aqui)</a></div>
    </div>
  </footer>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
