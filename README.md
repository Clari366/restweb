# Ex.07 Restaurant Website
## Date:5/05/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
homepage.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fusion Feast</title>

    <style>
        body {
            background-color: lavender;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: rgb(221, 172, 233);
            color: rgb(35, 62, 195);
            text-align: center;
            padding: 20px 0;
            font-size: 48px;
            font-weight: bold;
        }

        .logo-bar {
            display: flex;
            align-items: center;
            padding: 10px 20px;
            background-color: #f3e5f5;
        }

        .logo-bar img {
            width: 50px;
            height: 50px;
            margin-right: 15px;
        }

        .nav-list {
            display: flex;
            justify-content: center;
            background-color: #d1c4e9;
            padding: 10px 0;
        }

        .nav-list a {
            margin: 0 20px;
            text-decoration: none;
            color: #333;
            font-size: 18px;
            font-weight: 500;
        }

        .nav-list a:hover {
            color: rgb(100, 40, 150);
        }

        .content {
            padding: 30px;
            text-align: center;
        }

        .content h2 {
            color: #4a148c;
        }

        .content p {
            font-size: 18px;
            font-family: cursive;
            text-align: justify;
            max-width: 900px;
            margin: 0 auto;
        }

        .image-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }

        .image-gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }

        footer {
            background-color: #ede7f6;
            padding: 20px 0;
            text-align: center;
            font-size: 16px;
        }

        footer h3 {
            font-style: italic;
            margin-top: 5px;
        }

        .footer-logo {
            margin-top: 10px;
        }
    </style>
</head>

<body>

    <div class="logo-bar">
        <img src="image.png" alt="The Golden Platter Logo">
        <span><strong>THE GOLDEN PLATTER</strong></span>
    </div>

    <header>
        THE GOLDEN PLATTER
    </header>

    <div class="nav-list">
        <a href="homepage.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Admin</a>
        <a href="contact.html">Contact Us</a>
    </div>

    <div class="content">
        <img src="res.png" alt="Restaurant Interior" width="500" height="400">
        <h2>Welcome to The Golden Platter– A place where taste meets your expectations!</h2>
        <h2>About golden platter</h2>
        <p>
            As you step into FEAST, you’re greeted by a cozy and inviting atmosphere. Soft, golden lights from elegant chandeliers illuminate the plush furnishings. The air is filled with the aroma of freshly baked bread, exotic spices, and slow-cooked dishes. Our menu brings you global flavors, traditional techniques, and beautifully presented meals.
        </p>
        <p>
            Many of our dishes use fresh, locally sourced ingredients, prepared with age-old methods like slow cooking, wood-fire roasting, fermenting, and clay pot cooking. Our ambiance and seasonal specialties celebrate cultures and festivals around the world – from Christmas roasts to Ramadan delicacies.
        </p>
    </div>

    <div class="image-gallery">
        <img src="kitchening.png" alt="Locally Sourced Ingredients">
        <img src="cook.png" alt=" Cooking Techniques">
        <img src="ambience.png"Restaurant Ambiance">
        <img src="fest.png" alt="Seasonal Festive Foods">
    </div>

    <footer>
        <p>&copy; 2025 The golden platter</p>
        <h3>Developed and Designed by Clarissa  k</h3>
        <div class="footer-logo">
            <img src="image.png" width="50" height="50" alt="Fusion Feast Logo">
        </div>
    </footer>

</body>
</html>

admin.html

