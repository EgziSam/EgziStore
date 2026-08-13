<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aura Accessories | Handmade Headbands & Scrunchies</title>
    <style>
        /* Base Styles & Modern Palette */
        :root {
            --primary-color: #8C6239;
            --secondary-color: #F7F3E9;
            --accent-color: #25D366; /* WhatsApp Green */
            --telegram-color: #0088cc; /* Telegram Blue */
            --text-color: #2C2C2C;
            --card-bg: #FFFFFF;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--secondary-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        /* Header / Navbar */
        header {
            background-color: #FFFFFF;
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-color);
            letter-spacing: 1px;
        }

        /* Hero Banner */
        .hero {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(rgba(140, 98, 57, 0.08), rgba(247, 243, 233, 1));
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: var(--primary-color);
        }

        .hero p {
            font-size: 1.1rem;
            max-width: 600px;
            margin: 0 auto;
            color: #666;
        }

        /* Product Grid Section */
        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 30px;
            font-size: 1.8rem;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .product-card {
            background-color: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.2s ease;
            display: flex;
            flex-direction: column;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            background-color: #f0f0f0;
        }

        .product-info {
            padding: 20px;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
        }

        .product-title {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 8px;
        }

        .product-desc {
            font-size: 0.9rem;
            color: #666;
            margin-bottom: 15px;
            flex-grow: 1;
        }

        .product-price {
            font-size: 1.3rem;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 15px;
        }

        .order-btn {
            display: block;
            text-align: center;
            background-color: var(--telegram-color);
            color: white;
            text-decoration: none;
            padding: 12px;
            border-radius: 6px;
            font-weight: 600;
            transition: background-color 0.2s;
        }

        .order-btn:hover {
            opacity: 0.9;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px;
            background-color: #FFFFFF;
            margin-top: 60px;
            font-size: 0.9rem;
            color: #888;
        }
    </style>
</head>
<body>

    <!-- Header Navigation -->
    <header>
        <div class="logo">AURA ACCESSORIES</div>
        <div>Handmade in Ethiopia</div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Handcrafted Hair Accessories</h1>
        <p>Premium satin scrunchies, twisted headbands, and matching tote sets designed for beauty, style, and total hair protection.</p>
    </section>

    <!-- Main Product Catalog -->
    <div class="container">
        <h2 class="section-title">Our Best Sellers</h2>
        <div class="product-grid">

            <!-- Product 1 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1620799140408-edc6dcb6d633?auto=format&fit=crop&w=600&q=80" alt="Satin Cloud Scrunchie" class="product-image">
                <div class="product-info">
                    <div class="product-title">Satin Cloud Scrunchie</div>
                    <div class="product-desc">Extra-full luxury satin scrunchie designed to protect hair from frizz and breakage.</div>
                    <div class="product-price">250 ETB</div>
                    <a href="https://t.me/yourusername" class="order-btn" target="_blank">Order on Telegram</a>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1584917865442-de89df76afd3?auto=format&fit=crop&w=600&q=80" alt="Twisted Front Headband" class="product-image">
                <div class="product-info">
                    <div class="product-title">Twisted Front Headband</div>
                    <div class="product-desc">Soft cotton twist headband with an elastic back strap for comfortable all-day wear.</div>
                    <div class="product-price">350 ETB</div>
                    <a href="https://t.me/yourusername" class="order-btn" target="_blank">Order on Telegram</a>
                </div>
            </div>

            <!-- Product 3 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1544816155-12df9643f363?auto=format&fit=crop&w=600&q=80" alt="Matching 3-Piece Bundle Set" class="product-image">
                <div class="product-info">
                    <div class="product-title">Matching 3-Piece Gift Set</div>
                    <div class="product-desc">Includes 1 Tote Bag, 1 Twist Headband, and 1 Scrunchie in matching fabric.</div>
                    <div class="product-price">950 ETB</div>
                    <a href="https://t.me/yourusername" class="order-btn" target="_blank">Order on Telegram</a>
                </div>
            </div>

        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Aura Accessories. All rights reserved. | Contact us via Telegram for custom orders.</p>
    </footer>

</body>
</html>
