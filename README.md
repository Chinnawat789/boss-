<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chinnawat Saengkaew - Resume</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* Global Styles */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f9;
            color: #333;
        }
        /* Navigation */
        nav {
            background: rgba(0, 123, 255, 0.8);
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin: 0;
            padding: 0;
            gap: 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
            padding: 5px 10px;
        }
        /* Header */
        header {
            text-align: center;
            padding: 20px;
            background: #007BFF;
            color: white;
        }
        .profile-picture {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }
        /* Skills Section */
        .chart-bar {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 10px;
        }
        .chart-bar span {
            flex-basis: 100px;
            font-size: 0.9rem;
            color: #555;
        }
        .chart-bar .bar {
            flex-grow: 1;
            height: 12px;
            background: #ddd;
            border-radius: 6px;
            position: relative;
            overflow: hidden;
        }
        .chart-bar .bar::after {
            content: '';
            display: block;
            height: 100%;
            background: linear-gradient(90deg, #007BFF, #0056b3);
            width: 0;
            border-radius: 6px;
            animation: loadBar 1.5s ease-in-out forwards;
        }
        @keyframes loadBar {
            from {
                width: 0;
            }
            to {
                width: var(--width);
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#work-history">Work History</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="resume-container">
        <!-- Header -->
        <header>
            <div class="profile-header">
                <img src="profile.jpg" alt="Profile Picture" class="profile-picture">
                <div class="profile-info">
                    <h1>Chinnawat Saengkaew</h1>
                    <p>Digital and Information Technology (DIT)</p>
                </div>
            </div>
        </header>
        <!-- About Me -->
        <section id="about">
            <h2>About Me</h2>
            <p>I work specifically with computers. I have basic knowledge of using programs, troubleshooting, and part replacement. I am eager to learn and adapt to new environments quickly.</p>
        </section>
        <!-- Skills -->
        <section id="skills">
            <h2>Skills</h2>
            <div class="chart-bar">
                <span>SQL</span>
                <div class="bar" style="--width: 80%;"></div>
            </div>
            <div class="chart-bar">
                <span>Networking</span>
                <div class="bar" style="--width: 70%;"></div>
            </div>
            <div class="chart-bar">
                <span>2D Animation</span>
                <div class="bar" style="--width: 60%;"></div>
            </div>
        </section>
    </div>
</body>
</html>