<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #edafe1;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            background-color: #000000;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: rgb(49, 140, 140);
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgb(222, 201, 222);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .team-section {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .team-member {
            text-align: center;
            background: #55aea8;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .team-member img {
            width: 100%;
            height: 80%;
            max-width: 150px;
            border-radius: 20%;
            margin-bottom: 10px;
        }
        .team-member h3 {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .team-member p {
            font-size: 0.9em;
            padding-bottom: 15px;
            color: #0c0b0c;
        }
        .picture{
            width: 100px;
            height: 100px;
            
        }
    </style>
 </head>
 <body>
    <header>
        <top left>
        <div class="logo">
            <img src="image.png" width="100" height="100" alt="FUSION FEAST Logo">
        <h1>Administration</h1>
    </top left>
    </header>
    <nav>
        <a href="homepage.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Admin</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <main>
        <div class="container">
            <center>
            <h2>OUR TEAM</h2>
        </center>
            <div class="team-section">
                <div class="team-member">
                    <img src="founder.png"   alt="founder.jpg">
                    <h3>G JANARDHAN NAIDU-Founder</h3>
                    
                </div>
                <div class="team-member">
                    <img src="WhatsApp Image 2025-05-02 at 12.38.25 AM.jpeg"  alt="co-founder.jpg">
                    <h3>Clarissa K-co-founder</h3>
                
                </div>
                <div class="team-member">
                    <img src="member1.png"   alt="Hari nayak.jpg">
                    <h3>Hari nayak-Marketing director</h3>
                   
                </div>
                <div class="team-member">
                    <img src="member2.png"   alt="Ranveer brar.jpg">
                    <h3>Ranveer brar-Manager</h3>

                </div>
                <div class="team-member">
                    <img src="member 3.png"   alt="Saransh goila.jpg">
                    <h3>Saransh goila-Master Chef</h3>
            
                </div>
                <div class="team-member">
                    <img src="member4.png"   alt="Koushik S.jpg">
                    <h3>Koushik S-Master chef</h3>
                    
                </div>
                <div class="team-member">
                    <img src="mem5.png" alt="Harphal singh sokhi.jpg">
                    <h3>Harphal singh sokhi-Chef</h3>
                    
                </div>
                <div class="team">
                    <img src="team.jpg"  alt="team.jpg">
                    <h3>OUR TEAM</h3>
                    
                </div>
            </div>
        </div>
        <footer>
            <div class="logo">
                <img src="image.png" width="50" height="50" class="footer" alt="Fusion feast Logo">
            </div>
            
                <palign="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by Clarissa K</h3>
        </footer>
    </main>
 </body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <div class="logo">
        <img src="image.png" width="50" height="50" alt="The Golden Platter Logo">
    </div>
    <title>FUSION FEAST - Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #2c3e50;
            color: white;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #ff5722;
        }

        .menu-container {
            padding: 40px 20px;
            background: #ffffff;
            text-align: center;
        }

        .menu-container h1 {
            font-size: 2.5rem;
            color: #2c3e50;
            margin-bottom: 30px;
            font-family: 'Playfair Display', serif;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .menu-item {
            background: white;
            border-radius: 15px;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: left;
        }

        .menu-item img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .menu-item:hover img {
            transform: scale(1.1);
        }

        .menu-details {
            padding: 15px;
        }

        .menu-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 10px;
            font-weight: 500;
        }

        .menu-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        .menu-details .price {
            font-weight: bold;
            font-size: 1.1rem;
            color: #e74c3c;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .menu-items {
                flex-direction: column;
                gap: 20px;
            }

            .menu-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>The Golden Platter</h1>
        <nav>
            <a href="homepage.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact us</a>
            
        </nav>
    </header>

    <div class="menu-container">
        <h1>OUR MENU</h1>
        <div class="menu-items">
            <div class="menu-item">
                <img src="baby-corn-pepper-fry.png"Baby corn pepper fry">
                <div class="menu-details">
                    <h3>Baby corn salt pepper</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="momos.png" alt="Veg momos">
                <div class="menu-details">
                    <h3>Veg momos</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="aalo.png"Aloo tikki">
                <div class="menu-details">
                    <h3>Aloo tikki</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="prawn.png" alt="Prawn fry">
                <div class="menu-details">
                    <h3>Prawn fry</h3>
                    <p class="price">₹180/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="fishfry.png" alt="Fish fry">
                <div class="menu-details">
                    <h3>Fish fry</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="tandoori.png" alt="Tandoori chicken">
                <div class="menu-details">
                    <h3>Tandoori chicken</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            
            <div class="menu-item">
                <img src="souind.png" alt="South indian meals">
                <div class="menu-details">
                    <h3>South indian meals</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="vegbi.png" alt="Veg biriyani">
                <div class="menu-details">
                    <h3>Veg biriyani</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="curd.png" alt="Curd rice">
                <div class="menu-details">
                    <h3>Curd rice</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="chickemb.png" alt=" chicken biriyani">
                <div class="menu-details">
                    <h3>Avakai chicken biriyani</h3>
                    <p class="price">₹250/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="muttonb.png" alt="Mutton biriyani">
                <div class="menu-details">
                    <h3>Mutton biriyani</h3>
                    <p class="price">₹350/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="prawnb.png" alt="Prawn biriyani">
                <div class="menu-details">
                    <h3>Prawn biriyani</h3>
                    <p class="price">₹350/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="oreo-milkshake.png" alt="Oreo milkshake">
                <div class="menu-details">
                    <h3>Oreo milkshake</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="oreo-milkshake.png" alt="Chocolate milkshake">
                <div class="menu-details">
                    <h3>Chocolate milkshake</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="rocher.png" alt="Ferrero rocher shake">
                <div class="menu-details">
                    <h3>Ferrero rocher shake</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="fruit.png" alt="Dry fruit shake">
                <div class="menu-details">
                    <h3>Dry fruit shake</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="mint.png" alt="Mint cooler">
                <div class="menu-details">
                    <h3>Mint cooler</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="mint.png"  alt="Ultra lime">
                <div class="menu-details">
                    <h3>Ultra lime</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            
            <div class="menu-item">
                <img src="hotchoco.png"  alt="Hot chocolate">
                <div class="menu-details">
                    <h3>Hot chocolate</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="cappo.png" alt="cappuccino">
                <div class="menu-details">
                    <h3>cappuccino</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="hotchoco.png" alt="Cold coffee">
                <div class="menu-details">
                    <h3>Cold coffee</h3>
                    <p class="price">₹90/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="falloda.png" alt="Falooda">
                <div class="menu-details">
                    <h3>Falooda</h3>
                    <p class="price">₹75/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="fruit.png" alt="Badam milk">
                <div class="menu-details">
                    <h3>Badam milk</h3>
                    <p class="price">₹50/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="brownie.png" alt="Sizzling brownie">
                <div class="menu-details">
                    <h3>Sizzling brownie</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="rasmalai.png"  alt="Rasmalai">
                <div class="menu-details">
                    <h3>Rasmalai</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="gulab.png"    alt="Gulab jamun">
                <div class="menu-details">
                    <h3>Gulab jamun</h3>
                    <p class="price">₹50/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="kheer.png"   alt="Kheer">
                <div class="menu-details">
                    <h3>Kheer</h3>
                    <p class="price">₹85/-</p>
                </div>
            </div>
            </div>
            <div class="menu-item">
                <img src="ice.png" alt="Ice cream">
                <div class="menu-details">
                    <h3>Ice cream</h3>
                    <p class="price">₹70/-</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
            
        <p align="center" class="copy">&copy; Copyright Fusion feast</p>

    <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
        Developed and designed by ASWINI G</h3>
</footer>
</center>
<div class="logo">
<img src="Fusion feast logo.jpg" width="50" height="50" class="footer" alt="Fusion feast Logo">
</div>


</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Contact Us - Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
             <center>
            <div class="logo">
                <img src="image.png" width="100" height="100" alt="FUSION FEAST Logo">
            </center>
            <h1>THE GOLDEN PLATTER</h1>
        <div class="container">
            <h1>Contact us</h1>
            <nav>
                <ul>
                <li><a href="homepage.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact us</a></li>
                </ul>
            </nav>
        </div>
    </header>
<style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #66c0ca;
    color: #1956cf;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #d8a2e6;
    padding: 20px 0;
    color: #fff;
}

