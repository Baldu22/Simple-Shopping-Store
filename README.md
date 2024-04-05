# Simple-Shopping-Store

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Simple Shopping Store</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
    }
    .container {
        max-width: 1200px;
        margin: 20px auto;
        padding: 20px;
        background-color: #fff;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .header {
        text-align: center;
        margin-bottom: 20px;
    }
    .products {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
    }
    .product {
        background-color: #f9f9f9;
        padding: 20px;
        border-radius: 5px;
        box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
    }
    .product img {
        max-width: 100%;
        border-radius: 5px;
    }
    .product h2 {
        margin-top: 0;
        font-size: 18px;
        margin-bottom: 10px;
    }
    .product p {
        margin: 0;
        font-size: 16px;
        color: #666;
    }
    .product button {
        display: block;
        width: 100%;
        padding: 10px 0;
        background-color: #3f51b5;
        color: #fff;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        margin-top: 10px;
    }
    .product button:hover {
        background-color: #2c387e;
    }
</style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Simple Shopping Store</h1>
            <p>Welcome to our store!</p>
        </div>
        <div class="products">
            <div class="product">
                <img src="C:\Users\johnr\OneDrive\Pictures\th.jpg" alt="Product Image">
                <h2>Product 1</h2>
                <p>$19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="C:\Users\johnr\OneDrive\Pictures\scd.jpg" alt="Product Image">
                <h2>Product 2</h2>
                <p>$24.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="C:\Users\johnr\OneDrive\Pictures\ff.jpg" alt="Product Image">
                <h2>Product 3</h2>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </div>
</body>
</html>
