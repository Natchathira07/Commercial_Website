# Ex02 Commercial Website
## Date: 24.02.2026

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

## contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Us - Stella Sip Station</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to right, #141e30, #243b55);
            color: white;
            text-align: center;
        }

        h1 {
            padding-top: 30px;
        }

        .contact-box {
            background: white;
            color: black;
            width: 400px;
            margin: 40px auto;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0px 10px 25px rgba(0,0,0,0.4);
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 8px;
            border: 1px solid #ccc;
        }

        button {
            background: #6a0572;
            color: white;
            border: none;
            padding: 10px 25px;
            border-radius: 20px;
            cursor: pointer;
        }

        button:hover {
            background: #9c27b0;
        }

        a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>

<body>

<h1>📞 Contact Stella Sip Station</h1>

<div class="contact-box">
    <form action="visit.html">
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="4" placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

<p><a href="index.html">⬅ Back to Home</a></p>

</body>
</html>
```
## welcome.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Stella Sip Station</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to right, #2c003e, #6a0572);
            color: white;
            text-align: center;
        }

        header {
            padding: 40px;
        }

        header h1 {
            font-size: 45px;
            letter-spacing: 2px;
        }

        header p {
            font-size: 18px;
            opacity: 0.9;
        }

        .hero {
            background-image: url("https://images.unsplash.com/photo-1462331940025-496dfbfc7564");
            background-size: cover;
            background-position: center;
            padding: 120px 20px;
        }

        .hero h2 {
            font-size: 50px;
            background: rgba(0,0,0,0.6);
            display: inline-block;
            padding: 15px 30px;
            border-radius: 10px;
        }

        footer {
            padding: 20px;
            background: #1a001f;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>✨ Stella Sip Station ✨</h1>
    <p>Cosmic. Dreamy. Delicious.</p>
</header>

<section class="hero">
    <h2>Explore the Universe of Flavors</h2>
</section>

<footer>
    © 2026 Stella Sip Station | Designed with 💜 by Natchathira
</footer>

</body>
</html>
```
## visit.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Thank You - Stella Sip Station</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            text-align: center;
            color: white;
        }

        header {
            background: linear-gradient(to right, #3a0ca3, #f72585);
            padding: 25px;
            font-size: 20px;
            font-weight: bold;
        }

        .hero {
            background-image: url("https://images.unsplash.com/photo-1462331940025-496dfbfc7564");
            background-size: cover;
            background-position: center;
            padding: 150px 20px;
            position: relative;
        }

        /* Dark overlay like your screenshot */
        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
        }

        .content {
            position: relative;
            z-index: 1;
        }

        h1 {
            font-size: 50px;
            margin-bottom: 15px;
        }

        p {
            font-size: 20px;
            opacity: 0.9;
        }

        .btn {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 30px;
            background: #f72585;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ff4da6;
            transform: scale(1.05);
        }

        footer {
            background: #1a001f;
            padding: 15px;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    ✨ Stella Sip Station ✨
</header>

<section class="hero">
    <div class="content">
        <h1>💜 Thank You for Visiting!</h1>
        <p>Your journey through the cosmos of flavors means the world to us ✨</p>
        <p>We can't wait to serve you again!</p>

        <a href="index.html" class="btn">Back to Home</a>
    </div>
</section>

<footer>
    © 2026 Stella Sip Station | See You Again 🌟
</footer>

</body>
</html>
```

## OUTPUT
<img width="1919" height="1085" alt="Screenshot 2026-02-23 155649" src="https://github.com/user-attachments/assets/3111528f-b3e0-4766-aeba-3be8db9cdd56" />

<img width="1919" height="942" alt="Screenshot 2026-02-23 155733" src="https://github.com/user-attachments/assets/e838e3ef-b0b7-4ab8-ad40-a03b9036699e" />

<img width="1914" height="1083" alt="image" src="https://github.com/user-attachments/assets/c66e0e12-e900-4448-8a1f-506a178b8ef8" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
