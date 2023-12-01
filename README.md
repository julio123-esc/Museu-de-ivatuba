OCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Seu Site</title>
</head>
<body>
    <header>
        <h1>Seu Nome</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main
        <section id="sobre">
            <h2>Sobre Mim</h2>
            <p>Coloque aqui informações sobre você.</p>
        </section>

        <section id="portfolio">
            <h2>Meu Portfolio</h2>
            <div class="portfolio-item">
                <img src="imagem1.jpg" alt="Projeto 1">
                <p>Descrição do Projeto 1</p>
            </div>
            <div class="portfolio-item">
                <img src="imagem2.jpg" alt="Projeto 2">
                <p>Descrição do Projeto 2</p>
            </div>
            <!-- Adicione mais itens conforme necessário -->
        </section>

        <section id="contato">
            <h2>Entre em Contato</h2>
            <form action="processar_formulario.php" method="post">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Seu Nome</p>
    </footer>
</body>
</html>
