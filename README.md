<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Force Athlétique - Réservations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #222;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #d91e18;
        }
        button {
            background-color: #d91e18;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #a41412;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Force Athlétique - Réservez votre place</h1>
        <p>Participez à l'événement du 12 avril 2025 avec Nicolas Peyraud !</p>
    </header>

    <section>
        <h2>Programme de l'événement</h2>
        <p><strong>Lieu :</strong> 6 Bd des Monts d'Or, 69580 Sathonay-Camp</p>
        <ul>
            <li><strong>Matinée théorique :</strong> 9h à 12h</li>
            <li><strong>Pesée des athlètes :</strong> 12h30</li>
            <li><strong>Compétition :</strong> 14h30 à 18h30</li>
        </ul>
    </section>

    <section>
        <h2>Formulaire d'inscription</h2>
        <form action="https://example.com/reservation" method="POST">
            <div class="form-group">
                <label for="name">Nom et Prénom :</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email :</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="category">Catégorie :</label>
                <select id="category" name="category" required>
                    <option value="bpjeps">BPJEPS</option>
                    <option value="adherent">Adhérent SUMMUM</option>
                    <option value="externe">Externe</option>
                </select>
            </div>
            <button type="submit">Réserver</button>
        </form>
    </section>

    <footer>
        <p>Contactez-nous : cayre.coaching@gmail.com | 07 69 39 59 02</p>
    </footer>
</body>
</html>
