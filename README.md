<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume - [Your Name]</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
        }
        .section-divider {
            border-top: 2px solid #ccc;
            margin: 30px 0;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Resume</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#about">About Me</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#education">Education</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#employment">Employment History</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#skills">Skills</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Me Section -->
    <section id="about" class="container my-5">
        <div class="text-center">
            <img src="profile.jpg" alt="Profile Picture" class="profile-img">
            <h1>[Your Name]</h1>
            <p><em>Major: [Your Major]</em></p>
            <p>Faculty of [Your Faculty], [Your Institution]</p>
            <p><a href="http://pim.ac.th" target="_blank">PIM Website</a></p>
        </div>
        <p>Short description about yourself goes here...</p>
        <hr class="section-divider">
    </section>

    <!-- Education Section -->
    <section id="education" class="container my-5">
        <h2>Education</h2>
        <p>Your educational background goes here...</p>
        <hr class="section-divider">
    </section>

    <!-- Employment History Section -->
    <section id="employment" class="container my-5">
        <h2>Employment History</h2>
        <p>Your work experience goes here...</p>
        <hr class="section-divider">
    </section>

    <!-- Skills Section -->
    <section id="skills" class="container my-5">
        <h2>Skills</h2>
        <p>List your skills here...</p>
        <hr class="section-divider">
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container my-5">
        <h2>Contact</h2>
        <ol>
            <li>Email: <a href="mailto:[your-email]">[your-email]@pim.ac.th</a></li>
            <li>Phone: [Your Phone Number]</li>
            <li>Address: [Your Address]</li>
        </ol>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
