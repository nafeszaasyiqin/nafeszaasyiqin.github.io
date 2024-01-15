
<html lang="en">
<h<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #007bff;
            color: #fff;
        }

        nav {
            text-align: center;
            margin: 20px 0;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #007bff;
            font-weight: bold;
        }

        section {
            margin-bottom: 30px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Name</h1>
        <p>Welcome to my personal website</p>
    </header>

    <nav>
        <a href="#profile">Profile</a>
        <a href="#contact">Contact</a>
        <a href="#journey">Life Journey</a>
        <a href="#projects">Projects</a>
        <a href="#education">Education</a>
    </nav>

    <section id="profile">
        <h2>Profile</h2>
        <p>Add your profile information here.</p>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Add your contact information here.</p>
    </section>

    <section id="journey">
        <h2>Life Journey</h2>
        <p>Share your life journey and experiences here.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>Showcase your projects and achievements here.</p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p>Provide details about your educational background.</p>
    </section>

    <script>
        // You can add JavaScript for interactivity here
        // For example, smooth scrolling to section anchors
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>

</body>
</html>

