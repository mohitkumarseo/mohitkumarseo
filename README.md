<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Resume</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
        }
        
        .resume-section {
            display: none;
        }
        
        .active {
            display: block;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#" id="summary-link">Summary</a></li>
                <li><a href="#" id="experience-link">Experience</a></li>
                <li><a href="#" id="education-link">Education</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="summary" class="resume-section active">
        <h2>Summary</h2>
        <p>Write a brief summary about yourself here.</p>
    </section>

    <section id="experience" class="resume-section">
        <h2>Experience</h2>
        <p>Include your work experience details here.</p>
    </section>

    <section id="education" class="resume-section">
        <h2>Education</h2>
        <p>List your educational qualifications here.</p>
    </section>

    <script>
        // JavaScript to toggle sections
        const summaryLink = document.getElementById("summary-link");
        const experienceLink = document.getElementById("experience-link");
        const educationLink = document.getElementById("education-link");
        const summarySection = document.getElementById("summary");
        const experienceSection = document.getElementById("experience");
        const educationSection = document.getElementById("education");

        summaryLink.addEventListener("click", () => {
            summarySection.classList.add("active");
            experienceSection.classList.remove("active");
            educationSection.classList.remove("active");
        });

        experienceLink.addEventListener("click", () => {
            summarySection.classList.remove("active");
            experienceSection.classList.add("active");
            educationSection.classList.remove("active");
        });

        educationLink.addEventListener("click", () => {
            summarySection.classList.remove("active");
            experienceSection.classList.remove("active");
            educationSection.classList.add("active");
        });
    </script>
</body>
</html>

