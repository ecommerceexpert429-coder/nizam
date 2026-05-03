# nizam
faryal portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Faryal Nizam — eCommerce Specialist</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  font-family:'Inter',sans-serif;
  background:#faf8f4;
  color:#333;
}

/* NAV */
nav{
  position:fixed;
  top:0;
  width:100%;
  background:#fff;
  padding:15px 40px;
  display:flex;
  justify-content:space-between;
  box-shadow:0 2px 10px rgba(0,0,0,0.05);
}

nav a{
  text-decoration:none;
  color:#000;
  margin-left:20px;
  font-size:14px;
}

/* HERO */
.hero{
  display:flex;
  min-height:100vh;
  padding-top:70px;
}

.hero-left{
  flex:1;
  padding:80px;
}

.hero-right{
  flex:1;
  background:#111;
}

.hero-right img{
  width:100%;
  height:100%;
  object-fit:cover;
}

h1{
  font-family:'Playfair Display',serif;
  font-size:60px;
  margin-bottom:10px;
}

.hero-title{
  color:#777;
  margin-bottom:20px;
}

.btn{
  display:inline-block;
  padding:12px 25px;
  background:#000;
  color:#fff;
  text-decoration:none;
  margin-right:10px;
}

section{
  padding:80px 10%;
}

.alt{
  background:#f5f0e8;
}

/* SIMPLE GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.card{
  background:#fff;
  padding:20px;
  border:1px solid #eee;
}

footer{
  background:#000;
  color:#fff;
  text-align:center;
  padding:20px;
}
</style>
</head>

<body>

<nav>
  <div><strong>Faryal.</strong></div>
  <div>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="hero-left">
    <h1>Faryal Nizam</h1>
    <p class="hero-title">eCommerce Specialist · Amazon & Shopify Expert</p>
    <p>
      Results-driven eCommerce specialist with 7+ years of experience scaling Amazon, Shopify, eBay, and Walmart stores.
    </p>

    <a href="#contact" class="btn">Hire Me</a>
    <a href="#skills" class="btn" style="background:#ccc;color:#000;">Skills</a>
  </div>

  <div class="hero-right">
    <!-- IMPORTANT: add this image in repo -->
    <img src="hero.jpg" alt="Profile Image">
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <h2>About</h2>
  <p>
    I specialize in eCommerce growth, Amazon PPC, and Shopify store optimization.
    My goal is to help brands scale profitably with proven strategies.
  </p>
</section>

<!-- SKILLS -->
<section id="skills" class="alt">
  <h2>Skills</h2>

  <div class="grid">
    <div class="card">Amazon PPC</div>
    <div class="card">Shopify Development</div>
    <div class="card">Product Research</div>
    <div class="card">SEO Optimization</div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Contact</h2>
  <p>Email: your@email.com</p>
  <p>Upwork / LinkedIn links here</p>
</section>

<footer>
  © 2026 Faryal Nizam
</footer>

</body>
</html>
