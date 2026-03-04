<!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Business Coach</title>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">

<style>

body{
background:linear-gradient(135deg,#0f172a,#1e293b);
color:white;
}

.hero{
padding:80px 0;
text-align:center;
}

.hero h1{
font-size:48px;
}

.hero p{
font-size:20px;
opacity:0.8;
}

.services{
margin-top:60px;
}

.card{
background:#1e293b;
padding:30px;
border-radius:15px;
box-shadow:0 10px 30px rgba(0,0,0,0.3);
}

.cta{
margin-top:60px;
text-align:center;
}

footer{
margin-top:80px;
text-align:center;
opacity:0.7;
}

</style>

</head>

<body>

<nav class="container-fluid">
<ul>
<li><strong>Business Coach</strong></li>
</ul>
<ul>
<li><a href="#">Servicii</a></li>
<li><a href="#">Proces</a></li>
<li><a href="#" role="button">Contact</a></li>
</ul>
</nav>

<main class="container">

<section class="hero">

<h1>Crește-ți Business-ul</h1>

<p>
Strategie, leadership și creștere reală pentru antreprenori și companii.
</p>

<a href="#" role="button">Programează o sesiune</a>

</section>


<section class="services grid">

<div class="card">

<h3>Business Strategy</h3>

<p>
Te ajut să creezi o strategie clară pentru creștere și profit.
</p>

</div>

<div class="card">

<h3>Leadership Coaching</h3>

<p>
Dezvoltă abilități de leadership pentru a conduce echipe performante.
</p>

</div>

<div class="card">

<h3>Scaling Business</h3>

<p>
Construim procese și sisteme pentru a scala compania ta.
</p>

</div>

</section>

<section class="cta">

<h2>Vrei să îți crești business-ul?</h2>

<p>
Programează o sesiune de coaching.
</p>

<a href="#" role="button">Contact</a>

</section>

</main>

<section aria-label="Subscribe example">
<div class="container">

<article>

<hgroup>
<h2>Primește strategii de business</h2>
<h3>Abonează-te la newsletter</h3>
</hgroup>

<form class="grid">

<input type="text" id="firstname" name="firstname" placeholder="Nume" aria-label="Nume" required>

<input type="email" id="email" name="email" placeholder="Email" aria-label="Email" required>

<button type="submit" onclick="event.preventDefault()">Subscribe</button>

</form>

</article>

</div>
</section>

<footer class="container">

<small>
<a href="#">Privacy</a> • <a href="#">Terms</a>
</small>

</footer>

</body>
</html>
