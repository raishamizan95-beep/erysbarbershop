<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ery’s Barbershop HQ | 24 Hour Premium Barber</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#0d0d0d;
color:white;
line-height:1.6;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#000;
position:sticky;
top:0;
}

nav h1{
color:#d4af37;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
font-size:14px;
}

/* HERO */

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.9)),
url("https://images.unsplash.com/photo-1585747860715-2ba37e788b70");
background-size:cover;
background-position:center;
}

.hero h2{
font-size:48px;
margin-bottom:20px;
}

.hero p{
max-width:600px;
margin-bottom:30px;
}

.btn{
padding:12px 25px;
background:#d4af37;
border:none;
color:black;
font-weight:bold;
cursor:pointer;
margin:10px;
text-decoration:none;
border-radius:4px;
}

/* SECTION */

section{
padding:70px 10%;
}

.title{
text-align:center;
margin-bottom:40px;
}

.title h2{
color:#d4af37;
font-size:32px;
}

/* SERVICES */

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}

.card{
background:#1a1a1a;
padding:20px;
border-radius:6px;
text-align:center;
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
background:#222;
}

/* REVIEWS */

.reviews{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.review{
background:#1a1a1a;
padding:20px;
border-left:4px solid #d4af37;
}

/* LOCATION */

.location{
text-align:center;
}

iframe{
width:100%;
height:350px;
border:0;
margin-top:20px;
}

/* CTA */

.cta{
background:#d4af37;
color:black;
text-align:center;
padding:60px 20px;
}

.cta h2{
margin-bottom:20px;
}

/* FOOTER */

footer{
text-align:center;
padding:20px;
background:#000;
font-size:14px;
}

</style>
</head>

<body>

<nav>
<h1>Ery’s Barbershop HQ</h1>
<div>
<a href="#services">Services</a>
<a href="#reviews">Reviews</a>
<a href="#location">Location</a>
</div>
</nav>

<section class="hero">

<h2>Premium Grooming 24 Hours</h2>

<p>Professional barbers providing sharp fades, beard grooming, and modern haircuts anytime in Pasir Gudang.</p>

<a class="btn" href="tel:01111962687">Call Now</a>
<a class="btn" href="#location">Get Directions</a>

</section>

<section id="services">

<div class="title">
<h2>Our Services</h2>
</div>

<div class="services">

<div class="card">Beard Dyeing</div>
<div class="card">Beard Maintenance</div>
<div class="card">Beard Trim</div>
<div class="card">Buzz Cut</div>
<div class="card">Capillary Hair Treatment</div>
<div class="card">Children's Cuts</div>
<div class="card">Fade Cut</div>
<div class="card">Groom Packages</div>
<div class="card">Hair Shape-up</div>
<div class="card">Hair Straightening</div>
<div class="card">Head Shave</div>
<div class="card">Long Haircut</div>
<div class="card">Military Haircut</div>
<div class="card">Razor Cut</div>
<div class="card">Scalp Treatment</div>
<div class="card">Scissor Cut</div>
<div class="card">Shampoo & Conditioning</div>
<div class="card">Shave</div>
<div class="card">Straight Razor Shave</div>

</div>

</section>

<section id="reviews">

<div class="title">
<h2>Customer Reviews</h2>
</div>

<div class="reviews">

<div class="review">
“This barber is so nice perfect cut and recommend.”
</div>

<div class="review">
“Iwan who cut my hair did a good job. Happy to accommodate my styling request. Definitely I will come again.”
</div>

<div class="review">
“Recommended barbershop, nice haircut from experienced hair stylist and hair colouring price is affordable. Around RM100 and below you can get a very nice hair colour.”
</div>

<div class="review">
“Best barber here guys. Best price and clean work.”
</div>

</div>

</section>

<section id="location" class="location">

<div class="title">
<h2>Visit Us</h2>
</div>

<p>
58, Jalan Bacang 38<br>
Taman Kota Masai<br>
81700 Pasir Gudang<br>
Johor Darul Ta’azin
</p>

<p><strong>Open 24 Hours</strong></p>
<p>Phone: 011-11962687</p>

<iframe
src="https://maps.google.com/maps?q=58%20Jalan%20Bacang%2038%20Pasir%20Gudang&t=&z=15&ie=UTF8&iwloc=&output=embed">
</iframe>

</section>

<section class="cta">

<h2>Look Sharp Anytime – We’re Open 24 Hours</h2>

<a class="btn" href="tel:01111962687">Call Now</a>

</section>

<footer>

<p>© 2026 Ery’s Barbershop HQ | Pasir Gudang</p>

</footer>

</body>
</html>
