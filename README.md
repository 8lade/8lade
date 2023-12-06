<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blade's Inventory</title>
    <style>
        /* Your CSS styles go here */
    </style>
</head>
<body>
    <header>
        <h1>Blade's Inventory</h1>
    </header>
    <section id="products">
        <!-- Product listings go here -->
        <div class="product">
            <img src="product-image.jpg" alt="Product Image">
            <h2>Product Name</h2>
            <p>Description of the product.</p>
            <p>$19.99</p>
            <button onclick="addToCart(1)">Add to Cart</button>
        </div>
        <!-- More products... -->
    </section>
    <section id="cart">
        <h2>Shopping Cart</h2>
        <ul id="cart-items">
            <!-- Cart items go here -->
        </ul>
        <p>Total: $<span id="cart-total">0.00</span></p>
    </section>
  
