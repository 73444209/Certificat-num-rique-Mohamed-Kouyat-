<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Certificat Numérique</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="logo-em-normandie.png" alt="EM Normandie" class="logo">
        <h1>Certificat Numérique</h1>
        <p class="subtitle">EM Normandie Business School</p>
    </header>
    <section class="certificate">
        <h2>Certificat d'Achèvement</h2>
        <p>Ce certificat atteste que</p>
        <p class="name">[Nom de l'Étudiant]</p>
        <p>a complété avec succès le programme</p>
        <p class="program">[Nom du Programme]</p>
        <p class="date">Le [Date]</p>
    </section>
    <footer>
        <p>EM Normandie - 1871</p>
    </footer>
</body>
</html> 
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #e60012;
    color: white;
    text-align: center;
    padding: 20px;
}

.logo {
    width: 100px;
}

.subtitle {
    font-size: 1.2rem;
    margin-top: 10px;
}

.certificate {
    background-color: white;
    border: 2px solid #e60012;
    padding: 20px;
    margin: 20px;
    text-align: center;
}

.name {
    font-size: 1.5rem;
    font-weight: bold;
}

.program {
    font-size: 1.2rem;
    margin-top: 10px;
}

.date {
    font-size: 1rem;
    margin-top: 10px;
}

footer {
    background-color: #e60012;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
