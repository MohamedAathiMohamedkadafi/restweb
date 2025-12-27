# Ex.06 Restaurant Website
## Date:27/12/2025

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
home.html

<html>
<head>
    <title>Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="heading">Fit Bites</h1>

    <p style="margin-left:60px;font-size:24px;">Eat clean Stay Lean</p>
    <p style="margin-left:60px;font-size:18px;max-width:800px;">
        Fit Bites is a healthy food restaurant concept that focuses on clean, nutritious, and low-calorie meals. It offers diet-friendly options like grilled foods, salads, whole grains, and protein-rich dishes prepared with less oil and no artificial additives. The aim of Fit Bites is to provide tasty food that supports fitness, weight management, and a healthy lifestyle.
    </p>

    <div class="cards">
        <div class="card">
            <img src="img.jpg">
        </div>
        
    </div>

    <div class="footer">
        © R P Mohamed Aathil M - (25008235)
    </div>

</div>
</body>
</html>

Admin.html

<html>
<head>
    <title>Admin</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h2 class="heading">ADMINISTRATION TEAM</h2>

    <div class="cards">
        <div class="card">
            <img src="kiddo.jpg">
            <h3>MD AADHIL</h3>
            <p>CEO</p>
        </div>

        <div class="card">
            <img src="anupama.jpg">
            <h3>ANUPAMA</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="card">
            <img src="Danielle Brown.jpg">
            <h3>Danielle Brown</h3>
            <p>Operations Manager</p>
        </div>

        <div class="card">
            <img src="Ellie Krieger.jpg">
            <h3></h3>
            <p>HR Manager</p>
        </div>

        <div class="card">
            <img src="Gina Homolk.jpg">
            <h3>Gina </h3>
            <p>Executive Manager</p>
        </div>
    </div>


    <div class="footer">
        © R P Mohamed Aathil M - (25008235)
    </div>

</div>
</body>
</html>

menu.html

<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="heading">MENU</h1>

    <div class="cards">
        <div class="card">
            <img src="chicken burito bowl.jpg">
            <h3>Chicken Burito</h3>
            <p>Rs.250</p>
        </div>

        <div class="card">
            <img src="grilled Fish.jpg">
            <h3>Grilled Fish</h3>
            <p>Rs. 300</p>
        </div>

        <div class="card">
            <img src="Tandoori-Chicken.jpg">
            <h3>Tandoori</h3>
            <p>Rs. 150</p>
        </div>

        <div class="card">
            <img src="Fruit-Bowl-with-Yogurt-and-Granola.jpg">
            <h3>Fruit Bowl</h3>
            <p>Rs. 220</p>
        </div>

        <div class="card">
            <img src="Chicken-Stir-Fry.jpg">
            <h3>Chicken Stir Fry</h3>
            <p>Rs. 220</p>
        </div>
    </div>

    <div class="footer">
        © R P Mohamed Aathil M - (25008235)
    </div>

</div>
</body>
</html>

contact.html

<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="heading">CONTACT</h1>

    <div style="margin-left:60px;font-size:20px;background-color: cornsilk;color: brown;">
        <p><b>Visit us at:</b></p>
        <p>Fit Bites<br>
           23,german street,<br>
           nazi state road,koyambedu.<br>
           India</p>

        <p><b>Phone:</b><br>+91 63589 52135</p>
        <p><b>Email ID:</b><br>FitBites@gmail.com</p>
    </div>

    <div class="footer">
       © R P Mohamed Aathil M - (25008235)
    </div>

</div>
</body>
</html>


css


body {
    margin: 0;
    font-family: Georgia, serif;
    background-color: #000;
}


.hero {
    background-image: url("offimg.jpg"); 
    background-size: cover;
    background-position: center;
    min-height: 100vh;
    color: #fff;
    position: relative;
}


.navbar {
    position: absolute;
    top: 20px;
    right: 40px;
    background: #f5f9ff;
    padding: 15px 40px;
    border: 2px solid #000;
}

.navbar a {
    margin: 0 20px;
    text-decoration: underline;
    color: purple;
    font-weight: bold;
}


.heading {
    font-size: 50px;
    color: #023232;
    margin: 120px 0 20px 60px;
    letter-spacing: 4px;
    background-color: blanchedalmond;
}


.cards {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin-top: 40px;
}


.card {
    background: #f8f6dc;
    width: 220px;
    padding: 20px;
    border-radius: 15px;
    text-align: center;
}

.card img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
}


.card h3 {
    margin: 15px 0 5px;
    color: #140101;
}

.card p {
    margin: 0;
    color: #140101;
}


.footer {
    position: absolute;
    bottom: 10px;
    width: 100%;
    text-align: center;
    font-size: 14px;
    color: #140101;
    background-color: burlywood;
}


## OUTPUT:
![alt text](<Screenshot 2025-12-27 092819-1.png>)

![alt text](<Screenshot 2025-12-27 092832.png>)

![alt text](<Screenshot 2025-12-27 092844.png>)

![alt text](<Screenshot 2025-12-27 092855.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
