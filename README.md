<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sai Pranith Mugala</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
    <style>
        body {
            background-color: #f8f9fa;
            font-family: 'Arial', sans-serif;
        }

        h1, h2, h3 {
            color: #343a40;
        }

        .profile-img {
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .section-title {
            margin-top: 40px;
            font-size: 24px;
            font-weight: bold;
        }

        .bar {
            width: 80%;
            height: 2px;
            background-color: #343a40;
            margin: 0 auto 20px;
        }

        .icons img {
            margin-right: 20px;
        }

        .footer-icons i {
            font-size: 40px;
            margin-right: 15px;
            color: #007bff;
        }

        .card {
            margin: 20px 0;
            padding: 15px;
        }

        .project-link {
            color: #007bff;
            text-decoration: none;
        }

        .like-section {
            margin: 30px 0;
            font-size: 20px;
            color: #6c757d;
        }

        .like-button {
            font-size: 25px;
            color: #007bff;
            cursor: pointer;
        }

        .like-button.liked {
            color: red;
        }

        .quote-section {
            margin: 40px 0;
            text-align: center;
        }

        .quote-section button {
            padding: 10px 20px;
            font-size: 18px;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
        }

        .quote-display {
            margin-top: 20px;
            font-style: italic;
            font-size: 22px;
            color: #343a40;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: scale(0.9);
            }
            100% {
                opacity: 1;
                transform: scale(1);
            }
        }

        footer {
            margin-top: 50px;
            font-size: 18px;
        }

        .visitor-counter {
            margin: 20px 0;
            font-size: 22px;
            color: #6c757d;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            text-align: center;
            padding: 20px;
        }
        .section-title {
            font-size: 2em;
            color: #4a90e2;
            margin-bottom: 20px;
        }
        .quote-section {
            margin-top: 20px;
            padding: 20px;
            border: 2px solid #4a90e2;
            border-radius: 10px;
            background-color: #ffffff;
            transition: all 0.3s ease;
        }
        .quote-section:hover {
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }
        #quoteButton {
            padding: 10px 20px;
            font-size: 1.2em;
            color: white;
            background-color: #4caf50;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        #quoteButton:hover {
            background-color: #45a049;
        }
        .quote-display {
            font-size: 1.5em;
            color: #333;
            margin-top: 20px;
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }
        .visible {
            opacity: 1;
        }
    </style>
</head>

