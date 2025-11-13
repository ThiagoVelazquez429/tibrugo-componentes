# tibrugo-componentes
hola, nosotros nos dedicamos a la venta de componentes de PCs 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechZone - Venta de PCs</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">💻 TechZone</div>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#productos">Productos</a>
            <a href="#nosotros">Nosotros</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>
    <section id="inicio" class="hero">
        <div class="hero-text">
            <h1>Encuentra tu PC ideal</h1>
            <p>Rendimiento, diseño y potencia al mejor precio.</p>
            <a href="#productos" class="btn">Ver catálogo</a>
        </div>
    </section>
    <section id="productos" class="productos">
        <h2>Nuestros equipos</h2>
        <div class="grid">
            <div class="card">
                <img src="https://via.placeholder.com/250x180" alt="PC Gamer">
                <h3>PC Gamer Pro</h3>
                <p>Procesador Ryzen 7, RTX 4070, 32GB RAM, SSD 1TB.</p>
                <span class="precio">$1,499</span>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/250x180" alt="PC Oficina">
                <h3>PC Oficina</h3>
                <p>Intel i5, 16GB RAM, SSD 512GB, ideal para trabajo diario.</p>
                <span class="precio">$699</span>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/250x180" alt="Laptop Ultra">
                <h3>Laptop Ultra</h3>
                <p>Liviana, potente y con batería de larga duración.</p>
                <span class="precio">$999</span>
            </div>
        </div>
    </section>
    <section id="nosotros" class="nosotros">
        <h2>Sobre nosotros</h2>
        <p>En <strong>TechZone</strong> somos apasionados por la tecnología. Ofrecemos equipos personalizados y soporte técnico para garantizar el mejor rendimiento en tu trabajo o tus juegos.</p>
    </section>
    <section id="contacto" class="contacto">
        <h2>Contáctanos</h2>
        <form>
            <input type="text" placeholder="Tu nombre" required>
            <input type="email" placeholder="Tu correo electrónico" required>
            <textarea placeholder="Tu mensaje" rows="5" required></textarea>
            <button type="submit">Enviar mensaje</button>
        </form>
    </section>
    <footer>
        <p>© 2025 TechZone - Todos los derechos reservados</p>
    </footer>

</body>
</html>
