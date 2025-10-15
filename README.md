<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahedihasan Nandoliya - Laravel Developer</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: #f9fafc;
        }

        .hero {
            background: #1B263B;
            color: #fff;
            padding: 80px 20px;
            text-align: center;
        }

        .hero h1 {
            font-weight: 700;
            margin-bottom: 10px;
        }

        .section-title {
            font-weight: 700;
            margin: 50px 0 30px;
            text-align: center;
        }

        .project-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            background: #fff;
            transition: transform 0.2s;
        }

        .project-card:hover {
            transform: scale(1.02);
        }

        .project-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }

        .skills span {
            background: #1B263B;
            color: #fff;
            padding: 5px 12px;
            border-radius: 20px;
            margin: 3px;
            display: inline-block;
        }

        .contact a {
            color: #1B263B;
            text-decoration: none;
        }

        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Mahedihasan Nandoliya</h1>
        <p>Laravel Developer | Remote | Backend Specialist</p>
    </section>

    <!-- About Me -->
    <section class="container my-5">
        <h2 class="section-title">About Me</h2>
        <p>I am a Laravel developer with 3 years of experience building and maintaining web applications. I have
            successfully delivered 10+ projects, including full custom builds and extending pre-built templates. I
            specialize in backend development, API integration, database design, and deployment. I am experienced in
            working independently in remote teams and delivering production-ready applications.</p>
    </section>

    <!-- Skills -->
    <section class="container my-5">
        <h2 class="section-title">Skills</h2>
        <div class="skills text-center">
            <span>Laravel</span>
            <span>PHP</span>
            <span>MySQL</span>
            <span>REST API</span>
            <span>Vue.js / Inertia.js</span>
            <span>Git / GitHub</span>
            <span>Deployment</span>
            <span>Security Best Practices</span>
        </div>
    </section>

    <!-- Projects -->
    <section class="container my-5">
        <h2 class="section-title">Projects</h2>

        <div class="row">
            <!-- From Scratch Projects -->
            <h3>Built From Scratch</h3>
            <div class="col-md-4">
                <div class="project-card">
                    <img src="project1-screenshot.jpg" alt="Project 1" class="project-img">
                    <h5 class="mt-3">Hotel Management System</h5>
                    <p>Built complete backend for hotel booking, rooms, payments. Tech: Laravel, MySQL, Vue.js. Solo
                        developer.</p>
                    <a href="https://github.com/username/project1" target="_blank">View on GitHub</a>
                </div>
            </div>

            <div class="col-md-4">
                <div class="project-card">
                    <img src="project2-screenshot.jpg" alt="Project 2" class="project-img">
                    <h5>E-Commerce Platform</h5>
                    <p>Complete Laravel e-commerce with products, cart, checkout, and admin panel. Built from scratch.
                    </p>
                    <a href="https://github.com/username/project2" target="_blank">View on GitHub</a>
                </div>
            </div>

            <!-- Add other 3 projects similarly -->

            <!-- Customized Purchased Projects -->
            <h3 class="mt-5">Customized / Extended Templates</h3>
            <div class="col-md-4">
                <div class="project-card">
                    <img src="project6-screenshot.jpg" alt="Project 6" class="project-img">
                    <h5>E-Learning Platform (Purchased)</h5>
                    <p>Extended Laravel template to add custom backend modules, APIs, and deployment. Solo work.</p>
                    <a href="https://github.com/username/project6" target="_blank">View on GitHub</a>
                </div>
            </div>

            <!-- Add other 4 purchased/customized projects similarly -->

        </div>
    </section>

    <!-- Contact -->
    <section class="container my-5">
        <h2 class="section-title">Contact</h2>
        <p class="text-center contact">
            Email: <a href="mailto:hdeveloper429@gmail.com">hdeveloper429@gmail.com</a> |
            GitHub: <a href="https://github.com/mahediali" target="_blank">github.com/mahediali</a> |
            LinkedIn: <a href="https://www.linkedin.com/in/username" target="_blank">linkedin.com/in/username</a>
        </p>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
