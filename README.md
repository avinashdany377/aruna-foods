# aruna-foods
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aruna Foods</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        .product, .blog-post {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
        }
        .product img, .blog-post img {
            width: 100%;
            border-radius: 8px;
        }
        .slideshow {
            width: 100%;
            margin: 20px 0;
        }
        .slideshow img {
            width: 100%;
            border-radius: 8px;
        }
    </style>
</head>
<body>

<header>
    <h1>Aruna Foods</h1>
    <p>Your destination for delicious and healthy treats</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container" id="home">
    <h2>Welcome to Aruna Foods</h2>
    <p>Explore our range of delectable and nutritious food items.</p>
</div>

<div class="container" id="products">
    <h2>Featured Product: Dry Fruits Laddu</h2>
    <div class="product">
        <img src="https://www.mygingergarlickitchen.com/wp-content/uploads/2021/12/Dry-Fruits-Laddu-Recipe-1.jpg" alt="Dry Fruits Laddu">
        <h3>Dry Fruits Laddu</h3>
        <p>Price: ₹900 per kg</p>
        <p>Our Dry Fruits Laddu is a wholesome, energy-packed sweet made from nutrient-rich dry fruits, nuts, and natural sweeteners like dates and figs. It's free from refined sugar, making it a perfect healthy snack for all age groups.</p>
        <a href="#contact">Order Now</a>
    </div>
</div>

<div class="container" id="blog">
    <h2>Latest Blog Post</h2>
    <div class="blog-post">
        <img src="https://www.mygingergarlickitchen.com/wp-content/uploads/2021/12/Dry-Fruits-Laddu-Recipe-1.jpg" alt="Dry Fruits Laddu Recipe">
        <h3>Dry Fruits Laddu Recipe</h3>
        <p>Discover the recipe for our signature Dry Fruits Laddu, a treat that's both delicious and nutritious. Learn how to make this sweet at home with our step-by-step guide.</p>
        <a href="https://www.mygingergarlickitchen.com/dry-fruits-laddu/">Read More</a>
    </div>
</div>

<div class="container" id="slideshow">
    <h2>Our Specialities</h2>
    <div class="slideshow">
        <div><img src="https://www.mygingergarlickitchen.com/wp-content/uploads/2021/12/Dry-Fruits-Laddu-Recipe-1.jpg" alt="Dry Fruits Laddu"></div>
        <div><img src="https://www.mygingergarlickitchen.com/wp-content/uploads/2021/12/Dry-Fruits-Laddu-Recipe-2.jpg" alt="Dry Fruits Laddu"></div>
        <div><img src="https://www.mygingergarlickitchen.com/wp-content/uploads/2021/12/Dry-Fruits-Laddu-Recipe-3.jpg" alt="Dry Fruits Laddu"></div>
    </div>
</div>

<div class="container" id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@arunafoods.com</p>
    <p>Phone: +91 123 456 7890</p>
    <p>Address: Kakinada, Andhra Pradesh, India</p>
</div>

<script>
    $(document).ready(function(){
        $('.slideshow').slick({
            autoplay: true,
            autoplaySpeed: 2000,
            dots: true,
            arrows: false
        });
    });
</script>

</body>
</html>
