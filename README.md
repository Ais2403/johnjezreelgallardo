<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JohnJezreelGallardoWebsite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('C:/Users/jezre/OneDrive/Desktop/Website/Background.jpg'); /* Use your background image path */
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }
        header {
            background-color: rgba(51, 51, 51, 0.8);
            color: #fff;
            padding: 1rem;
            text-align: center;
            position: relative;
            margin-left: 220px; /* Added to align with sidebar */
        }
        nav {
            width: 200px;
            position: fixed;
            top: 0;
            left: 0;
            height: 100%;
            background-color: rgba(68, 68, 68, 0.8);
            padding-top: 1rem;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .profile {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            overflow: hidden;
            border: 2px solid #fff;
            margin-bottom: 1rem;
        }
        .profile img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        nav a {
            color: #fff;
            padding: 1rem;
            text-decoration: none;
            display: block;
            font-weight: bold;
            text-align: center;
            width: 100%;
        }
        nav a:hover {
            background-color: rgba(85, 85, 85, 0.8);
        }
        .container {
            padding: 2rem;
            background-color: rgba(244, 244, 244, 0.8); 
            margin-left: 220px; /* Added to align with sidebar */
        }
        .video-section {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            margin-bottom: 2rem;
        }
        .video {
            flex: 1 1 calc(33.333% - 2rem); 
            box-sizing: border-box;
        }
        .video iframe {
            width: 100%;
            height: 300px; 
        }
        .about-section, .contact-section {
            display: none;
            background-color: rgba(255, 255, 255, 0.9); /* Lightened background */
            padding: 2rem;
            margin-left: 220px; /* Added to align with sidebar */
            font-size: 1.2rem; /* Adjusted font size */
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: rgba(51, 51, 51, 0.8);
            color: #fff;
            position: fixed;
            bottom: 0;
            width: calc(100% - 220px); /* Adjusted to align with sidebar */
            margin-left: 220px; /* Added to align with sidebar */
        }
    </style>
</head>
<body>
    <nav>
        <div class="profile">
            <img src="C:/Users/jezre/OneDrive/Desktop/Website/Profile.png" alt="Profile Picture"> <!-- Use your profile image path -->
        </div>
        <a href="#" onclick="showSection('home')">Home</a>
        <a href="#" onclick="showSection('about')">About</a>
        <a href="#" onclick="showSection('contact')">Contact Us</a>
    </nav>
    <header>
        <h1>Hi Jezreel here known as Ais_sama, Hi!!</h1>
    </header>
    <div class="container home-section">
        <!-- To link my youtube videos I need to get the embedded link -->
        <h2>Highlights</h2>
        <div class="video-section">
            <div class="video">
                <h2>Highlight 1</h2>
                <iframe width="100" height="300" src="https://www.youtube.com/embed/0rSKJ-HF898?si=Jm4KNoFDJLyivzXL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
            <div class="video">
                <h2>Highlight 2</h2>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/6JIvn3GtJ50?si=zSTXP4QRtbcCVlw9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
            <div class="video">
                <h2>Highlight 3</h2>
               <iframe width="560" height="315" src="https://www.youtube.com/embed/A3rYe_qTSz4?si=lq784HROfCuXSKHV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
        </div>
        <h2>Longer Clips</h2>
        <div class="video-section">
            <div class="video">
                <h2>Another Video 1</h2>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/KutrUaZa6sU?si=8C3CsmussqQqbdVU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
            <div class="video">
                <h2>Another Video 2</h2>
				<iframe width="560" height="315" src="https://www.youtube.com/embed/oaTAtPIQp10?si=3hCASYO2FtO6yoU2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
            <div class="video">
                <h2>Another Video 3</h2>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/98ORlBFHERo?si=b2qE80-Vcu1xIi4A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
        </div>
    </div>
    <div class="container about-section">
        <p>This website is created by Gallardo, John Jezreel E. of Bachelor of Science in Psychology and is in compliance with the requirements for the subject GEE423 (Living In The IT Era) as part of the Final Examination for the AY 2023-2024.</p>
        <p>This website I created is a personal vlog website where in I post or upload the highlights I get in doing my hobby which is gaming, here you can all see my highlights it will direct you to youtube or you can watch it<br>
        directly on the website.</p>
        <p>Gallardo John Jezreel E.</p>
        <p>Bachelor of Science in Psychology</p>
        <p> JILCF College Department </p>
    </div>
    <div class="container contact-section">
        <form id="contactForm">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" style="width: 100%;" required></textarea><br>
            <input type="submit" value="Submit">
        </form>
		 
    </div>
    <footer>
        <p>&copy; 2024 Highlights</p>
    </footer>
    <script>
        function showSection(section) {
            document.querySelectorAll('.container').forEach(container => {
                container.style.display = 'none'; // Hide all sections
            });

            // Show the selected section
            document.querySelector('.' + section + '-section').style.display = 'block';
        }

        // Show the home section by default
        showSection('home');
    </script>
</body>
</html>
