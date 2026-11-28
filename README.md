# Nawouri-Kadee
Création de sites web 

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ALANTRAN DIGITAL</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
font-family:Arial,sans-serif;
background:#081426;
color:white;
line-height:1.6;
}
header{
background:#101f38;
padding:20px;
text-align:center;
border-bottom:2px solid #d6aa43;
}
.logo{
font-size:27px;
font-weight:bold;
color:#e8bd58;
}
nav{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:18px;
padding:15px;
}
nav a{
color:white;
text-decoration:none;
font-weight:bold;
}
nav a:hover{color:#e8bd58}
.hero{
text-align:center;
padding:85px 20px;
background:linear-gradient(135deg,#102544,#081426);
}
.hero h1{
font-size:38px;
color:#e8bd58;
margin-bottom:15px;
}
.hero p{
font-size:18px;
margin-bottom:25px;
}
.btn{
display:inline-block;
background:#d6aa43;
color:#081426;
padding:12px 25px;
border-radius:7px;
text-decoration:none;
font-weight:bold;
}
section{
padding:55px 20px;
text-align:center;
}
section h2{
color:#e8bd58;
font-size:28px;
margin-bottom:25px;
}
.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
max-width:1000px;
margin:auto;
}
.card{
background:#142641;
padding:25px;
border-radius:12px;
border:1px solid #34465f;
}
.card h3{
color:#e8bd58;
margin-bottom:12px;
}
.card p{color:#d5deeb}
.about{
max-width:750px;
margin:auto;
}
footer{
background:#101f38;
padding:25px;
text-align:center;
border-top:2px solid #d6aa43;
color:#d5deeb;
}
</style>
</head>
<body>

<header>
<div class="logo">ALANTRAN DIGITAL</div>
<nav>
<a href="#accueil">Accueil</a>
<a href="#investissement">Investissement</a>
<a href="#business">Business</a>
<a href="#developpement">Développement</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero" id="accueil">
<h1>Bienvenue chez ALANTRAN DIGITAL</h1>
<p>Investissement, Business, Développement et Innovation.</p>
<a href="#apropos" class="btn">Découvrir notre plateforme</a>
</div>

<section id="investissement">
<h2>Investissement</h2>
<div class="cards">
<div class="card">
<h3>💰 Investissement</h3>
<p>Découvrez les principes de l'investissement et apprenez à mieux comprendre les opportunités financières.</p>
</div>
</div>
</section>

<section id="business">
<h2>Business</h2>
<div class="cards">
<div class="card">
<h3>📈 Entrepreneuriat</h3>
<p>Explorez les idées, les stratégies et les connaissances pour développer vos projets.</p>
</div>
</div>
</section>

<section id="developpement">
<h2>Développement et Innovation</h2>
<div class="cards">
<div class="card">
<h3>🚀 Développement</h3>
<p>Découvrez les outils numériques et les nouvelles technologies.</p>
</div>
<div class="card">
<h3>💡 Innovation</h3>
<p>Apprenez, explorez et imaginez les solutions de demain.</p>
</div>
</div>
</section>

<section id="apropos">
<h2>À propos de nous</h2>
<div class="about">
<p>ALANTRAN DIGITAL est une plateforme dédiée à la découverte du monde numérique, du business, de l'investissement et de l'innovation.</p>
<p>Notre ambition : apprendre, explorer et développer de nouvelles connaissances.</p>
</div>
</section>

<section id="contact">
<h2>Contact</h2>
<p>Bienvenue dans l'univers ALANTRAN DIGITAL.</p>
<p>Pour toute information, contactez notre équipe.</p>
</section>

<footer>
<p>© 2026 ALANTRAN DIGITAL - Tous droits réservés.</p>
<p>Investir • Développer • Innover</p>
</footer>

</body>
</html>