<body>
    <div class="container text-center">
        <p align="right">
            <a href="https://docs.google.com/document/d/1HeEkr6ZxXwDRXBxH6ZM4T22DTOBsKwjdjHNISRhO090/edit?usp=sharing"
                style="text-decoration:none">
                <i class="fas fa-file-alt"></i> <strong>My Resume</strong>
            </a>
        </p>

        <h1 class="display-4 mb-4">
            <img alt="Sai Pranith Mugala" class="profile-img" src="https://via.placeholder.com/150" width="150px" />
            Hello, Virtual Beings 👋, I'm <strong>Sai Pranith Mugala</strong>
        </h1>

        <div class="bar"></div>

        <section>
            <h2 class="section-title">About Me</h2>
            <p><i>I'm a Java Backend Developer with 3+ years of experience, specializing in creating scalable backend applications using Core Java (Java 8), Spring Boot, and microservices architecture. I have expertise in Spring MVC, Spring AOP, Spring Security, and database management (PostgreSQL, MySQL). Additionally, I work with ORM frameworks like Hibernate and Spring Data JPA.</i></p>

            <p><i>I've experience with front-end technologies like HTML, CSS, JavaScript, and Angular. I use Docker, Git, JUnit, and Agile methodologies to ensure top-quality development. I'm passionate about building secure, scalable, and maintainable software solutions.</i></p>
        </section>

        <section class="like-section">
            <i class="fas fa-thumbs-up like-button" id="likeButton"></i> <span id="likeCount">0</span> Likes
        </section>

        <section>
            <h2 class="section-title">Tools & Technologies</h2>
            <div class="icons d-flex justify-content-center">
                <img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/IntelliJ_IDEA_Icon.svg" alt="IntelliJ IDEA" width="80">
                <img src="https://yt3.googleusercontent.com/X-rhKMndFm9hT9wIaJns1StBfGbFdLTkAROwm4UZ3n9ucrBky5CFIeeZhSszFXBgQjItzCD0SA=s900" alt="Postman" width="80">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRASLBH37lru-UTcOTakcTdOsWuNoTEZpmSmA&s" alt="MySQL" width="80">
                <img src="data:image/png;base64,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" alt="Swagger" width="80">
                <img src="https://blog.cloudanalogy.com/wp-content/uploads/2020/03/vsc-01.jpg" alt="VSCode" width="80">
                <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub" width="80">
                <img src="data:image/jpeg;base64,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" alt="STS" width="80">
                <img src="data:image/png;base64,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" alt="Docker" width="80">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqD6sAj8raVxoy6fP9ZAQ8oQN6AddCO07nfA&s" alt="Jenkins" width="80">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQxboo9g6S9XYSoxPW5HEa8Tin9gp-tqkggWg&s" alt="SonarQube" width="80">
                <img src="data:image/jpeg;base64,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" alt="Jira" width="80">
            </div>
        </section>

        <section>
            <h2 class="section-title">Projects</h2>
            <p class="card">
                <i class="fas fa-laptop-code"></i> All my projects are available on 
                <a href="https://github.com/Msaipranith" class="project-link" target="_blank"><i class="fab fa-github"></i> GitHub</a>
            </p>
        </section>

        <section>
            
            
                <button id="quoteButton">✨ Click here and see the Magic! ✨</button>
                <p id="quoteDisplay" class="quote-display"></p>

        </section>

        <section>
            <h2 class="section-title">Contact</h2>
            <p><i class="fas fa-envelope"></i> Email: <a href="mailto:saipranithsunny@gmail.com">saipranithsunny@gmail.com</a></p>
            <p><i class="fas fa-file-alt"></i> View my <a href="https://docs.google.com/document/d/1YopmhiCAqMHdWBiYIzFb5wlN65umDAdF/edit?usp=sharing&ouid=111582633320935881139&rtpof=true&sd=true" target="_blank">Resume</a></p>
        </section>

        <section>
            <h2 class="section-title">Connect with Me</h2>
            <div class="footer-icons">
                <a href="https://www.linkedin.com/in/pranith0418/" target="_blank"><i class="fab fa-linkedin"></i></a>
                <a href="https://github.com/Msaipranith" target="_blank"><i class="fab fa-github"></i></a>
                <a href="mailto:saipranithsunny@gmail.com"><i class="fas fa-envelope"></i></a>
            </div>
        </section>

        <section>
            <h2 class="section-title">GitHub Stats</h2>
            <div class="d-flex justify-content-center">
                <a href="#"><img alt="GitHub Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs?username=Msaipranith&show_icons=true&theme=merko" height="192px" width="360px"></a>
            </div>
            <div class="d-flex justify-content-center">
                <a href="#"><img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=Msaipranith&theme=merko&show_icons=true" height="192px" width="430px"></a>
            </div>
        </section>

        <section>
            <h2 class="section-title">Github Streaks 🔥</h2>
            <p align="center">
                <a href="#"><img width="500px" src="https://github-readme-streak-stats.herokuapp.com/?user=Msaipranith&hide_border=true&theme=merko"></a>
            </p>
        </section>

        <footer>
            <p align="center" class="visitor-counter">💖 Lucky Visitor Number 💖</br>
                <img title="Visitor Count" align="center" alt="Visitor Count" width="200"
                    src="https://profile-counter.glitch.me/Msaipranith/count.svg" />
            </p>
        </footer>

    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Like Button Functionality
        let likeCount = 0;
        const likeButton = document.getElementById('likeButton');
        const likeDisplay = document.getElementById('likeCount');

        likeButton.addEventListener('click', function () {
            if (!this.classList.contains('liked')) {
                this.classList.add('liked');
                likeCount++;
                likeDisplay.textContent = likeCount;
            } else {
                this.classList.remove('liked');
                likeCount--;
                likeDisplay.textContent = likeCount;
            }
        });

        const quotes = [
            "😊 Smile! It's the key that fits the lock of everybody's heart.",
            "🌟 A smile is a universal welcome.",
            "💖 Your smile is a light in the window of your soul.",
            "😄 A smile can change the world!",
            "✨ Keep smiling, because life is a beautiful thing!",
        ];

        document.getElementById('quoteButton').addEventListener('click', function() {
            const quoteDisplay = document.getElementById('quoteDisplay');
            const randomQuote = quotes[Math.floor(Math.random() * quotes.length)];
            quoteDisplay.textContent = randomQuote;
            quoteDisplay.classList.remove('visible'); // Reset opacity
            void quoteDisplay.offsetWidth; // Trigger reflow to restart animation
            quoteDisplay.classList.add('visible'); // Add class to fade in
        });
    </script>
</body>

</html>
