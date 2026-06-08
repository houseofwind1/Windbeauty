<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Wind Beauty Limited | Natural Luxury Skincare Made in Nigeria</title>

<meta name="description" content="Wind Beauty Limited offers premium natural skincare products crafted for African skin using carefully selected botanical ingredients. Made in Nigeria.">

<link rel="icon" type="image/x-icon" href="assets/favicon.ico">

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

:root{
    --purple:#4B216D;
    --gold:#C8A44D;
    --cream:#FAF7F2;
    --dark:#2A2A2A;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:var(--cream);
    color:var(--dark);
}

/* HEADER */

header{
    background:white;
    box-shadow:0 3px 15px rgba(0,0,0,.08);
    position:sticky;
    top:0;
    z-index:999;
}

.navbar{
    max-width:1300px;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 5%;
}

.logo img{
    height:80px;
}

nav a{
    text-decoration:none;
    margin-left:30px;
    color:var(--purple);
    font-weight:600;
    transition:.3s;
}

nav a:hover{
    color:var(--gold);
}

/* HERO */

.hero{
    min-height:85vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:80px 5%;
    background:
    linear-gradient(rgba(250,247,242,.92),rgba(250,247,242,.92)),
    url("assets/images/wb-logo.png");
    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:900px;
}

.hero h1{
    font-family:'Cinzel',serif;
    color:var(--purple);
    font-size:4rem;
    margin-bottom:20px;
}

.hero p{
    font-size:1.2rem;
    line-height:1.9;
    margin-bottom:35px;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    border-radius:40px;
    text-decoration:none;
    font-weight:600;
    transition:.3s;
}

.btn-primary{
    background:var(--purple);
    color:white;
}

.btn-primary:hover{
    background:#35104f;
}

.btn-secondary{
    background:var(--gold);
    color:white;
    margin-left:15px;
}

.btn-secondary:hover{
    opacity:.9;
}

/* FEATURES */

.features{
    padding:80px 5%;
}

.section-title{
    text-align:center;
    font-family:'Cinzel',serif;
    color:var(--purple);
    font-size:2.7rem;
    margin-bottom:50px;
}

