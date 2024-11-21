<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ชินวัฒน์ แสงแก้ว - ประวัติย่อ</title>
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
        nav ul li a:hover {
            text-decoration: underline;
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
        /* About Section */
        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            font-size: 1.5rem;
            color: #007BFF;
            border-bottom: 2px solid #007BFF;
            padding-bottom: 5px;
        }
        /* Skill Bars */
        .chart-bar {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 10px;
        }
        .chart-bar span {
            flex-basis: 150px;
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
            <li><a href="#about">เกี่ยวกับฉัน</a></li>
            <li><a href="#skills">ทักษะ</a></li>
            <li><a href="#contact">ติดต่อ</a></li>
        </ul>
    </nav>
    <!-- Header -->
    <header>
        <img src="profile.jpg" alt="รูปโปรไฟล์" class="profile-picture">
        <h1>ชินวัฒน์ แสงแก้ว</h1>
        <p>สาขาวิชาดิจิทัลและเทคโนโลยีสารสนเทศ (DIT)</p>
    </header>
    <!-- About Section -->
    <section id="about">
        <h2>เกี่ยวกับฉัน</h2>
        <p>
            ฉันทำงานเกี่ยวกับคอมพิวเตอร์โดยเฉพาะ ฉันมีความรู้พื้นฐานเกี่ยวกับการใช้โปรแกรม การแก้ไขปัญหา และการเปลี่ยนชิ้นส่วน 
            ฉันกระตือรือร้นที่จะเรียนรู้และปรับตัวเข้ากับสภาพแวดล้อมใหม่ๆ ได้อย่างรวดเร็ว
        </p>
    </section>
    <!-- Skills Section -->
    <section id="skills">
        <h2>ทักษะ</h2>
        <div class="chart-bar">
            <span>เอสคิวแอล</span>
            <div class="bar" style="--width: 80%;"></div>
        </div>
        <div class="chart-bar">
            <span>การสร้างเครือข่าย</span>
            <div class="bar" style="--width: 70%;"></div>
        </div>
        <div class="chart-bar">
            <span>แอนิเมชั่น 2D</span>
            <div class="bar" style="--width: 60%;"></div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact">
        <h2>ติดต่อ</h2>
        <p><strong>โทรศัพท์:</strong> 082-926-6961</p>
        <p><strong>อีเมล:</strong> rejikung100@gmail.com</p>
    </section>
</body>
</html>
