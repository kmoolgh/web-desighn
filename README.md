# web-desighn
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website!</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>I am a web developer passionate about coding and designing websites.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <article>
                <h3>Project 1</h3>
                <p>Description of project 1.</p>
            </article>
            <article>
                <h3>Project 2</h3>
                <p>Description of project 2.</p>
            </article>
        </section>
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Python</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>Contact me: your-email@example.com</p>
    </footer>
</body>
</html>
