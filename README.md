
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Deepak & Dolly | Wedding Invitation</title>
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Cormorant+Garamond:wght@400;600&family=Poppins:wght@400;500&display=swap" rel="stylesheet">
<style>
:root {
  --wine: #4b101e;
  --gold: #d5b16c;
  --cream: #fff8ec;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  margin: 0;
  font-family: Poppins, sans-serif;
  text-align: center;
  color: var(--wine);
  background: var(--cream);
}
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 45px 20px;
  color: var(--cream);
  background: radial-gradient(circle, #792d3b, var(--wine) 75%);
  border: 12px double var(--gold);
  outline: 1px solid var(--gold);
  outline-offset: -22px;
}
.om { color: var(--gold); font-size: 27px; }
.small {
  letter-spacing: 4px;
  text-transform: uppercase;
  font-size: 12px;
}
h1 {
  font: 400 clamp(50px, 12vw, 90px) "Great Vibes", cursive;
  color: var(--gold);
  margin: 25px 0;
}
h2 {
  font: 600 38px "Cormorant Garamond", serif;
}
.hero h2 { font-size: 25px; color: var(--cream); }
.heart { color: var(--gold); font-size: 28px; }
.button {
  display: inline-block;
  margin: 12px 5px;
  padding: 13px 22px;
  background: var(--gold);
  color: var(--wine);
  text-decoration: none;
  border-radius: 4px;
  font-size: 13px;
  font-weight: 500;
}
.button:hover { opacity: .85; }
section { padding: 65px 20px; }
.intro { max-width: 650px; margin: auto; line-height: 1.9; }
.gold { color: #a7792c; }
.countdown {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
  margin: 25px 0;
}
.time {
  background: white;
  border: 1px solid var(--gold);
  padding: 15px 12px;
  min-width: 75px;
}
.time strong {
  display: block;
  font: 600 30px "Cormorant Garamond", serif;
}
.time span { font-size: 10px; text-transform: uppercase; }
.events {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
  max-width: 950px;
  margin: 25px auto;
}
.card {
  padding: 25px 18px;
  background: white;
  border: 1px solid var(--gold);
  border-radius: 5px;
  box-shadow: 0 6px 20px #4b101e10;
}
.card h3 { font: 600 26px "Cormorant Garamond", serif; }
.venue { background: var(--wine); color: var(--cream); }
.venue h2 { color: var(--gold); }
footer {
  background: #2c0811;
  color: var(--gold);
  padding: 30px 15px;
}
.fade {
  animation: fadeIn 1.4s ease both;
}
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(18px); }
  to { opacity: 1; transform: translateY(0); }
}
.petal {
  position: fixed;
  top: -20px;
  z-index: 5;
  color: var(--gold);
  pointer-events: none;
  animation: fall 8s linear forwards;
}
@keyframes fall {
  to { transform: translateY(105vh) rotate(360deg); opacity: 0; }
}
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation: none !important;
    scroll-behavior: auto !important;
  }
}
</style>
</head>
<body>

<header class="hero">
  <div class="fade">
    <div class="om">॥ श्री गणेशाय नमः ॥</div>
    <p class="small">Together with our families</p>
    <p>We joyfully invite you to celebrate the wedding of</p>
    <h1>Deepak <span class="heart">&</span> Dolly</h1>
    <div class="heart">❦ ✦ ❦</div>
    <h2>24 November 2026</h2>
    <p>Two hearts, one beautiful journey.</p>
    <a class="button" href="#invitation">Open Invitation ♡</a>
  </div>
</header>

<main>
<section id="invitation">
  <p class="small gold">A celebration of love</p>
  <h2>Our Forever Begins</h2>
  <div class="intro">
    With hearts full of happiness, we invite you to join us
    as we begin this beautiful new chapter of our lives.
    Your presence and blessings will make our day unforgettable.
  </div>
  <div class="heart">❦</div>
</section>

