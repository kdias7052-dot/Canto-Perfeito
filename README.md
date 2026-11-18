<!DOCTYPE html>
<html lang="pt-BR">

</head>
<body>

<header>
<h1>🎤 Canto Perfeito</h1>
<nav>
<a href="#inicio">Início</a>
<a href="#aulas">Aulas</a>
<a href="#exercicios">Exercícios</a>
<a href="#dicas">Dicas</a>
</nav>
</header>

<div class="hero" id="inicio">
<h2>Descubra a sua voz! 🎶</h2>
<p>Aprenda a cantar, desenvolva sua técnica vocal e solte a voz!</p>
<button onclick="document.getElementById('aulas').scrollIntoView({behavior:'smooth'})">
Começar minhas aulas
</button>
</div>

<section id="aulas">
<h2>📚 Aprenda a cantar</h2>
<div class="cards">
<div class="card">
<h3>🎵 Aula 1 - Respiração</h3>
<p>A respiração é essencial para cantar bem.</p>
<ul>
<li>Inspire pelo nariz.</li>
<li>Deixe o abdômen expandir suavemente.</li>
<li>Solte o ar devagar.</li>
<li>Evite levantar os ombros.</li>
</ul>
</div>

<div class="card">
<h3>🎼 Aula 2 - Afinação</h3>
<p>Afinação é conseguir reproduzir corretamente as notas musicais.</p>
<ul>
<li>Escute uma nota.</li>
<li>Tente reproduzir com a voz.</li>
<li>Repita devagar.</li>
<li>Use um instrumento como referência.</li>
</ul>
</div>

<div class="card">
<h3>🎤 Aula 3 - Aquecimento vocal</h3>
<p>Prepare sua voz antes de cantar.</p>
<ul>
<li>Faça vibração de lábios.</li>
<li>Produza sons suaves de "mmm".</li>
<li>Faça escalas confortáveis.</li>
<li>Não force a garganta.</li>
</ul>
</div>

<div class="card">
<h3>🎶 Aula 4 - Dicção</h3>
<p>Aprenda a pronunciar as palavras claramente.</p>
<ul>
<li>Leia em voz alta.</li>
<li>Pronuncie cada sílaba.</li>
<li>Pratique trava-línguas.</li>
<li>Cante sem engolir as palavras.</li>
</ul>
</div>

<div class="card">
<h3>🌟 Aula 5 - Alcance vocal</h3>
<p>Descubra as notas que sua voz consegue alcançar confortavelmente.</p>
<ul>
<li>Comece com notas confortáveis.</li>
<li>Suba e desça gradualmente.</li>
<li>Não force notas agudas.</li>
<li>Respeite seus limites.</li>
</ul>
</div>

<div class="card">
<h3>🎭 Aula 6 - Interpretação</h3>
<p>Aprenda a transmitir emoções através da música.</p>
<ul>
<li>Entenda a letra.</li>
<li>Trabalhe as emoções.</li>
<li>Controle a intensidade.</li>
<li>Cante com expressão.</li>
</ul>
</div>
</div>
</section>

<section id="exercicios">
<h2>🎯 Teste seus conhecimentos</h2>
<div class="exercise">
<h3>1. O que devemos fazer antes de cantar?</h3>
<button onclick="responder(false)">Gritar bastante</button>
<button onclick="responder(true)">Aquecer a voz</button>
<button onclick="responder(false)">Forçar notas agudas</button>
<p id="result"></p>
</div>
</section>

<section id="dicas">
<h2>💗 Dicas para cuidar da voz</h2>
<div class="cards">
<div class="card">
<h3>💧 Beba água</h3>
<p>Mantenha-se hidratado ao longo do dia.</p>
</div>
<div class="card">
<h3>😴 Descanse</h3>
<p>Evite exagerar no uso da voz e respeite o descanso vocal.</p>
</div>
<div class="card">
<h3>🎤 Pratique</h3>
<p>Faça exercícios regularmente, sem forçar sua voz.</p>
</div>
<div class="card">
<h3>❤️ Respeite sua voz</h3>
<p>Se sentir dor ou rouquidão persistente, pare e procure orientação profissional.</p>
</div>
</div>
</section>

<footer>
<h2>🎤 Canto Perfeito</h2>
<p>Sua voz é única. Descubra todo o seu potencial!</p>
<p>©️ 2026 - Todos os direitos reservados.</p>
</footer>

<script>
function responder(correto){
 const resultado=document.getElementById("result");
 if(correto){
 resultado.innerHTML="🎉 Parabéns! Resposta correta!";
 resultado.style.color="green";
 }else{
 resultado.innerHTML="❌ Tente novamente!";
 resultado.style.color="red";
 }
}
</script>

</body>
</html>