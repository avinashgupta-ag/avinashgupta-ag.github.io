<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avinash Gupta - Resume</title>
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
            display: none; /* Remove the header */
        }

        .container {
            display: flex;
            justify-content: space-between;
            padding: 20px;
        }

        .left-section {
            width: 30%; /* Adjust as needed */
            margin-right: 20px;
        }

        .right-section {
            width: 70%; /* Adjust as needed */
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .experience {
            margin-bottom: 20px;
        }

        .experience h2 {
            margin-bottom: 10px;
        }

        .experience ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        .experience ul li {
            margin-bottom: 10px;
        }

        .logo-container {
            width: 45%; /* Adjust as needed */
            margin-bottom: 10px;
        }

        .logo-container img {
            width: 100%;
            height: auto;
            cursor: pointer; /* Make logos clickable */
            transition: transform 0.3s ease;
        }

        .logo-container img:hover {
            transform: scale(1.1); /* Enlarge on hover */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-section">
            <!-- Left section content -->
            <div class="experience">
                <h2>Work Experience</h2>
                <ul>
                    <li><img src="axtria.jpg" alt="Axtria Logo" class="logo"></li>
                    <li><img src="Mu-Sigma.jpg" alt="Mu Sigma Logo" class="logo"></li>
                </ul>
            </div>
            <div class="experience">
                <h2>Internship Experience</h2>
                <ul>
                    <li><img src="bain.png" alt="Bain Logo" class="logo"></li>
                    <li><img src="kantar.png" alt="Kantar Logo" class="logo"></li>
                    <li><img src="Menrva.webp" alt="Menrva Logo" class="logo"></li>
                    <li><img src="projectverde.png" alt="Project Verde Logo" class="logo"></li>
                </ul>
            </div>
            <div class="experience">
                <h2>Education</h2>
                <ul>
                    <li><img src="SCMHRD.jpeg" alt="SCMHRD Logo" class="logo"></li>
                    <li><img src="SRM.png" alt="SRM Logo" class="logo"></li>
                </ul>
            </div>
        </div>
        <div class="right-section">
            <!-- Right section content -->
            <div class="portfolio" style="width: 48%;">
                <h2>Portfolio</h2>
                <!-- Portfolio content -->
            </div>
            <div class="resume" style="width: 48%;">
                <h2>Resume</h2>
                <!-- Resume content -->
            </div>
            <div class="contact" style="width: 100%;">
                <h2>Contact Us</h2>
                <!-- Contact content -->
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Avinash Gupta. All rights reserved.</p>
    </footer>
</body>
</html>
