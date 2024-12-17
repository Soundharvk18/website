# Ex.07 Restaurant Website
# Date:8/11/24
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to One8 Restaurant - Delight in Exquisite Cuisines.">
    <title>One8 Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: black;
        }

        header {
            background-image: url("download.png");
            background-repeat: no-repeat;
            object-fit: cover;
            color: white;
            padding: 15px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #444;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav ul li a:hover {
            background-color: #555;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        footer {
            background-color: black;
            color: white;
            text-align: center;
            padding: 2px ;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        h1 {
            color: white;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .image1{
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .menu-item {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .menu-item h3 {
            margin: 0 0 10px 0;
        }

        .menu-item p {
            color: #666;
        }
        
      </style>
</head>
<body>

<header>
    <h1>One8 Restaurant</h1>
    <p>Delight in Exquisite Cuisines</p>
</header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#image">image</a></li>
        <li><a href="#admini">Administration</a></li>
        <li><a href="#about">About Us</a></li>
        
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="home">
    <h2>Welcome to One8 Restaurant</h2>
    <p>At One8, we serve the finest dishes made from the freshest ingredients. Our chefs are dedicated to bringing you an unforgettable dining experience, where great food meets warm hospitality. We are dedicated to providing you with an unforgettable dining experience, featuring fresh ingredients and bold flavors. Whether you're here for a casual meal or a special occasion, we look forward to serving you. Enjoy your time at one8!</p>
</section>

<section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid" >
        <div class="menu-item">
            <img src="salman.jpg">
            <h3>Grilled Salmon</h3>
            <p>Freshly grilled salmon with a side of vegetables.</p>
            <p><strong> ₹440</strong></p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\filet migon.jpg" width="100%">
            <h3>Filet Mignon</h3>
            <p>Tender filet mignon served with mashed potatoes and asparagus.</p>
            <p><strong> ₹380</strong></p>
        </div>
        <div class="menu-item">
            <img src="seisar.jpg" width="100%">
            <h3>Caesar Salad</h3>
            <p>Crispy romaine lettuce with parmesan and Caesar dressing.</p>
            <p><strong> ₹270</strong></p>
        </div>
        <div class="menu-item">
            <img src="salad.jpg" width="100%">
            <h3>super food salad</h3>
            <p>assorted mesclun green, roasted pumpkin seeds, cantaloupe melon, amaranth seeds</p>
            <p><strong> ₹310</strong></p>
        </div>
        <div class="menu-item">
            <img src="pasta.jpg" width="100%">
            <h3>Pasta Primavera</h3>
            <p>Penne pasta with fresh vegetables in a light garlic sauce.</p>
            <p><strong> ₹520</strong></p>
        </div>
        <div class="menu-item">
            <img src="avacada.jpg" width="100%">
            <h3>Tartar Topped On Avocado</h3>
            <p>with crispy corn, sriracha, scallion, japanese spicy mayonnaise </p>
            <p><strong> ₹460</strong></p>
        </div>
        <div class="menu-item">
            <img src="mush.jpg" width="100%">
            <h3>Mushroom Googly </h3>
            <p>assorted wild mushrooms, cream cheese, vegetarian broth, truffle oil            </p>
            <p><strong> ₹460</strong></p>
        </div>
        <div class="menu-item">
            <img src="cheese.jpg" width="100%">
            <h3>cheese board </h3>
            <p>choice of cheese selections, fresh fruits, relish and crackers            </p>
            <p><strong> ₹1245</strong></p>
        </div>
        <div class="menu-item">
            <img src="charcute.jpg" width="100%">
            <h3>Charcutiere Board            </h3>
            <p>choice of cold cut selections, pickles vegetables, relish and crackers           </p>
            <p><strong> ₹1475</strong></p>
        </div>
        <div class="menu-item">
            <img src="buratta.jpg" width="100%">
            <h3>Deconstructed Buratta            </h3>
            <p>olive tapenade, sweet and sour jam, sour dough            </p>
            <p><strong> ₹775</strong></p>
        </div>
        <div class="menu-item">
            <img src="phyiio.jpg" width="100%">
            <h3>Phyllo Baked            </h3>
            <p>raw papaya relish, California grapes and truffle honey drizzle          </p>
            <p><strong> ₹695</strong></p>
        </div>
        <div class="menu-item">
            <img src="beirut.jpg" width="100%">
            <h3> Beirut Hummus</h3>
            <p>Assorted lavash stick,olive,pita,fattoush salad and pickles</p>
            <p><strong> ₹560</strong></p>
        </div>
<section id="admini">
    <h2>Administration</h2>
    <div class="menu-grid">
        <div class="menu-item">
        <img src="viratcasual.jpg">
            <h3>Founder</h3>
            <p>Virat kohli</p>
        </div>
        <div class="menu-grid">
        <img src="c:\web developmebt\manager.jpg">
        <h3>Co-Founder</h3>
        <p>dhinesh</p>
        </div>
        <a href="https://www.instagram.com/shraddhakapoor/?hl=en"></a>
        <img src="WhatsApp Image 2024-11-25 at 13.35.59_c5bd1e50.jpg" width="100%" height="70%">
        <h3>Brand ambassador </h3>
        <p>Deepan adhithya</p>
        </div>
        <div class="menu-grid">
            <img src="soundhar1.jpg" width="100%" height="70%">
            <h3>Brand ambassador</h3>
            <p>soundhar</p>
        </div>

        <div class="menu-grid">
            <img src="monish.jpg" width="100%">
            <h3>manager</h3>
            <p>monish</p>
        </div>
        <div class="menu-grid">
            <img src="danu.jpg" width="100%">
            <h3>Chief Chef</h3>
            <p>chef Damu</p>
        </div>
    
        <div class="administration">
            <img src="venkatesh.jpg" width="100%">
            <h3>Assistant Chef</h3>
            <p>venkatesh batt</p>
        </div>

</div>
</section>
<section id="image">
    <div class="menu-grid">
        <div class="image1">
           <img src="download7.jpg" width="100%">
        </div>
        <div class="image1">
           <img src="download1.jpg" width="100%">
        </div>
        <div class="image1">
           <img src="download2.jpg" width="100%">
        </div>
        <div class="image1">
            <img src="download3.jpg" width="100%">
        </div>
        <div class="image1">
            <img src="download8.jpg" width="105%">
        </div>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>One8 Restaurant was founded with the vision of creating a dining experience like no other. Our passion for food and hospitality drives us to continuously innovate and serve dishes that captivate the senses.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>123 Flavor Street, Gourmet City,bangal0re</p>
    <p>Phone: 9360723703</p>
    <p>Email: one8restaurant18@gmail.com</p>
</section>

<footer>
    <p><strong>One8</strong>&copy; Created by Jeya Soundhar</p>
</footer>

</body>
</html>
```
# OUTPUT:
![Screenshot 2024-12-13 182752](https://github.com/user-attachments/assets/900791b9-0ff5-4686-b45e-2d3ae05a91b1)
![Screenshot 2024-12-13 182810](https://github.com/user-attachments/assets/c833ea1d-ce91-4f28-b084-df928dbcf9b5)
![Screenshot 2024-12-17 190844](https://github.com/user-attachments/assets/d41534ba-c47e-4f35-bb4f-25d2407df53c)
![Screenshot 2024-12-17 190905](https://github.com/user-attachments/assets/9840a485-52f2-4c75-9a08-268e185983e2)
![Screenshot 2024-12-17 190928](https://github.com/user-attachments/assets/4c53536a-5a7d-4d2f-9ae0-9f23cff2a087)

![Screenshot 2024-12-17 190950](https://github.com/user-attachments/assets/32728252-781c-4040-bd05-65d8c3b2f853)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
