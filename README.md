# crypto
omo
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GROK - Komunitas Crypto Merah Putih Paling Ganas 2025</title>
  <meta name="description" content="Signal VIP 90% akurasi • Edukasi dari nol sampai whale • Komunitas 24 jam • Merah Putih Crypto Indonesia"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700;900&family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root { --red: #ff0033; --red-dark: #c7002a; --white: #ffffff; --black: #0a0a0a; --glow: #ff3366; }
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family:'Poppins',sans-serif; background:#000; color:white; overflow-x:hidden; }
    #particles-js { position:fixed; width:100%; height:100%; top:0; left:0; z-index:-1; }

    /* HERO SECTION */
    header {
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      background: linear-gradient(135deg, rgba(255,0,51,0.95), rgba(199,0,42,0.98)),
                  url('https://images.unsplash.com/photo-1639762681485-074b7f938ba0?w=1600') center/cover;
    }
    .hero h1 {
      font-family:'Orbitron',sans-serif;
      font-size:7rem;
      font-weight:900;
      background:linear-gradient(90deg, white, #ff6b6b, white);
      -webkit-background-clip:text;
      -webkit-text-fill-color:transparent;
      text-shadow:0 0 40px var(--glow);
      animation: glow 2s infinite alternate;
    }
    @keyframes glow { from { text-shadow:0 0 20px var(--glow); } to { text-shadow:0 0 60px var(--glow), 0 0 100px var(--glow); } }
    .hero p { font-size:2rem; margin:1.5rem 0; font-weight:600; }
    .hero .countdown {
      font-family:'Orbitron';
      font-size:3rem;
      background:var(--white);
      color:var(--red);
      padding:20px 60px;
      border-radius:60px;
      display:inline-block;
      margin:3rem 0;
      box-shadow:0 0 50px rgba(255,0,51,0.6);
    }

    .container { max-width:1300px; margin:0 auto; padding:0 20px; }

    section { padding:8rem 0; }
    h2 { font-family:'Orbitron',sans-serif; font-size:3.5rem; text-align:center; margin-bottom:3rem; color:var(--red); text-shadow:0 0 20px var(--red); }

    .features-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(320px,1fr)); gap:2.5rem; }
    .fcard {
      background:rgba(255,255,255,0.07);
      backdrop-filter:blur(15px);
      border:2px solid rgba(255,0,51,0.3);
      padding:3rem 2rem;
      border-radius:25px;
      text-align:center;
      transition:0.5s;
    }
    .fcard:hover { transform:translateY(-25px) scale(1.05); border-color:var(--red); box-shadow:0 0 0 60px rgba(255,0,51,0.5); }
    .fcard i { font-size:4.5rem; color:var(--red); margin-bottom:1.5rem; }

    .testi { background:linear-gradient(135deg,#111,#222); padding:6rem 0; }
    .testi-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(350px,1fr)); gap:3rem; }
    .testimonial {
      background:rgba(255,255,255,0.05);
      padding:2.5rem;
      border-radius:20px;
      border-left:6px solid var(--red);
      font-style:italic;
    }

    .join {
      background:linear-gradient(135deg,var(--red),var(--red-dark));
      border-radius:40px;
      padding:6rem 3rem;
      text-align:center;
      margin:6rem auto;
      max-width:900px;
      box-shadow:0 30px 80px rgba(255,0,51,0.6);
    }
    .join h2 { color:white; font-size:4rem; }
    .join input { width:100%; padding:20px; margin:15px 0; border:none; border-radius:15px; font-size:1.2rem; }
    .join button {
      width:100%; padding:22px; background:white; color:var(--red); border:none;
      font-size:1.8rem; font-weight:900; border-radius:50px; cursor:pointer;
      box-shadow:0 15px 40px rgba(0,0,0,0.4);
      transition:0.4s;
    }
    .join button:hover { transform:scale(1.08); box-shadow:0 20px 60px rgba(0,0,0,0.6); }

    .social-big {
      display:flex; gap:3rem; justify-content:center; margin:6rem 0; flex-wrap:wrap;
    }
    .soc-btn {
      background:white; color:var(--red); padding:25px 70px; border-radius:60px;
      font-size:1.8rem; font-weight:900; text-decoration:none; display:flex;
      align-items:center; gap:20px; box-shadow:0 20px 50px rgba(0,0,0,0.5);
      transition:0.5s;
    }
    .soc-btn:hover { transform:translateY(-15px) scale(1.1); }

    .back-top {
      position:fixed; bottom:40px; right:40px; background:var(--red); color:white;
      width:70px; height:70px; border-radius:50%; display:grid; place-items:center;
      font-size:2.5rem; cursor:pointer; box-shadow:0 10px 30px rgba(255,0,51,0.7);
      opacity:0; transition:0.5s; z-index:999;
    }
    .back-top.show { opacity:1; }

    footer { background:#000; text-align:center; padding:4rem; font-size:1.3rem; }
  </style>
</head>
<body>

  <div id="particles-js"></div>

  <!-- HERO -->
  <header>
    <div class="hero">
      <h1>GROK</h1>
      <p class="typing" id="typing"></p>
      <div class="countdown">PROMO SPESIAL MERDEKA<br><span id="timer" style="font-size:4rem;">88:88:88</span></div>
      <a href="#join" style="font-size:2rem; background:white; color:var(--red); padding:20px 80px; border-radius:60px; text-decoration:none; font-weight:900;">JOIN SEKARANG GRATIS</a>
    </div>
  </header>

  <!-- FITUR -->
  <section class="container">
    <h2>Kenapa Harus GROK?</h2>
    <div class="features-grid">
      <div class="fcard"><i class="fas fa-fire"></i><h3>Signal VIP 90%++</h3><p>Entry & exit presisi, win rate tertinggi se-Indonesia</p></div>
      <div class="fcard"><i class="fas fa-graduation-cap"></i><h3>Belajar dari Nol</h3><p>Kelas live, ebook, mentoring 1-on-1 bareng whale</p></div>
      <div class="fcard"><i class="fas fa-users"></i><h3>30.000+ Member</h3><p>Grup paling rame 24/7, dari newbie sampai pro</p></div>
      <div class="fcard"><i class="fas fa-trophy"></i><h3>Airdrop Hunter</h3><p>Dapat notif airdrop legit duluan, farming bareng</p></div>
      <div class="fcard"><i class="fas fa-shield-alt"></i><h3>Anti Rugi</h3><p>Risk management ketat, portofolio management gratis</p></div>
      <div class="fcard"><i class="fas fa-rocket"></i><h3>Copy Trade</h3><p>Ikut trade master trader, profit bareng</p></div>
    </div>
  </section>

  <!-- TESTIMONI -->
  <section class="testi">
    <div class="container">
      <h2>Apa Kata Member GROK</h2>
      <div class="testi-grid">
        <div class="testimonial">“Dari 5 juta jadi 127 juta dalam 4 bulan berkat signal GROK!” – Dika, Jakarta</div>
        <div class="testimonial">“Mentornya sabar banget, dari nggak ngerti apa-apa jadi bisa trading sendiri” – Salsa, Bandung</div>
        <div class="testimonial">“Airdrop yg direkomendasiin GROK selalu 10-50x, gila!” – Reza, Surabaya</div>
      </div>
    </div>
  </section>

  <!-- JOIN FORM BESAR -->
  <div class="container">
    <div class="join" id="join">
      <h2>GABUNG GROK SEKARANG</h2>
      <p style="font-size:2rem; margin:2rem 0;">Trial VIP GRATIS 14 HARI + Bonus Ebook + Signal Lifetime</p>
      <form id="joinForm">
        <input type="text" placeholder="Nama Lengkap" required>
        <input type="email" placeholder="Email Aktif" required>
        <input type="text" placeholder="Nomor WhatsApp (08xx)" required>
        <button type="submit">KLAIM AKSES GRATIS SEKARANG</button>
      </form>
      <div id="success" style="display:none; margin-top:20px; font-size:2rem; color:#00ff00;">
        Berhasil! Cek WhatsApp kamu dalam 1 menit
      </div>
    </div>
  </div>

  <!-- SOSIAL BESAR -->
  <div class="container social-big">
    <a href="https://t.me/grokcommunity" class="soc-btn">
      <i class="fab fa-telegram fa-3x"></i> TELEGRAM GROK
    </a>
    <a href="https://discord.gg/grok" class="soc-btn">
      <i class="fab fa-discord fa-3x"></i> DISCORD GROK
    </a>
  </div>

  <div class="back-top" id="backTop"><i class="fas fa-rocket"></i></div>

  <!-- PARTICLES + JAVASCRIPT GILA -->
  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      particles: { number: { value: 120 }, color: { value: ["#ffffff", "#ff0033"] }, size: { value: 5 }, move: { speed: 6 }, line_linked: { enable: true, color: "#ff0033", opacity: 0.3 } },
      interactivity: { events: { onhover: { enable: true, mode: "repulse" } } }
    });

    // Typing
    const teks = ["Komunitas Crypto Merah Putih", "Signal Paling Akurat 2025", "Dari Nol Jadi Whale", "GROK = Profit Konsisten"];
    let idx=0, char=0, current="";
    function ketik(){
      if(char < teks[idx].length){
        current += teks[idx].charAt(char);
        document.getElementById("typing").innerHTML = current + "│";
        char++;
        setTimeout(ketik, 100);
      } else {
        setTimeout(()=>{ char=0; current=""; idx=(idx+1)%teks.length; document.getElementById("typing").innerHTML=""; ketik(); }, 2500);
      }
    }
    ketik();

    // Countdown 88 jam 88 menit (biar dramatis)
    let waktu = 88*3600 + 88*60 + 88;
    setInterval(()=>{
      if(waktu<=0) waktu = 88*3600 + 88*60 + 88;
      let h = String(Math.floor(waktu/3600)).padStart(2,'0');
      let m = String(Math.floor((waktu%3600)/60)).padStart(2,'0');
      let s = String(waktu%60).padStart(2,'0');
      document.getElementById("timer").textContent = `${h}:${m}:${s}`;
      waktu--;
    },1000);

    // Form
    document.getElementById("joinForm").onsubmit = function(e){
      e.preventDefault();
      document.getElementById("success").style.display="block";
      this.reset();
      setTimeout(()=>document.getElementById("success").style.display="none",6000);
    };

    // Back to top
    window.onscroll = ()=> document.getElementById("backTop").classList.toggle("show", window.scrollY > 800);
    document.getElementById("backTop").onclick = ()=> window.scrollTo({top:0, behavior:'smooth'});
  </script>

</body>
</html>
