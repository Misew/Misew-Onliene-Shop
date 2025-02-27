<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Misew Online Shop</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
        }
        .navbar {
            margin-bottom: 20px;
        }
        .container {
            max-width: 1200px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            background: white;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
        }
        .cart {
            position: fixed;
            top: 20px;
            right: 20px;
            background: white;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Misew Online Shop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Inicio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Productos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="cart">
        <h3>🛒 Carrito: <span id="cart-count">0</span></h3>
    </div>

    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <div class="product">
                    <img src="https://via.placeholder.com/200" alt="Producto 1">
                    <h3>Producto 1</h3>
                    <p>$10.00</p>
                    <button class="btn btn-primary" onclick="addToCart()">Agregar al Carrito</button>
                </div>
            </div>
            <div class="col-md-4">
                <div class="product">
                    <img src="https://via.placeholder.com/200" alt="Producto 2">
                    <h3>Producto 2</h3>
                    <p>$15.00</p>
                    <button class="btn btn-primary" onclick="addToCart()">Agregar al Carrito</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        let cartCount = 0;
        function addToCart() {
            cartCount++;
            document.getElementById('cart-count').innerText = cartCount;
        }
    </script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