header h1 {
    text-align: center;
    font-size: 2.5em;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-size: 1.2em;
}

nav ul li a:hover {
    text-decoration: underline;
}

.contact-us {
    background-color: #fff;
    padding: 40px 0;
    margin-top: 20px;
}

.contact-us h2 {
    text-align: center;
    font-size: 2.5em;
    margin-bottom: 20px;
}

.contact-us p {
    text-align: center;
    font-size: 1.2em;
    margin-bottom: 40px;
}

form {
    width: 100%;
    max-width: 600px;
    margin: 0 auto;
    background-color: #ecf0f1;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    font-size: 1.1em;
    margin-bottom: 5px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    font-size: 1em;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin-top: 5px;
}

button {
    width: 100%;
    padding: 12px;
    background-color: #27dcd3;
    color: #fff;
    font-size: 1.2em;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #2775c4;
}

footer {
    background-color: #5b7fa2;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 40px;
}

</style>
    <section class="contact-us">
        <div class="container">
            <h2>Contact Us</h2>
            <p>"We'd love to hear from you! Need a reservation or have a query?"</p>
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                </div>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
    <footer>
        <h1>Address-Amudala,chittoor district</h1>
        <h1>email-goldenplaater@gmail.com</h1>
        <h1>Phone-+919515127326</h1>
          <h2>Food that not only satisfies your hunger but also your soul</h2>  
        <p align="center" class="copy">&copy; Copyright golden platter</p>

    <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
        Developed and designed by ASWINI G</h3>
</footer>
    

</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2025-05-05 074144-1.png>)

![alt text](<Screenshot 2025-05-05 074831.png>)

![alt text](<Screenshot 2025-05-05 074200.png>)

![alt text](<Screenshot 2025-05-05 074230.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
