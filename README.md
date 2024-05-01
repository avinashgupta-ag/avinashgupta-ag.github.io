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

        /* Timeline styles */
        .main-timeline {
            position: relative;
        }

        .main-timeline:before {
            content: "";
            display: block;
            width: 2px;
            height: 100%;
            background: #c6c6c6;
            margin: 0 auto;
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
        }

        .main-timeline .timeline {
            margin-bottom: 40px;
            position: relative;
        }

        .main-timeline .timeline:after {
            content: "";
            display: block;
            clear: both;
        }

        .main-timeline .icon {
            width: 18px;
            height: 18px;
            line-height: 18px;
            margin: auto;
            position: absolute;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
        }

        .main-timeline .icon:before,
        .main-timeline .icon:after {
            content: "";
            width: 100%;
            height: 100%;
            border-radius: 50%;
            position: absolute;
            top: 0;
            left: 0;
            transition: all 0.33s ease-out 0s;
        }

        .main-timeline .icon:before {
            background: #fff;
            border: 2px solid #232323;
            left: -3px;
        }

        .main-timeline .icon:after {
            border: 2px solid #c6c6c6;
            left: 3px;
        }

        .main-timeline .timeline:hover .icon:before {
            left: 3px;
        }

        .main-timeline .timeline:hover .icon:after {
            left: -3px;
        }

        .main-timeline .date-content {
            width: 50%;
            float: left;
            margin-top: 22px;
            position: relative;
        }

        .main-timeline .date-content:before {
            content: "";
            width: 36.5%;
            height: 2px;
            background: #c6c6c6;
            margin: auto 0;
            position: absolute;
            top: 0;
            right: 10px;
            bottom: 0;
        }

        .main-timeline .date-outer {
            width: 125px;
            height: 125px;
            font-size: 16px;
            text-align: center;
            margin: auto;
            z-index: 1;
        }

        .main-timeline .date-outer:before,
        .main-timeline .date-outer:after {
            content: "";
            width: 125px;
            height: 125px;
            margin: 0 auto;
            border-radius: 50%;
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            transition: all 0.33s ease-out 0s;
        }

        .main-timeline .date-outer:before {
            background: #fff;
            border: 2px solid #232323;
            left: -6px;
        }

        .main-timeline .date-outer:after {
            border: 2px solid #c6c6c6;
            left: 6px;
        }

        .main-timeline .timeline:hover .date-outer:before {
            left: 6px;
        }

        .main-timeline .timeline:hover .date-outer:after {
            left: -6px;
        }

        .main-timeline .date {
            width: 100%;
            margin: auto;
            position: absolute;
            top: 27%;
            left: 0;
        }

        .main-timeline .month {
            font-size: 18px;
            font-weight: 700;
        }

        .main-timeline .year {
            display: block;
            font-size: 30px;
            font-weight: 700;
            color: #232323;
            line-height: 36px;
        }

        .main-timeline .timeline-content {
            width: 50%;
            padding: 20px 0 20px 50px;
            float: right;
        }

        .main-timeline .title {
            font-size: 19px;
            font-weight: 700;
            line-height: 24px;
            margin: 0 0 15px 0;
        }

        .main-timeline .description {
            margin-bottom: 0;
        }

        .main-timeline .timeline:nth-child(2n) .date-content {
            float: right;
        }

        .main-timeline .timeline:nth-child(2n) .date-content:before {
            left: 10px;
        }

        .main-timeline .timeline:nth-child(2n) .timeline-content {
            padding: 20px 50px 20px 0;
            text-align: right;
        }

        @media only screen and (max-width: 991px) {
            .main-timeline .date-content {
                margin-top: 35px;
            }
            .main-timeline .date-content:before {
                width: 22.5%;
            }
            .main-timeline .timeline-content {
                padding: 10px 0 10px 30px;
            }
            .main-timeline .title {
                font-size: 17px;
            }
            .main-timeline .timeline:nth-child(2n) .timeline-content {
                padding: 10px 30px 10px 0;
            }
        }

        @media only screen and (max-width: 767px) {
            .main-timeline:before {
                margin: 0;
                left: 7px;
            }
            .main-timeline .timeline {
                margin-bottom: 20px;
            }
            .main-timeline .timeline:last-child {
                margin-bottom: 0;
            }
            .main-timeline .icon {
                margin: auto 0;
            }
            .main-timeline .date-content {
                width: 95%;
                float: right;
                margin-top: 0;
            }
            .main-timeline .date-content:before {
                display: none;
            }
            .main-timeline .date-outer {
                width: 110px;
                height: 110px;
            }
            .main-timeline .date-outer:before,
            .main-timeline .date-outer:after {
                width: 110px;
                height: 110px;
            }
            .main-timeline .date {
                top: 30%;
            }
            .main-timeline .year {
                font-size: 24px;
            }
            .main-timeline .timeline-content,
            .main-timeline .timeline:nth-child(2n) .timeline-content {
                width: 95%;
                text-align: center;
                padding: 10px 0;
            }
            .main-timeline .title {
                margin-bottom: 10px;
            }
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
            <div class="main-timeline">
                <div class="timeline">
                    <div class="icon"></div>
                    <div class="date-content">
                        <div class="date-outer">
                            <span class="date">
                                <span class="month">2 months</span>
                                <span class="year">2023</span>
                            </span>
                        </div>
                    </div>
                    <div class="timeline-content">
                        <h3><img src="png-transparent-logo-bain-company-germany-inc-brand-product-bain-company-logo-text-logo-usc.png" alt="Bain & Company Logo" class="company-logo">
                        Summer Associate          04/23 - 06/23</h3>
                    </div>
                </div>
                <div class="timeline">
                    <div class="icon"></div>
                    <div class="date-content">
                        <div class="date-outer">
                            <span class="date">
                                <span class="month">29 months</span>
                                <span class="year">2022</span>
                            </span>
                        </div>
                    </div>
                    <div class="timeline-content">
                        <h3> <img src="Axtria_Logo.png" alt="Axtria Logo" class="company-logo">
                        Associate                 12/19 - 05/22</h3>
                    </div>
                </div>
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
