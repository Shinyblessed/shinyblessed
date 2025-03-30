## Hi there 👋

<!--
**Shinyblessed/shinyblessed** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html><html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Negozio Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background: #ff6600;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 24px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .product {
            background: white;
            margin: 10px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 250px;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .btn {
            background: #ff6600;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn:hover {
            background: #cc5500;
        }
    </style>
</head>
<body>
    <header>Negozio Online</header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Prodotto 1">
            <h3>Prodotto 1</h3>
            <p>€10.00</p>
            <button class="btn">Aggiungi al carrello</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Prodotto 2">
            <h3>Prodotto 2</h3>
            <p>€15.00</p>
            <button class="btn">Aggiungi al carrello</button>
        </div>
    </div>
</body>
</html>
