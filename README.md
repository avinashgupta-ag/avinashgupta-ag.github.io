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

        .container {
            padding: 20px;
        }

        .section {
            margin-bottom: 40px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .section:hover {
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

        .logo-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            grid-gap: 20px;
        }

        .company-logo,
        .internship-logo,
        .education-logo {
            max-width: 100px;
            height: auto;
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
    <div class="static-section">
        <h2>Avinash Gupta</h2>
        <h3>Work Experience</h3>
        <div class="logo-grid">
            <img src="axtria.jpg" alt="Axtria Logo" class="company-logo">
            <img src="Mu-Sigma.jpg" alt="Mu-Sigma Logo" class="company-logo">
        </div>
        
        <h3>Internship Experience</h3>
        <div class="logo-grid">
            <img src="bain.png" alt="Bain & Company Logo" class="internship-logo">
            <img src="kantar.png" alt="Kantar Logo" class="internship-logo">
            <img src="Menrva.webp" alt="Menrva Logo" class="internship-logo">
            <img src="projectverde.png" alt="Project Verde Logo" class="internship-logo">
        </div>
        
        <h3>Education</h3>
        <div class="logo-grid">
            <img src="SCMHRD.jpeg" alt="SCMHRD Logo" class="education-logo">
            <img src="SRM.png" alt="SRM Logo" class="education-logo">
        </div>
    </div>
    
    <div class="container">
        <section id="portfolio" class="section">
            <h2>Portfolio</h2>
            <!-- Portfolio Section Content -->
        </section>
        
        <section id="resume" class="section">
            <h2>Resume</h2>
            <!-- Resume Section Content -->
        </section>
        
        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <!-- Contact Section Content -->
        </section>
    </div>   
    
    <footer>
        <p>&copy; 2024 Avinash Gupta. All rights reserved.</p>
    </footer>
</body>
</html>
