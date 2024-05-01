<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avinash Gupta - Resume</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Reset styles */
        body, h1, h2, h3, h4, h5, h6, p, ul, li {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
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
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            margin: 20px 0;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-bottom: 10px;
            font-size: 24px;
            color: #333;
        }

        section p {
            margin-bottom: 10px;
            line-height: 1.6;
        }

        .work-experience {
            overflow-y: auto;
            max-height: 400px;
            padding-right: 20px;
        }

        .timeline {
            position: relative;
            padding-left: 40px;
        }

        .timeline::before {
            content: '';
            position: absolute;
            top: 0;
            left: 20px;
            width: 2px;
            height: 100%;
            background-color: #ccc;
        }

        .timeline-item {
            position: relative;
            padding: 20px 40px;
            margin-bottom: 20px;
            border-radius: 5px;
            background-color: #f9f9f9;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .timeline-item::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 12px;
            transform: translateY(-50%);
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background-color: #333;
        }

        .timeline-item:last-child {
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
        <p>
            Associate with 2.5 years of experience in the Life Sciences and Retail industry. Proficient in technical and functional roles. Completed four internships with reputable MNCs and participated in national-level competitions.
        </p>
        <p>
            Functional Areas:
            <ul>
                <li>Business Analytics</li>
                <li>Data Reconciliation</li>
                <li>ETL Processes</li>
                <li>Business Intelligence (BI)</li>
            </ul>
        </p>
    </section>
    
    <section id="work-experience">
        <h2>Work Experience</h2>
        <div class="work-experience">
            <div class="timeline">
                <div class="timeline-item">
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
                    <h3>Axtria, Gurugram, India</h3>
                    <p>Associate (03/2022 – 05/2022)</p>
                    <ul>
                        <li>Contributed to ETL-based projects across 8+ Life Science subject areas within the Business Intelligence Management team</li>
                        <li>Attained consistent performance exceeding expectations and meeting 99% of the KPIs, resulting in successive promotions</li>
                    </ul>
                </div>
                <div class="timeline-item">
                    <h3>Axtria, Gurugram, India</h3>
                    <p>Analyst (03/2021 – 03/2022)</p>
                    <ul>
                        <li>Developed SQL validation scripts which reduced Data Aggregation process time by 94% to enable weekly sales monitoring</li>
                        <li>Collaborated effectively with 4+ cross-functional teams, business stakeholders, to deliver high-quality solutions</li>
                    </ul>
                </div>
                <div class="timeline-item">
                    <h3>Axtria, Gurugram, India</h3>
                    <p>Trainee Analyst (12/2019 – 03/2021)</p>
                    <ul>
                        <li>Analyzed business logic and performed Data Reconciliation to ensure 0 gaps between legacy and data warehouse system</li>
                        <li>Achieved 87% reduction in TAT of data issues/bug management process during quality assessment phases</li>
                    </ul>
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
        <p>
            Feel free to contact me via email at <a href="mailto:toavinashgupta@gmail.com">toavinashgupta@gmail.com</a> or give me a call at <a href="tel:+919884206218">+91-9884206218</a>. You can also connect with me on <a href="https://www.linkedin.com/in/toavinashgupta">LinkedIn</a>.
        </p>
    </section>

    <footer>
        <p>&copy; 2024 Avinash Gupta. All rights reserved.</p>
    </footer>
</body>
</html>
