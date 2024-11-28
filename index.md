<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Analyst Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Cybersecurity Analyst Student</h1>
            <p>Passionate about safeguarding digital assets and exploring advanced cybersecurity solutions.</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <main>
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>I am a dedicated cybersecurity student with a strong interest in penetration testing, threat analysis, and incident response. Currently pursuing a degree in computer science, I aim to contribute to a safer digital world.</p>
        </section>

        <section id="skills" class="section">
            <h2>Skills</h2>
            <ul>
                <li>Penetration Testing</li>
                <li>Network Security</li>
                <li>Incident Response</li>
                <li>Python and Bash Scripting</li>
            </ul>
        </section>

        <section id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li>Developed a custom firewall for enhanced network security.</li>
                <li>Conducted vulnerability assessments on web applications.</li>
                <li>Automated log analysis using Python.</li>
            </ul>
        </section>

        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Feel free to reach out to me for opportunities or collaborations.</p>
            <a href="mailto:student@cybersecurity.com" class="btn">Email Me</a>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Cybersecurity Analyst Student. All Rights Reserved.</p>
    </footer>
</body>
</html>
/* styles.css */

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background: #1a1a2e;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
}

header p {
    font-size: 1.2rem;
}

nav {
    background: #16213e;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ffa62b;
}

.section {
    padding: 20px;
    max-width: 800px;
    margin: 20px auto;
    background: #f8f8f8;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.section h2 {
    color: #16213e;
    margin-bottom: 10px;
}

.section ul {
    list-style: square;
    padding-left: 20px;
}

.section .btn {
    display: inline-block;
    background: #ffa62b;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s;
}

.section .btn:hover {
    background: #e68a00;
}

footer {
    text-align: center;
    background: #1a1a2e;
    color: #fff;
    padding: 10px 0;
    margin-top: 20px;
    font-size: 0.9rem;
}
