# web-development-portfolio

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Channelle Kibunyi - Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .hero {
            background-color: #f8f9fa;
            padding: 80px 0;
            text-align: center;
        }
        .section-title {
            margin-top: 40px;
            margin-bottom: 20px;
        }
        footer {
            background-color: #343a40;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>

<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1 class="display-4">Channelle Kibunyi</h1>
            <p class="lead">Welcome to my portfolio website</p>
        </div>
    </section>

    <!-- About Section -->
    <section class="container">
        <h2 class="section-title">About Me</h2>
        <p>Hi! I'm Channelle Kibunyi, a passionate developer currently learning full-stack development. This is a sample portfolio website built using HTML, CSS, and Bootstrap.</p>
    </section>

    <!-- What I Can Do Section -->
    <section class="container">
        <h2 class="section-title">What I Can Do</h2>
        <p>I specialize in front-end and back-end web development. I create responsive, user-friendly interfaces and robust backend systems using modern technologies. Below are some of the skills I bring to the table:</p>
        <ul>
            <li>HTML, CSS, JavaScript, Bootstrap</li>
            <li>Python, PHP, Node.js</li>
            <li>MySQL, MongoDB</li>
            <li>REST API Integration</li>
            <li>Git & GitHub for version control</li>
        </ul>
        <p>Success Stories:</p>
        <ul>
            <li>Developed a student portal for assignment tracking and resource sharing.</li>
            <li>Built an e-commerce mockup database schema with optimized entity relationships.</li>
            <li>Contributed to group projects and hackathons with clean, reusable code.</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section class="container">
        <h2 class="section-title">Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-body">
                        <h5 class="card-title">Project 1</h5>
                        <p class="card-text">Description of project 1.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-body">
                        <h5 class="card-title">Project 2</h5>
                        <p class="card-text">Description of project 2.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-body">
                        <h5 class="card-title">Project 3</h5>
                        <p class="card-text">Description of project 3.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="container">
        <h2 class="section-title">Contact</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" value="Channelle Kibunyi" readonly>
            </div>
            <div class="mb-3">
                <label for="phone" class="form-label">Phone</label>
                <input type="text" class="form-control" id="phone" value="0748309419" readonly>
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" value="channellekibunyi3@gmail.com" readonly>
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Channelle Kibunyi. All rights reserved.</p>
        </div>
    </footer>
</body>

</html>
