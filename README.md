<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <style>
        /* General Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Bahnschrift, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #7b1fa2, #512da8);
            color: #f3f3f3;
            display: flex;
            flex-direction: column;
            align-items: center;
            font-family: Bahnschrift, sans-serif;
        }

        .container {
            width: 80%;
            margin: auto;
            max-width: 1200px;
        }

        /* Header Section */
        header {
            text-align: center;
            padding: 30px 0;
            color: #f3f3f3;
        }

        header h1 {
            font-size: 3.5em;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        nav a {
            color: #ffeb3b;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 15px;
            transition: color 0.3s, background 0.3s;
        }

        nav a:hover {
            background: #ffeb3b;
            color: #7b1fa2;
            border-radius: 5px;
        }

        /* Section Styling */
        section {
            margin: 50px 0;
            padding: 25px;
            border-radius: 15px;
            background-color: rgba(255, 255, 255, 0.1);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.2s;
        }

        section:hover {
            transform: scale(1.02);
        }

        section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #ffeb3b;
            text-align: center;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.3);
        }

        section p {
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 15px;
            text-align: justify;
        }

        /* Button Styling */
        .btn {
            display: inline-block;
            padding: 12px 25px;
            background: #ffeb3b;
            color: #7b1fa2;
            text-decoration: none;
            border-radius: 10px;
            font-weight: bold;
            transition: background 0.3s, transform 0.2s;
        }

        .btn:hover {
            background: #fff176;
            transform: translateY(-3px);
        }

        /* Footer Styling */
        footer {
            background: #512da8;
            color: white;
            text-align: center;
            padding: 20px 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My World</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About Me</a>
            <a href="#education">Education</a>
            <a href="#experience">Experience</a>
            <a href="#publications">Publications</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="container">
        <h2>Welcome</h2>
        <p>Hello! I'm Hriddhita Bhattacharjee, a student at University of Engineering and Management. Welcome to my personal website where you can learn more about my background, projects, and achievements.</p>
    </section>

    <!-- About Me Section -->
    <section id="about" class="container">
        <h2>About Me</h2>
        <p>Hi! My name is Hriddhita but my friends usually call me Rhea. I am studying Btech on Computer Science Engineering with a specialisation in Internet of Things, Block Chain Technology, and Cyber Security. My hobbies are reading, writing and travelling. I love to watch sports like ice skating and Formula One. I like to study about the science of the Fourth dimension, blackholes, wormholes, parallel universes and other things related to outer space and quantum mechanics.</p>
    </section>

    <!-- Education Section -->
    <section id="education" class="container">
        <h2>Educational Background</h2>
        <p>I am an ex-student of the prestigious South Point High School. I passed my Secondary and my Higher Secondary Board Examinations from there.</p>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="container">
        <h2>Experience</h2>
        <p>I have never gone anywhere for an internship or any part time job but I wish to in future times.</p>
    </section>

    <!-- Publications Section -->
    <section id="publications" class="container">
        <h2>Paper/Patent Publications</h2>
        <p>I haven't had anything published anywhere.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container">
        <h2>Projects</h2>
        <p>I have completed the Economic 1000 Rupees Challenge, Physics Live Model Project and the Maths Flyer Making Project.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container">
        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to reach out at hiddhitabhattacharjee@gmail.com or connect with me on hriddhita.bhattacharjee2024@uem.edu.in.</p>
        <a href="mailto:hriddhitabhattacharjee@gmail.com" class="btn">Contact Me</a>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 [Your Name]. All Rights Reserved.</p>
    </footer>

</body>
</html>
