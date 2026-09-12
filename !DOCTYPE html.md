<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">



<title>INVENIO 2026 | Yoshida Shokanji International</title>



<style>

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800\&family=Space+Grotesk:wght@500;600;700\&display=swap');



\* {

&#x20;   margin: 0;

&#x20;   padding: 0;

&#x20;   box-sizing: border-box;

&#x20;   scroll-behavior: smooth;

}



body {

&#x20;   font-family: 'Inter', sans-serif;

&#x20;   background: #050816;

&#x20;   color: white;

&#x20;   overflow-x: hidden;

}



/\* ---------- BACKGROUND ---------- \*/



body::before {

&#x20;   content: "";

&#x20;   position: fixed;

&#x20;   inset: 0;

&#x20;   z-index: -2;

&#x20;   background:

&#x20;       radial-gradient(circle at 20% 20%, rgba(93, 52, 180, .25), transparent 30%),

&#x20;       radial-gradient(circle at 80% 30%, rgba(25, 100, 220, .18), transparent 30%),

&#x20;       radial-gradient(circle at 50% 90%, rgba(150, 40, 200, .15), transparent 35%),

&#x20;       #050816;

}



.stars {

&#x20;   position: fixed;

&#x20;   inset: 0;

&#x20;   z-index: -1;

&#x20;   pointer-events: none;

&#x20;   background-image:

&#x20;       radial-gradient(2px 2px at 20% 30%, white, transparent),

&#x20;       radial-gradient(1px 1px at 70% 20%, white, transparent),

&#x20;       radial-gradient(2px 2px at 80% 70%, white, transparent),

&#x20;       radial-gradient(1px 1px at 40% 80%, white, transparent),

&#x20;       radial-gradient(1px 1px at 90% 40%, white, transparent),

&#x20;       radial-gradient(2px 2px at 10% 70%, white, transparent);

&#x20;   background-size: 400px 400px;

&#x20;   opacity: .5;

}



/\* ---------- NAVBAR ---------- \*/



nav {

&#x20;   position: fixed;

&#x20;   top: 0;

&#x20;   width: 100%;

&#x20;   z-index: 100;

&#x20;   padding: 18px 7%;

&#x20;   display: flex;

&#x20;   align-items: center;

&#x20;   justify-content: space-between;



&#x20;   background: rgba(5, 8, 22, .72);

&#x20;   backdrop-filter: blur(18px);

&#x20;   border-bottom: 1px solid rgba(255,255,255,.08);

}



.logo {

&#x20;   font-family: 'Space Grotesk', sans-serif;

&#x20;   font-size: 25px;

&#x20;   font-weight: 700;

&#x20;   letter-spacing: 1px;

}



.logo span {

&#x20;   background: linear-gradient(90deg,#b66cff,#56c9ff);

&#x20;   -webkit-background-clip: text;

&#x20;   color: transparent;

}



.nav-links {

&#x20;   display: flex;

&#x20;   gap: 35px;

&#x20;   list-style: none;

}



.nav-links a {

&#x20;   color: #d9dcf5;

&#x20;   text-decoration: none;

&#x20;   font-size: 14px;

&#x20;   transition: .3s;

}



.nav-links a:hover {

&#x20;   color: #a86cff;

}



.nav-btn {

&#x20;   padding: 11px 20px;

&#x20;   border-radius: 30px;

&#x20;   background: linear-gradient(90deg,#a94cff,#4fc3ff);

&#x20;   color: white !important;

&#x20;   font-weight: 600;

}



/\* ---------- HERO ---------- \*/



.hero {

&#x20;   min-height: 100vh;

&#x20;   display: flex;

&#x20;   align-items: center;

&#x20;   padding: 120px 8% 70px;

&#x20;   position: relative;

}



.hero-content {

&#x20;   max-width: 680px;

}



.badge {

&#x20;   display: inline-block;

&#x20;   padding: 9px 18px;

&#x20;   border: 1px solid rgba(160,100,255,.5);

&#x20;   border-radius: 30px;

&#x20;   color: #cda9ff;

&#x20;   font-size: 13px;

&#x20;   margin-bottom: 25px;

&#x20;   background: rgba(120,60,220,.08);

}



.hero h1 {

&#x20;   font-family: 'Space Grotesk', sans-serif;

&#x20;   font-size: clamp(55px, 8vw, 100px);

&#x20;   line-height: .95;

&#x20;   margin-bottom: 25px;

}



