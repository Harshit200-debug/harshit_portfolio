# harshit_portfolio
This is my personal portfolio website designed using HTML and CSS. It showcases my skills, projects, and basic information in a clean and responsive layout. The website focuses on semantic HTML structure and modern CSS styling to ensure readability, accessibility, and a user-friendly experience across different devices
<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
            integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw=="
            crossorigin="anonymous" referrerpolicy="no-referrer" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link
            href="https://fonts.googleapis.com/css2?family=Gravitas+One&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
            rel="stylesheet">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>PORTFOLIO</title>
    </head>
    <body>
        <nav>
            <div class="left">
                <a href="/">harshit kushwah</a>
            </div>
            <div class="right">
                <a href="http://github.com" target="_blank" rel="noopener noreferrer">
                    <i class="fa-brands fa-github"></i>
                    <span>Github</span>
                </a>
                <a href="http://linkdin.com" target="_blank" rel="noopener noreferrer">
                    <i class="fa-brands fa-linkedin"></i>
                    <span>Linkedin</span>
                </a>
                <a href="mailto:harshit@gmail.com">
                    <i class="fa-solid fa-envelope"></i>
                    <span>Gmail</span>
                </a>
            </div>
        </nav>
        <main>
            <!-- section 1 : hero -->
            <section class="hero-section">
                <div class="text">
                    <h2>Hi, I'm Harshit &#128075;</h2>
                    <p>I am a Computer Science Engineering fresher with a strong foundation in programming, data
                        structures, and web technologies. I have hands-on experience through academic projects and a
                        keen interest in software development. I am a quick learner, detail-oriented, and motivated to
                        contribute to a professional team while continuously enhancing my technical skills.</p>
                    <div class="link">
                        <a href="#skills">
                            <i class="fa-solid fa-code"></i>
                            <span>Skills</span>
                        </a>
                        <a href="#testimony">
                            <i class="fa-solid fa-pen"></i>
                            <span>Testimony</span>
                        </a>
                        <a href="#contact">
                            <i class="fa-solid fa-envelope"></i>
                            <span>Contact</span>
                        </a>
                    </div>
                </div>
                <div class="headshot">
                    <img src="WhatsApp Image 2026-01-15 at 7.05.01 PM.jpeg" alt="hk image">
                </div>
            </section>
            <!-- section 2 : skills  -->
            <section id="skills" class="skills-section">
                <h2>Skills</h2>
                <div class="text">
                    Strong understanding of programming fundamentals including variables, loops, functions, and
                    object-oriented concepts. Familiar with languages such as Html,Css, Python, and JavaScript, with the
                    ability
                    to write clean and efficient code.
                </div>
                <div class="cells">
                    <div class="cell">
                        <i class="fa-brands fa-html5"></i>
                        <span>HTML</span>
                    </div>
                    <div class="cell">
                        <i class="fa-brands fa-css3"></i>
                        <span>CSS</span>
                    </div>
                    <div class="cell">
                        <i class="fa-brands fa-java"></i>
                        <span>Java</span>
                    </div>
                    <div class="cell">
                        <i class="fa-brands fa-python"></i>
                        <span>Python</span>
                    </div>
                </div>
            </section>
            <!-- section 3 : testimony -->
            <section id="testimony" class="testimony-section">
                <h2>Testimony</h2>
                <div class="group">
                    <div class="person-details">
                        <img src="WhatsApp Image 2026-01-15 at 7.05.01 PM.jpeg">
                        <p>Harshit kushwah </p>
                        <p>Computer Science Engineer | Fresher</p>
                    </div class="text">
                    A passionate Computer Science fresher with a strong learning mindset, good technical fundamentals,
                    and the ability to adapt quickly to new technologies.
                </div>
                </div>
            </section>
            <!-- section 4 : contact  -->
            <section id="contact" class="contact-section">
                <h2>Contact</h2>
                <div class="group">
                    <div class="text">
                        I welcome professional inquiries, collaborative opportunities, and meaningful discussions
                        related to technology and innovation. Whether you are interested in potential employment,
                        project collaboration, or knowledge exchange, please feel free to reach out. I am always open to
                        engaging in constructive conversations and exploring impactful opportunities.
                    </div>
                    <form>
                        <label for="name">Name</label>
                        <input type="text" id="name">
                        <label for="email">Email</label>
                        <input type="email" id="email">
                        <label for="message">Message</label>
                        <textarea id="message" rows="5"></textarea>
                        <button type="submit">Send Message</button>
                    </form>
                </div>
            </section>
        </main>
    </body>
</html>
<!-- CSS CODE -->
:root {
    --text-color: #1a1c20;
    --link-color: #4a76ee;
    --background-color: #eeeff1;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;

}

body {
    font-family: 'poppins', sans-serif;
    background-color: var(--background-color);
    max-width: 1400px;
    margin: 0 auto;
}

a {
    color: var(--link-color);
    text-decoration: none;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 0 50px;
    align-items: center;
    height: 80px;
}

