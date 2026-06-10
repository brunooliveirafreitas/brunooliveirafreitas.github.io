<!DOCTYPE html>

<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LockTech | Instalação Profissional de Fechaduras Eletrônicas</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Montserrat',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0B1220;
    color:#fff;
    overflow-x:hidden;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

header{
    position:fixed;
    width:100%;
    top:0;
    z-index:1000;
    background:rgba(11,18,32,.95);
    backdrop-filter:blur(12px);
    border-bottom:1px solid rgba(255,255,255,.08);
}

.nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 0;
}

.logo{
    font-size:28px;
    font-weight:800;
    color:#D4AF37;
}

.menu a{
    color:white;
    text-decoration:none;
    margin-left:30px;
    font-weight:500;
}

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    background:
    linear-gradient(rgba(11,18,32,.75),rgba(11,18,32,.9)),
    url('https://images.unsplash.com/photo-1558002038-1055907df827?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:700px;
}

.hero h1{
    font-size:4rem;
    line-height:1.1;
    margin-bottom:20px;
}

.gold{
    color:#D4AF37;
}

.hero p{
    font-size:1.2rem;
    color:#d1d5db;
    margin-bottom:35px;
}

.btn{
    display:inline-block;
    padding:18px 35px;
    border-radius:50px;
    text-decoration:none;
    font-weight:700;
    transition:.3s;
}

.btn-primary{
    background:#D4AF37;
    color:#0B1220;
}

.btn-primary:hover{
    transform:translateY(-3px);
}

.section{
    padding:100px 0;
}

.section-title{
    text-align:center;
    margin-bottom:60px;
}

.section-title h2{
    font-size:2.8rem;
}

.section-title p{
    color:#9ca3af;
    margin-top:15px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:#111827;
    padding:35px;
    border-radius:20px;
    border:1px solid rgba(212,175,55,.15);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
    border-color:#D4AF37;
}

.card h3{
    margin-bottom:15px;
    color:#D4AF37;
}

.stats{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
}

.stat{
    background:#111827;
    padding:30px;
    border-radius:15px;
    text-align:center;
}

.stat h3{
    font-size:2rem;
    color:#D4AF37;
}

.testimonials{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.testimonial{
    background:#111827;
    padding:30px;
    border-radius:20px;
}

.cta{
    background:linear-gradient(135deg,#D4AF37,#F4D77C);
    color:#0B1220;
    text-align:center;
    border-radius:30px;
    padding:70px 40px;
}

.cta h2{
    font-size:3rem;
    margin-bottom:20px;
}

.cta p{
    margin-bottom:30px;
}

footer{
    padding:40px 0;
    text-align:center;
    color:#9ca3af;
}

.whatsapp{
    position:fixed;
    bottom:25px;
    right:25px;
    background:#25D366;
    color:white;
    width:70px;
    height:70px;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:30px;
    text-decoration:none;
    box-shadow:0 10px 30px rgba(0,0,0,.4);
}

@media(max-width:768px){

.hero h1{
    font-size:2.5rem;
}

.stats{
    grid-template-columns:repeat(2,1fr);
}

.menu{
    display:none;
}

}

</style>

</head>

<body>

<header>
<div class="container nav">
<div class="logo">LOCKTECH</div>

<nav class="menu">
<a href="#servicos">Serviços</a>
<a href="#vantagens">Vantagens</a>
<a href="#clientes">Clientes</a>
<a href="#contato">Contato</a>
</nav>
</div>
</header>

<section class="hero">

<div class="container hero-content">

<h1>
Segurança Inteligente para
<span class="gold">Casas e Empresas</span>
</h1>

<p>
Instalação profissional de fechaduras eletrônicas,
biométricas e inteligentes com acabamento impecável,
garantia e atendimento especializado.
</p>

<a href="https://wa.me/5541999999999" class="btn btn-primary">
Solicitar Orçamento
</a>

</div>
</section>

<section class="section" id="servicos">

<div class="container">

<div class="section-title">
<h2>Nossos Serviços</h2>
<p>Soluções completas em controle de acesso</p>
</div>

<div class="cards">

<div class="card">
<h3>Instalação Profissional</h3>
<p>Instalação em portas de madeira, alumínio, aço e portas pivotantes.</p>
</div>

<div class="card">
<h3>Configuração Completa</h3>
<p>Cadastro de senhas, digitais, tags e aplicativos.</p>
</div>

<div class="card">
<h3>Manutenção</h3>
<p>Suporte técnico e manutenção preventiva.</p>
</div>

</div>

</div>
</section>

<section class="section" id="vantagens">

<div class="container">

<div class="section-title">
<h2>Por que escolher a LockTech?</h2>
</div>

<div class="stats">

<div class="stat">
<h3>500+</h3>
<p>Instalações</p>
</div>

<div class="stat">
<h3>98%</h3>
<p>Satisfação</p>
</div>

<div class="stat">
<h3>24h</h3>
<p>Atendimento</p>
</div>

<div class="stat">
<h3>1 Ano</h3>
<p>Garantia</p>
</div>

</div>

</div>

</section>

<section class="section" id="clientes">

<div class="container">

<div class="section-title">
<h2>O que nossos clientes dizem</h2>
</div>

<div class="testimonials">

<div class="testimonial">
★★★★★
<p><br>Serviço impecável e extremamente profissional. Recomendo.</p>
<br><strong>Marcos A.</strong>
</div>

<div class="testimonial">
★★★★★
<p><br>Instalação rápida e muito bem feita. Atendimento excelente.</p>
<br><strong>Fernanda R.</strong>
</div>

<div class="testimonial">
★★★★★
<p><br>Minha fechadura ficou perfeita. Excelente acabamento.</p>
<br><strong>Carlos M.</strong>
</div>

</div>

</div>

</section>

<section class="section">

<div class="container">

<div class="cta" id="contato">

<h2>Proteja seu imóvel hoje mesmo</h2>

<p>
Receba uma avaliação gratuita enviando uma foto da sua porta.
</p>

<a href="https://wa.me/5541999999999" class="btn btn-primary">
Falar com um Especialista
</a>

</div>

</div>

</section>

<footer>
© 2026 LOCKTECH • Instalação de Fechaduras Eletrônicas • Curitiba e Região
</footer>

<a class="whatsapp"
href="https://wa.me/5541999999999">
💬 </a>

</body>
</html>
```
