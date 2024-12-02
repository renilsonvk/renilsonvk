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
/* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and general styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

/* Header styles */
header {
    background-color: #003366;
    color: white;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    display: flex;
    list-style: none;
}

header nav ul li {
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

/* Hero section */
.hero {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 50px 0;
}

.hero h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

.cta-btn {
    background-color: #ff6600;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    font-size: 1.1em;
}

/* Sections */
section {
    padding: 50px 20px;
    text-align: center;
}

section h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

section ul {
    list-style: none;
    margin: 20px 0;
}

section ul li {
    font-size: 1.2em;
    margin: 10px 0;
}

/* Form Styles */
form input, form textarea {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #28a745;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background-color: #218838;
}

/* Footer styles */
footer {
    background-color: #003366;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer .social-media a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

footer p {
    margin-top: 10px;
}
document.getElementById("simulation-form").addEventListener("submit", function(event) {
    event.preventDefault();
    let value = document.getElementById("value").value;
    let term = document.getElementById("term").value;
    alert(`Simulação: R$${value} por ${term} meses.`);
});

document.getElementById("application-form").addEventListener("submit", function(event) {
    event.preventDefault();
    alert("Sua solicitação foi enviada!");
});

document.getElementById("contact-form").addEventListener("submit", function(event) {
    event.preventDefault();
    alert("Sua mensagem foi enviada. Nós entraremos em contato.");
});
