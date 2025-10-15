<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FireHub - Roblox Scripts & Accounts Shop</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header/Navbar -->
    <header>
        <nav>
            <div class="logo">FireHub</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#scripts">Scripts</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#discord">Discord</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Willkommen bei FireHub</h1>
            <p>Dein Discord-Server für top Roblox-Scripts, Accounts und mehr. Tritt bei und level up dein Game!</p>
            <a href="#discord" class="cta-button">Tritt unserem Discord bei</a>
        </div>
    </section>

    <!-- Scripts Section -->
    <section id="scripts" class="section">
        <h2>Roblox Scripts</h2>
        <p>Unsere Community teilt kostenlose und premium Scripts für alle deine Lieblingsgames. Hier ein paar Highlights:</p>
        <div class="grid">
            <div class="card">
                <h3>NoClip Script</h3>
                <p>Gehe durch Wände – perfekt für Exploration!</p>
                <pre><code>-- Beispiel-Code
local player = game.Players.LocalPlayer
local character = player.Character
local humanoid = character:WaitForChild("Humanoid")
humanoid:ChangeState(Enum.HumanoidStateType.Physics)
-- Füge mehr Code hinzu...</code></pre>
                <a href="#" class="buy-btn">Download (Free)</a>
            </div>
            <div class="card">
                <h3>Auto-Farm Script</h3>
                <p>Automatisiere dein Farming in Tycoons.</p>
                <p>Beispiel: Infinite Robux-Generator (Testversion).</p>
                <a href="#" class="buy-btn">Kaufen für 50 Robux</a>
            </div>
            <div class="card">
                <h3>ESP Script</h3>
                <p>Sieh Spieler durch Wände – für PvP-Dominanz.</p>
                <p>Kompatibel mit Jailbreak & mehr.</p>
                <a href="#" class="buy-btn">Download (Premium)</a>
            </div>
        </div>
    </section>

    <!-- Shop Section -->
    <section id="shop" class="section">
        <h2>Shop - Roblox Accounts</h2>
        <p>Sichere, geprüfte Accounts mit Robux und Items. Alle Verkäufe über Discord!</p>
        <div class="grid">
            <div class="card">
                <h3>Starter Account</h3>
                <p>Neuer Account mit 1000 Robux.</p>
                <span class="price">€5</span>
                <a href="#discord" class="buy-btn">Kaufen</a>
            </div>
            <div class="card">
                <h3>Premium Account</h3>
                <p>Mit 5000 Robux + VIP-Items (z.B. Dominus).</p>
                <span class="price">€20</span>
                <a href="#discord" class="buy-btn">Kaufen</a>
            </div>
            <div class="card">
                <h3>God Account</h3>
                <p>Full-loaded: 10k Robux, alle Rares.</p>
                <span class="price">€50</span>
                <a href="#discord" class="buy-btn">Kaufen</a>
            </div>
        </div>
    </section>

    <!-- Discord Section -->
    <section id="discord" class="section">
        <h2>Tritt unserem Discord bei</h2>
        <p>Diskutiere Scripts, kaufe Accounts und chatte mit der Community. Über 1k Member!</p>
        <a href="https://discord.gg/YOUR_INVITE_HERE" class="cta-button discord-btn" target="_blank">Join Discord</a>
        <p>Server-Link: discord.gg/YOUR_INVITE_HERE (ersetze mit deinem echten Link!)</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 FireHub. Alle Rechte vorbehalten. | <a href="#">Impressum</a> | <a href="#">Datenschutz</a></p>
    </footer>
</body>
</html>
