
<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>FinanceFlow</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#f4f7ff;
color:#222;
}

/* HEADER */

header{
background:linear-gradient(135deg,#111827,#2563eb);
padding:18px 8%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:1000;
}

header h1{
color:white;
font-size:32px;
font-weight:700;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
font-weight:500;
}

/* HERO */

.hero{
background:
linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
url('https://images.unsplash.com/photo-1554224155-6726b3ff858f?q=80&w=1600&auto=format&fit=crop');

background-size:cover;
background-position:center;
height:90vh;

display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
color:white;
}

.hero-content h2{
font-size:58px;
margin-bottom:20px;
font-weight:700;
}

.hero-content p{
font-size:22px;
margin-bottom:30px;
}

.hero-btn{
display:inline-block;
padding:15px 32px;
background:#ffcc00;
color:#111;
text-decoration:none;
font-weight:700;
border-radius:40px;
transition:0.3s;
}

.hero-btn:hover{
transform:scale(1.05);
background:white;
}

/* TITLE */

.section-title{
text-align:center;
font-size:42px;
margin-top:70px;
margin-bottom:20px;
color:#1e293b;
}

/* LOAN CARDS */

.loan-container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:28px;
padding:50px 8%;
}

.loan-card{
background:white;
border-radius:22px;
overflow:hidden;
box-shadow:0 10px 25px rgba(0,0,0,0.12);
transition:0.4s;
}

.loan-card:hover{
transform:translateY(-10px);
}

.loan-card img{
width:100%;
height:220px;
object-fit:cover;
}

.loan-content{
padding:22px;
}

.loan-content h3{
font-size:26px;
margin-bottom:12px;
color:#2563eb;
}

.loan-content p{
font-size:15px;
line-height:1.7;
margin-bottom:20px;
}

.apply-btn{
display:inline-block;
padding:12px 24px;
background:linear-gradient(135deg,#2563eb,#7c3aed);
color:white;
text-decoration:none;
border-radius:30px;
font-weight:600;
}

/* FEATURES */

.features{
background:linear-gradient(135deg,#2563eb,#7c3aed);
padding:80px 8%;
color:white;
margin-top:40px;
}

.features h2{
text-align:center;
font-size:42px;
margin-bottom:40px;
}

.feature-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.feature-box{
background:rgba(255,255,255,0.12);
padding:30px;
border-radius:18px;
text-align:center;
}

.feature-box h3{
margin-bottom:12px;
font-size:24px;
}

/* CONTACT */

.contact{
padding:80px 8%;
text-align:center;
}

.contact h2{
font-size:42px;
margin-bottom:25px;
}

.contact-box{
background:white;
padding:30px;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
max-width:700px;
margin:auto;
}

.contact-box p{
font-size:18px;
margin-bottom:15px;
}

/* FOOTER */

footer{
background:#111827;
color:white;
text-align:center;
padding:22px;
margin-top:40px;
}

/* WHATSAPP */

.whatsapp{
position:fixed;
right:20px;
bottom:20px;
z-index:999;
}

.whatsapp img{
width:70px;
}

/* MOBILE */

@media(max-width:768px){

.hero-content h2{
font-size:36px;
}

.hero-content p{
font-size:18px;
}

nav{
display:none;
}

}

</style>

</head>

<body>

<header>

<h1>FinanceFlow</h1>

<nav>
<a href="#">Home</a>
<a href="#">Loans</a>
<a href="#">Features</a>
<a href="#contact">Contact</a>
</nav>

</header>

<!-- HERO -->

<section class="hero">

<div class="hero-content">

<h2>Fast & Easy Loan Solutions</h2>

<p>
Personal Loan | Business Loan | Home Loan | Mortgage Loan | Used Car Loan
</p>

<a href="#contact" class="hero-btn">Contact Now</a>

</div>

</section>

<!-- LOANS -->

<h2 class="section-title">Our Loan Services</h2>

<section class="loan-container">

<div class="loan-card">

<img src="https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?q=80&w=1200&auto=format&fit=crop">

<div class="loan-content">

<h3>Personal Loan</h3>

<p>
Quick approvals with minimum documentation and low interest rates.
</p>

<a href="#contact" class="apply-btn">Apply Now</a>

</div>
</div>

<div class="loan-card">

<img src="https://images.unsplash.com/photo-1664575602554-2087b04935a5?q=80&w=1200&auto=format&fit=crop">

<div class="loan-content">

<h3>Business Loan</h3>

<p>
Flexible funding solutions for startups, shops, and growing businesses.
</p>

<a href="#contact" class="apply-btn">Apply Now</a>

</div>
</div>

<div class="loan-card">

<img src="https://images.unsplash.com/photo-1560518883-ce09059eeffa?q=80&w=1200&auto=format&fit=crop">

<div class="loan-content">

<h3>Home Loan</h3>

<p>
Affordable home loans with attractive EMI repayment options.
</p>

<a href="#contact" class="apply-btn">Apply Now</a>

</div>
</div>

<div class="loan-card">

<img src="https://images.unsplash.com/photo-1570129477492-45c003edd2be?q=80&w=1200&auto=format&fit=crop">

<div class="loan-content">

<h3>Mortgage Loan</h3>

<p>
Unlock your property value with high-value mortgage loans.
</p>

<a href="#contact" class="apply-btn">Apply Now</a>

</div>
</div>

<div class="loan-card">

<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1200&auto=format&fit=crop">

<div class="loan-content">

<h3>Used Car Loan</h3>

<p>
Easy finance solutions for second-hand car purchases.
</p>

<a href="#contact" class="apply-btn">Apply Now</a>

</div>
</div>

</section>

<!-- FEATURES -->

<section class="features">

<h2>Why Choose FinanceFlow?</h2>

<div class="feature-grid">

<div class="feature-box">
<h3>⚡ Instant Approval</h3>
<p>Fast processing and quicker disbursement.</p>
</div>

<div class="feature-box">
<h3>📄 Less Documentation</h3>
<p>Simple process with minimum paperwork.</p>
</div>

<div class="feature-box">
<h3>💰 Low Interest Rates</h3>
<p>Affordable EMI and flexible repayment plans.</p>
</div>

<div class="feature-box">
<h3>🤝 Trusted Service</h3>
<p>Dedicated customer support and guidance.</p>
</div>

</div>

</section>

<!-- CONTACT -->

<section class="contact" id="contact">

<h2>Contact Us</h2>

<div class="contact-box">

<p><b>📞 Phone:</b> +91 9542359321</p>

<p><b>📧 Email:</b> jayashreeailla95@gmail.com</p>

<p><b>📍 Address:</b> Hyderabad, India</p>

<p><b>⏰ Working Hours:</b> Mon - Sat : 9AM to 7PM</p>

</div>

</section>

<!-- FOOTER -->

<footer>

<p>© 2026 FinanceFlow. All Rights Reserved.</p>

</footer>

<!-- WHATSAPP -->

<a class="whatsapp" href="https://wa.me/919542359321" target="_blank">

<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png">

</a>

</body>

</html>
