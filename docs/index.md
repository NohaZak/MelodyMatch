# MelodyMatch Landing Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MelodyMatch</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .cover {
            background-image: url('cover-image.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }
        .cover h1 {
            font-size: 3em;
        }
        .cover p {
            font-size: 1.5em;
        }
        .features, .about {
            padding: 20px;
            text-align: center;
        }
        .features img, .about img {
            width: 100%;
            max-width: 300px;
            height: auto;
        }
        .features .feature, .about .team-member {
            margin: 20px 0;
        }
        .video {
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#features">Features</a>
            <a href="#about">About</a>
            <a href="https://deployed-project-link.com">Try MelodyMatch</a>
        </nav>
    </header>
    <div class="cover">
        <div>
            <h1>MelodyMatch</h1>
            <p>Your personalized music recommender</p>
        </div>
    </div>
    <section id="features" class="features">
        <h2>Key Features</h2>
        <div class="feature">
            <img src="feature1.jpg" alt="Personalized Playlists">
            <h3>Personalized Playlists</h3>
            <p>MelodyMatch creates personalized playlists based on your listening history and preferences. By analyzing your favorite songs and genres, it curates a unique playlist that matches your musical taste.</p>
        </div>
        <div class="feature">
            <img src="feature2.jpg" alt="Real-time Recommendations">
            <h3>Real-time Recommendations</h3>
            <p>Get real-time song recommendations as you listen. MelodyMatch uses advanced algorithms to suggest songs that complement your current playlist, ensuring a seamless and enjoyable listening experience.</p>
        </div>
        <div class="feature">
            <img src="feature3.jpg" alt="Social Sharing">
            <h3>Social Sharing</h3>
            <p>Share your favorite playlists and songs with friends on social media. MelodyMatch allows you to connect with other music enthusiasts, discover new tracks, and share your musical journey with the world.</p>
        </div>
    </section>
    <section id="about" class="about">
        <h2>About MelodyMatch</h2>
        <p>MelodyMatch was inspired by our love for music and the desire to help people discover new songs they will love. This project started as a portfolio project for Holberton School and has grown into a full-fledged application.</p>
        <div class="team-member">
            <img src="team-member1.jpg" alt="Team Member 1">
            <h3>Noha Zakaria</h3>
            <p>Full-stack developer passionate about coding and creating applications.</p>
            <p>
                <a href="https://www.linkedin.com/in/noha-zakaria">LinkedIn</a> |
                <a href="https://github.com/NohaZak">GitHub</a> |
                <a href="https://twitter.com/noha_zakaria">Twitter</a>
            </p>
        </div>
        <p><a href="https://github.com/NohaZak/MelodyMatch">GitHub Repository</a></p>
    </section>
    <section class="video">
        <h2>Project Video</h2>
        <video controls>
            <source src="project-video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>
</body>
</html>
