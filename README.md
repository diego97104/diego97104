<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog di Notizie di Calcio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #ff4500;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .post {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .post img {
            max-width: 100%;
            border-radius: 8px;
        }
        .post h2 {
            color: #ff4500;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Blog di Notizie di Calcio</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Notizie</a>
        <a href="#">Campionati</a>
        <a href="#">Contatti</a>
    </nav>
    <div class="container">
        <div class="post">
            <h2>Titolo della Notizia di Calcio</h2>
            <img src="immagine_calcio.jpg" alt="Immagine di calcio">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam auctor, nulla a aliquet consequat, turpis tortor consequat purus, vel volutpat sapien est sit amet magna. Curabitur consectetur, nisl vel porta ullamcorper, metus purus vestibulum ligula, sit amet aliquet odio erat non tortor.</p>
        </div>
        <div class="post">
            <h2>Un'altra Notizia di Calcio</h2>
            <img src="immagine_calcio_2.jpg" alt="Immagine di calcio">
            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Blog di Notizie di Calcio. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
