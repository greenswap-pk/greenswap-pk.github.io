<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GreenSwap – Prototyp</title>

<style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; }

    /* NAVIGATION */
    nav {
        background: #2e7d32;
        padding: 12px 20px;
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    nav img { height: 45px; }

    nav a {
        color: white;
        text-decoration: none;
        margin-left: 20px;
        font-weight: bold;
    }

    nav a:hover { text-decoration: underline; }

    /* HERO SECTION */
    .hero {
        background: #e8f5e9;
        padding: 60px 20px;
        text-align: center;
    }

    .hero h1 { margin: 0; font-size: 40px; color: #2e7d32; }
    .hero p { font-size: 18px; color: #444; }

    /* MAIN CONTAINER */
    .container {
        max-width: 1000px;
        margin: 30px auto;
        padding: 20px;
        background: white;
        border-radius: 10px;
        box-shadow: 0 0 10px #0001;
    }

    h2 { color: #2e7d32; }

    .placeholder {
        background: #eeeeee;
        border: 2px dashed #999;
        padding: 20px;
        text-align: center;
        border-radius: 8px;
        color: #666;
        margin-top: 15px;
    }

    .button-disabled {
        display: inline-block;
        padding: 10px 18px;
        background: #cccccc;
        color: white;
        border-radius: 6px;
        margin-top: 10px;
        text-decoration: none;
        pointer-events: none;
    }

    footer {
        text-align: center;
        padding: 20px;
        margin-top: 40px;
        color: #777;
    }
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>
    <div style="display:flex; align-items:center; gap:15px;">
        <img src="logo.png" alt="GreenSwap Logo">
        <strong>GreenSwap</strong>
    </div>

    <div>
        <a href="#">Startseite</a>
        <a href="#">Funktionen</a>
        <a href="#">Über uns</a>
        <a href="#">Kontakt</a>
    </div>
</nav>

<!-- HERO SECTION -->
<div class="hero">
    <h1>Willkommen bei GreenSwap</h1>
    <p>Die nachhaltige Tauschplattform für Studierende – bald verfügbar.</p>
</div>

<!-- ÜBER DIE IDEE -->
<div class="container">
    <h2>Unsere Idee</h2>
    <p>
        GreenSwap soll Studierenden ermöglichen, Gegenstände lokal zu tauschen,
        um Ressourcen zu sparen und nachhaltiger zu leben.  
        Diese Website ist ein Prototyp und wird aktuell Schritt für Schritt erweitert.
    </p>
</div>

<!-- FUNKTIONSÜBERSICHT -->
<div class="container">
    <h2>Geplante Funktionen</h2>

    <div class="placeholder">🌍 Lokale Tauschbörse (in Entwicklung)</div>
    <div class="placeholder">💬 Chat-Funktion (folgt)</div>
    <div class="placeholder">📍 Kartenübersicht (geplant)</div>
    <div class="placeholder">🎒 Kategorien (in Arbeit)</div>

    <p style="margin-top:15px;">Diese Funktionen werden im nächsten Sprint eingebaut.</p>
</div>

<!-- VIDEO -->
<div class="container">
    <h2>Pitch-Video</h2>
    <p>Unser Video wird aktuell produziert und bald hier sichtbar sein.</p>

    <div class="placeholder">
        ▶ Video-Bereich – folgt
    </div>
</div>

<!-- CALENDLY -->
<div class="container">
    <h2>Terminvereinbarung</h2>
    <p>
        Bald können Interessenten direkt einen Termin für Feedback oder Fragen
        über Calendly buchen.
    </p>

    <div class="placeholder">
        Calendly-Integration – folgt
    </div>

    <a class="button-disabled">Termin buchen (bald verfügbar)</a>
</div>

<!-- FOOTER -->
<footer>
    © 2025 GreenSwap – Prototyp von Hannah & Yasmin
</footer>

</body>
</html>
