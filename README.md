<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FC Uchalni</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color:white;
}

header{
    text-align:center;
    padding:40px 20px;
    background: rgba(0,0,0,0.4);
}

header h1{
    font-size:48px;
    margin:0;
}

nav{
    display:flex;
    justify-content:center;
    gap:20px;
    background:#111;
    padding:10px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    transition:0.2s;
}

nav a:hover{
    color:gold;
}

.container{
    max-width:1000px;
    margin:40px auto;
    padding:20px;
}

.card{
    background: rgba(255,255,255,0.1);
    border-radius:15px;
    padding:20px;
    margin-bottom:20px;
    backdrop-filter: blur(6px);
}

h2{
    color:gold;
}

.players{
    display:grid;
    grid-template-columns: repeat(auto-fit,minmax(150px,1fr));
    gap:15px;
}

.player{
    background:#111;
    padding:10px;
    border-radius:10px;
    text-align:center;
}

footer{
    text-align:center;
    padding:20px;
    background:#111;
    margin-top:40px;
}
</style>
</head>

<body>

<header>
<h1>FC Uchalni</h1>
<p>Najlepszy klub ligi osiedlowej w Pile ⚽</p>
</header>

<nav>
<a href="#">Start</a>
<a href="#sklad">Skład</a>
<a href="#mecze">Mecze</a>
<a href="#kontakt">Kontakt</a>
</nav>

<div class="container">

<div class="card">
<h2>O klubie</h2>
<p>FC Uchalni to drużyna z Piły, założona w 2026 roku. Klub szybko stał się jednym z faworytów ligi osiedlowej. Zespół słynie z ofensywnego stylu gry, dobrej atmosfery i walki do końca.</p>
</div>

<div class="card" id="sklad">
<h2>Skład</h2>
<div class="players">
<div class="player">Bramkarz<br>Aleks Polasik</div>
<div class="player">Obrońca<br></div>
<div class="player">Obrońca<br>Bartek</div>
<div class="player">Pomocnik<br>Oskar</div>
<div class="player">Pomocnik<br>Patryk</div>
<div class="player">Napastnik<br>Adrian</div>
</div>
</div>

<div class="card" id="mecze">
<h2>Ostatnie mecze</h2>
<ul>
<li>FC Uchalni 10:7 FC Ulani</li>
<li>FC Uchalni 10:2 FC Ulani</li>
</ul>
</div>

<div class="card" id="kontakt">
<h2>Kontakt</h2>
<p>Email: fcuchalni@gmail.com</p>
<p>Instagram: @fcuchalni</p>
</div>

</div>

<footer>
<p>© 2026 FC Uchalni</p>
</footer>

</body>
</html>
