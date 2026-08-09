# Group-Page<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team Profile</title>
    <style>
        * {margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif;}
        body {background-color: #f0f4f8; padding: 40px 20px;}
        h1 {text-align: center; color: #2d3748; margin-bottom: 50px; font-size: 36px; text-transform: uppercase; letter-spacing: 2px;}
        
        /* FIX: Changed max-width from 1200px to 1300px */
        .team-container {display: flex; flex-wrap: wrap; justify-content: center; gap: 30px; max-width: 1300px; margin: 0 auto;}
        
        .member-card {background: white; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); overflow: hidden; width: 280px; text-align: center; transition: transform 0.3s ease;}
        .member-card:hover {transform: translateY(-10px);}
        .member-img {width: 100%; height: 280px; object-fit: cover;}
        .member-info {padding: 20px;}
        .member-name {font-size: 22px; color: #1a202c; margin-bottom: 8px; font-weight: bold;}
        .member-role {font-size: 15px; color: #2b6cb0; margin-bottom: 12px; font-weight: 600;}
        .member-desc {font-size: 14px; color: #4a5568; line-height: 1.6;}
        @media (max-width: 768px) {.team-container {flex-direction: column; align-items: center;}}
    </style>
</head>
<body>

<h1> 🤝 Our Team </h1>
<div class="team-container">

    <!-- Member 1 -->
    <div class="member-card">
       <img src="C:\Users\valsf\OneDrive\Pictures\Saved Pictures\娜娜.png" alt="Novelene Udtohan" class="member-img">
        <div class="member-info">
            <h2 class="member-name">Novelene Udtohan</h2>
            <p class="member-role">Team Leader / Fullstack Developer</p>
            <p class="member-desc">I am a versatile developer who builds complete applications from the ground up. I love tackling both visual layouts and complex server logic, utilizing tools like C#, Java, and SQL to create seamless, end-to-end solutions that look great and run perfectly.</p>
        </div>
    </div>

    <!-- Member 2 -->
    <div class="member-card">
       <img src="C:\Users\valsf\OneDrive\Pictures\Saved Pictures\玛丽·罗斯.jpg" alt="Marryrose Delos Santos" class="member-img"> 
        <div class="member-info">
            <h2 class="member-name">Mary Rose De Los Santos</h2>
            <p class="member-role">UI/UX Designer</p>
            <p class="member-desc">I am a creative problem-solver dedicated to crafting visually stunning and intuitive digital experiences. My goal is to deeply understand user needs and design beautiful, user-friendly interfaces that make technology accessible and enjoyable for everyone.</p>
        </div>
    </div>

    <!-- Member 3  -->
    <div class="member-card">
        <img src="https://uploads.onecompiler.io/439j5g6ny/1786153603074/Screenshot_2026-06-04-11-21-30-145_com.miui.gallery.jpg" alt="Glen Delgado" class="member-img">
        <div class="member-info">
            <h2 class="member-name">Glen Delgado</h2>
            <p class="member-role">Front-end Developer</p>
            <p class="member-desc">I bring designs to life! I focus entirely on the user-facing side of applications, writing clean code to build responsive and highly interactive layouts. I ensure that every website I touch is easy to navigate and looks incredible on any device.</p>
        </div>
    </div>

    <!-- Member 4 -->
    <div class="member-card">
        <img src="C:\Users\valsf\OneDrive\Pictures\Saved Pictures\crisnar.jpg" alt="Fourth Member" class="member-img">
        <div class="member-info">
            <h2 class="member-name">Crisnar Villagarcia</h2>
            <p class="member-role">Back-end Developer</p>
            <p class="member-desc">I am the architect working behind the scenes. I build the core foundation of applications, design robust database schemas, and write the server-side logic that powers everything. My focus is on keeping systems secure, fast, and efficient.</p>
        </div>
    </div>

</div>
</body>
</html>
