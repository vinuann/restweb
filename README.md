# Ex.07 Restaurant Website
## Date:13-05-2025

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - DINE YOUR CRAVE</title>
  <link rel="stylesheet" href="home.css">
</head>
<body>
  <header>
    <h1>Welcome to DINE YOUR CRAVE</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="banner"></div>
  <div class="container">
    <h2>About Us</h2>
    <p>We serve the most delicious food in town using only the freshest ingredients.</p>
  </div>
  <footer>
    <p>Website designed by VINUTHAA NN</p>
  </footer>
</body>
</html>
```
index.css
```
body {
    margin: 0;
    font-family: Ariaurll, sans-serif;
    background-image: url('restaurent\ bg.jpeg');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;
    color: #fff;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  
  .container {
    width: 90%;
    max-width: 800px;
    margin: 30px auto;
    background-color: rgba(0, 0, 0, 0.6); /* semi-transparent bg */
    padding: 20px;
    border-radius: 10px;
  }
  
  header, nav, footer {
    text-align: center;
    padding: 20px;
  }
  
  nav {
    background-color: rgba(255, 255, 255, 0.2);
  }
  
  nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
  }
  
  footer {
    background-color: rgba(0, 0, 0, 0.6);
  }
  ```
  admin.html
  ```<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Administration</title>
<link rel="stylesheet" href="admin.css">
</head>
<body>
<header>
  <h1>Our Team</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <div class="team">
    <!-- Repeat for 6 members -->
    <div class="member">
      <img src="james beard.jpeg" alt="Chef">
      <h3>James beard</h3>
      <p>Head Chef</p>
    </div>
    <div class="member">
      <img src="jane smith.jpg" alt="Chef">
      <h3>Jane Smith</h3>
      <p>Chef</p>
    </div>
    <div class="member">
      <img src="karthikeyan.jpeg" alt="Manager">
      <h3>Karthikeyan</h3>
      <p>Manager</p>
    </div>
    <div class="member">
      <img src="madhampathy.jpeg" alt="Chef">
      <h3>madhampathy</h3>
      <p>Chef</p>
    </div>
    <!-- 4 more -->
  </div>
</div>
<footer>
  <p>Website designed by VINUTHAA NN</p>
</footer>
</body>
</html>
```
admin.css
```body {
  font-family: sans-serif;
  background-color: #f9f9f9;
  margin: 0;
}

header, footer {
  background-color: #8B0000;
  color: white;
  text-align: center;
  padding: 20px 10px;
}

nav {
  background-color: #ddd;
  text-align: center;
  padding: 10px;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: #8B0000;
}

.container {
  padding: 20px;
}

.team {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.member {
  background: white;
  padding: 10px;
  text-align: center;
}

.member img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}
```
menu.html
```<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Menu</title>
<link rel="stylesheet" href="menu.css">
</head>
<body>
<header>
  <h1>Our Menu</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <div class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="item">
      <img src="tandoori.jpeg" alt="tandoori">
      <h3>Chicken Tandoori</h3>
      <p>Rs.300</p>
    </div>
    <div class="item">
      <img src="pizza.webp" alt="Pizza">
      <h3>Pizza</h3>
      <p>Rs.250</p>
    </div>
    <div class="item">
      <img src="pasta.jpg" alt="pasta">
      <h3>Pasta</h3>
      <p>Rs.350</p>
    </div>
    <div class="item">
      <img src="parotta.jpg" alt="parotta">
      <h3>parotta</h3>
      <p>Rs.100</p>
    </div>
    <div class="item">
      <img src="noodles.jpg" alt="noodles">
      <h3>noodles</h3>
      <p>Rs.250</p>
    </div>
    <div class="item">
      <img src="momos.avif" alt="momos">
      <h3>Chicken Momos</h3>
      <p>Rs.150</p>
    </div>
    <div class="item">
      <img src="mexican shawarma.jpg" alt="shawarma">
      <h3>Mexican shawarma</h3>
      <p>Rs.240</p>
    </div>
    <div class="item">
      <img src="french fries.jpeg" alt="French fries">
      <h3>French fries</h3>
      <p>Rs.199</p>
    </div>
    <div class="item">
      <img src="chocolate falooda.jpg" alt="falooda">
      <h3>Chocolate falooda</h3>
      <p>Rs.200</p>
    </div>
    <div class="item">
      <img src="brownie ice cream.jpg" alt="brownie">
      <h3>Brownie ice cream</h3>
      <p>Rs.300</p>
    </div>
    <div class="item">
      <img src="briyani.jpg" alt="briyani">
      <h3>Chicken briyani</h3>
      <p>Rs.350</p>
    </div>
    <!-- Add 10 more -->
  </div>
</div>
<footer>
  <p>Website designed by VINUTHAA NN</p>
</footer>
</body>
</html>
```
menu.css
```body {
  font-family: sans-serif;
  background-color: #fdf6ec;
  margin: 0;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background-color: #eee;
  text-align: center;
  padding: 10px;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: #8B0000;
}

.container {
  padding: 20px;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.item {
  background-color: white;
  padding: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

footer {
  background-color: #8B0000;
  color: white;
  text-align: center;
  padding: 10px;
}
```
contact.html
```<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contact Us</title>
<link rel="stylesheet" href="contact.css">
</head>
<body>
<header>
  <h1>Contact Us</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <h2>Reach Out to Us</h2>
  <p><strong>Address:</strong>Sivalingam nagar Town extension Mayiladuthurai </p>
  <p><strong>Phone:</strong>9363970274</p>
  <p><strong>Email:</strong> dineyourcrave@gmail.com</p>
</div>
<footer>
  <p>Website designed by VINUTHAA NN</p>
</footer>
</body>
</html>
```
contact.css
```body {
  font-family: sans-serif;
  background-color: #f2f2f2;
  margin: 0;
}

header, footer {
  background-color: #8B0000;
  color: white;
  text-align: center;
  padding: 20px;
}

nav {
  background-color: #eee;
  text-align: center;
  padding: 10px;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: #8B0000;
}

.container {
  padding: 30px;
  background-color: white;
  margin: 20px;
  border-radius: 8px;
}
```




## OUTPUT:
![alt text](<vinuthaa/webapp/static/Screenshot 2025-05-13 210349.png>)
![alt text](<vinuthaa/webapp/static/Screenshot 2025-05-13 210247.png>)
![alt text](<vinuthaa/webapp/static/Screenshot 2025-05-13 210223.png>)
![alt text](<vinuthaa/webapp/static/Screenshot 2025-05-13 210150.png>)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
