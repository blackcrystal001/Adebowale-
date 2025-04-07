# Adebowale-
Gadget store 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NexaCore Gadget - Premium Tech Store</title>
    <link rel="stylesheet" href="assets/styles/main.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    Nexa<span>Core</span>
                </div>
                <div class="search-bar">
                    <input type="text" id="searchInput" placeholder="Search for phones, laptops, accessories...">
                    <button id="searchButton">Search</button>
                </div>
                <div class="user-actions">
                    <a href="login.html">Login</a>
                    <a href="cart.html">Cart <span class="cart-count">0</span></a>
                </div>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <div class="container">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Deals</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="main">

        <!-- Hero Section -->
        <section class="hero">
            <div class="container">
                <h1>Find Your Perfect Gadget</h1>
                <p>Discover top-rated phones, laptops, and accessories at unbeatable prices.</p>
                <button class="hero-btn">Shop Now</button>
            </div>
        </section>

        <!-- Categories Section -->
        <section class="categories">
            <div class="container">
                <div class="category">
                    <img src="assets/images/category-phone.jpg" alt="Phones">
                    <h3>Phones</h3>
                </div>
                <div class="category">
                    <img src="assets/images/category-laptop.jpg" alt="Laptops">
                    <h3>Laptops</h3>
                </div>
                <div class="category">
                    <img src="assets/images/category-accessories.jpg" alt="Accessories">
                    <h3>Accessories</h3>
                </div>
                <div class="category">
                    <img src="assets/images/category-tablet.jpg" alt="Tablets">
                    <h3>Tablets</h3>
                </div>
            </div>
        </section>

        <!-- Featured Products Section -->
        <section class="products">
            <div class="container">
                <div class="product-card">
                    <img src="assets/images/product1.jpg" alt="Samsung Galaxy A14">
                    <h4>Samsung Galaxy A14</h4>
                    <p>$150</p>
                    <a href="#" class="view-details" data-product="Samsung Galaxy A14">View Details</a>
                </div>
                <div class="product-card">
                    <img src="assets/images/product2.jpg" alt="HP EliteBook 840">
                    <h4>HP EliteBook 840</h4>
                    <p>$420</p>
                    <a href="#" class="view-details" data-product="HP EliteBook 840">View Details</a>
                </div>
                <div class="product-card">
                    <img src="assets/images/product3.jpg" alt="iPhone 13 Pro">
                    <h4>iPhone 13 Pro</h4>
                    <p>$999</p>
                    <a href="#" class="view-details" data-product="iPhone 13 Pro">View Details</a>
                </div>
                <div class="product-card">
                    <img src="assets/images/product4.jpg" alt="Dell XPS 13">
                    <h4>Dell XPS 13</h4>
                    <p>$850</p>
                    <a href="#" class="view-details" data-product="Dell XPS 13">View Details</a>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 NexaCore. All rights reserved.</p>
    </footer>

    <script src="assets/scripts/main.js"></script>

</body>
</html>
