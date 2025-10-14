<html lang="pt-BR">
<head>
<link rel="stylesheet" href="styles.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link
href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,
600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
rel="stylesheet">
<title>Julio Music</title>
</head>
<body>
<header>JULIOMUSIC</header>
<section class="chamada">
<div class="chamada-texto">
<h1>The Time of My Life</h1>
<p>Bill & McKenna Medley</p>
</div>
<div>
<iframe width="560" height="315"
src="https://www.youtube.com/embed/H1MS6apBgzA?si=Q_bCkU99I9AoL1pJ"

title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-
write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-
when-cross-origin" allowfullscreen></iframe>

</div>
</section>
<section class="categoria">
<h2>Estilo de músicas</h2>
<div class="categoria-videos">
<a
href="https://www.youtube.com/watch?v=zRi5vOwNF1U&list=RDzRi5vOwNF1U&start_radi
o=1">
<img src="https://img.youtube.com/vi/zRi5vOwNF1U/maxresdefault.jpg" />
</a>
<a
href="https://www.youtube.com/watch?v=bo_efYhYU2A&list=RDYQHsXMglC9A&index=3"
>
<img src="https://img.youtube.com/vi/bo_efYhYU2A/maxresdefault.jpg" />
</a>
<a
href="https://www.youtube.com/watch?v=zvFroLUxRDQ&list=RDYQHsXMglC9A&index=2
7">
<img src="https://img.youtube.com/vi/zvFroLUxRDQ/maxresdefault.jpg" />
</a>
<a
href="https://www.youtube.com/watch?v=u1V8YRJnr4Q&list=RDYQHsXMglC9A&index=14
">

<img src="https://img.youtube.com/vi/u1V8YRJnr4Q/maxresdefault.jpg" />
</a>
<a
href="https://www.youtube.com/watch?v=2oX2FSv4Rys&list=RDYQHsXMglC9A&index=15
">
<img src="https://img.youtube.com/vi/2oX2FSv4Rys/maxresdefault.jpg" />
</a>
<a
href="https://www.youtube.com/watch?v=rtOvBOTyX00&list=RDYQHsXMglC9A&index=27
">
<img src="https://img.youtube.com/vi/rtOvBOTyX00/maxresdefault.jpg" />
</a>
</div>
</section>
</body>
</html>

Style.css

body {
color: white;
background: rgb(23, 2, 78);
margin: 0px;
font-family: "Chakra Petch", sans-serif;
margin-bottom: 100px;
}
header {
border-bottom: solid 2px rgb(42, 122, 228);
padding: 20px;
font-size: 32px;
color: rgb(238, 14, 14);
}
.chamada {
background: rgb(5, 238, 44);
padding-bottom: 80px;
padding-top: 80px;
display: flex;
justify-content: center;
}
.chamada-texto {
margin-right: 5%;
}
h1 {
font-size: 40px;
}

p {
font-size: 20px;
}
.categoria-videos {
display: flex;
overflow-x: auto;
gap: 10px;
}
.categoria {
padding-left: 20px;
padding-right: 20px;
margin-top: 50px;
}
.categoria-videos img {
opacity: 0.5;
height: 200px;
}
.categoria-videos img:hover {
opacity: 1.0;
border: 3px solid green;
}
.categoria h2 {
color: rgb(226, 13, 13);
}
