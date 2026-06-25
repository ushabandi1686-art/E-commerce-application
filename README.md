# E-commerce-application
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechStore | E-Commerce</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="logo">TechStore</div>
        <div class="nav-links">
            <input type="text" placeholder="Search products..." class="search-bar">
            <a href="#">Cart (0)</a>
            <a href="#" class="login-btn">Login</a>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="container">
        <aside class="filters">
            <h3>Filters</h3>
            <div class="filter-group">
                <label>Category</label>
                <select>
                    <option>All Electronics</option>
                    <option>Laptops</option>
                    <option>Accessories</option>
                </select>
            </div>
        </main>

        <section class="product-grid">
            <!-- Product Card 1 -->
            <div class="card">
                <div class="image-placeholder"></div>
                <div class="card-info">
                    <h4>Wireless Headphones</h4>
                    <p class="price">$99.00</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
            </div>
            <!-- Product Card 2 -->
            <div class="card">
                <div class="image-placeholder"></div>
                <div class="card-info">
                    <h4>Smart Watch</h4>
                    <p class="price">$149.00</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
            </div>
        </section>
    </main>
</body>
</html>
