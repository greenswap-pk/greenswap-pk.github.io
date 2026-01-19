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

/* NAV */
nav {
    background: #2f6f2e;
    padding: 16px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav span {
    color: white;
    font-size: 22px;
    font-weight: bold;
}

nav a {
    color: white;
    margin-left: 25px;
    text-decoration: none;
    font-weight: 500;
}

/* HERO */
.hero {
    padding: 90px 20px;
    text-align: center;
    background: linear-gradient(135deg, #6cc04a, #2f6f2e);
    color: white;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 20px;
    max-width: 700px;
    margin: auto;
}

/* SECTION */
section {
    max-width: 1100px;
    margin: 80px auto;
    padding: 0 25px;
}

.section-title {
    border-left: 6px solid #6cc04a;
    padding-left: 15px;
    margin-bottom: 25px;
}

.section-title h2 {
    margin: 0;
    font-size: 32px;
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
    border-top: 6px solid #6cc04a;
}

/* HIGHLIGHT */
.highlight {
    background: #f4fdf0;
    padding: 35px;
    border-radius: 18px;
    margin-top: 40px;
    font-size: 18px;
}

/* PLACEHOLDER */
.placeholder {
    background: #ffffff;
    border: 3px dashed #6cc04a;
    border-radius: 18px;
    padding: 60px;
    text-align: center;
    font-size: 18px;
    color: #2f6f2e;
    margin-top: 30px;
}

/* CTA */
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
    <span>GreenSwap</span>
    <div>
        <a href="#idee">Idee</a>
        <a href="#video">Pitch</a>
        <a href="#termin">Termin</a>
    </div>
</nav>

<section class="hero">
    <h1>GreenSwap</h1>
    <p>
        Tauschen statt Wegwerfen.<br>
        Nachhaltig. Lokal. Kostenlos.
    </p>
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
            🌱 <strong>Ökologischer Impact</strong><br>
            Weniger Müll, geringerer Ressourcenverbrauch.
        </div>
        <div class="card">
            🎓 <strong>Studierendenzentriert</strong><br>
            Für Wohnheime, WGs und Hochschulstandorte.
        </div>
        <div class="card">
            🤝 <strong>Community-Gedanke</strong><br>
            Teilen stärkt lokale Gemeinschaften.
        </div>
    </div>
</section>

<section id="video">
    <div class="section-title">
        <h2>MVP Pitch-Video</h2>
    </div>

    <p>
        In unserem Pitch-Video erklären wir die Idee, das Problem
        und warum GreenSwap ein nachhaltiger Lösungsansatz ist.
    </p>

    <div class="placeholder">
        🎬 Hier wird das selbstgedrehte Pitch-Video eingebettet
    </div>
</section>

<section id="termin">
    <div class="section-title">
        <h2>Interesse geweckt?</h2>
    </div>

    <p>
        Wir freuen uns über Feedback, Fragen oder Austausch zur Idee.
        Buchen Sie gerne einen Termin mit dem Projektteam.
    </p>

   <div style="margin-top: 30px;">
    <iframe 
        src="https://calendly.com/khetibyasmin7/neues-meeting?month=2026-01"
        width="100%" 
        height="700" 
        frameborder="0">
    </iframe>
</div>


    <div class="cta">
        <a href="#">Termin buchen</a>
    </div>
</section>

<footer>
    © 2025 GreenSwap – Hochschulprojekt von Hannah & Yasmin
</footer>

</body>
</html>