.gradient {

&#x20;   background: linear-gradient(90deg,#c36cff,#5bcaff);

&#x20;   -webkit-background-clip: text;

&#x20;   color: transparent;

}



.hero p {

&#x20;   color: #b5bad5;

&#x20;   font-size: 18px;

&#x20;   line-height: 1.7;

&#x20;   max-width: 600px;

}



.hero-buttons {

&#x20;   margin-top: 35px;

&#x20;   display: flex;

&#x20;   gap: 15px;

&#x20;   flex-wrap: wrap;

}



.btn {

&#x20;   text-decoration: none;

&#x20;   padding: 14px 25px;

&#x20;   border-radius: 30px;

&#x20;   font-weight: 600;

&#x20;   transition: .3s;

}



.primary {

&#x20;   background: linear-gradient(90deg,#a84dff,#49c5ff);

&#x20;   color: white;

}



.secondary {

&#x20;   border: 1px solid rgba(255,255,255,.2);

&#x20;   color: white;

&#x20;   background: rgba(255,255,255,.04);

}



.btn:hover {

&#x20;   transform: translateY(-3px);

}



/\* ---------- PLANET ---------- \*/



.planet {

&#x20;   position: absolute;

&#x20;   right: 8%;

&#x20;   width: 360px;

&#x20;   height: 360px;

&#x20;   border-radius: 50%;



&#x20;   background:

&#x20;       radial-gradient(circle at 30% 25%, #b9a0ff, #6d42c8 35%, #20104e 75%);



&#x20;   box-shadow:

&#x20;       0 0 60px rgba(130,70,255,.6),

&#x20;       0 0 130px rgba(70,150,255,.2);

}



.planet::after {

&#x20;   content: "";

&#x20;   position: absolute;

&#x20;   width: 520px;

&#x20;   height: 110px;

&#x20;   border: 2px solid rgba(150,130,255,.5);

&#x20;   border-radius: 50%;

&#x20;   top: 125px;

&#x20;   left: -80px;

&#x20;   transform: rotate(-15deg);

}



/\* ---------- SECTIONS ---------- \*/



section {

&#x20;   padding: 100px 8%;

}



.section-title {

&#x20;   text-align: center;

&#x20;   margin-bottom: 60px;

}



.section-title small {

&#x20;   color: #a66cff;

&#x20;   text-transform: uppercase;

&#x20;   letter-spacing: 3px;

&#x20;   font-weight: 700;

}



.section-title h2 {

&#x20;   font-family: 'Space Grotesk';

&#x20;   font-size: 45px;

&#x20;   margin-top: 12px;

}



.section-title p {

&#x20;   color: #a9aec8;

&#x20;   max-width: 650px;

&#x20;   margin: 15px auto;

&#x20;   line-height: 1.7;

}



/\* ---------- ABOUT ---------- \*/



.about-grid {

&#x20;   display: grid;

&#x20;   grid-template-columns: 1fr 1fr;

&#x20;   gap: 50px;

&#x20;   align-items: center;

}



.about-text h3 {

&#x20;   font-size: 30px;

&#x20;   margin-bottom: 20px;

}



.about-text p {

&#x20;   color: #aeb3ce;

&#x20;   line-height: 1.8;

&#x20;   margin-bottom: 18px;

}



.about-card {

&#x20;   padding: 45px;

&#x20;   border-radius: 25px;

&#x20;   background: linear-gradient(

&#x20;       145deg,

&#x20;       rgba(125,70,220,.18),

&#x20;       rgba(30,120,220,.08)

&#x20;   );

&#x20;   border: 1px solid rgba(255,255,255,.1);

&#x20;   box-shadow: 0 20px 70px rgba(0,0,0,.3);

}



.about-card h3 {

&#x20;   font-size: 25px;

&#x20;   margin-bottom: 20px;

}



.about-card ul {

&#x20;   list-style: none;

}



.about-card li {

&#x20;   padding: 13px 0;

&#x20;   border-bottom: 1px solid rgba(255,255,255,.08);

&#x20;   color: #c7cae0;

}



/\* ---------- EVENTS ---------- \*/



.events {

&#x20;   display: grid;

&#x20;   grid-template-columns: repeat(3,1fr);

&#x20;   gap: 20px;

}



