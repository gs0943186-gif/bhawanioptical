  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bhawani Optical and eye care centre – 3D Graphics Website</title>
  <style>
    :root{
      --bg:#f7f9fc;
      --ink:#a2a3a7;
      --brand:#999da3;
      --line:rgba(0, 1, 3, 0.1);
      --depth: 900px;
    }
    body{margin:0;font-family:system-ui,Segoe UI,Roboto,Arial,sans-serif;color:var(--ink);background:var(--bg)}
    .container{width:min(1100px,92vw);margin:0 auto}

    /* ===== Rotating 3D Header with Matching Background ===== */
    header{
      padding:60px 0;
      text-align:center;
      perspective:var(--depth);
      position:relative;
      overflow:hidden;
      background:radial-gradient(1000px 600px at 10% -10%, #eef4ff, transparent 60%),
                 radial-gradient(900px 600px at 120% 10%, #eaf7f6, transparent 55%),
                 var(--bg);
      animation:moveBg 12s ease-in-out infinite alternate;
    }
    @keyframes moveBg{
      0%{background-position:0% 50%, 100% 50%, center}
      100%{background-position:100% 50%, 0% 50%, center}
    }

    .head-3d{
      display:inline-block;
      font-size:clamp(32px,8vw,64px);
      font-weight:900;
      letter-spacing:1px;
      color:var(--brand);
      text-transform:uppercase;
      transform-style:preserve-3d;
      animation:spinText 8s linear infinite;
      text-shadow:0 4px 16px rgba(37,99,235,.35);
    }
    @keyframes spinText{
      0%{transform:rotateY(0deg) translateZ(40px)}
      100%{transform:rotateY(360deg) translateZ(40px)}
    }
  </style>
</head>
<body>
    
  <header>
    <div class="container">
      <div class="head-3d">Bhawani Optical and eye care centre</div>
    </div>
  </header>
</body>
</html>


<header class="container" style="margin-top:20px;">
  <div style="display:flex;align-items:center;justify-content:center;gap:16px;flex-wrap:wrap;">
    
    <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcRdeiZbnVkOPgAuSrj7f-dtMt82zAHrBjK2YnoUD9ZRRETs7TwQ">
    <!-- Logo -->
    <div style="height:70px;width:70px;border-radius:16px;
                background:linear-gradient(135deg,#1f2b5a,#0f1837);
                display:flex;align-items:center;justify-content:center;
                box-shadow:0 4px 20px rgba(97,255,202,0.4);">
      <!-- Example SVG Glasses Icon -->
      <svg width="40" height="40" viewBox="0 0 24 24" fill="none"
           xmlns="http://www.w3.org/2000/svg">
        <path d="M4 13a4 4 0 1 0 8 0v-1h0a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2v1Zm8 0a4 4 0 1 0 8 0v-1a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v1Z" 
              stroke="#61ffca" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </div>

    <!-- Shop Name -->
    <div style="text-align:left;">
      <h1 style="font-size:42px;font-weight:800;
                 background:linear-gradient(90deg,#61ffca,#7aa2ff);
                 -webkit-background-clip:text;-webkit-text-fill-color:transparent;
                 margin:0;">
        Bhawani Optical
      </h1>
      <p style="margin:6px 0 0;font-size:16px;color:var(--muted);">
        Near Government Hospital, Paota, Jaipur(303106) <br>
        Optician: <strong>Ashok Kumar Sharma</strong> • 📞 <a href="tel:8003849847">8003849847 , 01421299238</a>
      </p>
    </div>

  </div>

  <!-- Navigation Buttons -->
  <div style="margin-top:14px;text-align:center;">
    <a class="btn primary" href="#services">Services</a>
    <a class="btn" href="#book">Book Eye Test</a>
    <a class="btn" href="#gallery">Gallery</a>
    <a class="btn" href="#contact">Contact</a>
    <a class="btn" href="#Payments">Payments</a>
  </div>
</header>


</header>

  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bhawani Optical – Paota, Jaipur</title>
  <meta name="description" content="Bhawani Optical – Eye testing, prescription glasses, contact lenses, sunglasses. Near Government Hospital, Paota, Jaipur. Optician: Ashok Kumar Sharma. Call 8003849847." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #0b1229;
      --card: rgba(255,255,255,.08);
      --stroke: rgba(255,255,255,.12);
      --text: #eef1ff;
      --muted: rgba(238,241,255,.78);
      --neon: #61ffca;
      --glass: rgba(255,255,255,.14);
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:var(--text);font-family:"Poppins",sans-serif}
    .container{max-width:1100px;margin:0 auto;padding:20px}
    .card{background:var(--card);border:1px solid var(--stroke);backdrop-filter: blur(10px);
      border-radius:20px;padding:18px;box-shadow:0 10px 35px rgba(0,0,0,.25);margin-bottom:20px}
    h1,h2,h3{margin:0 0 10px}
    .btn{display:inline-block;margin:5px 0;padding:10px 16px;border-radius:12px;text-decoration:none;font-weight:600;background:var(--glass);border:1px solid var(--stroke);color:var(--text)}
    .btn.primary{background:linear-gradient(135deg,var(--neon),#c5ffe9);color:#0b1229}
    footer{margin:36px 0 18px;border-top:1px dashed rgba(255,255,255,.08);padding-top:16px;color:var(--muted);font-size:14px}
    ul{padding-left:20px}
    .gallery img{width:100%;border-radius:12px;margin-bottom:12px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px}
  </style>
</head>
<body>
  
    </div>
  </header>

  <main class="container">
    <!-- About Us -->
    <section id="about" class="card">
      <h2>About Us</h2>
      <p>Welcome to <strong>Bhawani Optical</strong>, your trusted eye care and eyewear partner in Paota, Jaipur. 
      We provide quality eye testing, prescription glasses, and stylish frames at affordable prices. 
      Our mission is to ensure everyone can <em>See Better & Look Better</em>.</p>
    </section>

    <!-- Services -->
    <section id="services" class="card">
      <h2>Our Services</h2>
      <ul>
        <li>👓 Computerised Eye Testing</li>
        <li>🕶️ Prescription Glasses & Sunglasses</li>
        <li>📦 Contact Lenses (Daily/Monthly)</li>
        <li>🔧 Repairs & Frame Fitting</li>
        <li>🎯 Kids & Budget Glasses Range</li>
      </ul>
    </section>

    <!-- Price List -->
    <section id="prices" class="card">
      <h2>Price List (Sample)</h2>
      <ul>
        <li>👓 Eye Testing – <strong>Free with purchase</strong></li>
        <li>🕶️ Sunglasses – Starting from ₹500</li>
        <li>📐 Single Vision Glasses – From ₹700</li>
        <li>🔄 Progressive Lenses – From ₹1499</li>
        <li>📦 Contact Lenses – at affordable price</li>
      </ul>
    </section>

    <!-- Why Choose Us -->
    <section id="why" class="card">
      <h2>Why Choose Bhawani Optical?</h2>
      <ul>
        <li>✅ Trusted by 1000+ customers in Jaipur</li>
        <li>✅ Wide range of budget & premium frames</li>
        <li>✅ Quick delivery and on-spot adjustments</li>
        <li>✅ Friendly and professional service</li>
      </ul>
    </section>

    <!-- Booking -->
    <section id="book" class="card">
      <h2>Book an Eye Test</h2>
      <form onsubmit="return sendBooking(event)">
        <input id="name" placeholder="Your Name" required style="width:100%;padding:10px;margin:6px 0;border-radius:8px;border:1px solid var(--stroke);">
        <input id="date" placeholder="Preferred Date" required style="width:100%;padding:10px;margin:6px 0;border-radius:8px;border:1px solid var(--stroke);">
        <input id="time" placeholder="Preferred Time" required style="width:100%;padding:10px;margin:6px 0;border-radius:8px;border:1px solid var(--stroke);">
        <button type="submit" class="btn primary">Send on WhatsApp</button>
      </form>
    </section>

    <!-- Gallery -->
    <section id="gallery" class="card">
      <h2>Gallery</h2>
      <div class="grid gallery">
        <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcR32rPlt0cXhhs35FY5Kk4Na14SumAdeQTDkzS_Kz4ij3ZVYGvmrm2sh4nofW75S7hjB0CwD0MGm-PSQoKMWpzlep9SZ6iX7brUOp_G8HCgjpEXbQH_vt9Rsw0" alt="Sunglasses">
        <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcSuAaANrnWqUo1DxLK1van7S6JDjjAJg44p_z87u99y53FqIXF8O-ymKpjjV_VucYhoPPja-jBdFcsSaJ3UOplSRs0nddEQ8EypE0dq1kVrYB_ES3_nHmzn" alt="Glasses">
        <img src="data:image/jpeg;base64,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" alt="Eyewear">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSnks5Xm-2S9F93K2u4kBcB5GD0NEMKpdEkUw&s">
        <img src="https://www.eyewearlabs.com/cdn/shop/files/1_d98fa425-93a3-4127-8a0c-8d590aa46735.png?crop=center&height=2000&v=1715073649&width=2000" alt="Optical Store">
        <img src="https://m.media-amazon.com/images/I/61XpOY9bBqL._UY1100_.jpg">
        <img src="data:image/jpeg;base64,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" alt="Optical Store">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRSdkVdyHV3qJ_l6xdAwK_w44tmqritFIdpoA&s" alt="Optical Store">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSk2IwLVSaDqIMKnRMoF80BnpTSgtEFlmVOHw&s" alt="Optical Store">
        <img src="https://static5.lenskart.com/media/catalog/product/pro/1/thumbnail/628x301/9df78eab33525d08d6e5fb8d27136e95//l/i/grey-transparent-gunmetal-full-rim-square-lenskart-air-switch-la-e151319-c1-eyeglasses_g_7369_04_01_2023.jpg" alt="Optical Store">
        <img src="https://static5.lenskart.com/media/catalog/product/pro/1/thumbnail/628x301/9df78eab33525d08d6e5fb8d27136e95//l/i/silver-grey-transparent-full-rim-square-lenskart-air-fusion-la-e17017-c1-eyeglasses__dsc4914_28_05_2024_28_05_2024.jpg" alt="Optical Store">
        <img src="https://static5.lenskart.com/media/catalog/product/pro/1/thumbnail/628x301/9df78eab33525d08d6e5fb8d27136e95//v/i/vincent-chase-vc--e17029-c2-eyeglasses__dsc3303_13_05_2024.jpg" alt="Optical Store">
        <img src="https://static1.lenskart.com/media/desktop/img/May22/glasses.jpg" alt="Eyeglasses">
        <img src="https://static1.lenskart.com/media/desktop/img/May22/Sunnies.jpg" alt="Sunglasses">
        <img src="https://static1.lenskart.com/media/desktop/img/May22/computer-glasses.jpg" alt="Zero power screen glasses">
        <img src=""
      </div>
    </section>
<article class="card">
          <div class="eyebrow">Payments</div>
          <h3>UPI / Card / Cash</h3>
          <p class="sub">Show UPI QR and receipt status here.</p>
          <button class="btn alt" onclick="alert('Demo only – payment options page can be added')">See Options</button>
        </article>
        
        
    <!-- Contact & Hours -->
    <section id="contact" class="card">
      <h2>Contact & Location</h2>
      <p><strong>Phone:</strong> <a href="tel:8003849847,01421299238">8003849847,01421299238</a></p>
      <p><strong>WhatsApp:</strong> <a href="https://wa.me/918003849847" target="_blank">Chat Now</a></p>
      <p><strong>Opening Hours:</strong><br>
       9:00 AM – 8:00 PM<br>
      <iframe src="https://www.google.com/maps?q=Bhawani+Optical+Paota+Jaipur&output=embed" width="100%" height="250" style="border:0;" loading="lazy"></iframe>
    </section>
  </main>

  <footer class="container">
    <span>© <span id="year"></span> Bhawani Optical – Paota, Jaipur</span>
  </footer>
  <!-- ===== Footer Section ===== -->
<footer style="
  background: #010122;
  color: #fff;
  text-align: center;
  padding: 20px 10px;
  font-family: Arial, sans-serif;
">
  <p style="margin: 5px 0;">Copyright © <strong>Bhawani Optical</strong> 2025</p>

  <div style="margin-top: 10px;">
    <!-- Facebook -->
    <a href="https://www.facebook.com/paotaashoksharma?mibextid=ZbWKwL" target="_blank" style="margin:0 12px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Facebook_icon.svg" width="30" alt="Facebook">
    </a>

    <!-- Instagram -->
    <a href="https://www.instagram.com/ashoksharma.ashoksharma009?igsh=aHN1dmdybjNsZHhk" target="_blank" style="margin:0 12px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" width="30" alt="Instagram">
    </a>

    <!-- WhatsApp -->
    <a href="https://wa.me/918003849847" target="_blank" style="margin:0 12px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" width="30" alt="WhatsApp">
    </a>
  </div>
</footer>


  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
    function sendBooking(e){
      e.preventDefault();
      const name=document.getElementById('name').value.trim();
      const date=document.getElementById('date').value.trim();
      const time=document.getElementById('time').value.trim();
      if(!name||!date||!time) return false;
      const msg=`Eye Test Booking Request\nName: ${name}\nDate: ${date}\nTime: ${time}\nShop: Bhawani Optical`;
      window.open(`https://wa.me/918003849847?text=${encodeURIComponent(msg)}`,'_blank');
      return false;
    }
    
  </script>
</body>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
</html>
