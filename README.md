<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUniverso das Calotas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            margin: 10px 0;
            padding: 10px;
        }
        .product img {
            max-width: 100%;
        }
        .product h2 {
            margin: 0 0 10px;
        }
        .footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Loja de Calotas Automotivas</h1>
</header>

<nav>
    <a href="#produtos">Produtos</a>
    <a href="#sobre">Sobre Nós</a>
    <a href="#dicas">Dicas de Instalação</a>
    <a href="#contato">Contato</a>
</nav>

<main>
    <section id="produtos">
        <h2>Produtos</h2>
        <div class="product">
            <img src="calota1.jpg" alt="Calota Modelo 1">
            <h2>Calota Modelo 1</h2>
            <p>Descrição detalhada da Calota Modelo 1.</p>
            <p>Preço: R$ 100,00</p>
        </div>
        <div class="product">
            <img src="calota2.jpg" alt="Calota Modelo 2">
            <h2>Calota Modelo 2</h2>
            <p>Descrição detalhada da Calota Modelo 2.</p>
            <p>Preço: R$ 120,00</p>
        </div>
        <!-- Adicione mais produtos conforme necessário -->
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Informações sobre a empresa e sua missão no mercado de calotas automotivas.</p>
    </section>

    <section id="dicas">
        <h2>Dicas de Instalação</h2>
        <p>Aqui você encontrará dicas detalhadas sobre como instalar suas calotas automotivas corretamente.</p>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato conosco através do formulário abaixo:</p>
        <form>
            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="nome"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="mensagem">Mensagem:</label><br>
            <textarea id="mensagem" name="mensagem"></textarea><br>
            <input type="submit" value="Enviar">
        </form>
    </section>
</main>

<footer class="footer">
    <p>&copy; 2024 Loja de Calotas Automotivas</p>
</footer>

</body>
</html>
