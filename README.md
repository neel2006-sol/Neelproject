<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="RULZZZ - Urban Clothing Brand. Trendy, Unique, Bold.">
    <meta name="keywords" content="clothing, streetwear, urban fashion, trendy apparel">
    <title>RULZZZ Clothing</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: 'Arial';
            margin: 0;
            padding: 0;
            top: 3cm;
            background-image: url("backgrounddd.jpg");
            background-position: center;
            background-size: auto;
            color: rgb(22, 225, 211)
        }

        header {
            background: linear-gradient(90deg, #fddc66, #51b4c3);
            padding: 20px 0;
            height: auto;
            width: 100%;
           
            
            
        }

        header h1 {
            font-size: 1cm;
            margin: 0;
            color: white;
            font-family: 'Times New Roman', Times, serif;
            text-shadow:4px 4px 4px black
            
        }
        header h1:hover{
            transform: scale(1.1);
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }

        nav a {
            color: rgb(255, 255, 255);
            font-size: 1.2rem;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: 0.3s;
        }

        nav a:hover {
            color: #000000;
            transform: scale(1.2);
            text-decoration: underline;
            
        }

        section.products {
            padding: 40px 10%;
            text-align: center;
        }

        section.products h2 {
            font-size: 4rem;
            margin-bottom: 30px;
            color: #ff6e7f;
        }

        .product-item {
            display: inline-block;
            width: 30%;
            margin: 15px;
            border: 1px solid #444;
            border-radius: 8px;
            background: #333;
            padding: 20px;
            text-align: center;
            transition: 0.3s;
        }

        .product-item:hover {
            transform: scale(1.05);
            border-color: #ff6e7f;
            
        }

        .product-item img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product-item h3 {
            font-size: 1.5rem;
            color: #ff6e7f;
            margin-top: 10px;
        }

        .product-item p {
            font-size: 1.1rem;
            color: #fff;
        }

        footer {
            background: linear-gradient(90deg, #fad378, #103338);
            padding: 20px;
            text-align: center;
            color: rgb(16, 36, 63);
        }

        footer p {
            font-size: 1rem;
        }
        .i1{
         position: absolute;
         top: 23px;
         left: 150px;
        }
        .i1:hover{
            transform: scale(1.1);
        }
        .i2{
         position: absolute;
         top: 23px;
         right: 250px;
         color: #fff;
         }
         .i2:hover{
            transform: scale(1.1);
         }
    </style>
</head>

<body>
   
     <header>
        <center><a class="i1" href=""><img src="rulzzz logooo.jpeg" title="LOGO" style="height: 2cm; width: 4cm; border: 2px solid black;"></a>
     <a class="i2" href="login page.html"><img src="user.png" style="height: 2cm; width: 2cm;" title="LOGIN"></a>
    <span><h1 title="Title">RULZZZ Apparels</h1>
        <nav>
            <a href="project.html">Home</a>
            <a href="about.html">About Us</a>
            <a href="contact us.html">Contact</a>
        </nav></span></center>
    </header>

    <section class="products">
        <h2>Our Collection</h2>
        <div class="product-item">
            <a href="artisticc.html"><img src="artisticcc.jpeg" alt="Product 1"></a>
            <h3>Artistic</h3>
            <p>Fresh, bold, and street-ready. Get your style on.</p>
        </div>
        <div class="product-item">
            <a href="fire.html"><img src="always on fire.jpeg" alt="Product 2"></a>
            <h3>Always On Fire</h3>
            <p>Comfort meets style. Perfect for any day.</p>
        </div>
           <div class="product-item">
            <a href="halloween.html"><img src="halloween.jpeg" alt="Product 3"></a>
            <h3>Halloween Special</h3>
            <p>Designed for scary, crafted for ghosts on Halloween.</p>
        </div>
        <div class="product-item">
            <a href="life.html"><img src="lifeeee.jpeg" alt="Product 4"></a>
            <h3>LIFE</h3>
            <p>Life is a Race, if you didn't run fast you will be like a broken Andaa</p>
        </div>
        <div class="product-item">
            <a href="vintage.html"><img src="vintage.jpeg" alt="Product 5"></a>
            <h3>Vintage</h3>
            <p>Designed for elegance, Perfect for old school.</p>
        </div>
        <div class="product-item">
            <a href="rulzzz.html"><img src="rulzzzz.jpeg" alt="Product 6"></a>
            <h3>Rulzzz</h3>
            <p>Style in rule or Style with Rulzzz it'sthe same.</p>
        </div>
        <div class="product-item">
            <a href="thunder.html"><img src="thunderr.jpeg" alt="Product 7"></a>
            <h3>Thunder</h3>
            <p>A Ronaldo Fan!!! Here's the one for you...</p>
        </div>
        <div class="product-item">
            <a href="money.html"><img src="money.jpeg" alt="Product 8"></a>
            <h3>Money</h3>
            <p>Designed for Aura... Design it with Rulzzz</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 RULZZZ Clothing. All rights reserved.</p>
    </footer>

</body>
</html>
