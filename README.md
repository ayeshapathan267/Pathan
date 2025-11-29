
<<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shajeb Multi Services - Mobile Store</title>

    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: url('https://images.unsplash.com/photo-1511707171634-5f897ff02aa9') center/cover no-repeat fixed;
            backdrop-filter: blur(4px);
        }

        /* Header */
        header {
            display: flex;
            align-items: center;
            gap: 15px;
            background: rgba(0, 0, 0, 0.7);
            padding: 15px 25px;
            color: #00eaff;
            box-shadow: 0 0 20px #00eaff;
        }

        header img {
            height: 60px;
            width: 60px;
            border-radius: 50%;
            border: 2px solid #00eaff;
            box-shadow: 0 0 15px #00eaff;
        }

        header h1 {
            font-size: 32px;
            letter-spacing: 2px;
            margin: 0;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: center;
            background: rgba(0, 0, 0, 0.6);
            padding: 12px;
            gap: 20px;
            backdrop-filter: blur(4px);
        }

        nav a {
            color: #00eaff;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 18px;
            transition: 0.3s;
        }

        nav a:hover {
            color: white;
            background: #00eaff;
            border-radius: 5px;
        }

        /* Banner */
        .banner {
            height: 280px;
            background: url('https://images.unsplash.com/photo-1512499617640-c2f999098c01') center/cover no-repeat;
            text-align: center;
            color: white;
            font-size: 40px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
            text-shadow: 0 0 15px #00eaff;
            margin-bottom: 25px;
        }

        /* Products Grid */
        .products {
            width: 90%;
            margin: auto;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .card {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 0 20px #00eaff;
            color: white;
            backdrop-filter: blur(6px);
            transition: 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 0 30px #00eaff;
        }

        .card img {
            width: 100%;
            height: 260px;
            border-radius: 10px;
            object-fit: cover;
        }

        .price {
            font-size: 22px;
            color: #00ff9d;
            font-weight: bold;
        }

        button {
            width: 100%;
            padding: 12px;
            border: none;
            background: #00eaff;
            border-radius: 5px;
            font-size: 18px;
            margin-top: 10px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #0088ff;
        }

        /* Footer */
        footer {
            background: rgba(0,0,0,0.7);
            color: #00eaff;
            text-align: center;
            padding: 18px;
            margin-top: 40px;
            box-shadow: 0 0 20px #00eaff;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="Shajeb Multi Services Logo">
    <h1>Shajeb Multi Services</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#Mobiles.html">Mobiles</a>
    <a href="#">Accessories</a>
    <a href="#">Offers</a>
    <a href="#">Contact</a>
</nav>

<div class="banner">Premium Latest Smartphones</div>

<!-- Products Section -->
<div class="products">

    <!-- Product 1 -->
    <div class="card">
        <img src="https://images.unsplash.com/photo-1517336714731-489689fd1ca8" alt="Samsung Galaxy A55">
        <h2>Samsung Galaxy A55</h2>
        <p class="price">₹28,999</p>
        <ul>
            <li>20MP Camera</li>
            <li>5000mAh Battery</li>
            <li>8GB RAM | 128GB</li>
            <li>Super AMOLED Display</li>
        </ul>
        <button>Buy Now</button>
    </div>

    <!-- Product 2 -->
    <div class="card">
        <img src="https://images.unsplash.com/photo-1592899677977-9c10ca588bbd" alt="iPhone 14">
        <h2>iPhone 14</h2>
        <p class="price">₹69,999</p>
        <ul>
            <li>48MP Camera</li>
            <li>4200mAh Battery</li>
            <li>A15 Bionic Chip</li>
            <li>Super Retina Display</li>
        </ul>
        <button>Buy Now</button>
    </div>

    <!-- Product 3 -->
    <div class="card">
        <img src="https://images.unsplash.com/photo-1601944179061-5a96edc0cfd4" alt="Redmi Note 13 Pro">
        <h2>Redmi Note 13 Pro</h2>
        <p class="price">₹18,499</p>
        <ul>
            <li>108MP Camera</li>
            <li>5000mAh Battery</li>
            <li>5G Support</li>
            <li>Snapdragon Processor</li>
        </ul>
        <button>Buy Now</button>
    </div>

</div>





<div class="banner">Premium Latest Smartphones</div>
<div class="products">
        <!-- Product 1 -->
                    <div class="card">
                    <img src="C:\Users\oswal\Pictures\V30_files\v30.PNG">
                     <h1>Vivo v3o</h1>
                     <p class="price">₹28,999</p>
                                  <ul>
                        <li>20MP Camera</li>
                           <li>5000mAh Battery</li>
                      <li>8GB RAM | 128GB</li>
                  <li>Super AMOLED Display</li>
                  </ul>
                   <button>Buy Now</button>
                            </div>
        <!-- Product 2 -->

    <div class="card">
        <img src="C:\Users\oswal\Videos\images\t1.jpg">
        <h1>Vivo T1 Pro </h1>
        <p class="price">₹18,000</p>
        <ul>
            <li>Rear: 50MP (main) + 2MP secondary </li>            
            <li>Battery: 7000mAh</li>
            <li>8GB RAM | 12GB or 256GB</li>
            <li>AMOLED Display</li>
        </ul>
        <button>Buy Now</button>
    </div>

        <!-- Product 3 -->

<div class="card">
    <img src="C:\Users\oswal\3D Objects\Oppo k13.JPEG">
        <h1> OPPO K13 </h1>
        <p class="price">₹18,999</p>
    <ul>
    <li>13MP Camera</li>
    <li>5000mAh Battery</li>
     <li>8GB RAM | 128GB</li>
     <li>6.67‑inch HD Display</li>
        </ul>
        <button>Buy Now</button>
    </div>

        <!-- Product 4 -->

<div class="card">
        <img src="C:\Users\oswal\Videos\images\nord.PNG">
        <h1>One Pluse Nord ce2 lite </h1>
        <p class="price">₹20,000</p>
        <ul>
            <li>64MP Camera</li>
            <li>5000mAh Battery</li>
            <li>8GB RAM | 128GB</li>
            <li>6.59‑inch Full HD display</li>
        </ul>
        <button>Buy Now</button>
    </div>



<div class="card">
        <img src="C:\Users\oswal\Videos\images\pop.WEBP">
        <h1>Tecno pop 9</h1>
        <p class="price">₹28,999</p>
        <ul>
            <li>20MP Camera</li>
            <li>5000mAh Battery</li>
            <li>8GB RAM | 128GB</li>
            <li>6.67‑inch HD Display</li>
        </ul>
        <button>Buy Now</button>
    </div>




<div class="card">
        
        <h1>Tecno pova 6</h1>
        <p class="price">₹28,999</p>
        <ul>
            <li>20MP Camera</li>
            <li>5000mAh Battery</li>
            <li>GB RAM | 128GB</li>
            <li>6.67‑inch HD Display</li>
        </ul>
        <button>Buy Now</button>
    </div>

</div>

<footer>
    <link rel="stylesheet" type="text/css" href="https://github.com/ayeshapathan267/Shajeb-Multi-Servise-github.io\"> © 2025 Shajeb Multi Services – All Rights Reserved
</footer>

</body>
</html>




























