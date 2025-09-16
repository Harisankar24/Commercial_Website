# Ex02 Commercial Website
## Date:8-09-2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Company</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
    <div class="logo">Sports Company</div>
    <nav>
      <ul class="nav-links">
        <li><a href="#index.html">Home</a></li>
        <li><a href="#product.html">Products</a></li>
        <li><a href="#about.html">About Us</a></li>
        <li><a href="#contact.html">Contact</a></li>
        <li><a href="#user.html">Account</a></li>
      </ul>
    </nav>
  </header>
  <!-- Home page -->
   <section class="homepage">
    <div class="page1">
    <h1>Welcome to Sports Company</h1><br><br>
    <p>Your Next Favorite Gadget Awaits</p>
    <p>Quality,Performance,and style - all in one place.</p>
    <p>Your one-stop solution for quality products and services.</p>
    <button class="btu">shop now</button>
    </div>
   </section>
   <!-- product page -->

   <div class="page3">
    <h1 id="hea">Our Products</h1>
    <section class="page2">
        
        <div>
            <img class="img1" src="bat1.jpg"><br>
            <h2>Bat</h2>
            <p>Stay paly and healhty with our latest bat.</p>
            <button class="btu">Add to Cart</button><br><br>
            <button class="btu">See Details</button>
        </div>
        <div>
            <img class="img1" src="cricket-equipment-digital-art.jpg"><br>
            <h2>Bat & Ball</h2>
            <p>Stay paly and healhty with our latest bat.</p>
            <button class="btu">Add to Cart</button><br><br>
            <button class="btu">See Details</button>
        </div>
        <div>
            <img class="img1" src="ball1.jpg"><br>
            <h2>Ball</h2>
            <p>Stay paly and healhty with our latest bat.</p>
            <button class="btu">Add to Cart</button><br><br>
            <button class="btu">See Details</button>
        </div>
    </section>
    </div>

    <!-- About page -->

    <div class="aboutpage">
        <h2>About Us</h2>
        <p>Welcome to Sports Company, where passion meets performance. We are more than just a sports company — we are a team of athletes, enthusiasts, and innovators dedicated to empowering every individual to achieve their best on and off the field.</p>
        <p>Our mission to inspire people of all ages to stay active, embrace sportsmanship, and unlock their true potential through reliable products and services.</p>
        <p>Our story founded with the vision to make sports accessible to all, we started our journey by creating high-quality gear for local teams. Over the years, we’ve grown into a trusted name in the sports industry, serving athletes, fitness lovers, and professionals worldwide.</p>
        <h2>Why choose sports company?</h2>
        <ul>
            <li>Excellence – Delivering top-quality gear that meets global standards.</li>
            <li>Integrity – Building trust with transparency and commitment.</li>
            <li>Passion – Fueling the love for sports in everything we do.</li>
            <li>Teamwork – Growing stronger together with athletes, partners, and communities.</li>
        </ul>
        <p>Join the sports company family today and explore a world where technology meets trust.</p>
    </div>

    <!-- contact page -->

    <div class="conactpage">
        <div class="con">
        <h2>Contact Us</h2>

        <h4>Email:harisankar34@gmail.com | Phone: +91 5498759578</h4>
        </div>
        <div class="use">
            <h2>User Account</h2>
            <a id="a" href="#Login">Login</a>
            <a href="#"> Sign up</a>
            <h3>Sign up with google</h3>
            <a href="https://accounts.google.com/signin" target="_blank" rel="noopener noreferrer" style="display: inline-block; margin-top: 15px;">
          <img src="data:image/png;base64,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" 
              alt="Google Sign Up" width="60" height="60" style="cursor: pointer;" />
        </a>
        <p style="margin-top: 10px;"><a href="#account" style="color: #888;">Close</a></p>
        <br><br>
        </div>
        <footer>
    
            <p>&copy; 2025 FlexCommerce. All rights reserved.</p>
        </footer>
    </div>

    <!-- user page -->

    <div class="userpage">
        <div class="user1">
        <h2>User Account</h2>
        <a id="a" href="#Login">Login</a>
        <a href="#"> Sign up</a>
        </div>
        <div class="form1">
            <h4>Login</h4>
            <form>
                <label>Name</label><br><br>
                <input type="text"><br><br>
                <label type="Password">Password</label><br><br>
                <input><br><br>
                <label>Mobile number</label><br><br>
                <input type="number"><br><br>
                <label>Email</label><br><br>
                <input type="email"><br><br>
                <label>Address</label><br><br>
                <textarea></textarea><br><br>
                <button class="btu">Sumit</button>
            </form>
        </div>
    </div>
    
</body>
</html>
```

## OUTPUT

![alt text](image.png)

![alt text](image-1.png)

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)
## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
