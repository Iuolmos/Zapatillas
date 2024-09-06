# Zapatillas
Venda de zapatillas 
Aquí tienes un esquema básico para crear una página web para vender zapatillas, con HTML y CSS:

### 1. **Estructura HTML:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Zapatillas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Tienda de Zapatillas</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="hero">
        <h2>Bienvenido a la mejor tienda de zapatillas</h2>
        <p>Encuentra las mejores zapatillas deportivas, urbanas y más</p>
        <a href="#productos" class="btn">Ver Productos</a>
    </section>

    <section id="productos">
        <h2>Nuestros Productos</h2>
        <div class="productos">
            <div class="producto">
                <img src="zapatilla1.jpg" alt="Zapatilla 1">
                <h3>Zapatilla Deportiva 1</h3>
                <p>$50.00</p>
                <a href="#" class="btn">Comprar Ahora</a>
            </div>
            <div class="producto">
                <img src="zapatilla2.jpg" alt="Zapatilla 2">
                <h3>Zapatilla Deportiva 2</h3>
                <p>$60.00</p>
                <a href="#" class="btn">Comprar Ahora</a>
            </div>
            <div class="producto">
                <img src="zapatilla3.jpg" alt="Zapatilla 3">
                <h3>Zapatilla Urbana 1</h3>
                <p>$45.00</p>
                <a href="#" class="btn">Comprar Ahora</a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Tienda de Zapatillas | Todos los derechos reservados</p>
        <p>Contacto: info@tiendadezapatillas.com</p>
    </footer>
</body>
</html>
```

### 2. **Estilos CSS (styles.css):**

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

.hero {
    background-image: url('zapatillas-hero.jpg');
    background-size: cover;
    background-position: center;
    text-align: center;
    padding: 100px 0;
    color: white;
}

.hero h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero p {
    font-size: 24px;
    margin-bottom: 30px;
}

.btn {
    background-color: #ff6600;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

#productos {
    padding: 50px 0;
    text-align: center;
}

.productos {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.producto {
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    margin: 20px;
    text-align: center;
    width: 300px;
}

.producto img {
    width: 100%;
    height: auto;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
    margin-top: 50px;
}
```

### 3. **Descripción de los Elementos:**

1. **Encabezado y Navegación:** Contiene el nombre de la tienda y los enlaces a las secciones principales de la página.
2. **Sección de Hero:** Una sección inicial que recibe a los usuarios con una imagen de fondo, un eslogan y un botón para ver productos.
3. **Sección de Productos:** Muestra los productos en venta con una breve descripción, imagen, precio y un botón de compra.
4. **Pie de Página:** Contiene información de derechos de autor y detalles de contacto.

Puedes adaptar el código para personalizar colores, fuentes o agregar más funcionalidades como un carrito de compras. ¡Es un diseño simple, pero funcional!
