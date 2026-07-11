<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Daniel's Fishing Sinkers</title>
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, sans-serif;
    }
    body {
        background: #f4f7fa;
        color: #333;
    }
    header {
        background: linear-gradient(135deg, #0a4d68, #088395);
        color: white;
        text-align: center;
        padding: 70px 20px;
    }
    header h1 {
        font-size: 3rem;
        margin-bottom: 10px;
    }
    header p {
        font-size: 1.2rem;
    }
    section {
        max-width: 1000px;
        margin: auto;
        padding: 60px 20px;
    }
    .cards {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
        margin-top: 30px;
    }
    .card {
        background: white;
        padding: 25px;
        border-radius: 15px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        text-align: center;
    }
    .contact {
        background: white;
        border-radius: 15px;
        padding: 30px;
        box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    footer {
        background: #0a4d68;
        color: white;
        text-align: center;
        padding: 20px;
    }
</style>
</head>
<body>
<header>
    <h1>Daniel's Fishing Sinkers</h1>
    <p>Your Local Fishing Tackle & Bait Shop in Brooklyn</p>
</header>
<section>
    <h2>What We Offer</h2>
    <div class="cards">
        <div class="card">
            <h3>Fishing Tackle</h3>
            <p>Sinkers, hooks, lines, and other fishing essentials.</p>
        </div>
        <div class="card">
            <h3>Live Bait</h3>
            <p>Worms and bait to help you catch more fish.</p>
        </div>
        <div class="card">
            <h3>Friendly Service</h3>
            <p>Helpful staff and reasonable prices for every angler.</p>
        </div>
    </div>
</section>
<section>
    <div class="contact">
        <h2>Visit Us</h2>
        <br>
        <p><strong>Address:</strong> 240 47th St, Brooklyn, NY 11220</p>
        <p><strong>Phone:</strong> (718) 795-0051</p>
        <p><strong>Hours:</strong> Open Daily • Closes at 10:00 PM</p>
    </div>
</section>
<footer>
    © 2026 Daniel's Fishing Sinkers. All Rights Reserved.
</footer>
</body>
</html>
