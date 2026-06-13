# REYESHOTSPRINGPRIVATEPOOL
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reyes Hotspring Private Pool</title>

<style>

/* RESET */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f5f5;
    color:#333;
}

/* HEADER */
header{
    background:#0b3d2e;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    margin-top:10px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

/* HERO */
.hero{
    height:80vh;
    background:url('B6851927-AF54-42A9-9695-B6C8ECC4A5C1.png') center/cover;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.hero-content{
    background:rgba(0,0,0,0.5);
    color:white;
    padding:40px;
    border-radius:15px;
}

.hero h1{
    font-size:50px;
    margin-bottom:15px;
}

.hero p{
    font-size:20px;
}

/* SECTION */
section{
    padding:60px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    color:#0b3d2e;
}

/* AMENITIES */
.amenities{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
    text-align:center;
}

/* RATES TABS */
.tabs{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    margin-bottom:30px;
}

.tab-btn{
    border:none;
    background:#0b3d2e;
    color:white;
    padding:15px 30px;
    margin:5px;
    cursor:pointer;
    border-radius:10px;
}

.tab-btn.active{
    background:#16a085;
}

.tab-content{
    display:none;
}

.tab-content.active{
    display:block;
}

.price-card{
    background:white;
    padding:30px;
    max-width:600px;
    margin:auto;
    border-radius:15px;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

.price-card h3{
    color:#0b3d2e;
    margin-bottom:15px;
}

/* CONTACT */
.contact{
    background:#0b3d2e;
    color:white;
    text-align:center;
}

.contact p{
    margin:10px 0;
}

/* FOOTER */
footer{
    text-align:center;
    padding:20px;
    background:#06261d;
    color:white;
}

</style>
</head>
<body>

<header>
    <h1>🏖️ Reyes Hotspring Private Pool</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#amenities">Amenities</a>
        <a href="#pricing">Rates</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HERO -->
<section class="hero" id="home">
    <div class="hero-content">
        <h1>Relax. Swim. Enjoy.</h1>
        <p>Your Perfect Private Resort Getaway in Pansol, Laguna</p>
    </div>
</section>

<!-- AMENITIES -->
<section id="amenities">
    <h2 class="section-title">Resort Amenities</h2>

    <div class="amenities">

        <div class="card">
            <h3>🏊 Adult Pool</h3>
            <p>Natural Hotspring Swimming Pool</p>
        </div>

        <div class="card">
            <h3>🛝 Kiddie Pool</h3>
            <p>Safe Pool for Children</p>
        </div>

        <div class="card">
            <h3>❄️ Airconditioned Rooms</h3>
            <p>2 Rooms with Private Bathrooms</p>
        </div>

        <div class="card">
            <h3>🍳 Kitchen Area</h3>
            <p>Complete Cooking Facilities</p>
        </div>

        <div class="card">
            <h3>🎤 Videoke</h3>
            <p>Enjoy Singing with Family & Friends</p>
        </div>

        <div class="card">
            <h3>🚗 Garage</h3>
            <p>Secure Parking Area</p>
        </div>

    </div>
</section>

<!-- RATES -->
<section id="pricing">
    <h2 class="section-title">Price Range</h2>

    <div class="tabs">
        <button class="tab-btn active" onclick="showTab('day')">Day Tour</button>
        <button class="tab-btn" onclick="showTab('night')">Overnight</button>
        <button class="tab-btn" onclick="showTab('hours22')">22 Hours</button>
    </div>

    <div id="day" class="tab-content active">
        <div class="price-card">
            <h3>☀️ Day Tour</h3>
            <p><strong>Weekday:</strong> ₱6,000</p>
            <p><strong>Weekend:</strong> ₱7,000</p>
        </div>
    </div>

    <div id="night" class="tab-content">
        <div class="price-card">
            <h3>🌙Overnight</h3>
            <p><strong>Weekday:</strong> ₱7,000</p>
            <p><strong>Weekend:</strong> ₱8,000</p>
        </div>
    </div>

    <div id="hours22" class="tab-content">
        <div class="price-card">
            <h3>🏡 22 Hours Stay</h3>
            <p><strong>Weekday:</strong> ₱10,000</p>
            <p><strong>Weekend:</strong> Contact Us</p>
        </div>
    </div>
</section>

<!-- CONTACT SECTION -->
<section class="contact" id="contact">
    <h2>Contact Us</h2>

    <p>📍 Pansol, Calamba City, Laguna</p>
    <p>For inquiries and reservations, contact us through WhatsApp or Viber:</p>

    <div class="contact-container">

        <div class="contact-card">
            <h3>📱 0917-806-4028</h3>

            <a href="https://wa.me/639178064028" target="_blank" class="whatsapp-btn">
                WhatsApp
            </a>

            <a href="viber://chat?number=%2B639178064028" class="viber-btn">
                Viber
            </a>
        </div>

        <div class="contact-card">
            <h3>📱 0915-289-6006</h3>

            <a href="https://wa.me/639152896006" target="_blank" class="whatsapp-btn">
                WhatsApp
            </a>

            <a href="viber://chat?number=%2B639152896006" class="viber-btn">
                Viber
            </a>
        </div>

    </div>
</section>

<footer>
    © 2026 Reyes Hotspring Private Pool | All Rights Reserved
</footer>

<script>

function showTab(tabId){

    let contents = document.querySelectorAll('.tab-content');
    contents.forEach(content=>{
        content.classList.remove('active');
    });

    let buttons = document.querySelectorAll('.tab-btn');
    buttons.forEach(btn=>{
        btn.classList.remove('active');
    });

    document.getElementById(tabId).classList.add('active');
    event.target.classList.add('active');
}

</script>

</body>
</html>
