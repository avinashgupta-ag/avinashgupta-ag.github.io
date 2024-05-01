<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avinash Gupta - Resume</title>
    <!-- Bootstrap CSS -->
    <link href="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
    <!-- Bootstrap JS -->
    <script src="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
    <!-- jQuery -->
    <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Add your custom styles here */
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            position: fixed;
            width: 100%;
            z-index: 1000;
            top: 0;
            left: 0;
            transition: background-color 0.3s ease;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            text-decoration: underline;
            color: #ffd700;
        }

        section {
            padding: 40px;
            margin: 80px 0;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        section:hover {
            transform: scale(1.02);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .static-section {
            position: fixed;
            top: 0;
            right: 0;
            width: 30%;
            height: 100vh;
            overflow-y: auto;
            padding: 20px;
            background-color: #f5f5f5;
            border-left: 1px solid #ccc;
        }

        .static-section h2 {
            margin-top: 0;
        }

        .static-section img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .company-logo {
            max-width: 50px;
            height: auto;
            margin-right: 10px;
        }

        .education-logo {
            max-width: 100px;
            height: auto;
            margin-right: 10px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Avinash Gupta</h1>
        <nav>
            <ul>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="static-section">
        <div style="text-align: center;">
            <img src="pp1 (3).jpg" alt="Your Photo">
            <h2>Avinash Gupta</h2>
            <h3>Work Experience</h3>
            <div class="logo-container">
                <img src="png-transparent-logo-bain-company-germany-inc-brand-product-bain-company-logo-text-logo-usc.png" alt="Bain & Company Logo" class="company-logo">
                <span>Bain & Company</span>
            </div>
            <div class="logo-container">
                <img src="Axtria_Logo.png" alt="Axtria Logo" class="company-logo">
                <span>Axtria</span>
            </div>
            <h3>Internship Experience</h3>
            <!-- Add internship experiences with company logos -->
            <h3>Education</h3>
            <!-- Add education details with college logos -->
        </div>
    </section>
    
    <section id="portfolio">
        <h2>Portfolio</h2>
        <!-- Add your portfolio projects here -->
        <!-- Include project descriptions, images, links, etc. -->
    </section>
    
    <section id="resume">
        <h2>Resume</h2>
        <p>Download my resume:</p>
        <p><a href="https://drive.google.com/file/d/1AGNA0EBOOxe64iFeyf4fMO5ag0PJGkSN/view?usp=sharing" target="_blank">Download PDF</a></p>
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <div style="display: flex; align-items: center;">
            <div style="margin-right: 20px;">
                <a href="https://www.linkedin.com/in/toavinashgupta">
                    <img src="LinkedIn_icon.svg.png" alt="LinkedIn" style="width: 30px; height: 30px;">
                </a>
                <span style="margin-left: 5px;">LinkedIn</span>
            </div>
            <div style="margin-right: 20px;">
                <a href="tel:+919884206218">
                    <img src="green-phone-icon-vector-40526969.jpg" alt="Phone" style="width: 30px; height: 30px;">
                </a>
                <span style="margin-left: 5px;">+91-9884206218</span>
            </div>
            <div>
                <a href="mailto:toavinashgupta@gmail.com">
                    <img src="75c95f7281b1a5adf041f96a07f8a711.jpg" alt="Email" style="width: 30px; height: 30px;">
                </a>
                <span style="margin-left: 5px;">toavinashgupta@gmail.com</span>
            </div>
        </div>
    </section>   
    
    <footer>
        <p>&copy; 2024 Avinash Gupta. All rights reserved.</p>
    </footer>
</body>
</html>