.feature-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.feature-box{
    background:white;
    padding:30px;
    border-radius:20px;
    text-align:center;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.feature-box h3{
    color:var(--purple);
    margin-bottom:10px;
}

/* PRODUCTS */

.products{
    background:white;
    padding:90px 5%;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:35px;
}

.product-card{
    border-radius:20px;
    overflow:hidden;
    box-shadow:0 8px 25px rgba(0,0,0,.08);
    background:white;
    transition:.3s;
}

.product-card:hover{
    transform:translateY(-10px);
}

.product-card img{
    width:100%;
    height:280px;
    object-fit:cover;
}

.product-content{
    padding:25px;
}

.product-content h3{
    color:var(--purple);
    margin-bottom:10px;
    font-size:1.2rem;
}

.price{
    color:var(--gold);
    font-size:2rem;
    font-weight:700;
    margin:10px 0;
}

.product-content p{
    line-height:1.7;
}

/* STORY */

.story{
    padding:90px 8%;
}

.story-content{
    max-width:1000px;
    margin:auto;
    text-align:center;
}

.story p{
    line-height:2;
    margin-bottom:25px;
}

/* CTA */

.cta{
    background:var(--purple);
    color:white;
    text-align:center;
    padding:80px 5%;
}

.cta h2{
    font-family:'Cinzel',serif;
    font-size:2.5rem;
    margin-bottom:20px;
}

.cta p{
    max-width:800px;
    margin:auto;
    margin-bottom:30px;
    line-height:1.8;
}

/* FOOTER */

footer{
    background:#2c0d43;
    color:white;
    text-align:center;
    padding:40px 20px;
}

footer p{
    margin:10px 0;
}

/* MOBILE */

@media(max-width:900px){

.navbar{
    flex-direction:column;
}

.logo img{
    height:65px;
    margin-bottom:15px;
}

nav{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
}

nav a{
    margin:10px;
}

.hero h1{
    font-size:2.7rem;
}

.hero p{
    font-size:1rem;
}

.btn{
    display:block;
    margin:10px auto;
    max-width:250px;
}

.btn-secondary{
    margin-left:0;
}
}

</style>
</head>

<body>

<header>

<div class="navbar">

<div class="logo">
<img src="assets/images/<img width="1402" height="1122" alt="wb-logo png" src="https://github.com/user-attachments/assets/7926b1e5-4a30-4dde-89af-ccabb5155ca8" />
" alt="Wind Beauty Limited">
</div>

<nav>
<a href="index.html">Home</a>
<a href="about.html">About Us</a>
<a href="products.html">Products</a>
<a href="contact.html">Contact</a>
</nav>

</div>

</header>

<section class="hero">

<div class="hero-content">

<h1>Wind Beauty Limited</h1>

<p>
Bringing Beauty To You On The Wings Of Mother Nature.
Premium Nigerian skincare crafted with nature's finest botanicals,
designed to nourish, hydrate, protect and restore healthy radiant skin
for every season across Nigeria and West Africa.
</p>

<a href="products.html" class="btn btn-primary">Shop Collection</a>

<a href="contact.html" class="btn btn-secondary">Contact Us</a>

</div>

</section>

<section class="features">

<h2 class="section-title">Why Choose Wind Beauty?</h2>

<div class="feature-grid">

<div class="feature-box">
<h3>100% Natural Ingredients</h3>
<p>
Made with carefully selected botanical oils, butters and extracts inspired by nature.
</p>
</div>

<div class="feature-box">
<h3>Made In Nigeria</h3>
<p>
Proudly formulated and produced in Nigeria for African skin and climate conditions.
</p>
</div>

<div class="feature-box">
<h3>Cruelty Free</h3>
<p>
No animal testing. Ethical skincare crafted with care and responsibility.
</p>
</div>

<div class="feature-box">
<h3>For All Skin Types</h3>
<p>
Suitable for dry, normal, oily and combination skin.
</p>
</div>

</div>

</section>

<section class="products">

<h2 class="section-title">Featured Products</h2>

<div class="product-grid">

<div class="product-card">
<img src="assets/images/<img width="1536" height="1024" alt="assetsimagesbody-butter jpg" src="https://github.com/user-attachments/assets/29487977-ff2e-4fd7-8e3d-9fda7f9deb65" />
" alt="Body Butter">

<div class="product-content">
<h3>Moisturizing Body Butter</h3>
<div class="price">₦10,000</div>

<p>
A luxurious blend of Coconut Oil, Mango Seed Butter,
Avocado Butter and Moringa Oil that deeply moisturizes,
restores elasticity and protects skin against dryness.
</p>
</div>
</div>

<div class="product-card">
<img src="assets/images/<img width="1254" height="1254" alt="assetsimagesbody-oil jpg" src="https://github.com/user-attachments/assets/9ea611f4-fad7-4715-9a92-237475d5dc54" />
" alt="Body Oil">

<div class="product-content">
<h3>Clear & Rejuvenating Body Oil</h3>

<div class="price">₦7,000</div>

<p>
Lightweight botanical oil formulated to nourish,
brighten and promote healthy glowing skin.
</p>
</div>
</div>

<div class="product-card">
<img src="assets/images/<img width="1254" height="1254" alt="assetsimagesrice-soap jpg" src="https://github.com/user-attachments/assets/b0466144-d4dc-44dd-856f-729fa7a01107" />
" alt="Rice Oat Acne Soap">

<div class="product-content">
<h3>Rice Oat Acne Soap</h3>

<div class="price">₦4,000</div>

<p>
Gentle cleansing soap designed to help soothe irritation,
balance oil production and support acne-prone skin.
</p>
</div>
</div>

<div class="product-card">
<img src="assets/images/<img width="1254" height="1254" alt="assetsimagestoner-soap jpg" src="https://github.com/user-attachments/assets/98c7cdd3-608a-43b2-beb4-04df79a46366" />
" alt="Turmeric Honey Toner Soap">

<div class="product-content">
<h3>Turmeric Honey Toner Soap</h3>

<div class="price">₦4,000</div>

<p>
Brightening soap enriched with turmeric and honey
to help improve skin tone and restore natural glow.
</p>
</div>
</div>

</div>

</section>

<section class="story">

<div class="story-content">

<h2 class="section-title">Inspired By Nature. Crafted For Africa.</h2>

<p>
The West African climate exposes the skin to intense sunlight,
humidity, dust, environmental pollution and seasonal dryness.
Wind Beauty products are formulated with nourishing oils,
protective botanical extracts and moisturizing butters that help
maintain the skin barrier while supporting healthy, radiant skin.
</p>

<p>
Our philosophy combines traditional African botanical wisdom
with modern skincare principles to create products that help
your skin look healthy, smooth, hydrated and naturally beautiful.
</p>

</div>

</section>

<section class="cta">

<h2>Experience Natural Luxury</h2>

<p>
Discover skincare that celebrates nature, quality and beauty.
Join the growing community of customers choosing Wind Beauty
for healthy radiant skin.
</p>

<a href="products.html" class="btn btn-secondary">
Explore Products
</a>

</section>

<footer>

<p><strong>WIND BEAUTY LIMITED</strong></p>

<p>
Bringing Beauty To You On The Wings Of Mother Nature
</p>

<p>
📞 +234 813 754 7281
</p>

<p>
© 2026 Wind Beauty Limited. All Rights Reserved.
</p>

</footer>

</body>
</html>
