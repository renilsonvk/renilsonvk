<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Empréstimo Pessoal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Logo</div>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#simulation">Simulação</a></li>
                <li><a href="#apply">Solicite Agora</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Empréstimo Pessoal Rápido e Fácil</h1>
        <p>Solicite seu empréstimo pessoal com taxas competitivas e condições acessíveis.</p>
        <a href="#apply" class="cta-btn">Solicite Agora</a>
    </section>

    <section id="benefits">
        <h2>Por que escolher nosso empréstimo?</h2>
        <ul>
            <li>Aprovação rápida</li>
            <li>Taxas de juros atrativas</li>
            <li>Sem burocracia</li>
            <li>Prazo flexível</li>
        </ul>
    </section>

    <section id="simulation">
        <h2>Simule seu Empréstimo</h2>
        <form id="simulation-form">
            <input type="number" placeholder="Valor desejado" id="value" required>
            <input type="number" placeholder="Prazo (em meses)" id="term" required>
            <button type="submit">Simular</button>
        </form>
    </section>

    <section id="about">
        <h2>Sobre Nós</h2>
        <p>Somos uma empresa especializada em empréstimos pessoais rápidos, com taxas justas e sem burocracia. Nossa missão é proporcionar soluções financeiras para nossos clientes de maneira simples e eficaz.</p>
    </section>

    <section id="apply">
        <h2>Solicite seu Empréstimo</h2>
        <form id="application-form">
            <input type="text" placeholder="Nome Completo" required>
            <input type="text" placeholder="CPF" required>
            <input type="email" placeholder="E-mail" required>
            <input type="number" placeholder="Valor do Empréstimo" required>
            <input type="number" placeholder="Prazo de Pagamento" required>
            <button type="submit">Enviar Solicitação</button>
        </form>
    </section>

    <section id="contact">
        <h2>Fale Conosco</h2>
        <p>Email: contato@emprestimopessoal.com</p>
        <p>Telefone: (11) 1234-5678</p>
        <form id="contact-form">
            <input type="text" placeholder="Nome" required>
            <input type="email" placeholder="E-mail" required>
            <textarea placeholder="Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
        </div>
        <p>&copy; 2024 Empréstimo Pessoal</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
