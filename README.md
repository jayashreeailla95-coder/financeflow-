
gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
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

/* SLIDER */

.slider{
background:#2563eb;
color:white;
padding:15px 0;
font-size:18px;
font-weight:600;
}

/* SECTION TITLE */

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

/* EMI */

.emi-section{
padding:70px 8%;
text-align:center;
}

.calculator-box{
background:white;
max-width:500px;
margin:auto;
padding:30px;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
}

.calculator-box input{
width:100%;
padding:15px;
margin-bottom:15px;
border-radius:10px;
border:1px solid #ccc;
}

.calc-btn{
background:#2563eb;
color:white;
padding:15px 30px;
border:none;
border-radius:30px;
font-size:16px;
cursor:pointer;
}

/* REVIEWS */

.review-section{
padding:70px 8%;
background:#eef3ff;
}

.review-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.review-box{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 10px 20px rgba(0,0,0,0.1);
}

/* CONTACT */

.contact{
padding:80px 8%;
text-align:center;
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

/* FORM */

form{
margin-top:30px;
}

form input,form textarea{
width:100%;
padding:15px;
margin-bottom:15px;
border-radius:10px;
border:1px solid #ccc;
}

.submit-btn{
background:linear-gradient(135deg,#2563eb,#7c3aed);
color:white;
padding:15px 30px;
border:none;
border-radius:30px;
font-size:16px;
font-weight:600;
cursor:pointer;
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

<h1>💰 FinanceFlow</h1>

<nav>
<a href="#">Home</a>
<a href="#">Loans</a>
<a href="#">EMI</a>
<a href="#">Contact</a>
</nav>

</header>

<!-- HERO -->

<section class="hero">

<div class="hero-content">

<h2>Fast & Easy Loan Solutions</h2>

<p>
Personal Loan | Business Loan | Home Loan | Mortgage Loan | Used Car Loan
</p>

<a href="#contact" class="hero-btn">Apply Now</a>

</div>

</section>

<!-- SLIDER -->

<div class="slider">

<marquee scrollamount="8">

🔥 Instant Personal Loan &nbsp;&nbsp;&nbsp;
🏠 Home Loan Available &nbsp;&nbsp;&nbsp;
🚗 Used Car Loan Available &nbsp;&nbsp;&nbsp;
💼 Business Loan Available &nbsp;&nbsp;&nbsp;
🏢 Mortgage Loan Available

</marquee>

</div>

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
Flexible funding solutions for startups and growing businesses.
</p>

<a href="#contact" class="apply-btn">Apply Now</a>

</div>
</div>

<div class="loan-card">

<img src="https
<a class="whatsapp" href="https://wa.me/919542359321" target="_blank">

<img src="https://cdn-icons-png.flaticon.com/512/733/733585.png">
</a>

</body>

</html>
