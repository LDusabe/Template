# Template
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Class</title>
    <style>
        body {
            background-color: bisque;
            margin: 0;
            font-family: Arial, sans-serif;
            overflow-y: scroll; /* Enable vertical scrolling */
        }
        header {
            font-size: 3em;
            font-weight: bold;
            color: rgb(15, 14, 13);
            text-align: center;
            padding: 20px 0;
            background-color: #e0e0e0;
            border-bottom: 2px solid #ccc;
        }

        nav {
            background-color: rgb(168, 47, 47);
            padding: 14px;
            position: relative;
        }
        ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: inline-block;
        }
        li {
            display: inline;
        }
        li a {
            text-decoration: none;
            color: rgb(15, 14, 13);
            font-size: large;
            padding: 10px 15px;
        }
        li a:hover {
            background-color: burlywood;
            color: black;
        }

        .about-us {
            position: absolute;
            top: 14px;
            right: 15px;
        }

        .content {
            display: flex;
            justify-content: center;
            padding: 20px;
            height: auto; /* Allow content to grow */
        }
        .column {
            text-align: left; /* Align text to the left */
            padding: 20px;
            margin: 0 10px; /* Margin for spacing */
        }
        .left-column, .right-column {
            flex: 0 0 23%; /* Set fixed width for side columns */
        }
        .middle-column {
            flex: 0 0 50%; /* Set width for the middle column */
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #e0e0e0;
            border-top: 2px solid #ccc;
            margin-top: 20px;
            font-size: small;
            color: rgb(15, 14, 13);
        }
    </style>
</head>
<body>
    <header>Freeman collection</header>

    <nav>
        <ul>
            <li><a href="#">HOME</a></li>
            <li>
                <a href="#">COLLECTION</a>
            </li>
            <li><a href="#">GALLERY</a></li>
            <li class="about-us"><a href="#">ABOUT US</a></li>
        </ul>
    </nav>

    <div class="content">
        <div class="column">
            <h1>Clothes</h1>
            <p>This section provides information about various clothing items available in our collection. We offer a range of styles, colors, and sizes to cater to your fashion needs. Our clothes are made from high-quality materials that ensure comfort and durability.</p>
            <p>From casual wear to formal attire, our selection will help you express your personal style. Explore our collection to find trendy outfits suitable for any occasion.</p>
            <p>Don't miss out on our latest arrivals and seasonal promotions that give you the best deals!</p>
        </div>
        
        <div class="column">
            <h1>Shoes</h1>
            <p>We offer a diverse selection of shoes ranging from casual sneakers to elegant formal footwear. Whether you're looking for comfortable shoes for daily wear or stylish options for special events, we have something for everyone.</p>
            <p>Our footwear collection is designed with both style and comfort in mind, ensuring that you not only look good but also feel great. Discover our range of shoes suitable for every season and occasion.</p>
            <p>Shop our latest styles and take advantage of exclusive offers available online!</p>
        </div>
        
        <div class="column">
            <h1>Others</h1>
            <p>In addition to shoes and clothing, we also offer various accessories that complement your outfits. Explore our collection of bags, belts, and jewelry that add the perfect finishing touch to your look.</p>
            <p>Our accessories are designed to enhance your style and provide functionality. Whether you're looking for everyday essentials or statement pieces, our selection has it all.</p>
            <p>Be sure to check out our new arrivals to find unique items that reflect your individual taste!</p>
        </div>
    </div>

    <footer>
        &copy; 2024 Linahcollection. All rights reserved.
    </footer>
</body>
</html>
