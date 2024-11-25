<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to West.-FlowAsk</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('kitchen-background.jpg');
            background-size: cover;
            color: #fff;
        }
        header {
            text-align: center;
            padding: 50px 20px;
            background: rgba(0, 0, 0, 0.6);
        }
        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.5em;
        }
        nav {
            margin-top: 20px;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 15px;
            font-size: 1.2em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            text-align: center;
            margin: 50px auto;
            max-width: 800px;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: rgba(0, 0, 0, 0.8);
            position: fixed;
            bottom: 0;
            width: 100%;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to West.-FlowAsk</h1>
        <p>Food For Your Happiness</p>
        <nav>
            <a href="menu.html">Menyer og priser</a>
            <a href="order.html">Bestill</a>
            <a href="location.html">Lokalisering</a>
            <a href="deals.html">Dagens tilbud</a>
            <a href="about.html">Om oss</a>
            <a href="staff.html">Ansatte</a>
            <a href="admin.html">Admin</a>
            <a href="feedback.html">Feedback</a>
        </nav>
    </header>
    <section>
        <h2>Velkommen til vår restaurant</h2>
        <p>Hos West.-FlowAsk serverer vi mat av høy kvalitet med de beste ingrediensene. Vi er lidenskapelige om god smak og fornøyde kunder.</p>
        <p>Utforsk menyen vår, finn ut mer om oss, og bestill ditt neste måltid i dag!</p>
    </section>
    <footer>
        <p>West.-FlowAsk &copy; 2024 | Mat for ditt velvære</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Om oss</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('about-background.jpg');
            background-size: cover;
            color: #fff;
        }
        header {
            text-align: center;
            padding: 50px 20px;
            background: rgba(0, 0, 0, 0.6);
        }
        header h1 {
            font-size: 2.5em;
        }
        section {
            max-width: 800px;
            margin: 50px auto;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: rgba(0, 0, 0, 0.8);
            position: fixed;
            bottom: 0;
            width: 100%;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Om oss</h1>
    </header>
    <section>
        <h2>Vår historie</h2>
        <p>West.-FlowAsk startet som en liten restaurant med en stor drøm: å gi alle en smak av ren lykke gjennom maten vår.</p>
        <h2>Våre verdier</h2>
        <ul>
            <li><strong>Kvalitet:</strong> Kun de beste ingrediensene.</li>
            <li><strong>Service:</strong> Gjestene våre er vår prioritet.</li>
            <li><strong>Bærekraft:</strong> Vi støtter lokale bønder og miljøvennlige løsninger.</li>
        </ul>
    </section>
    <footer>
        <p>West.-FlowAsk &copy; 2024</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menyer og priser</title>
</head>
<body>
    <header>
        <h1>Menyer og priser</h1>
        <a href="index.html">Tilbake til start</a>
    </header>
    <section>
        <h2>Vår meny</h2>
        <ul>
            <li>Pasta Carbonara - 120kr</li>
            <li>Pizza Margherita - 150kr</li>
            <li>Sushi Combo - 200kr</li>
        </ul>
        <p>Du kan også laste opp bilder av retter her:</p>
        <form action="#" method="POST" enctype="multipart/form-data">
            <label for="upload">Last opp bilder:</label>
            <input type="file" id="upload" name="dish-image" accept="image/*">
            <button type="submit">Last opp</button>
        </form>
    </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bestill</title>
</head>
<body>
    <header>
        <h1>Bestill mat</h1>
        <a href="index.html">Tilbake til start</a>
    </header>
    <form action="#" method="POST">
        <label for="name">Navn:</label>
        <input type="text" id="name" name="name" required>
        <label for="order">Din bestilling:</label>
        <textarea id="order" name="order" required></textarea>
        <label for="date">Leveringsdato:</label>
        <input type="date" id="date" name="date" required>
        <button type="submit">Send bestilling</button>
    </form>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lokalisering</title>
</head>
<body>
    <header>
        <h1>Vår beliggenhet</h1>
        <a href="index.html">Tilbake til start</a>
    </header>
    <p>Adresse: Hovedgata 123, 1234 Oslo</p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d243647.25251412134!2d10.550844755110968!3d59.91386880747767!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46416e61dc09d4ab%3A0x6d19f17e0d0c7f51!2sOslo!5e0!3m2!1sen!2sno!4v1630315029394!5m2!1sen!2sno" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dagens tilbud</title>
</head>
<body>
    <header>
        <h1>Dagens tilbud</h1>
        <a href="index.html">Tilbake til start</a>
    </header>
    <p>Dagens spesialtilbud: 20% rabatt på alle pizzaretter!</p>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback</title>
</head>
<body>
    <header>
        <h1>Feedback</h1>
        <a href="index.html">Tilbake til start</a>
    </header>
    <form action="#" method="POST">
        <label for="name">Navn:</label>
        <input type="text" id="name" name="name">
        <label for="feedback">Din tilbakemelding:</label>
        <textarea id="feedback" name="feedback"></textarea>
        <button type="submit">Send</button>
    </form>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ansatte</title>
</head>
<body>
    <header>
        <h1>Våre ansatte</h1>
        <a href="index.html">Tilbake til start</a>
    </header>
    <section>
        <h2>Teamet vårt</h2>
        <ul>
            <li>Maria Hansen - Kokk</li>
            <li>Jonas Pettersen - Servitør</li>
            <li>Anne Lunde - Daglig leder</li>
        </ul>
    </section>
</body>
</html>
