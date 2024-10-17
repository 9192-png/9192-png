<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miel de La Pampa - Venta al Mayorista</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Miel Pura de La Pampa</h1>
        <nav>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#products">Productos</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Miel Pura al Mayorista</h2>
        <p>Ofrecemos miel pura de La Pampa en envases de 1 kg y tachos de 13 kg. Calidad garantizada para mayoristas.</p>
        <img src="miel.jpg" alt="Envases de miel pura">
    </section>

    <section id="products">
        <h2>Productos</h2>
        <div class="product">
            <h3>Miel Pura - Envase de 1 kg</h3>
            <p>Precio: $4000 c/u (descuento a $3500 c/u por más de 10 envases)</p>
            <label for="quantity1kg">Cantidad:</label>
            <input type="number" id="quantity1kg" name="quantity1kg" min="1" value="1">
            <button onclick="addToCart1kg()">Agregar al carrito</button>
        </div>
        <div class="product">
            <h3>Miel Pura - Tacho de 13 kg</h3>
            <p>Precio: $39,000 c/u</p>
            <label for="quantity13kg">Cantidad:</label>
            <input type="number" id="quantity13kg" name="quantity13kg" min="1" value="1">
            <button onclick="addToCart13kg()">Agregar al carrito</button>
        </div>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <form>
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name">
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email">
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Miel de La Pampa. Todos los derechos reservados.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
