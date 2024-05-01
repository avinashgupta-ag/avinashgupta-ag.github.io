<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avinash Gupta - Resume</title>
    <link rel="stylesheet" href="styles.css">
    <!-- Include cool-timeline CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/cool-timeline/1.1.3/cool-timeline.min.css">
    <style>
        /* Add your custom styles here */
        /* Existing styles remain unchanged */
    </style>
</head>
<body>
    <header>
        <!-- Header content remains unchanged -->
    </header>
    
    <section id="about">
        <!-- About section content remains unchanged -->
    </section>
    
    <section id="work-experience">
        <h2>Work Experience</h2>
        <!-- Add cool-timeline markup -->
        <div class="cool_timeline">
            <div class="timeline" id="timeline">
                <div class="timeline-month">
                    <h2 class="timeline-month-title">April 2023</h2>
                    <div class="timeline-section">
                        <div class="timeline-date">April 23</div>
                        <div class="timeline-content">
                            <div class="timeline-icon">
                                <i class="fa fa-briefcase"></i>
                            </div>
                            <div class="timeline-title">Summer Associate at Bain & Company</div>
                            <div class="timeline-description">Engaged in the B2C Pricing CoE and utilized Python and ML algorithms for KVI classification in the Retail Domain</div>
                        </div>
                    </div>
                </div>
                <div class="timeline-month">
                    <h2 class="timeline-month-title">March 2022</h2>
                    <div class="timeline-section">
                        <div class="timeline-date">March 2022</div>
                        <div class="timeline-content">
                            <div class="timeline-icon">
                                <i class="fa fa-briefcase"></i>
                            </div>
                            <div class="timeline-title">Associate at Axtria</div>
                            <div class="timeline-description">Contributed to ETL-based projects across 8+ Life Science subject areas within the Business Intelligence Management team</div>
                        </div>
                    </div>
                </div>
                <!-- Add more timeline items as needed -->
            </div>
        </div>
    </section>
    
    <section id="resume">
        <!-- Resume section content remains unchanged -->
    </section>
    
    <section id="portfolio">
        <!-- Portfolio section content remains unchanged -->
    </section>
    
    <section id="contact">
        <!-- Contact section content remains unchanged -->
    </section>   
    
    <footer>
        <!-- Footer content remains unchanged -->
    </footer>

    <!-- Include cool-timeline JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/cool-timeline/1.1.3/cool-timeline.min.js"></script>
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            CoolTimeline.init({
                animation_effect: 'fadeInUp',
                timeline_styles: 'default',
                timeline_scrollbar: 'on',
                timeline_always_mobile: 'on',
            });
        });
    </script>
</body>
</html>
