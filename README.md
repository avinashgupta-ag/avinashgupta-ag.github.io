<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avinash Gupta - Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            justify-content: space-between;
            padding: 20px;
        }

        .left-section {
            width: 75%;
            margin-right: 20px;
        }

        .right-section {
            width: 25%;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .section {
            margin-bottom: 20px;
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .resume-link {
            color: blue;
            text-decoration: underline;
            cursor: pointer;
        }

        .resume-link:hover {
            color: purple;
        }

        .logo-container {
            margin-bottom: 10px;
            text-align: center;
        }

        .logo-container img {
            width: 100px;
            height: auto;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .logo-container img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-section">
            <div class="section">
                <h2>Portfolio</h2>
                <!-- Add portfolio content here -->
            </div>
            <div class="section">
                <h2>Resume</h2>
                <p>View my resume:</p>
                <p class="resume-link" onclick="window.open('https://drive.google.com/file/d/1AGNA0EBOOxe64iFeyf4fMO5ag0PJGkSN/view?usp=drive_link', '_blank')">Click here</p>
            </div>
            <div class="section">
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
        <div class="right-section">
            <div class="section">
                <h2>Work Experience</h2>
                <div class="logo-container">
                    <img src="axtria.jpg" alt="Axtria Logo">
                    <img src="Mu-Sigma.jpg" alt="Mu Sigma Logo">
                </div>
            </div>
            <div class="section">
                <h2>Internship Experience</h2>
                <div class="logo-container">
                    <img src="bain.png" alt="Bain Logo">
                    <img src="kantar.png" alt="Kantar Logo">
                    <img src="Menrva.webp" alt="Menrva Logo">
                    <img src="projectverde.png" alt="Project Verde Logo">
                </div>
            </div>
            <div class="section">
                <h2>Education</h2>
                <div class="logo-container">
                    <img src="SCMHRD.jpeg" alt="SCMHRD Logo">
                    <img src="SRM.png" alt="SRM Logo">
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Avinash Gupta. All rights reserved.</p>
    </footer>
</body>
</html>