.event-card {

&#x20;   padding: 30px;

&#x20;   min-height: 210px;

&#x20;   border-radius: 22px;

&#x20;   background: rgba(255,255,255,.04);

&#x20;   border: 1px solid rgba(255,255,255,.08);

&#x20;   transition: .35s;

}



.event-card:hover {

&#x20;   transform: translateY(-8px);

&#x20;   border-color: rgba(160,90,255,.5);

&#x20;   background: rgba(120,70,220,.08);

}



.icon {

&#x20;   font-size: 35px;

&#x20;   margin-bottom: 20px;

}



.event-card h3 {

&#x20;   margin-bottom: 10px;

}



.event-card p {

&#x20;   color: #9fa5c2;

&#x20;   line-height: 1.6;

}



/\* ---------- GALLERY ---------- \*/



.gallery {

&#x20;   display: grid;

&#x20;   grid-template-columns: repeat(3,1fr);

&#x20;   gap: 15px;

}



.gallery-item {

&#x20;   height: 250px;

&#x20;   border-radius: 20px;

&#x20;   overflow: hidden;

&#x20;   position: relative;

&#x20;   background: linear-gradient(135deg,#21124d,#102e5b);

&#x20;   border: 1px solid rgba(255,255,255,.08);

}



.gallery-item img {

&#x20;   width: 100%;

&#x20;   height: 100%;

&#x20;   object-fit: cover;

&#x20;   transition: .5s;

}



.gallery-item:hover img {

&#x20;   transform: scale(1.08);

}



.gallery-placeholder {

&#x20;   width: 100%;

&#x20;   height: 100%;

&#x20;   display: flex;

&#x20;   align-items: center;

&#x20;   justify-content: center;

&#x20;   color: #888fac;

&#x20;   font-size: 14px;

}



/\* ---------- CONTACT ---------- \*/



.contact-container {

&#x20;   max-width: 950px;

&#x20;   margin: auto;

&#x20;   display: grid;

&#x20;   grid-template-columns: 1fr 1fr;

&#x20;   gap: 25px;

}



.contact-card {

&#x20;   padding: 35px;

&#x20;   border-radius: 22px;

&#x20;   background: rgba(255,255,255,.04);

&#x20;   border: 1px solid rgba(255,255,255,.08);

}



.contact-card h3 {

&#x20;   margin-bottom: 20px;

}



.contact-card p {

&#x20;   color: #a9aec8;

&#x20;   line-height: 1.8;

&#x20;   margin-bottom: 12px;

}



.contact-card a {

&#x20;   color: #a96cff;

&#x20;   text-decoration: none;

}



/\* ---------- FOOTER ---------- \*/



footer {

&#x20;   padding: 45px 8%;

&#x20;   text-align: center;

&#x20;   border-top: 1px solid rgba(255,255,255,.08);

&#x20;   color: #777d9b;

}



footer strong {

&#x20;   color: white;

}



/\* ---------- MOBILE ---------- \*/



@media(max-width:900px) {



&#x20;   .nav-links {

&#x20;       display: none;

&#x20;   }



&#x20;   .planet {

&#x20;       opacity: .25;

&#x20;       right: -100px;

&#x20;   }



&#x20;   .about-grid,

&#x20;   .contact-container {

&#x20;       grid-template-columns: 1fr;

&#x20;   }



&#x20;   .events {

&#x20;       grid-template-columns: 1fr 1fr;

&#x20;   }



&#x20;   .gallery {

&#x20;       grid-template-columns: 1fr 1fr;

&#x20;   }

}



@media(max-width:600px) {



&#x20;   section {

&#x20;       padding: 75px 6%;

&#x20;   }



&#x20;   .hero {

&#x20;       padding: 120px 6% 70px;

&#x20;   }



&#x20;   .hero h1 {

&#x20;       font-size: 55px;

&#x20;   }



&#x20;   .events,

&#x20;   .gallery {

&#x20;       grid-template-columns: 1fr;

&#x20;   }



&#x20;   .section-title h2 {

&#x20;       font-size: 35px;

&#x20;   }

}

</style>

</head>



<body>



<div class="stars"></div>



<!-- NAVIGATION -->



<nav>



&#x20;   <div class="logo">

&#x20;       INVE<span>NIO</span>

&#x20;   </div>



&#x20;   <ul class="nav-links">

