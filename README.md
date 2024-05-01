<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avinash Gupta - Resume</title>
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

        .work-experience {
            overflow-x: auto;
            padding-right: 20px;
        }

        .timeline-item {
            position: relative;
            padding: 20px 40px;
            margin-bottom: 40px;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .timeline-item:hover {
            transform: scale(1.02);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .company-logo {
            max-width: 100px;
            height: auto;
            margin-right: 20px;
            transition: transform 0.3s ease;
        }

        .company-logo:hover {
            transform: scale(1.1);
        }

        .logo-container {
            background-color: white;
            display: inline-block;
            padding: 5px; /* Adjust as needed */
            border-radius: 5px; /* Adjust as needed */
            margin-bottom: 10px; /* Adjust as needed */
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
                <li><a href="#about">About</a></li>
                <li><a href="#work-experience">Work Experience</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <div style="text-align: center;">
            <img src="pp1 (3).jpg" alt="Your Photo" style="width: 200px; height: 200px; border-radius: 50%;">
            <p style="font-size: 20px; font-weight: bold; margin-top: 20px;">Hi, I'm Avinash Gupta</p>
        </div>
    </section>
    
    <section id="work-experience">
        <h2>Work Experience</h2>
        <div class="work-experience">
            <div class="timeline">
                <div class="timeline-item">
                    <div class="logo-container">
                        <img src="png-transparent-logo-bain-company-germany-inc-brand-product-bain-company-logo-text-logo-usc.png" alt="Bain & Company Logo" class="company-logo">
                    </div>
                    <h3>Bain & Company, Gurugram, India</h3>
                    <p>Summer Associate (04/2023 – 06/2023)</p>
                    <ul>
                        <li>Engaged in the B2C Pricing CoE and utilized Python and ML algorithms for KVI classification in the Retail Domain</li>
                        <li>Developed 5+ VBA dashboard to assess impact (units/revenue/margin) of shifting to user-recommended price index</li>
                        <li>Streamlined the entire process, enabling the business to generate their own product classification at a half-yearly basis</li>
                        <li>Created a summary deck consisting of 15 slides outlining the methodology, end-to-end process, and actionable insights</li>
                    </ul>
                </div>
                <div class="timeline-item">
                    <div class="logo-container">
                        <img src="Axtria_Logo.png" alt="Axtria Logo" class="company-logo">
                    </div>
                    <h3>Axtria, Gurugram, India</h3>
                    <p>Associate (03/2022 – 05/2022)</p>
                    <ul>
                        <li>Contributed to ETL-based projects across 8+ Life Science subject areas within the Business Intelligence Management team</li>
                        <li>Attained consistent performance exceeding expectations and meeting 99% of the KPIs, resulting in successive promotions</li>
                    </ul>
                </div>
                <!-- Add more timeline items as needed -->
            </div>
        </div>
    </section>
    
    <section id="resume">
        <h2>Resume</h2>
        <p>Download my resume:</p>
        <p><a href="https://drive.google.com/file/d/1AGNA0EBOOxe64iFeyf4fMO5ag0PJGkSN/view?usp=sharing" target="_blank">Download PDF</a></p>
    </section>
    
    <section id="portfolio">
        <h2>Portfolio</h2>
        <!-- Add your portfolio projects here -->
        <!-- Include project descriptions, images, links, etc. -->
    </section>
    <section id="contact">
    <h2>Contact Me</h2>
    <div style="display: flex; align-items: center;">
        <div style="margin-right: 20px;">
            <a href="https://www.linkedin.com/in/toavinashgupta">
                <img src="linkedin_logo.png" alt="LinkedIn" style="width: 30px; height: 30px;">
            </a>
            <span style="margin-left: 5px;">LinkedIn</span>
        </div>
        <div style="margin-right: 20px;">
            <a href="tel:+919884206218">
                <img src="phone_logo.png" alt="Phone" style="width: 30px; height: 30px;">
            </a>
            <span style="margin-left: 5px;">+91-9884206218</span>
        </div>
        <div>
            <a href="mailto:toavinashgupta@gmail.com">
                <img src="email_logo.png" alt="Email" style="width: 30px; height: 30px;">
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
