
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ngoc Huyen | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;1,400&family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

:root {
    --red: #781f32;
    --green: #586344;
    --cream: #f4eadb;
    --dark: #29251f;
}

body {
    background: var(--cream);
    color: var(--dark);
    font-family: 'DM Sans', sans-serif;
}

header {
    padding: 25px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #d5c9b9;
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 27px;
    color: var(--red);
}

nav a {
    text-decoration: none;
    color: var(--dark);
    margin-left: 20px;
    font-size: 12px;
    text-transform: uppercase;
}

nav a:hover {
    color: var(--red);
}

.hero {
    min-height: 85vh;
    padding: 70px 10%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 60px;
}

.intro {
    max-width: 550px;
}

.intro small {
    color: var(--red);
    letter-spacing: 4px;
}

h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(48px, 7vw, 85px);
    font-weight: 400;
    margin: 25px 0;
}

h1 em {
    color: var(--red);
}

.intro p {
    color: #766e63;
    line-height: 2;
    font-size: 15px;
}

.photo {
    background: var(--green);
    padding: 18px;
    transform: rotate(2deg);
    width: 350px;
    flex-shrink: 0;
}

.photo img {
    width: 100%;
    height: 430px;
    object-fit: cover;
    display: block;
}

.photo p {
    color: var(--cream);
    text-align: center;
    padding-top: 15px;
    font-family: 'Playfair Display', serif;
    font-style: italic;
}

.button {
    display: inline-block;
    margin-top: 30px;
    padding: 15px 28px;
    background: var(--red);
    color: white;
    text-decoration: none;
    font-size: 12px;
    letter-spacing: 1px;
}

.button:hover {
    background: var(--green);
}

.section {
    padding: 85px 10%;
}

.section h2 {
    font-family: 'Playfair Display', serif;
    font-size: 45px;
    font-weight: 400;
    margin: 15px 0 25px;
}

.label {
    color: var(--red);
    letter-spacing: 3px;
    font-size: 11px;
}

.about {
    background: #fffaf2;
    line-height: 2;
    color: #766e63;
}

.skills {
    background: var(--green);
    color: var(--cream);
}

.skills .label {
    color: #e8cbb2;
}

.skills h2 {
    color: var(--cream);
}

.skill-list {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.skill {
    padding: 28px;
    border: 1px solid #a4a990;
    transition: .3s;
}

.skill:hover {
    background: var(--red);
    transform: translateY(-5px);
}

.skill h3 {
    font-family: 'Playfair Display', serif;
    font-size: 23px;
    margin-bottom: 15px;
}

.skill p {
    font-size: 13px;
    line-height: 1.8;
}

.projects {
    background: var(--cream);
}

.project {
    padding: 25px;
    background: #fffaf2;
    border-left: 4px solid var(--red);
    margin-bottom: 20px;
}

.project h3 {
    font-family: 'Playfair Display', serif;
    font-size: 25px;
    margin-bottom: 10px;
}

.project p {
    color: #766e63;
    line-height: 1.8;
}

.contact {
    background: var(--red);
    color: var(--cream);
    text-align: center;
}

.contact .label {
    color: #e8cbb2;
}

.contact a {
    color: var(--cream);
}

footer {
    padding: 25px;
    text-align: center;
    background: var(--dark);
    color: var(--cream);
    font-size: 12px;
}

@media(max-width: 768px) {
    header {
        flex-direction: column;
        gap: 20px;
    }

    nav a {
        margin: 0 5px;
        font-size: 10px;
    }

    .hero {
        flex-direction: column;
        text-align: center;
    }

    .photo {
        width: min(100%, 350px);
    }

    .photo img {
        height: 380px;
    }

    .skill-list {
        grid-template-columns: 1fr;
    }

    .section h2 {
        font-size: 36px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">NGOC HUYEN.</div>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">

    <div class="intro">
        <small>PERSONAL PORTFOLIO · 2026</small>

        <h1>Hello,<br>I'm <em>Ngoc Huyen.</em></h1>

        <p>
            A curious student passionate about technology,
            creativity and lifelong learning.

            I enjoy discovering new ideas, developing
            my skills and creating meaningful projects.
        </p>

        <a href="#about" class="button">DISCOVER MY STORY</a>
    </div>

    <div class="photo">
        <!-- CHANGE THE IMAGE NAME HERE -->
        <img src="avatar.jpg" alt="Ngoc Huyen">
        <p>A little world of my own.</p>
    </div>

</section>

<section class="section about" id="about">

    <span class="label">01 / ABOUT ME</span>

    <h2>A story of curiosity.</h2>

    <p>
        My name is Ngoc Huyen. I am currently a student
        interested in Information Technology and
        Artificial Intelligence.

        I enjoy learning Python, website development
        and exploring new technologies.

        My goal is to continuously improve myself,
        gain practical experience and create
        meaningful digital products.
    </p>

</section>

<section class="section skills" id="skills">

    <span class="label">02 / MY SKILLS</span>

    <h2>What I am learning.</h2>

    <div class="skill-list">

        <div class="skill">
            <h3>Programming</h3>
            <p>Python, HTML, CSS and basic programming.</p>
        </div>

        <div class="skill">
            <h3>Artificial Intelligence</h3>
            <p>AI fundamentals and Machine Learning.</p>
        </div>

        <div class="skill">
            <h3>Creative Design</h3>
            <p>Website interfaces and digital creativity.</p>
        </div>

    </div>

</section>

<section class="section projects" id="projects">

    <span class="label">03 / MY PROJECTS</span>

    <h2>Things I've explored.</h2>

    <div class="project">
        <h3>Personal Portfolio Website</h3>
        <p>
            A personal website designed with HTML and CSS
            to introduce my background and interests.
        </p>
    </div>

    <div class="project">
        <h3>Python Programming</h3>
        <p>
            Practicing Python fundamentals through
            small learning projects and exercises.
        </p>
    </div>

    <div class="project">
        <h3>AI Learning Journey</h3>
        <p>
            Exploring Artificial Intelligence,
            Machine Learning and modern technologies.
        </p>
    </div>

</section>

<section class="section contact" id="contact">

    <span class="label">04 / GET IN TOUCH</span>

    <h2>Let's connect.</h2>

    <p>
        Thank you for visiting my personal portfolio.
        I would love to connect and share ideas.
    </p>

    <p style="margin-top:25px;">
        Email: <a href="mailto:yourmail@gmail.com">
        yourmail@gmail.com</a>
    </p>

</section>

<footer>
    © 2026 NGOC HUYEN. ALL RIGHTS RESERVED.
</footer>

</body>
</html>

