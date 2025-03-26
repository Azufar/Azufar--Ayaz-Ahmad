<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Azufar - Biography</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        header {
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            background: linear-gradient(to right, #ff00ff, #00ffff);
            background-clip: text;
            -webkit-background-clip: text;
            -moz-background-clip: text;
            -o-background-clip: text;
            -ms-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            animation: slideUp 1.5s ease-in-out;
        }
        .social-icons a {
            margin: 10px;
            color: #00ffff;
            text-decoration: none;
            font-size: 20px;
            transition: transform 0.3s ease-in-out;
        }
        .social-icons a:hover {
            transform: scale(1.2);
        }
        .music-player {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            background-color: #ff00ff;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 20px;
            transition: transform 0.3s;
        }
        button:hover {
            background-color: #00ffff;
            transform: scale(1.1);
            box-shadow: 0px 0px 10px #00ffff;
        }
        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin-top: 20px;
            animation: pulse 2s infinite;
            box-shadow: 0px 0px 15px rgba(255, 0, 255, 0.8);
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes pulse {
            0% { transform: scale(1); box-shadow: 0px 0px 15px rgba(255, 0, 255, 0.8); }
            50% { transform: scale(1.05); box-shadow: 0px 0px 25px rgba(0, 255, 255, 0.8); }
            100% { transform: scale(1); box-shadow: 0px 0px 15px rgba(255, 0, 255, 0.8); }
        }
        .glow-text {
            text-shadow: 0px 0px 10px #ff00ff;
            transition: text-shadow 0.5s ease-in-out;
        }
        .glow-text:hover {
            text-shadow: 0px 0px 20px #00ffff;
        }
    </style>
</head>
<body>
    <header class="glow-text">Azufar</header>
    <div class="container">
        <a href="https://www.instagram.com/azu__far/" target="_blank">
            <img src="/mnt/data/photo_2025-01-17_09-13-12.jpg" alt="Azufar" class="profile-img">
        </a>
        <h2 class="glow-text">About Me</h2>
        <p>Azufar—a name that echoes more than just music. Born as Ayaz Ahmad in Jamshedpur, Jharkhand, he carries a soul that feels deeply, loves endlessly, and creates fearlessly. A firm believer in one God and the equality of all humans, he pours his heart into every beat, every mix, and every melody, not just to entertain but to awaken something greater—humanity.</p>
        <p>Life hasn’t been easy for him. He’s walked through storms most wouldn’t dare, carrying the weight of childhood and teenage traumas. But instead of breaking, he built himself anew. Every struggle became a verse, every tear a rhythm, and every heartbreak a lesson. Through his music, he doesn’t just tell his story—he tells yours, mine, and ours.</p>
        <p>Beyond the studio, he finds solace in the gym, on the football field, and in the art of editing, always pushing the boundaries of creativity. But at the core of it all, Azufar is more than an artist—he’s a movement, a feeling, a reminder that we are all one, united by love, music, and the heartbeat of humanity.</p>
        
        <h2 class="glow-text">My Work</h2>
        <p>Check out my latest projects and music below!</p>
        <div class="music-player">
            <p>Listen to my latest track:</p>
            <audio controls>
                <source src="https://open.spotify.com/artist/2BVsvqNhFgmqrBynJdVv89" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
        
        <h2 class="glow-text">Connect with Me</h2>
        <div class="social-icons">
            <a href="https://www.instagram.com/azu__far/" target="_blank">Instagram</a>
            <a href="https://open.spotify.com/artist/2BVsvqNhFgmqrBynJdVv89" target="_blank">Spotify</a>
        </div>
        
        <h2 class="glow-text">Contact Me</h2>
        <button onclick="alert('Contact me at: azuthink4tyourself@gmail.com')">Email Me</button>
    </div>
</body>
</html>
