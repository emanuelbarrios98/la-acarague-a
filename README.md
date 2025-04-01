# la-acaragueña
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Acaragueña - Hamburguesas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(to right, #ff5733, #ffcc00);
            color: white;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.3);
            margin-top: 50px;
            color: black;
        }
        .menu-item {
            margin: 20px 0;
        }
        .menu-item img {
            width: 200px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.5);
        }
        .order-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
        .order-button:hover {
            background-color: #218838;
        }
        h1 {
            text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bienvenidos a La Acaragueña</h1>
        <p>¡Las hamburguesas más deliciosas de la colonia Acaragua!</p>
        
        <div class="menu-item">
            <img src="hamburguesa1.jpg" alt="Hamburguesa Clásica">
            <h2>Hamburguesa Clásica</h2>
            <p>$500</p>
            <a class="order-button" href="https://wa.me/3755551148?text=Quiero%20pedir%20una%20Hamburguesa%20Clásica">Ordenar por WhatsApp</a>
        </div>
        
        <div class="menu-item">
            <img src="hamburguesa2.jpg" alt="Hamburguesa Doble">
            <h2>Hamburguesa Doble</h2>
            <p>$700</p>
            <a class="order-button" href="https://wa.me/3755551148?text=Quiero%20pedir%20una%20Hamburguesa%20Doble">Ordenar por WhatsApp</a>
        </div>
    </div>
</body>
</html>
