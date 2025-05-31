<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  
  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <script src="https://c.webfontfree.com/c.js?f=Playmaker-Script" type="text/javascript"></script>
  <link href="https://fonts.cdnfonts.com/css/blackbracelet" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  
  <!-- Internal Styles -->
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

    @font-face {
      font-family: 'rastanty-cortez';
      src: url('/fonts/rastanty-cortez.woff2') format('woff2'),
           url('/fonts/rastanty-cortez.woff') format('woff'),
           url('/fonts/rastanty-cortez.ttf') format('truetype');
    }

    /* General Page Settings */
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #fdfdfb;
      color: #333333;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    /* Navbar */
    nav {
      position: fixed;
      width: 25%;
      background-color: #c27ba0;
      height: 100vh;
      overflow: auto;
    }
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }
    nav li a {
      display: block;
      color: #000;
      padding: 8px 16px;
      text-decoration: none;
    }
    nav li a:hover {
      background-color: #ffe6e1;
    }

    /* Section Layouts */
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: 0 auto;
      background-color: #ffffff;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
      margin-bottom: 30px;
    }

    /* Headings */
    h1, h2, h3, h4 {
      color: #c27ba0;
      font-weight: 300;
      font-family: 'rastanty-cortez', cursive;
    }
    h2 {
      font-size: 2rem;
      border-bottom: 2px solid #ffe6e1;
      padding-bottom: 5px;
      margin-bottom: 20px;
    }
    h3 {
      margin-top: 20px;
    }
    h4 {
      margin-top: 15px;
    }

    /* Lists */
    ul {
      list-style-type: disc;
      padding-left: 20px;
      margin-top: 10px;
    }
    li {
      margin-bottom: 8px;
    }

    /* Buttons */
    button, .button {
      background-color: #c27ba0;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      font-weight: 600;
      transition: background-color 0.3s ease;
      cursor: pointer;
    }
    button:hover, .button:hover {
      background-color: #a35f88;
    }
    button a {
      color: white;
      text-decoration: none;
    }
    button a:hover {
      text-decoration: none;
    }

    /* Links */
    a {
      color: #a39ec9;
      text-decoration: none;
      font-weight: 500;
    }
    a:hover {
      color: #8e86c5;
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <nav>
    <div class="logo">
      <img src="ChatGPT Image Apr 26, 2025, 01_19_26 PM.png" alt="Logo" width="100%">
    </div>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <main style="margin-left:25%;padding:1px 16px;height:1000px;">
    <section id="home">
      <h2>Hi, I'm Michelle</h2>
      <p>Learning to build, design, and grow — one step at a time.</p>
      <button><a href="Michelle Bennett-CV.html" target="_blank">View My CV</a></button>
    </section>

 <section id="about">
      <h2>About Me</h2>
      <p>Hi, I’m Michelle — a creative and determined individual from Randburg, South Africa. I've always had a love for art and design, bringing ideas to life using simple tools like PowerPoint, drawing, and now, web development.</p>
      <p>After caring for a loved one, I realized how much I want to grow, learn, and create freely. While I’ve faced personal challenges like anxiety, depression, and learning differences, they’ve made me more empathetic, resilient, and driven.</p>
      <p>I’m currently building my skills in web development and design through hands-on projects. Every line of code and design choice is a step toward becoming the person I know I can be — confident, capable, and proud of my journey.</p>
      <p>If you’re looking for someone who learns through doing, brings creativity to their work, and builds with heart — that’s me.</p>
    </section>

   <section id="projects">
      <h2>Projects</h2>

 <h3>Web Development</h3>
      <ul>
        <li><a href="https://github.com/MLB1996/website1" target="_blank">Website 1</a> – Basic webpage structure, images, and first CSS experiments.</li>
        <li><a href="https://github.com/MLB1996/website-2" target="_blank">Website 2</a> – Multi-page site with navigation and consistent styling.</li>
        <li><a href="https://github.com/MLB1996/customer-survey" target="_blank">Customer Survey</a> – Interactive online survey form (HTML forms & accessibility).</li>
        <li><a href="https://github.com/MLB1996/The-Gastby-Grande" target="_blank">The Grande Gatsby</a> – Fictional luxury hotel website (HTML, CSS, visual branding).</li>
      </ul>

 <h3>Graphic Design</h3>
      <!-- You can add graphic design projects here later -->
    </section>

 <section id="skills">
      <h2>Skills</h2>

 <h3>Technical Skills</h3>

 <h4>Web Development:</h4>
      <ul>
        <li>HTML5 – Comfortable creating basic page structures and forms.</li>
        <li>CSS3 – Able to apply simple styling, color schemes, fonts, and spacing.</li>
        <li>Responsive Design – Learning to make layouts adapt to different screen sizes.</li>
        <li>Forms & Input Elements – Created simple surveys and feedback forms.</li>
      </ul>

 <h4>Tools & Platforms:</h4>
      <ul>
        <li>Git – Basic understanding of version control and saving project versions.</li>
        <li>GitHub – Able to upload and manage simple code repositories.</li>
        <li>VS Code – Comfortable editing and organizing HTML/CSS files.</li>
      </ul>

   <h3>Creative & Design Skills</h3>

 <h4>Graphic Design:</h4>
      <ul>
        <li>Adobe Photoshop (Foundational) – Basic photo editing, layering, and creating visuals with mood and tone in mind.</li>
        <li>Adobe Illustrator (Beginner) – (You can continue this description...)</li>
      </ul>
    </section>

 <section id="contact">
      <h2>Contact</h2>
    
 </section>
  </main>
</body>
</html>
