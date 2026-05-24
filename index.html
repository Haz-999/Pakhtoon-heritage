<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pakhtoon's - Made by Haz</title>

<style>
/* RESET */
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, sans-serif;
}

body{
  background:#f4f4f4;
  transition:0.3s;
}

/* INTRO */
#intro{
  position:fixed;
  width:100%;
  height:100vh;
  background:#000;
  color:white;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  z-index:999;
  animation:fadeOut 3s forwards;
  animation-delay:2.5s;
}

#intro h1{
  font-size:45px;
  animation:zoom 1.5s ease;
}

#intro p{
  opacity:0.7;
}

@keyframes zoom{
  from{transform:scale(0)}
  to{transform:scale(1)}
}

@keyframes fadeOut{
  to{opacity:0;visibility:hidden}
}

/* SIDEBAR */
.sidebar{
  width:220px;
  height:100vh;
  background:#111;
  color:white;
  position:fixed;
  padding:20px;
}

.sidebar a{
  display:block;
  color:white;
  padding:10px;
  text-decoration:none;
  margin:5px 0;
  border-radius:5px;
}

.sidebar a:hover{
  background:#333;
}

/* MAIN */
.main{
  margin-left:240px;
  padding:20px;
}

/* HEADER */
header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  flex-wrap:wrap;
}

button{
  padding:8px 12px;
  background:green;
  color:white;
  border:none;
  border-radius:5px;
  cursor:pointer;
}

/* SEARCH */
input{
  width:100%;
  padding:10px;
  margin:15px 0;
  border-radius:5px;
  border:1px solid #ccc;
}

/* CARDS */
.card{
  background:white;
  padding:15px;
  margin:10px 0;
  border-radius:10px;
  box-shadow:0 0 10px rgba(0,0,0,0.1);
  opacity:0;
  transform:translateY(50px);
  transition:0.5s;
}

.card.show{
  opacity:1;
  transform:translateY(0);
}

/* GALLERY */
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:10px;
}

.gallery img{
  width:100%;
  border-radius:10px;
}

/* DARK MODE */
.dark{
  background:#121212;
  color:white;
}

.dark .card{
  background:#1e1e1e;
}

.dark .sidebar{
  background:#000;
}

.dark input{
  background:#222;
  color:white;
}

/* MOBILE */
@media(max-width:768px){
  .sidebar{
    position:relative;
    width:100%;
    height:auto;
  }
  .main{
    margin-left:0;
  }
}
</style>
</head>

<body>

<!-- INTRO -->
<div id="intro">
  <h1>Pakhtoon's</h1>
  <p>Made by Haz ✨</p>
</div>

<!-- SIDEBAR -->
<div class="sidebar">
  <h2>📚 Menu</h2>
  <a href="#leaders">Leaders</a>
  <a href="#poets">Poets</a>
  <a href="#culture">Culture</a>
  <a href="#gallery">Gallery</a>
  <a href="#faq">FAQ</a>
</div>

<!-- MAIN -->
<div class="main">

<header>
  <h1>🌍 Pakhtoon Heritage</h1>
  <button onclick="toggleDark()">🌙 Dark Mode</button>
</header>

<input type="text" id="search" placeholder="Search anything..." onkeyup="search()">

<!-- LEADERS -->
<section id="leaders">
<h2>🌟 Leaders</h2>

<div class="card">Abdul Ghaffar Khan (Bacha Khan) — Non-violence leader who promoted peace and education.</div>
<div class="card">Ahmad Shah Durrani — Founder of Afghan Empire.</div>
<div class="card">Hamid Karzai — Former President of Afghanistan.</div>
<div class="card">Malala Yousafzai — Education activist and Nobel Prize winner.</div>
</section>

<!-- POETS -->
<section id="poets">
<h2>📚 Poets</h2>

<div class="card">Rehman Baba — “Do good to others, and peace will follow you.”</div>
<div class="card">Khoshal Khan Khattak — “Freedom is the soul of life.”</div>
<div class="card">Ghani Khan — Philosophical poetry about life and humanity.</div>
</section>

<!-- CULTURE -->
<section id="culture">
<h2>🏔️ Culture</h2>

<div class="card">Pashtunwali — Code of honor, bravery, and hospitality.</div>
<div class="card">Melmastia — Respect and hospitality for guests.</div>
<div class="card">Nang — Honor and dignity in society.</div>
</section>

<!-- GALLERY -->
<section id="gallery">
<h2>🖼️ Gallery</h2>

<div class="gallery">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Bacha_Khan.jpg">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Rehman_Baba_Tomb.jpg">
<img src="https://upload.wikimedia.org/wikipedia/commons/1/1f/Malala_Yousafzai_2013.jpg">
</div>

</section>

<!-- FAQ -->
<section id="faq">
<h2>❓ FAQ</h2>

<div class="card">
<strong>Who are Pakhtoons?</strong>
<p>An ethnic group mainly in Pakistan and Afghanistan.</p>
</div>

<div class="card">
<strong>What is Pashtunwali?</strong>
<p>Traditional code of ethics: honor, bravery, hospitality.</p>
</div>

<div class="card">
<strong>Who is Bacha Khan?</strong>
<p>Freedom leader known for non-violence movement.</p>
</div>

</section>

</div>

<!-- SCRIPT -->
<script>
function toggleDark(){
  document.body.classList.toggle("dark");
  localStorage.setItem("dark", document.body.classList.contains("dark"));
}

window.onload=function(){
  if(localStorage.getItem("dark")==="true"){
    document.body.classList.add("dark");
  }
  reveal();
}

function search(){
  let input=document.getElementById("search").value.toLowerCase();
  let cards=document.getElementsByClassName("card");

  for(let i=0;i<cards.length;i++){
    let text=cards[i].innerText.toLowerCase();
    cards[i].style.display=text.includes(input)?"block":"none";
  }
}

function reveal(){
  let cards=document.querySelectorAll(".card");
  for(let c of cards){
    let top=c.getBoundingClientRect().top;
    if(top<window.innerHeight-100){
      c.classList.add("show");
    }
  }
}

window.addEventListener("scroll",reveal);
</script>

</body>
</html>
