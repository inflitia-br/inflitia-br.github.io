<!doctype html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Inflitia | Criação de sites que vendem</title>
<meta name="description" content="A Inflitia cria sites rápidos, bonitos e pensados para transformar visitante em cliente. Peça um orçamento gratuito.">
<meta property="og:title" content="Inflitia | Criação de sites que vendem">
<meta property="og:description" content="Sites rápidos, feitos sob medida e pensados para gerar contatos e vendas.">
<meta property="og:type" content="website">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' fill='%23000'/%3E%3Crect x='38' y='14' width='24' height='56' fill='%236FF7FF'/%3E%3Cpath d='M50 54 78 90H22z' fill='%23E8336B'/%3E%3C/svg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{--paper:#FAFBFB;--ink:#000;--cyan:#6FF7FF;--pink:#E8336B;--focus:#E8336B;--pad:clamp(20px,5vw,80px)}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--ink);font:400 18px/1.55 Inter,system-ui,sans-serif}
a{color:inherit}
:focus-visible{outline:4px solid var(--focus);outline-offset:4px}
.dark{--focus:var(--cyan)}
.on-pink{--focus:#000}
h1,h2,h3,.display{font-family:Anton,Impact,"Arial Narrow",sans-serif;font-weight:400;text-transform:uppercase;margin:0}
h1{font-size:clamp(64px,13.5vw,200px);line-height:.92}
h2{font-size:clamp(44px,7.5vw,104px);line-height:.95}
section,header,footer{padding-left:var(--pad);padding-right:var(--pad)}
.wrap{max-width:1280px;margin:0 auto}
.btn{display:inline-block;padding:20px 32px;background:var(--ink);color:var(--paper);font:700 20px/1 Inter,sans-serif;text-decoration:none;border:4px solid var(--ink);cursor:pointer;transition:background .15s,color .15s}
.btn:hover{background:var(--pink);border-color:var(--pink);color:#000}
.btn.light{background:var(--paper);color:#000;border-color:var(--paper)}
.btn.light:hover{background:var(--cyan);border-color:var(--cyan)}
.link{font-weight:700;text-underline-offset:6px}

/* topo */
header{display:flex;justify-content:space-between;align-items:center;gap:20px;padding-top:28px;padding-bottom:28px;position:relative;z-index:2}
.logo{font:400 40px/1 Anton,Impact,sans-serif;text-decoration:none;letter-spacing:1px}
nav{display:flex;align-items:center;gap:32px}
nav a{font-weight:500;text-decoration:none}
nav a:hover{text-decoration:underline;text-underline-offset:6px}
nav .btn{padding:14px 22px;font-size:17px;color:var(--paper)}
@media(max-width:760px){nav a:not(.btn){display:none}}

/* hero */
.hero{position:relative;overflow:hidden;padding-top:clamp(40px,8vw,110px);padding-bottom:clamp(70px,10vw,140px)}
.hero .wrap{position:relative}
.hero h1{max-width:9em;position:relative;z-index:1}
.hero p{max-width:34em;font-size:clamp(19px,2vw,24px);margin:36px 0 40px;position:relative;z-index:1}
.cta-row{display:flex;flex-wrap:wrap;gap:20px 32px;align-items:center;position:relative;z-index:1}
.shape{position:absolute;pointer-events:none}
.rect{background:var(--cyan);width:clamp(40px,7vw,100px);height:clamp(110px,19vw,270px);right:clamp(40px,12vw,200px);top:calc(-1 * clamp(40px,8vw,110px) - 90px);animation:drop 1s cubic-bezier(.2,.8,.2,1) both}
.tri{background:var(--pink);clip-path:polygon(50% 0,100% 100%,0 100%);width:clamp(70px,12vw,190px);height:clamp(90px,15vw,240px);right:clamp(10px,5vw,90px);top:clamp(80px,14vw,200px);animation:rise 1s .25s cubic-bezier(.2,.8,.2,1) both}
@keyframes drop{from{transform:translateY(-130%)}}
@keyframes rise{from{transform:translateY(60px);opacity:0}}
@media(prefers-reduced-motion:reduce){.rect,.tri{animation:none}html{scroll-behavior:auto}}

/* problema */
.problem{background:var(--ink);color:var(--paper);padding-top:clamp(70px,10vw,140px);padding-bottom:clamp(70px,10vw,140px)}
.problem h2{max-width:10em}
.problem .lead{max-width:36em;font-size:clamp(19px,2vw,24px);margin:32px 0 64px}
.three{display:grid;grid-template-columns:repeat(3,1fr);gap:0}
.three div{padding:28px 32px 8px 0;border-top:4px solid var(--cyan)}
.three div:nth-child(2){border-color:var(--pink)}
.three h3{font-size:clamp(30px,3.4vw,44px);margin-bottom:10px;line-height:1}
.three p{margin:0;max-width:20em;opacity:.85}
@media(max-width:820px){.three{grid-template-columns:1fr;gap:32px}}

/* serviços */
.services{padding-top:clamp(70px,10vw,140px);padding-bottom:clamp(70px,10vw,140px)}
.services h2{margin-bottom:56px}
.row{display:grid;grid-template-columns:1fr 1.2fr;gap:12px 48px;padding:32px 0;border-top:4px solid var(--ink)}
.row:last-child{border-bottom:4px solid var(--ink)}
.row h3{font-size:clamp(32px,4.2vw,56px);line-height:1}
.row p{margin:0;max-width:30em;font-size:20px}
@media(max-width:760px){.row{grid-template-columns:1fr}}

/* processo */
.process{background:var(--cyan);padding-top:clamp(70px,10vw,140px);padding-bottom:clamp(70px,10vw,140px)}
.process h2{margin-bottom:64px}
.steps{display:grid;grid-template-columns:repeat(4,1fr);gap:40px;list-style:none;margin:0;padding:0}
.steps li{border-top:4px solid var(--ink);padding-top:20px}
.steps .n{font:400 clamp(70px,8vw,110px)/1 Anton,Impact,sans-serif}
.steps h3{font-size:34px;margin:6px 0 10px}
.steps p{margin:0}
@media(max-width:900px){.steps{grid-template-columns:1fr 1fr}}
@media(max-width:520px){.steps{grid-template-columns:1fr}}

/* faq */
.faq{padding-top:clamp(70px,10vw,140px);padding-bottom:clamp(70px,10vw,140px)}
.faq .wrap{display:grid;grid-template-columns:1fr 1.5fr;gap:48px}
details{border-top:4px solid var(--ink);padding:22px 0}
details:last-child{border-bottom:4px solid var(--ink)}
summary{cursor:pointer;font:700 22px/1.3 Inter,sans-serif;list-style:none;display:flex;justify-content:space-between;gap:20px}
summary::-webkit-details-marker{display:none}
summary::after{content:"+";font:400 36px/1 Anton,Impact,sans-serif;flex:none}
details[open] summary::after{content:"\2212"}
details p{margin:14px 0 0;max-width:36em}
@media(max-width:820px){.faq .wrap{grid-template-columns:1fr}}

/* contato */
.contact{background:var(--pink);padding-top:clamp(70px,10vw,140px);padding-bottom:clamp(70px,10vw,140px);position:relative;overflow:hidden}
.contact .wrap{display:grid;grid-template-columns:1.2fr 1fr;gap:56px;align-items:end}
.contact p{font-size:22px;max-width:24em;margin:28px 0 0}
form{display:flex;flex-direction:column;gap:20px}
label{font-weight:700;display:flex;flex-direction:column;gap:8px}
input,textarea{font:400 18px Inter,sans-serif;padding:16px;border:4px solid #000;background:var(--paper);color:#000;border-radius:0;width:100%}
textarea{min-height:110px;resize:vertical}
form .btn{width:100%;text-align:center;font-size:20px}
form small{font-size:15px}
@media(max-width:860px){.contact .wrap{grid-template-columns:1fr}}

footer{background:var(--ink);color:var(--paper);padding-top:40px;padding-bottom:40px}
footer .wrap{display:flex;flex-wrap:wrap;justify-content:space-between;align-items:center;gap:16px 32px}
footer a{text-underline-offset:5px}
</style>
</head>
<body>

<header>
  <a class="logo" href="#topo" aria-label="Inflitia, início">INFLITIA</a>
  <nav aria-label="Principal">
    <a href="#servicos">Serviços</a>
    <a href="#processo">Como funciona</a>
    <a href="#perguntas">Perguntas</a>
    <a class="btn" href="#contato">Orçamento grátis</a>
  </nav>
</header>

<main id="topo">
  <section class="hero">
    <div class="shape rect" aria-hidden="true"></div>
    <div class="shape tri" aria-hidden="true"></div>
    <div class="wrap">
      <h1>Seu site tem que vender.</h1>
      <p>A Inflitia cria sites rápidos, bonitos e feitos sob medida para transformar quem visita em quem chama. Sem template pronto, sem enrolação.</p>
      <div class="cta-row">
        <a class="btn" href="https://wa.me/5548992223419?text=Oi%2C%20quero%20um%20or%C3%A7amento%20de%20site%20com%20a%20Inflitia" target="_blank" rel="noopener">Chamar no WhatsApp</a>
        <a class="link" href="#processo">Ver como funciona</a>
      </div>
    </div>
  </section>

  <section class="problem dark">
    <div class="wrap">
      <h2>Seu cliente decide em segundos.</h2>
      <p class="lead">Antes de ligar, ele abre o seu site. Se demora para carregar, quebra no celular ou não deixa claro o que você faz, ele volta para o Google e clica no concorrente.</p>
      <div class="three">
        <div><h3>Rápido de verdade</h3><p>Páginas leves, que abrem na hora e não deixam o visitante esperando.</p></div>
        <div><h3>Bom no celular</h3><p>Projetamos primeiro para a tela pequena, onde muita gente chega até você.</p></div>
        <div><h3>Contato a um toque</h3><p>Botão de WhatsApp e formulário no lugar certo, sem o cliente ter que procurar.</p></div>
      </div>
    </div>
  </section>

  <section class="services" id="servicos">
    <div class="wrap">
      <h2>O que a gente faz</h2>
      <div class="row"><h3>Site institucional</h3><p>Apresenta sua empresa e seus serviços com clareza e leva o visitante até o contato.</p></div>
      <div class="row"><h3>Landing page</h3><p>Uma página com um único objetivo: gerar pedidos de orçamento, agendamentos ou vendas.</p></div>
      <div class="row"><h3>Redesign</h3><p>Seu site existe, mas afasta cliente? Refazemos mantendo o que funciona e trocando o que não funciona.</p></div>
      <div class="row"><h3>Suporte e ajustes</h3><p>Depois do site no ar, você continua com ajuda para atualizar textos, fotos e o que mais precisar.</p></div>
    </div>
  </section>

  <section class="process" id="processo">
    <div class="wrap">
      <h2>Como funciona</h2>
      <ol class="steps">
        <li><div class="n">1</div><h3>Conversa</h3><p>Entendemos seu negócio, seu público e o que o site precisa gerar.</p></li>
        <li><div class="n">2</div><h3>Proposta</h3><p>Você recebe escopo, prazo e valor por escrito, antes de começar.</p></li>
        <li><div class="n">3</div><h3>Criação</h3><p>Você acompanha o andamento e pede ajustes antes de publicar.</p></li>
        <li><div class="n">4</div><h3>No ar</h3><p>Publicamos o site e ficamos por perto para o que vier depois.</p></li>
      </ol>
    </div>
  </section>

  <section class="faq" id="perguntas">
    <div class="wrap">
      <h2>Perguntas frequentes</h2>
      <div>
        <details><summary>Quanto custa um site?</summary><p>Depende do que você precisa: número de páginas, funcionalidades e conteúdo. O orçamento é gratuito e sem compromisso, e o valor fica fechado antes de começarmos.</p></details>
        <details><summary>Quanto tempo leva?</summary><p>Depende do tamanho do projeto e de quando recebemos os conteúdos. O prazo vem definido na proposta.</p></details>
        <details><summary>Preciso ter textos e fotos prontos?</summary><p>Não. A gente orienta o que reunir e ajuda a organizar o conteúdo.</p></details>
        <details><summary>O site funciona no celular?</summary><p>Sim. Todo site que fazemos é pensado primeiro para o celular e testado em telas de vários tamanhos.</p></details>
        <details><summary>Vocês cuidam do site depois de publicado?</summary><p>Sim. Oferecemos suporte e ajustes depois que o site está no ar.</p></details>
      </div>
    </div>
  </section>

  <section class="contact on-pink" id="contato">
    <div class="wrap">
      <div>
        <h2>Vamos colocar sua empresa na tela?</h2>
        <p>Conte em duas linhas o que você faz. A conversa abre no WhatsApp e o orçamento é gratuito e sem compromisso.</p>
      </div>
      <form id="form" novalidate>
        <label for="nome">Seu nome<input id="nome" name="nome" autocomplete="name" required></label>
        <label for="negocio">O que sua empresa faz?<textarea id="negocio" name="negocio" required></textarea></label>
        <button class="btn" type="submit">Enviar pelo WhatsApp</button>
        <small id="erro" role="alert"></small>
      </form>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    <span class="display" style="font-size:32px">INFLITIA</span>
    <span><a href="https://instagram.com/inflitia" target="_blank" rel="noopener">Instagram</a> &nbsp;|&nbsp; &copy; 2026 Inflitia</span>
  </div>
</footer>

<script>
  var NUMERO = "5548992223419";
  document.getElementById("form").addEventListener("submit", function (e) {
    e.preventDefault();
    var nome = document.getElementById("nome").value.trim();
    var negocio = document.getElementById("negocio").value.trim();
    var erro = document.getElementById("erro");
    if (!nome || !negocio) { erro.textContent = "Preencha seu nome e o que sua empresa faz."; return; }
    erro.textContent = "";
    var msg = "Oi, sou " + nome + ". Minha empresa: " + negocio + ". Quero um orçamento de site.";
    window.open("https://wa.me/" + NUMERO + "?text=" + encodeURIComponent(msg), "_blank", "noopener");
  });
</script>
</body>
</html>