&#x20;       <li><a href="#home">Home</a></li>

&#x20;       <li><a href="#about">About Us</a></li>

&#x20;       <li><a href="#events">Events</a></li>

&#x20;       <li><a href="#gallery">Gallery</a></li>

&#x20;       <li><a href="#contact">Contact Us</a></li>

&#x20;       <li>

&#x20;           <a href="#contact" class="nav-btn">Get Involved →</a>

&#x20;       </li>

&#x20;   </ul>



</nav>





<!-- HERO -->



<section class="hero" id="home">



&#x20;   <div class="hero-content">



&#x20;       <span class="badge">

&#x20;           YOSHIDA SHOKANJI INTERNATIONAL • 2026

&#x20;       </span>



&#x20;       <h1>

&#x20;           Where Ideas<br>

&#x20;           Become <span class="gradient">Innovation.</span>

&#x20;       </h1>



&#x20;       <p>

&#x20;           Welcome to INVENIO 2026 — a celebration of science,

&#x20;           creativity, innovation and young minds bringing ideas

&#x20;           to life.

&#x20;       </p>



&#x20;       <div class="hero-buttons">



&#x20;           <a href="#about" class="btn primary">

&#x20;               Explore INVENIO →

&#x20;           </a>



&#x20;           <a href="#gallery" class="btn secondary">

&#x20;               View Gallery

&#x20;           </a>



&#x20;       </div>



&#x20;   </div>



&#x20;   <div class="planet"></div>



</section>





<!-- ABOUT -->



<section id="about">



&#x20;   <div class="section-title">



&#x20;       <small>About Us</small>



&#x20;       <h2>Discover INVENIO</h2>



&#x20;       <p>

&#x20;           A platform where curiosity meets creativity and

&#x20;           students transform ideas into meaningful innovations.

&#x20;       </p>



&#x20;   </div>



&#x20;   <div class="about-grid">



&#x20;       <div class="about-text">



&#x20;           <h3>More Than An Exhibition.</h3>



&#x20;           <p>

&#x20;               INVENIO is an innovation and science exhibition

&#x20;               organised by the Maths \& Science Society together

&#x20;               with the Environmental Society of Yoshida Shokanji

&#x20;               International.

&#x20;           </p>



&#x20;           <p>

&#x20;               From young scientists and inventors to artists,

&#x20;               researchers and problem-solvers, INVENIO gives

&#x20;               students a platform to showcase what they can create.

&#x20;           </p>



&#x20;           <p>

&#x20;               This year's exhibition explores the intersection of

&#x20;               science, technology, sustainability and imagination.

&#x20;           </p>



&#x20;       </div>



&#x20;       <div class="about-card">



&#x20;           <h3>Explore Our Themes</h3>



&#x20;           <ul>

&#x20;               <li>🌱 Agriculture</li>

&#x20;               <li>⚡ Energy</li>

&#x20;               <li>🌍 Sustainability \& Conservation</li>

&#x20;               <li>🤖 Modern Technology</li>

&#x20;               <li>🔬 Natural Sciences</li>

&#x20;           </ul>



&#x20;       </div>



&#x20;   </div>



</section>





<!-- EVENTS -->



<section id="events">



&#x20;   <div class="section-title">



&#x20;       <small>Experience</small>



&#x20;       <h2>What's Happening?</h2>



&#x20;       <p>

&#x20;           There's something for everyone at INVENIO.

&#x20;       </p>



&#x20;   </div>



&#x20;   <div class="events">



&#x20;       <div class="event-card">

&#x20;           <div class="icon">🚀</div>

&#x20;           <h3>Innovation Exhibition</h3>

&#x20;           <p>

&#x20;               Explore creative inventions and innovative

&#x20;               solutions created by young minds.

&#x20;           </p>

&#x20;       </div>



&#x20;       <div class="event-card">

&#x20;           <div class="icon">🧠</div>

&#x20;           <h3>Interschool Quiz</h3>

&#x20;           <p>

&#x20;               Put your science and mathematics knowledge

&#x20;               to the ultimate test.

&#x20;           </p>

&#x20;       </div>



&#x20;       <div class="event-card">

&#x20;           <div class="icon">🎨</div>

&#x20;           <h3>Poster Gallery</h3>

&#x20;           <p>

&#x20;               Discover scientific ideas presented through

&#x20;               creativity and visual storytelling.