nav .left a {
    color: var(--text-color);
    font-size: 22px;
    font-weight: 600;
}

nav .right a {
    color: var(--text-color);
    margin: 0 10px;
}

nav .right a:last-child {
    color: var(--background-color);
    background-color: var(--text-color);
    padding: 5px;
    border-radius: 5px;
}

nav .right a span {
    margin-left: 5px;
}

/* section 1 : hero  */
.hero-section {
    display: flex;
    justify-content: space-between;
    padding: 0 50px;
    margin: 50px 0;
    align-items: center;
    gap: 40px;
}


.hero-section .text {
    flex: 5;
}

.hero-section .text h2 {
    font-size: 45px;
}

.hero-section .text .link {
    margin-top: 25px;
}

.hero-section .text .link a {
    display: inline-block;
    padding: 5px 10px;
    border: 2px solid var(--link-color);
    border-radius: 5px;
    margin-right: 10px;
    margin-bottom: 10px;
    transition: .1s;
}

.hero-section .text .link a:hover {
    color: var(--text-color);
    border: 2px solid var(--text-color);

}

.hero-section .headshot {
    flex: 2;
    display: flex;
    justify-content: right;
}

.hero-section .headshot img {
    width: 350px;
    border-radius: 75%;
}


/* section 2 : skills */
.skills-section {
    padding: 0 50px;
    margin-bottom: 100px;

}

.skills-section h2 {
    text-align: center;
    font-size: 35px;
}

.skills-section h2 {
    text-align: center;
    margin-bottom: 20px;
}

.skills-section .cells {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;

}

.skills-section .cells .cell {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 200px;
    margin: 10px;
    padding: 10px 20px;
    border: 1.5px solid #d3d3d3d3;
    border-radius: 5px;
    gap: 10px;
}

.skills-section .cells .cell img {
    width: 30px;
    height: 30px;
    object-fit: contain;
    border-radius: 2px;
}


.skills-section .cells .cell span {
    font-size: 18px;

}

/* section 3: testimony */
.testimony-section {
    padding: 0 50px;
    margin-bottom: 100px;
}

.testimony-section h2 {
    font-size: 35px;
    margin-bottom: 30px;
}

.testimony-section .group {
    display: flex;
    align-items: center;
    gap: 50px;
}

.testimony-section .group .person-details {
    text-align: center;
    flex: 2;
}

.testimony-section .group .text {
    flex: 8;

}

.testimony-section .group .person-details img {
    aspect-ratio: 1/1;
    object-fit: cover;
    width: 200px;
    border-radius: 50%;
    margin-bottom: 10px;
}

.testimony-section .group .person-details p {
    font-weight: 600;
    width: 300px;
}

.testimony-section .group .person-details p:last-child {
    font-weight: normal;

}

@media (max-width: 850px) {
    /* section : 1 hero  */
    .hero-section {
        flex-direction: column-reverse;
    }
    /* section 3: testimony */
    .testimony-section {
        text-align: center;
    }
    .testimony-section .group {
        flex-direction: column;
    }
    /* section 4: contact */
    .contact-section .group{
        flex-direction: column;
    }
}

.hero-section .headshot img {
    width: 300px;
}

/* seciton 4 : contact */
.contact-section {
    padding: 0 50px;
    margin-bottom: 100px;
}

.contact-section h2 {
    font-size: 35px;
}

.contact-section .group {
    display: flex;
    gap: 50px;

}

.contact-section .group .text {
    flex: 3;
    margin-top: 20px;
}

.contact-section .group form {
    flex: 3;
    display: flex;
    flex-direction: column;
}

.contact-section .group input,
.contact-section .group form textarea {
    font-family: 'Poppins', sans-serif;
    border: 2px solid var(--link-color);
    background-color: transparent;
    padding: 10px;
    margin-bottom: 15px;
    outline: none;
    resize: none;
}

.contact-section .group button {
    font-size: 16px;
    font-family: 'Poppins', sans-serif;
    columns: #fff;
    background-color: var(--link-color);
    border: none;
    height: 50px;
    cursor: pointer;
    transition: .1s;
}
.contact-section .group button:hover{
    filter: brightness(.9);
}


@media (max-width: 740px) {
    /* section : 1 hero  */
    .hero-section .text .link h2 {
        font-size: 35px;
    }
    @media (max-width: 600px) {
        nav {
            padding: 0 20px;
        }
        nav .right a {
            font-size: 22px;
        }
        nav .right a:last-child {
            color: var(--text-color);
            background-color: transparent;
            padding: 0;
        }
        nav .right a span {
            display: none;
        }
        /* section 1 : hero  */
        .hero-section {
            padding: 0 20px;
        }
        .hero-section .text h2 {
            font-size: 30px;
        }
        /* section 2: skills  */
        .skills-section {
            padding: 0 20px;
        }
        .skills-section .cells .cell span {
            font-size: 16px;
        }
        /* section 3: testimony */
        .testimony-section {
            padding: 0 20px;
        }
        /* section 4: contact  */
        .contact-section{
            padding: 0 20px;
        }
    }
}
