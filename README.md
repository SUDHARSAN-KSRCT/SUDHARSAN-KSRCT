```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sudarshan - MERN Stack Web Artisan</title>
    <!-- Option 1: Clean & Modern with Animated Background -->
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #141E30, #243B55); /* Example gradient */
            color: #fff;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.05); /* Semi-transparent white for a frosted glass effect */
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
        }

        h1, h2 {
            text-align: center;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .profile-image {
            display: block;
            margin: 0 auto 20px;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        .tech-stack {
            text-align: center;
            margin-bottom: 20px;
        }

        .tech-stack img {
            max-width: 100%; /* Ensure it fits the container */
            height: auto;
        }

        .section-title {
            color: #ddd;
            border-bottom: 1px solid #444;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }

        .leetcode-stats, .github-stats {
            text-align: center;
            margin-bottom: 20px;
        }

        .leetcode-stats img, .github-stats img {
            max-width: 100%;
            height: auto;
        }

        /* Optional: Animated background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://i.imgur.com/5A7zD8s.gif'); /* Replace with a cool tech-related GIF */
            background-size: cover;
            z-index: -1;
            opacity: 0.2; /* Subtle background */
        }

        .contact-button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #64ffda; /* Neon Green */
            color: #000; /* Dark text for contrast */
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .contact-button:hover {
            background-color: #4cd1bb; /* A slightly darker shade on hover */
        }

    </style>
</head>
<body>

<div class="container">
    <h1>SUDHARSAN</h1>
    <p style="text-align:center;">MERN Stack Web Artisan | Building Beautiful and Functional Web Experiences</p>
    <img src="https://avatars.githubusercontent.com/u/6002100?v=4" alt="Sudarshan" class="profile-image">

    <section>
        <h2 class="section-title">Tech Stack</h2>
        <div class="tech-stack">
            <img src="https://skillicons.dev/icons?i=html,css,js,java,react,nodejs,mongodb,git,github,vscode,figma" alt="Tech Stack"/>
        </div>
    </section>

    <section>
        <h2 class="section-title">LeetCode Performance</h2>
        <div class="leetcode-stats">
            <a href="https://leetcode.com/u/SUDHARSAN_CSBS/"><img
                    src="https://leetcard.jacoblin.cool/SUDHARSAN_CSBS?theme=dark&font=FiraCode"
                    alt="LeetCode Stats"/></a>
            <p>Sharpening problem-solving skills with algorithms and data structures.</p>
        </div>
    </section>

    <section>
        <h2 class="section-title">GitHub Activity</h2>
        <div class="github-stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=SUDHARSAN-KSRCT&theme=tokyonight&hide_border=true"
                 alt="GitHub Stats"/>
        </div>
    </section>

    <div style="text-align: center; margin-top: 30px;">
        <a href="https://www.linkedin.com/in/sudarshan-ksrct/" class="contact-button">Let's Connect!</a>
    </div>

</div>

</body>
</html>
```
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sudarshan - MERN Stack Web Developer</title>
    <!-- Option 2: Focus on Projects and Storytelling -->
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 40px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        h1, h2 {
            color: #2c3e50;
            text-align: left;
        }

        .profile-header {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
        }

        .profile-image {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            margin-right: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.15);
        }

        .profile-info h1 {
            margin: 0;
        }

        .profile-info p {
            color: #777;
            margin: 5px 0;
        }

        .section-title {
            color: #3498db; /* A blue accent color */
            border-bottom: 2px solid #3498db;
            padding-bottom: 8px;
            margin-bottom: 20px;
        }

        .project {
            margin-bottom: 30px;
            border-left: 4px solid #3498db; /* Left border for visual distinction */
            padding-left: 20px;
        }

        .project h3 {
            margin-top: 0;
            color: #2c3e50;
        }

        .project p {
            color: #555;
        }

        .project-tech {
            font-size: 0.9em;
            color: #777;
            margin-top: 5px;
        }

        .contact-info {
            margin-top: 40px;
            text-align: center;
        }

        .contact-button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #3498db;
            color: #fff;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .contact-button:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="profile-header">
        <img src="https://avatars.githubusercontent.com/u/6002100?v=4" alt="Sudarshan" class="profile-image">
        <div class="profile-info">
            <h1>Sudarshan</h1>
            <p>MERN Stack Web Developer</p>
            <p>Crafting user-centric web applications with passion and precision.</p>
        </div>
    </div>

    <section>
        <h2 class="section-title">Featured Projects</h2>

        <div class="project">
            <h3>E-commerce Website</h3>
            <p>Developed a fully functional e-commerce platform with user authentication, product catalog, shopping cart,
                and secure payment gateway integration. Focused on creating a responsive and intuitive user interface for
                seamless shopping experience.</p>
            <p class="project-tech">Tech: React, Node.js, MongoDB, Express</p>
            <a href="https://github.com/SUDHARSAN-KSRCT/ecommerce" target="_blank">View on GitHub</a>
            <!--| <a href="LINK_TO_LIVE_DEMO">Live Demo</a> -->
        </div>

        <div class="project">
            <h3>Task Management Application</h3>
            <p>Designed and implemented a task management application to help users organize and track their tasks
                efficiently. Implemented features such as task creation, categorization, prioritization, and progress
                tracking. Focused on creating a user-friendly interface and ensuring data persistence.</p>
            <p class="project-tech">Tech: React, Redux, Firebase</p>
            <a href="https://github.com/SUDHARSAN-KSRCT/task-manager" target="_blank">View on GitHub</a>
        </div>
    </section>

    <section>
        <h2 class="section-title">Skills & Expertise</h2>
        <p>Proficient in:</p>
        <ul>
            <li>JavaScript (ES6+)</li>
            <li>React</li>
            <li>Node.js</li>
            <li>Express.js</li>
            <li>MongoDB</li>
            <li>Git/GitHub</li>
            <li>HTML5/CSS3</li>
        </ul>
    </section>

    <div class="contact-info">
        <a href="https://www.linkedin.com/in/sudarshan-ksrct/" class="contact-button">Get in Touch</a>
    </div>

</div>

</body>
</html>
```
