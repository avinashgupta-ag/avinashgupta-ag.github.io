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

        /* Bootstrap 5 Timeline */
        .experience {
            font-family: 'Poppins', sans-serif;
        }

        .section-title h4 {
            color: #222;
            font-size: 30px;
            font-weight: 700;
            margin-bottom: 10px;
        }

        .section-title p {
            color: #555;
            margin-bottom: 0;
        }

        .timeline-list {
            padding: 0;
            margin-top: 40px;
            list-style: none;
            position: relative;
        }

        .timeline-list:before {
            content: '';
            background: #222;
            width: 4px;
            height: 100%;
            position: absolute;
            left: 50%;
            top: 0;
            transform: translateX(-50%);
        }

        .timeline-list li {
            margin-bottom: 50px;
            position: relative;
        }

        .timeline-list li:last-child {
            margin-bottom: 0;
        }

        .timeline_content {
            padding-left: 50px;
        }

        .timeline_content span {
            display: block;
            color: #666;
            font-size: 18px;
            font-weight: 500;
            margin-bottom: 10px;
        }

        .timeline_content h4 {
            color: #222;
            font-size: 24px;
            font-weight: 600;
            margin-bottom: 10px;
        }

        .timeline_content p {
            color: #666;
            margin-bottom: 0;
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
            <section class="experience pt-100 pb-100" id="experience">
                <div class="container">
                    <div class="row">
                        <div class="col-xl-8 mx-auto text-center">
                            <div class="section-title">
                                <h4>bootstrap 5 timeline</h4>
                                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                       <div class="col-xl-12">
                          <ul class="timeline-list">
                             <!-- Single Experience -->
                             <li>
                                <div class="timeline_content">
                                   <span>2008</span>
                                   <h4>Intern Developer span</h4>
                                   <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                                </div>
                             </li>
                             <!-- Single Experience -->
                             <li>
                                <div class="timeline_content">
                                <span>2007-2012</span>
                                   <h4>Junior Developer</h4>
                                   <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                                </div>
                             </li>
                             <!-- Single Experience -->
                             <li>
                                <div class="timeline_content">
                                <span>2012-2015</span>
                                   <h4>Senior Developer</h4>
                                   <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                                </div>
                             </li>
                             <!-- Single Experience -->
                             <li>
                                <div class="timeline_content">
                                <span>2015-2018</span>
                                   <h4>Project Manager</h4>
                                   <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                                </div>
                             </li>
                          </ul>
                       </div>
                    </div>
                </div>
              </section>
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
