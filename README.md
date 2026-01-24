<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GreenSwap – Nachhaltig teilen</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #ffffff;
    color: #2c2c2c;
}

/* NAVIGATION */
nav {
    background: #2f6f2e;
    padding: 12px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav img {
    height: 70px;
}

nav a {
    color: white;
    margin-left: 30px;
    text-decoration: none;
    font-weight: 500;
    font-size: 16px;
}

/* HERO */
.hero {
    padding: 80px 20px 70px;
    text-align: center;
    background: #2f6f2e;
    color: white;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 20px;
    margin: 6px 0;
    opacity: 0.95;
}

/* SECTIONS */
section {
    max-width: 1100px;
    margin: 80px auto;
    padding: 0 25px;
}

.section-title {
    margin-bottom: 25px;
}

.section-title h2 {
    margin: 0;
    font-size: 30px;
    color: #2f6f2e;
}

p {
    font-size: 18px;
    max-width: 900px;
}

/* CARDS */
.cards {
    display: flex;
    gap: 25px;
    flex-wrap: wrap;
    margin-top: 40px;
}

.card {
    flex: 1;
    min-width: 260px;
    background: #f4fdf0;
    padding: 30px;
    border-radius: 16px;
}

/* HIGHLIGHT BOX */
.highlight {
    background: #f4fdf0;
    padding: 35px;
    border-radius: 18px;
    margin-top: 40px;
    font-size: 18px;
}

/* VIDEO */
.video-wrapper {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    margin-top: 30px;
    border-radius: 16px;
}

.video-wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

/* BUTTON */
.cta {
    text-align: center;
    margin-top: 40px;
}

.cta a {
    background: #2f6f2e;
    color: white;
    padding: 18px 40px;
    border-radius: 50px;
    text-decoration: none;
    font-size: 20px;
    font-weight: bold;
}

/* FOOTER */
footer {
    margin-top: 100px;
    padding: 30px;
    background: #2f6f2e;
    color: white;
    text-align: center;
}
</style>
</head>

<body>

<nav>
    <img src="Logo.png" alt="GreenSwap Logo">
    <div>
        <a href="#idee">Idee</a>
        <a href="#video">Pitch</a>
        <a href="#termin">Termin</a>
    </div>
</nav>

<section class="hero">
    <h1>GreenSwap</h1>
    <p>Tauschen statt Wegwerfen</p>
    <p>Nachhaltig · Lokal · Kostenlos</p>
</section>

<section id="idee">
    <div class="section-title">
        <h2>Warum braucht es GreenSwap?</h2>
    </div>

    <p>
        Jedes Semester werden unzählige funktionierende Gegenstände entsorgt,
        obwohl sie noch genutzt werden könnten. Gerade Studierende besitzen vieles
        nur temporär – und zahlen am Ende doppelt: mit Geld und Umweltkosten.
    </p>

    <div class="highlight">
        <strong>GreenSwap setzt genau hier an:</strong><br>
        Wir verbinden Studierende lokal miteinander, damit Dinge weiterverwendet
        statt weggeworfen werden.
    </div>
</section>

<section>
    <div class="section-title">
        <h2>Was macht GreenSwap besonders?</h2>
    </div>

    <div class="cards">
        <div class="card">
            🌱 <strong>Nachhaltig & sinnvoll</strong><br>
            Gegenstände werden weitergegeben statt weggeworfen – das spart Ressourcen und Müll.
        </div>

        <div class="card">
            🎓 <strong>Speziell für Studierende</strong><br>
            Viele Dinge werden nur für kurze Zeit gebraucht – GreenSwap erleichtert den Austausch.
        </div>

        <div class="card">
            🤝 <strong>Einfach & lokal</strong><br>
            Tauschen innerhalb der eigenen Stadt oder Hochschule – ohne Versand oder Kosten.
        </div>
    </div>
</section>

<section>
    <div class="section-title">
        <h2>So funktioniert GreenSwap</h2>
    </div>

    <div class="cards">
        <div class="card">📦 <strong>1. Einstellen</strong><br>Studierende stellen Gegenstände ein, die sie nicht mehr benötigen (z. B. Möbel, Küchengeräte oder Lernmaterialien).</div>
        <div class="card">🔍 <strong>2. Finden</strong><br>Andere Studierende aus der Nähe sehen die Angebote und finden genau das, was sie gerade brauchen.</div>
        <div class="card">🤝 <strong>3. Abholen</strong><br>Die Übergabe erfolgt direkt und lokal – kostenlos, unkompliziert und nachhaltig.</div>
    </div>
</section>

<section id="video">
    <div class="section-title">
        <h2>Video</h2>
    </div>

    <p>In unserem Video erklären wir die Idee, das Problem und warum GreenSwap ein nachhaltiger Lösungsansatz ist</p>

    <div class="video-wrapper">
        <iframe src="https://www.youtube.com/embed/PDAm-zsWw5Q"
        title="GreenSwap Pitch Video"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
    </div>
</section>

<section id="termin">
    <div class="section-title">
        <h2>Interesse geweckt?</h2>
    </div>

    <p>Wir freuen uns über Feedback, Fragen oder Austausch zur Idee.
       Buchen Sie gerne einen Termin mit uns.
    </p>

    <div class="cta">
        <a href="https://calendly.com/khetibyasmin7/neues-meeting?month=2026-01" target="_blank">
            Termin buchen
        </a>
    </div>
</section>

<footer>
    © 2025 GreenSwap
</footer>

</body>
</html>