&#x20;           </p>

&#x20;       </div>



&#x20;       <div class="event-card">

&#x20;           <div class="icon">👩‍🚀</div>

&#x20;           <h3>Science Costume Parade</h3>

&#x20;           <p>

&#x20;               Watch young innovators bring the world of

&#x20;               space and science to life.

&#x20;           </p>

&#x20;       </div>



&#x20;       <div class="event-card">

&#x20;           <div class="icon">🎮</div>

&#x20;           <h3>Games \& Activities</h3>

&#x20;           <p>

&#x20;               Challenge yourself with fun science-themed

&#x20;               games and activities.

&#x20;           </p>

&#x20;       </div>



&#x20;       <div class="event-card">

&#x20;           <div class="icon">🍴</div>

&#x20;           <h3>Food Stalls</h3>

&#x20;           <p>

&#x20;               Take a break, grab something delicious and

&#x20;               enjoy the exhibition.

&#x20;           </p>

&#x20;       </div>



&#x20;   </div>



</section>





<!-- GALLERY -->



<section id="gallery">



&#x20;   <div class="section-title">



&#x20;       <small>Moments</small>



&#x20;       <h2>Gallery</h2>



&#x20;       <p>

&#x20;           A glimpse into the world of INVENIO.

&#x20;       </p>



&#x20;   </div>



&#x20;   <div class="gallery">



&#x20;       <!-- Replace these with your actual photos -->



&#x20;       <div class="gallery-item">

&#x20;           <div class="gallery-placeholder">

&#x20;               Your Photo Here

&#x20;           </div>

&#x20;       </div>



&#x20;       <div class="gallery-item">

&#x20;           <div class="gallery-placeholder">

&#x20;               Your Photo Here

&#x20;           </div>

&#x20;       </div>



&#x20;       <div class="gallery-item">

&#x20;           <div class="gallery-placeholder">

&#x20;               Your Photo Here

&#x20;           </div>

&#x20;       </div>



&#x20;       <div class="gallery-item">

&#x20;           <div class="gallery-placeholder">

&#x20;               Your Photo Here

&#x20;           </div>

&#x20;       </div>



&#x20;       <div class="gallery-item">

&#x20;           <div class="gallery-placeholder">

&#x20;               Your Photo Here

&#x20;           </div>

&#x20;       </div>



&#x20;       <div class="gallery-item">

&#x20;           <div class="gallery-placeholder">

&#x20;               Your Photo Here

&#x20;           </div>

&#x20;       </div>



&#x20;   </div>



</section>





<!-- CONTACT -->



<section id="contact">



&#x20;   <div class="section-title">



&#x20;       <small>Get In Touch</small>



&#x20;       <h2>Contact Us</h2>



&#x20;       <p>

&#x20;           Have a question about INVENIO? We'd love to hear from you.

&#x20;       </p>



&#x20;   </div>



&#x20;   <div class="contact-container">



&#x20;       <div class="contact-card">



&#x20;           <h3>INVENIO 2026</h3>



&#x20;           <p>

&#x20;               📍 Yoshida Shokanji International

&#x20;           </p>



&#x20;           <p>

&#x20;               📅 September 2026

&#x20;           </p>



&#x20;           <p>

&#x20;               🔬 Maths \& Science Society

&#x20;           </p>



&#x20;           <p>

&#x20;               🌱 Environmental Society

&#x20;           </p>



&#x20;       </div>



&#x20;       <div class="contact-card">



&#x20;           <h3>Reach Us</h3>



&#x20;           <p>

&#x20;               For enquiries and registration:

&#x20;           </p>



&#x20;           <p>

&#x20;               📱 <a href="#">WhatsApp / Contact Number</a>

&#x20;           </p>



&#x20;           <p>

&#x20;               ✉️ <a href="#">Email Address</a>

&#x20;           </p>



&#x20;           <p>

&#x20;               📷 <a href="#">Instagram</a>

&#x20;           </p>



&#x20;       </div>



&#x20;   </div>



</section>





<!-- FOOTER -->



<footer>



&#x20;   <p>

&#x20;       © 2026 <strong>INVENIO</strong> ·

&#x20;       Yoshida Shokanji International

&#x20;   </p>



&#x20;   <p style="margin-top:10px;">

&#x20;       Ideas • Innovation • Impact

&#x20;   </p>



</footer>





</body>

</html>

