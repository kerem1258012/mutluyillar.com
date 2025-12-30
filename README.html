<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>New Year Online</title>

<!-- =======================
     RESET & BASE STYLES
======================== -->
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    width: 100%;
    height: 100%;
    background: #000;
    color: #fff;
    font-family: 'Segoe UI', Arial, sans-serif;
    overflow-x: hidden;
}

body {
    cursor: none;
}

/* =======================
     CUSTOM CURSOR
======================== */
.cursor {
    position: fixed;
    width: 10px;
    height: 10px;
    background: white;
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transition: transform 0.1s ease;
}

.cursor-ring {
    position: fixed;
    width: 30px;
    height: 30px;
    border: 1px solid rgba(255,255,255,0.4);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9998;
    transition: all 0.15s ease;
}

/* =======================
     LOADING SCREEN
======================== */
#loader {
    position: fixed;
    inset: 0;
    background: #000;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    z-index: 10000;
}

.loader-bar {
    width: 300px;
    height: 6px;
    background: #111;
    overflow: hidden;
    margin-top: 20px;
}

.loader-fill {
    width: 0%;
    height: 100%;
    background: linear-gradient(90deg, #fff, #aaa);
    animation: load 4s linear forwards;
}

@keyframes load {
    to { width: 100%; }
}

/* =======================
     MAIN SECTIONS
======================== */
section {
    min-height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}

/* =======================
     HERO
======================== */
#hero {
    flex-direction: column;
    text-align: center;
}

#hero h1 {
    font-size: 5rem;
    letter-spacing: 8px;
    opacity: 0;
    animation: fadeIn 2s ease forwards;
    animation-delay: 4.2s;
}

#hero p {
    margin-top: 20px;
    font-size: 1.2rem;
    opacity: 0;
    animation: fadeIn 2s ease forwards;
    animation-delay: 5s;
}

@keyframes fadeIn {
    to {
        opacity: 1;
    }
}

/* =======================
     COUNTDOWN
======================== */
#countdown {
    display: flex;
    gap: 40px;
    margin-top: 60px;
}

.time-box {
    text-align: center;
}

.time-box span {
    display: block;
    font-size: 3rem;
}

.time-box label {
    font-size: 0.8rem;
    opacity: 0.6;
}

/* =======================
     STARS BACKGROUND
======================== */
.star {
    position: absolute;
    width: 2px;
    height: 2px;
    background: white;
    opacity: 0.5;
    animation: twinkle infinite alternate;
}

@keyframes twinkle {
    from { opacity: 0.2; }
    to { opacity: 1; }
}

/* =======================
     SCROLL SECTION
======================== */
#scroll {
    flex-direction: column;
}

.scroll-line {
    width: 2px;
    height: 150px;
    background: white;
    opacity: 0.4;
    margin-top: 20px;
    animation: scrollPulse 2s infinite;
}

@keyframes scrollPulse {
    0% { opacity: 0.2; }
    50% { opacity: 1; }
    100% { opacity: 0.2; }
}

/* =======================
     FOOTER
======================== */
footer {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #000;
}

footer h2 {
    font-size: 3rem;
    letter-spacing: 6px;
    opacity: 0.7;
}
</style>
</head>

<body>

<!-- CURSOR -->
<div class="cursor"></div>
<div class="cursor-ring"></div>

<!-- LOADER -->
<div id="loader">
    <div>INITIALIZING 2025</div>
    <div class="loader-bar">
        <div class="loader-fill"></div>
    </div>
</div>

<!-- HERO -->
<section id="hero">
    <h1>2025</h1>
    <p>System Online</p>

    <div id="countdown">
        <div class="time-box">
            <span id="days">00</span>
            <label>DAYS</label>
        </div>
        <div class="time-box">
            <span id="hours">00</span>
            <label>HOURS</label>
        </div>
        <div class="time-box">
            <span id="minutes">00</span>
            <label>MINUTES</label>
        </div>
        <div class="time-box">
            <span id="seconds">00</span>
            <label>SECONDS</label>
        </div>
    </div>
</section>

<!-- SCROLL -->
<section id="scroll">
    <div>SCROLL</div>
    <div class="scroll-line"></div>
</section>

<!-- FOOTER -->
<footer>
    <h2>CONTINUE</h2>
</footer>

<!-- =======================
     JAVASCRIPT
======================== -->
<script>
/* CURSOR */
const cursor = document.querySelector('.cursor');
const ring = document.querySelector('.cursor-ring');

document.addEventListener('mousemove', e => {
    cursor.style.left = e.clientX + 'px';
    cursor.style.top = e.clientY + 'px';

    ring.style.left = e.clientX - 15 + 'px';
    ring.style.top = e.clientY - 15 + 'px';
});

/* LOADER */
window.addEventListener('load', () => {
    setTimeout(() => {
        document.getElementById('loader').style.display = 'none';
    }, 4200);
});

/* STARS */
for (let i = 0; i < 200; i++) {
    const star = document.createElement('div');
    star.className = 'star';
    star.style.left = Math.random() * 100 + 'vw';
    star.style.top = Math.random() * 100 + 'vh';
    star.style.animationDuration = (Math.random() * 3 + 2) + 's';
    document.body.appendChild(star);
}

/* COUNTDOWN */
function updateCountdown() {
    const now = new Date();
    const target = new Date(now.getFullYear() + 1, 0, 1);
    const diff = target - now;

    const d = Math.floor(diff / (1000 * 60 * 60 * 24));
    const h = Math.floor((diff / (1000 * 60 * 60)) % 24);
    const m = Math.floor((diff / (1000 * 60)) % 60);
    const s = Math.floor((diff / 1000) % 60);

    document.getElementById('days').textContent = String(d).padStart(2, '0');
    document.getElementById('hours').textContent = String(h).padStart(2, '0');
    document.getElementById('minutes').textContent = String(m).padStart(2, '0');
    document.getElementById('seconds').textContent = String(s).padStart(2, '0');
}

setInterval(updateCountdown, 1000);
updateCountdown();
</script>

</body>
</html>
