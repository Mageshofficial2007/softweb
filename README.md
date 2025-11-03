# Ex.07 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
## home.html
```python
<head>=
    <title>SPOT ON</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        header {
            background-color: wheat;
            text-align: center;
            padding: 20px;
        }
        header img {
            width: 50px;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        .banner {
            text-align: right;
            background-image: url('banner.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 50px;
        }
        .banner h2 {
            margin: 0;
        }
        .banner p {
            margin-top: 10px;
        }
        .sections {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            gap: 10px;
        }
        .section {
            background-color: wheat;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            width: 30%;
        }
        .section img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            background-color: white;
            padding: 10px;
            margin-top: 20px;
        }
        footer a {
            text-decoration: none;
            color: blanchedalmond;
        }
    </style>
</head>
<body>

    <header>
        <img src="logo.jpg" alt="HOTSPOT Logo" style="width: 250px; height: auto;">
        <h1>SARA RESTAURANT</h1>
    </header>
    
    

<nav>
  <a href="home.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
  <a href="feedback.html">Feedback</a>
</nav>


<div class="banner">
    <h2>30% Off This Weekend</h2>
    <p>Don't miss out on our special offer! Visit us this weekend and enjoy delicious meals at discounted prices.</p>
</div>

<div class="sections">
    <div class="section">
        <img src="menu.jpg" alt="Menu"style="width: 250px; height: 300px;"> 
        <h3>Our New Menu</h3>
        <p>Explore a variety of mouthwatering dishes crafted to satisfy every taste. From savory appetizers to hearty main courses, there's something for everyone.</p>
        <a href="menu.html">TAKE A LOOK AT OUR MENU</a>
    </div>
    <div class="section">
        <img src="back.jpg" alt="Book a Table"style="width: 250px; height: 300px;"> 
        <h3>Reserve Your Spot</h3>
        <p>Enjoy an unforgettable dining experience at HOTSPOT. Book your table today and treat yourself to a fantastic meal in a cozy ambiance.</p>
        <a href="contacts.html">BOOK NOW</a>
    </div>
    <div class="section">
        <img src="timimg.jpg" alt="Opening Hours"style="width: 250; height: 300px;"> 
        <h3>OPENING HOURS</h3>
        <p>
            MON-THRU:8am- 10pm
            <br>
            FRI-SAT: 10AM- 2pm
            <br>
             SUNDAY CLOSED
        </p>
    </div>
</div>



</body>
<footer>  <p>&copyrights; MAGESH BOOPATHI.M (212224230145)</p></footer>
</html>
```
## menu.html
```python
<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2dfb3; /* beige-like tone */
        }

        header {
            text-align: center;
            background-color: #f2dfb3;
            padding: 20px;
        }

        header img {
            width: 180px;
            border-radius: 10px;
        }

        header h1 {
            font-size: 28px;
            margin: 10px 0 0 0;
            color: black;
        }

        nav {
            background-color: gray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            padding: 30px;
            max-width: 1100px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            margin-top: 20px;
            margin-bottom: 30px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        main h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 30px;
        }

        .menu-list {
            list-style-type: none;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            padding: 0;
        }

        .menu-list li {
            background-color: #f2dfb3;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 250px;
            padding: 15px;
            font-weight: bold;
            color: #333;
        }

        .menu-list img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 10px;
        }

        .menu-list li:hover {
            transform: scale(1.05);
            transition: 0.3s ease;
        }

        footer {
            background-color: #f2dfb3;
            text-align: center;
            padding: 15px;
            color: black;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.jpg" alt="logo">
    <h1>SARA RESTAURANT</h1>
</header>


<nav>
  <a href="home.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
  <a href="feedback.html">Feedback</a>
</nav>


<main>
    <h2>AVAILABLE MENU ITEMS</h2>
    <ul class="menu-list">
        <li><img src="briyani.jpg" alt="Biryani">Biryani - $30</li>
        <li><img src="spring.jpg" alt="Spring Rolls">Spring Rolls - $8</li>
        <li><img src="butter.jpg" alt="Butter Chicken">Butter Chicken - $12</li>
        <li><img src="crab.jpg" alt="Crab Curry">Crab Curry - $7</li>
        <li><img src="lobster.jpg" alt="Lobster">Lobster - $15</li>
        <li><img src="mutton.jpg" alt="Mutton Curry">Mutton Curry - $15</li>
        <li><img src="fish barbeque.jpg" alt="Fish Barbeque">Fish Barbeque - $26</li>
        <li><img src="grill chicken.jpg" alt="Full Grill Chicken">Full Grill Chicken - $50</li>
        <li><img src="tandoori.jpg" alt="Tandoori">Tandoori - $16</li>
    </ul>
</main>

<footer>
    © Rights; MAGESH BOOPATHI.M (212224230145)
</footer>

</body>
</html>

```
## administation.html
```python
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Administration - SARA RESTAURANT</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: white;
    }

    header {
      background-color: #f2d7b0;
      text-align: center;
      padding: 20px 0;
    }

    header img {
      width: 150px;
      border-radius: 8px;
    }

    header h1 {
      margin: 10px 0;
      font-size: 2rem;
    }

    nav {
      background-color: grey;
      text-align: center;
      padding: 10px 0;
    }

    nav a {
      text-decoration: none;
      color: white;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: lightcoral;
    }

    main {
      text-align: center;
      padding: 60px 20px;
      background-color: #fff8ef;
    }

    .admin-image {
      width: 200px;
      height: 250px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      margin-bottom: 40px;
    }

    .admin-content {
      max-width: 800px;
      margin: auto;
      background-color: #f2d7b0;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    .admin-content h2 {
      color: #333;
      margin-bottom: 20px;
    }

    .admin-content p {
      color: #333;
      font-size: 1.1rem;
      line-height: 1.8;
    }

    footer {
      text-align: center;
      background-color: #f2d7b0;
      padding: 10px;
      margin-top: 50px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.jpg" alt="Sara's Kitchen Logo">
    <h1>SARA RESTAURANT</h1>
  </header>

<nav>
  <a href="home.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
  <a href="feedback.html">Feedback</a>
</nav>

  <main>
    <img src="my image.jpg" alt="Administration" class="admin-image">

    <div class="admin-content">
      <h2>FOUNDER OF SARA RESTAURANT</h2>
      <p>
        Welcome to the Administration Panel of <b>Sara Restaurant</b>.  
        Here, authorized staff can manage the restaurant’s daily operations — including updating menu items, monitoring customer feedback, managing reservations, and reviewing staff performance.  
      </p>
      <p>
        The administration section ensures that the restaurant runs smoothly and maintains the highest level of service for our customers.
      </p>
    </div>
  </main>

  <footer>
    © Rights; MAGESH BOOPATHI.M (212224230145)
  </footer>
</body>
</html>

```
## contact.html
```python
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact & Book a Table - SARA RESTAURANT</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f2dfb3;
    }

    header {
        text-align: center;
        background-color: #f2dfb3;
        padding: 20px;
    }

    header img {
        width: 180px;
        border-radius: 10px;
    }

    header h1 {
        font-size: 28px;
        margin: 10px 0 0 0;
        color: black;
    }

    nav {
        background-color: gray;
        color: white;
        display: flex;
        justify-content: center;
        padding: 10px 0;
    }

    nav a {
        text-decoration: none;
        color: white;
        margin: 0 15px;
        font-weight: bold;
    }

    nav a:hover {
        text-decoration: underline;
    }

    main {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 30px;
        padding: 30px;
        max-width: 1200px;
        margin: auto;
    }

    .contact-box, .book-box {
        background-color: white;
        padding: 30px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        flex: 1 1 400px;
        min-width: 300px;
    }

    h2 {
        text-align: center;
        color: darkslateblue;
        margin-bottom: 20px;
    }

    address {
        font-style: normal;
        color: #333;
        line-height: 1.8;
        text-align: center;
        font-size: 1rem;
    }

    form label {
        display: block;
        margin-top: 10px;
        font-weight: bold;
    }

    form input, form select, form textarea {
        width: 100%;
        padding: 8px;
        margin-top: 5px;
        border-radius: 5px;
        border: 1px solid #ccc;
        box-sizing: border-box;
    }

    form textarea {
        resize: vertical;
    }

    form button {
        margin-top: 15px;
        padding: 10px 20px;
        background-color: darkslateblue;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-weight: bold;
    }

    form button:hover {
        background-color: slateblue;
    }

    footer {
        background-color: #f2dfb3;
        text-align: center;
        padding: 15px;
        color: black;
        font-weight: bold;
    }

    @media (max-width: 800px) {
        main {
            flex-direction: column;
            align-items: center;
        }
    }
</style>
</head>
<body>
<header>
    <img src="logo.jpg" alt="logo">
    <h1>SARA RESTAURANT</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a> <!-- Make sure this matches the file name exactly -->
    <a href="feedback.html">Feedback</a>
</nav>

<main>
    <!-- Contact Section -->
    <div class="contact-box">
        <h2>Contact Us</h2>
        <p>VISIT US AT💐🫶🏻:</p>
        <address>
            SARA RESTAURANT<br>
            143,ANNA NAGAR,<br>
            CHENGAM,<br>
            TIRUVANNAMALAI-606709<BR>
            Phone:(+91) 987-456-1230<br>
            Email:sararestaurant1321@gmail.com
        </address>
    </div>

    <div class="book-box">
        <h2>Book a Table</h2>
        <form action="#" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="date">Date:</label>
            <input type="date" id="date" name="date" required>

            <label for="time">Time:</label>
            <input type="time" id="time" name="time" required>

            <label for="guests">Number of Guests:</label>
            <select id="guests" name="guests" required>
                <option value="">Select</option>
                <option value="1">1 Person</option>
                <option value="2">2 People</option>
                <option value="3">3 People</option>
                <option value="4">4 People</option>
                <option value="5">5 People</option>
                <option value="6+">6 or more</option>
            </select>

            <label for="message">Additional Notes:</label>
            <textarea id="message" name="message" rows="3"></textarea>

            <button type="submit">Confirm Booking</button>
        </form>
    </div>
</main>

<footer>
    © Rights; MAGESH BOOPATHI.M (212224230145)
</footer>

</body>
</html>

```
## feedback.html
```python
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feedback - SARA RESTAURANT</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2dfb3; /* beige tone */
    }

    /* HEADER */
    header {
      text-align: center;
      background-color: #f2dfb3;
      padding: 20px;
    }

    header img {
      width: 180px;
      border-radius: 10px;
    }

    header h1 {
      font-size: 28px;
      margin: 10px 0 0 0;
      color: black;
    }

    /* NAVIGATION BAR */
    nav {
      background-color: gray;
      color: white;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      text-decoration: none;
      color: white;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* MAIN CONTENT */
    main {
      padding: 30px;
      max-width: 700px;
      margin: 40px auto;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    main h2 {
      text-align: center;
      color: darkslateblue;
      margin-bottom: 30px;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    label {
      font-weight: bold;
      color: #333;
      text-align: left;
    }

    input, textarea, select {
      padding: 10px;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    textarea {
      resize: none;
      height: 120px;
    }

    button {
      background-color: gray;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
      font-weight: bold;
    }

    button:hover {
      background-color: darkslategray;
    }

    footer {
      background-color: #f2dfb3;
      text-align: center;
      padding: 15px;
      color: black;
      font-weight: bold;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <img src="logo.jpg" alt="logo">
  <h1>SARA RESTAURANT</h1>
</header>

<nav>
  <a href="home.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="administration.html">Administration</a>
  <a href="contact.html">Contact Us</a>
  <a href="feedback.html">Feedback</a>
</nav>

<main>
  <h2>We Value Your Feedback</h2>

  <form>
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required>

    <label for="email">Email Address:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required>

    <label for="rating">Rate Your Experience:</label>
    <select id="rating" name="rating" required>
      <option value="">Select Rating</option>
      <option value="5">⭐⭐⭐⭐⭐ Excellent</option>
      <option value="4">⭐⭐⭐⭐ Good</option>
      <option value="3">⭐⭐⭐ Average</option>
      <option value="2">⭐⭐ Poor</option>
      <option value="1">⭐ Very Poor</option>
    </select>

    <label for="message">Your Feedback:</label>
    <textarea id="message" name="message" placeholder="Write your comments here..." required></textarea>

    <button type="submit">Submit Feedback</button>
  </form>
</main>

<footer>
  © Rights; MAGESH BOOPATHI.M (212224230145)
</footer>

</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-11-03 231150.png>)
![alt text](<Screenshot 2025-11-03 231313.png>)
![alt text](<Screenshot 2025-11-03 231033.png>)
![alt text](<Screenshot 2025-11-03 230812.png>)
![alt text](<Screenshot 2025-11-03 230912.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
