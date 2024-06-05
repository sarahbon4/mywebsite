# MY Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarah | Graphic Designer</title>
    <style>
        body {
            font-family: 'Helvetica Neue', sans-serif;
            font-weight: 100;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff69b4;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff1493;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #ff69b4;
        }
        section {
            padding: 40px 20px;
            max-width: 800px;
            margin: auto;
        }
        .about-me, .portfolio, .contact {
            background: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #ff1493;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #ff69b4;
            color: white;
        }
    </style>
</head>
<body>

<header>
    <h1>Sarah | Graphic Designer</h1>
</header>

<nav>
    <a href="#about-me">About Me</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about-me" class="about-me">
    <h2>About Me</h2>
    <p>Hi, I'm Sarah, a passionate graphic designer with a flair for creating vibrant and eye-catching designs. With a love for all things Y2K and a keen eye for detail, I strive to bring a fresh and innovative perspective to every project I work on.</p>
</section>

<section id="portfolio" class="portfolio">
    <h2>Portfolio</h2>
    <p>Here are some of my favorite projects:</p>
    <ul>
        <li>Project 1: Description of project 1</li>
        <li>Project 2: Description of project 2</li>
        <li>Project 3: Description of project 3</li>
        <!-- Add more projects as needed -->
    </ul>
</section>

<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>If you'd like to get in touch, please fill out the form below:</p>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br>
        <input type="submit" value="Submit">
    </form>
</section>

<footer>
    <p>&copy; 2024 Sarah. All rights reserved.</p>
</footer>

</body>
</html>
