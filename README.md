
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="icon" type="image/x-icon" href="Think Thrift Logo.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <link rel="stylesheet" href="home.css">
    <script src="cart.js"></script>
</head>
<body>
    <!-- Header Start -->
    <header>
        <div class="logo">
            <img src="Think Thrift Logo.png" alt="Logo">
        </div>
        <nav>
            <input type="checkbox" id="check">
            <label for="check" class="check-btn">&#9776;</label>
            <ul class="navbar">
                <li><a href="home.html" class="active">Home</a></li>
                <li><a href="about.html"class="active">About</a></li>
                <li><a href="menu.html"class="active">Menu</a></li>
            </ul>
        </nav>
        <div class="search-form">
            <input type="text" placeholder="Search...">
            <label for="search">&#128269;</label>
        </div>
        <!-- Fixed Cart Button -->
        <div class="cart-icon">
            <a href="cart.html" title="Shop Cart">🛒</a>
        </div>
    </header>
    <!-- Header End -->

    <!-- Menu Section -->
    <!-- Main Content --> <br><br><br><br>
    <section id="home">
        <div class="owner-card">
            <div class="owner-img">
                <img src="Lorrencee.jpg" alt="Owner">
            </div>
            <div class="owner-info">
                <h2>Owner of ThinkThrift</h2>
                <p>Welcome to Think Thrift, Vintage vibes, modern finds!</p>
                <button class="buy-now-btn">Buy Now</button>
            </div>
        </div>
    </section>

    <!-- Order Guide -->
    <section class="order-guide">
        <button>Order Now</button>
        <img src="Instructions.jpg" alt="Order Instructions">
    </section>
<br><br><br>
    <!-- Menu Section -->
    <section id="menu" class="menu-section">
        <div class="menu container">
            <div class="menu-box">
                <img src="Jorts.png" alt="Vintage Wide Leg Jorts">
                <div class="menu-content">
                    <h3>Star Boy Wide Leg Jorts</h3>
                    <p>Jorts!</p>
                    <select>
                        <option>Waist 30-31</option>
                        <option>Waist 28-29</option>
                        <option>Waist 26-27</option>
                    </select>
                    <button>Add to Cart</button>
                </div>
                <img src="Jersey Shirts.png" alt="Jersey Shirts">
                <div class="menu-content">
                    <h3>Choize Jersey Tee</h3>
                    <p>Jersey Shirts!</p>
                    <select>
                        <option>Small</option>
                        <option>Medium</option>
                        <option>Larges</option>
                    </select>
                    <button>Add to Cart</button>
                </div>
                <img src="Vintage T.png" alt="Vintage T-shirts">
                <div class="menu-content">
                    <h3>Spiderman Grapic Shirt</h3>
                    <p>Vintage T-shirts!</p>
                    <select>
                        <option>Small</option>
                        <option>Medium</option>
                        <option>Large</option>
                    </select>
                    <button>Add to Cart</button>
                </div>
            </div>
        </div>
    </section>
 <br><br><br>
    <!-- Footer Start -->
    <footer class="footer">
        <div class="footer-box">
            <h3>About Us</h3>
            <p>We are committed to providing the best service possible.</p>
        </div>
        <div class="footer-box">
            <h3>Quick Links</h3>
            <a href="HOME.html">Home</a><br>
            <a href="ABOUT.html">About</a><br>
            <a href="MENU.html">Menu</a><br>
        </div>
        <div class="footer-box">
            <h3>For more questions</h3>
            <form>
                <input type="email" placeholder="Enter your email">
                <button type="submit">Email here</button>
            </form>
        </div>
    </footer>
    
    <!-- Footer End -->
    <script src="2-menu.js"></script>
</body>
</html>
