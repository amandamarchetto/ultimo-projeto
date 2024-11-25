# código html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Vendas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Loja Online</h1>
        <p>Bem-vindo à nossa loja!</p>
    </header>

    <main>
        <section id="products">
            <h2>Produtos</h2>
            <div class="product" data-id="1" data-name="Produto A" data-price="50">
                <h3>Produto A</h3>
                <p>Preço: R$ 50,00</p>
                <button class="add-to-cart">Adicionar ao carrinho</button>
            </div>
            <div class="product" data-id="2" data-name="Produto B" data-price="75">
                <h3>Produto B</h3>
                <p>Preço: R$ 75,00</p>
                <button class="add-to-cart">Adicionar ao carrinho</button>
            </div>
        </section>

        <section id="cart">
            <h2>Carrinho</h2>
            <ul id="cart-items">
                <!-- Itens do carrinho aparecerão aqui -->
            </ul>
            <p id="total-price">Total: R$ 0,00</p>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
