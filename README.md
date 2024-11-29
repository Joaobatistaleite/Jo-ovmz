<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Interativa de Estudos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Biblioteca Interativa de Estudos</h1>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#subjects">Assuntos</a></li>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Bem-vindo à Biblioteca Interativa de Estudos</h2>
            <p>Aqui você encontrará recursos educativos para melhorar seus estudos em várias disciplinas.</p>
        </section>
        <section id="subjects">
            <h2>Assuntos</h2>
            <div class="subject-grid">
                <div class="subject-item">
                    <h3>Matemática</h3>
                    <p>Recursos e exercícios de matemática.</p>
                </div>
                <div class="subject-item">
                    <h3>Ciências</h3>
                    <p>Informações e experimentos científicos.</p>
                </div>
                <div class="subject-item">
                    <h3>História</h3>
                    <p>Artigos e cronologias históricas.</p>
                </div>
                <div class="subject-item">
                    <h3>Literatura</h3>
                    <p>Textos literários e análises.</p>
                </div>
            </div>
        </section>
        <section id="about">
            <h2>Sobre</h2>
            <p>Saiba mais sobre a nossa missão e como podemos ajudar nos seus estudos.</p>
        </section>
        <section id="contact">
            <h2>Contato</h2>
            <p>Entre em contato conosco para mais informações e suporte.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Biblioteca Interativa de Estudos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #0073e6;
    color: white;
    padding: 15px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline-block;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

main section {
    margin-bottom: 20px;
}

.subject-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
}

.subject-item {
    background-color: white;
    padding: 15px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #0073e6;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: relative;
    width: 100%;
}

@media (min-width: 600px) {
    .subject-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (min-width: 900px) {
    nav ul li {
        margin: 0 15px;
    }

    main {
        padding: 40px;
    }

    .subject-grid {
        grid-template-columns: repeat(3, 1fr);
    }
}