<section style="background:#f2e4ce">
  <p class="small gold">Save the date</p>
  <h2>Countdown to Forever</h2>
  <div class="countdown">
    <div class="time"><strong id="days">0</strong><span>Days</span></div>
    <div class="time"><strong id="hours">0</strong><span>Hours</span></div>
    <div class="time"><strong id="minutes">0</strong><span>Minutes</span></div>
    <div class="time"><strong id="seconds">0</strong><span>Seconds</span></div>
  </div>
  <p id="countdownMessage">Until the wedding day ❤️</p>
</section>

<section>
  <p class="small gold">Join our celebration</p>
  <h2>Wedding Events</h2>
  <p>We look forward to celebrating with you.</p>
  <div class="events">
    <div class="card">
      <div class="heart">🌼</div>
      <h3>Haldi Ceremony</h3>
      <p>24 November 2026</p>
      <p>Time to be confirmed</p>
    </div>
    <div class="card">
      <div class="heart">🪷</div>
      <h3>Wedding Ceremony</h3>
      <p>24 November 2026</p>
      <p>Time to be confirmed</p>
    </div>
    <div class="card">
      <div class="heart">✨</div>
      <h3>Reception</h3>
      <p>24 November 2026</p>
      <p>Time to be confirmed</p>
    </div>
  </div>
  <p><i>Please replace the sample event details with confirmed timings.</i></p>
</section>

<section class="venue">
  <p class="small">We saved you a place</p>
  <h2>Wedding Venue</h2>
  <div class="heart">❦</div>
  <h3>Punjabi Bhag</h3>
  <p>Old Faridabad, Haryana, India</p>
  <p>Please confirm the exact venue address before sharing.</p>
  <a class="button"
     href="https://www.google.com/maps/search/?api=1&query=Punjabi+Bhag+Old+Faridabad+Haryana"
     target="_blank" rel="noopener">
     Get Directions ↗
  </a>
</section>

<section>
  <p class="small gold">Kindly reply</p>
  <h2>Will You Join Us?</h2>
  <p class="intro">
    Your presence is our greatest gift.
    Please confirm your attendance with us.
  </p>
  <!-- Replace 91XXXXXXXXXX with your WhatsApp number, including country code. -->
  <a class="button"
     href="https://wa.me/918630966203?text=Congratulations%20Deepak%20and%20Dolly!%20I%20will%20attend%20your%20wedding."
     target="_blank" rel="noopener">
     RSVP on WhatsApp
  </a>
</section>
</main>

<footer>
  <h2 style="color:#d5b16c">Deepak & Dolly</h2>
  <p>24 · 11 · 2026</p>
  <p>Made with love ♥</p>
</footer>

<script>
const weddingDate = new Date("2026-11-24T19:00:00+05:30");

function updateCountdown() {
  const diff = weddingDate.getTime() - Date.now();
  const ids = ["days", "hours", "minutes", "seconds"];
  const message = document.getElementById("countdownMessage");

  if (diff <= 0) {
    ids.forEach(id => document.getElementById(id).textContent = "0");
    message.textContent = "The celebration day is here! ❤️";
    return;
  }

  document.getElementById("days").textContent =
    Math.floor(diff / 86400000);
  document.getElementById("hours").textContent =
    Math.floor(diff / 3600000) % 24;
  document.getElementById("minutes").textContent =
    Math.floor(diff / 60000) % 60;
  document.getElementById("seconds").textContent =
    Math.floor(diff / 1000) % 60;
}
updateCountdown();
setInterval(updateCountdown, 1000);

// Decorative falling gold petals.
if (!window.matchMedia("(prefers-reduced-motion: reduce)").matches) {
  setInterval(() => {
    const petal = document.createElement("span");
    petal.className = "petal";
    petal.textContent = Math.random() > 0.5 ? "✦" : "❀";
    petal.style.left = Math.random() * 100 + "vw";
    petal.style.fontSize = (12 + Math.random() * 12) + "px";
    document.body.appendChild(petal);
    setTimeout(() => petal.remove(), 8000);
  }, 1200);
}
</script>

</body>
</html>
