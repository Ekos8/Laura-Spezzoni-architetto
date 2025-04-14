<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Studio di Architettura</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: #ffffff;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: 600;
        }
        .hero {
            padding: 100px 20px;
            text-align: center;
            background-color: #f5f5f5;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 24px;
            color: #666;
        }
        section {
            padding: 60px 20px;
            max-width: 1200px;
            margin: auto;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project {
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            background-color: white;
            transition: box-shadow 0.3s ease;
        }
        .project:hover {
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .project img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .project p {
            padding: 15px;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        input, textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Studio di Architettura</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#progetti">Progetti</a>
        <a href="#contatti">Contatti</a>
    </nav>
</header>

<section class="hero" id="home">
    <h1>Semplicità che accoglie, dettaglio che distingue.</h1>
    <p>Progettiamo spazi che raccontano storie di armonia e precisione.</p>
</section>

<section id="progetti">
    <h2>I Nostri Progetti</h2>
    <div class="projects">
        <div class="project">
            <img src="https://via.placeholder.com/300x200" alt="Progetto 1">
            <p>Residenza privata - minimalismo e funzionalità.</p>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/300x200" alt="Progetto 2">
            <p>Studio professionale - linee pulite e dettagli naturali.</p>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/300x200" alt="Progetto 3">
            <p>Villa immersa nel verde - semplicità dei volumi e luce.</p>
        </div>
    </div>
</section>

<section id="contatti">
    <h2>Contattaci</h2>
    <form>
        <input type="text" placeholder="Nome" required>
        <input type="email" placeholder="Email" required>
        <textarea placeholder="Messaggio" rows="5" required></textarea>
        <button type="submit">Invia</button>
    </form>
</section>

<footer>
    &copy; 2025 Studio di Architettura - Tutti i diritti riservati
</footer>

</body>
</html>
