# index1.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Exemplo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Meu Logo</div>
        <nav>
            <button onclick="scrollToSection('home')">Home</button>
            <button onclick="scrollToSection('about')">Sobre</button>
            <button onclick="scrollToSection('contact')">Contato</button>
        </nav>
    </header>
    <main>
        <section id="home">
            <h1>Bem-vindo ao Meu Site!</h1>
            <p>Este é um exemplo simples de um site usando HTML, CSS e JavaScript.</p>
            <img src="https://via.placeholder.com/600x300" alt="Imagem de exemplo">
        </section>
        <section id="about">
            <h2>Sobre Nós</h2>
            <p>Somos uma equipe apaixonada por tecnologia, criando projetos incríveis para o futuro.</p>
        </section>
        <section id="contact">
            <h2>Contato</h2>
            <p>Entre em contato conosco pelo e-mail: <a href="mailto:contato@exemplo.com">contato@exemplo.com</a></p>
        </section>
    </main>
    <footer>
        <p>Autor: Livia Gabriala </p>
        <p>Contato: 41991765379
          contato@liviafelician.com</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
