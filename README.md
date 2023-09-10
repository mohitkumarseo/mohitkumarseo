
<!DOCTYPE html>
<html>
<head>
<title>SEO Analyst Resume</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: sans-serif;
}

.resume {
  width: 100%;
  max-width: 500px;
  margin: 0 auto;
}

.section {
  margin-top: 20px;
}

.section h2 {
  font-size: 18px;
  margin-bottom: 10px;
}

.section p {
  font-size: 16px;
}

.skills ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.skills li {
  margin-bottom: 10px;
}

.skills li a {
  color: #333;
}

.dynamic-content {
  display: none;
}

.btn-show {
  background-color: #333;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
}
</style>
</head>
<body>
<div class="resume">
  <section>
    <h2>Personal Information</h2>
    <p>John Doe</p>
    <p>123 Main Street</p>
    <p>Anytown, CA 12345</p>
    <p>john.doe@email.com</p>
    <p>(123) 456-7890</p>
  </section>
  <section>
    <h2>Education</h2>
    <p>Stanford University</p>
    <p>Bachelor of Science in Computer Science</p>
    <p>2023</p>
  </section>
  <section>
    <h2>Work Experience</h2>
    <p>
      SEO Analyst
      <br>
      Acme Corporation
      <br>
      January 2023 - Present
    </p>
    <p>
      Performed SEO audits for client websites, conducted research on competitors, identified keyword optimization opportunities, and provided recommendations to enhance web page sitemaps, resulting in a 60%-120% increase in organic traffic for customers.
    </p>
  </section>
  <section>
    <h2>Skills</h2>
    <ul class="skills">
      <li><a href="#">HTML</a></li>
      <li><a href="#">CSS</a></li>
      <li><a href="#">JavaScript</a></li>
      <li><a href="#">Python</a></li>
      <li><a href="#">SQL</a></li>
      <li><a href="#">Google Analytics</a></li>
      <li><a href="#">SEMrush</a></li>
      <li><a href="#">Ahrefs</a></li>
    </ul>
  </section>
  <section>
    <h2>Show More</h2>
    <button class="btn-show">Show More</button>
  </section>
</div>

<script>
var skills = document.querySelector(".skills");
var showMoreButton = document.querySelector(".btn-show");

showMoreButton.addEventListener("click", function() {
  skills.classList.toggle("show");
});
</script>
</body>
</html>
