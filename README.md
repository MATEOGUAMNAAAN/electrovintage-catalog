<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ElectroVintage - Catálogo de Lámparas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2C3E50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #2C3E50;
            font-weight: bold;
        }
        .catalog {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .lamp-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .lamp-card img {
            width: 100%;
            height: auto;
        }
        .lamp-card .details {
            padding: 15px;
            text-align: center;
        }
        .lamp-card h3 {
            margin: 10px 0;
            font-size: 1.2em;
        }
        .lamp-card p {
            font-size: 0.9em;
            color: #555;
        }
        footer {
            background-color: #2C3E50;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ElectroVintage</h1>
        <p>Iluminación con Estilo Retro y Funcionalidad Moderna</p>
    </header>

    <nav>
        <a href="#catalogo">Catálogo</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="catalogo" class="catalog">
        <div class="lamp-card">
            <img src="lamp1.jpg" alt="Lámpara Roja Retro">
            <div class="details">
                <h3>Lámpara Roja Retro</h3>
                <p>Incluye puerto USB y toma de corriente. Ideal para espacios modernos.</p>
                <p><strong>Precio:</strong> $50</p>
            </div>
        </div>
        <div class="lamp-card">
            <img src="lamp2.jpg" alt="Lámpara Vintage Minimalista">
            <div class="details">
                <h3>Lámpara Vintage Minimalista</h3>
                <p>Diseño elegante con bombilla LED de bajo consumo.</p>
                <p><strong>Precio:</strong> $45</p>
            </div>
        </div>
        <div class="lamp-card">
            <img src="lamp3.jpg" alt="Lámpara Industrial Reutilizable">
            <div class="details">
                <h3>Lámpara Industrial Reutilizable</h3>
                <p>Fabricada con materiales reciclados, perfecta para ambientes sostenibles.</p>
                <p><strong>Precio:</strong> $60</p>
            </div>
        </div>
    </section>

    <footer id="contacto">
        <h3>Contáctanos</h3>
        <p><strong>Instagram:</strong> <a href="https://www.instagram.com/Electro_vintage" target="_blank">@Electro_vintage</a></p>
        <p><strong>Facebook:</strong> <a href="https://www.facebook.com/ElectroVintaje.tec" target="_blank">ElectroVintaje.tec</a></p>
        <p><strong>TikTok:</strong> <a href="https://www.tiktok.com/@VintajeElectrotec" target="_blank">@VintajeElectrotec</a></p>
        <p><strong>Email:</strong> Electrovintaje2024@gmail.com</p>
        <p><strong>Celular:</strong> 0985808007 - 096319421</p>
    </footer>
</body>
</html>
