<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digvijay Jakhaniya - GitHub Profile</title>
  <!-- <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> -->
  <style>
    /* Add your custom CSS styles here */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f5f5;
      color: #333;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      position: relative;
      overflow: hidden;
    }
    h1, h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }
    p {
      text-align: center;
      margin-bottom: 30px;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-bottom: 30px;
    }
    .skills img {
      margin: 5px;
      filter: grayscale(50%);
      transition: filter 0.3s ease;
    }
    .skills img:hover {
      filter: none;
    }
    .social-links {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
    .social-links a {
      margin: 0 10px;
      color: #333;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    .social-links a:hover {
      color: #007bff;
    }
    .stats {
      display: flex;
      justify-content: space-around;
      margin-bottom: 30px;
    }
    .stats div {
      text-align: center;
    }
    .stats i {
      font-size: 24px;
      color: #007bff;
      margin-bottom: 10px;
    }
    .stats span {
      display: block;
    }
    .background-circle {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background-color: rgba(0, 123, 255, 0.1);
      width: 400px;
      height: 400px;
      border-radius: 50%;
      z-index: -1;
      animation: float 5s infinite alternate;
    }
    @keyframes float {
      0% {
        transform: translate(-50%, -50%) scale(1);
      }
      100% {
        transform: translate(-50%, -50%) scale(1.1);
      }
    }
    .github-calendar {
      margin-top: 50px;
      overflow: hidden;
    }
    .github-calendar iframe {
      border: none;
      width: 100%;
      height: 600px;
      transform: scale(0.8);
      transform-origin: 0 0;
      transition: transform 0.5s ease;
    }
    .github-calendar:hover iframe {
      transform: scale(1);
    }
    .projects {
      margin-top: 50px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .project {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      margin: 20px;
      padding: 20px;
      width: 300px;
      transition: transform 0.3s ease;
    }
    .project:hover {
      transform: translateY(-5px);
    }
    .project h3 {
      margin-top: 0;
    }
    .project p {
      color: #777;
    }
  </style>
</head>
<body>

  <div class="background-circle"></div>

  <div class="container">
    <h1>Hello! I’m Digvijay Jakhaniya 👋</h1>
    
    <p>As a creative web developer with project-based experience, I can help you develop your website.<br><br>I like to craft solid and scalable Fullstack products with great user experiences. I use my passion and skills to develop websites for different agencies and companies. I have expertise in various languages like CSS, HTML, React.js, Flutter, PHP, and many more. Always ready to enhance skills and expertise in different domains.</p>

    <h2>Skills</h2>
    
    <div class="skills">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5 logo">
      <img src="https://cdn.simpleicons.org/css3/1572B6" height="40" alt="CSS3 logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript logo">
      <img src="https://cdn.simpleicons.org/php/777BB4" height="40" alt="PHP logo">
      <img src="https://cdn.simpleicons.org/laravel/FF2D20" height="40" alt="Laravel logo">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="React logo">
      <img src="https://cdn.simpleicons.org/flutter/02569B" height="40" alt="Flutter logo">
      <img src="https://cdn.simpleicons.org/mysql/4479A1" height="40" alt="MySQL logo">
      <img src="https://cdn.simpleicons.org/mongodb/47A248" height="40" alt="MongoDB logo">
    </div>  

    <!-- <div class="stats">
      <div>
        <i class="fas fa-code"></i>
        <span>Over 5 years of coding experience</span>
      </div>
      <div>
        <i class="fas fa-project-diagram"></i>
        <span>Worked on 50+ projects</span>
      </div>
      <div>
        <i class="fas fa-users"></i>
        <span>Collaborated with 20+ clients</span>
      </div>
    </div> -->

    <div align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=DigvijayJakhaniya&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="200" alt="languages graph"  />
    </div>

    <!-- <div align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=DigvijayJakhaniya&show_icons=true&theme=dracula&hide_border=true" alt="GitHub Stats" />
    </div> -->

    <h2>Social Media Links</h2>
    
    <div class="social-links">
        <a href="https://linktr.ee/digvijay.jakhaniya" target="_blank">
            <img src="https://cdn.simpleicons.org/linktree" height="35" alt="linktree logo"  />
        </a>
        <a href="https://www.linkedin.com/in/digvijayjakhaniya/" target="_blank">
            <img src="https://cdn.simpleicons.org/Linkedin" height="35" alt="Linkedin logo"  />
        </a>  
        <a href="https://www.instagram.com/digvijay.jakhaniya/" target="_blank">
            <img src="https://cdn.simpleicons.org/instagram" height="35" alt="Instagram logo"  />
        </a>  
        <a href="https://www.facebook.com/digvijay.jakhaniyaaa" target="_blank">
            <img src="https://cdn.simpleicons.org/facebook" height="35" alt="Facebook logo"  />
        </a>  
        <a href="https://twitter.com/Digvijay__02" target="_blank">
            <img src="https://cdn.simpleicons.org/X/1DA1F2" height="35" alt="X logo" />
        </a>
    </div>

    <!-- <div class="github-calendar">
      <iframe src="https://ghchart.rshah.org/DigvijayJakhaniya" frameborder="0"></iframe>
    </div>

    <h2>Highlighted Projects</h2>

    <div class="projects">
      <div class="project">
        <h3>Project 1</h3>
        <p>This is a description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <p>This is a description of Project 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
      <div class="project">
        <h3>Project 3</h3>
        <p>This is a description of Project 3. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
  </div> -->

</body>
</html>
