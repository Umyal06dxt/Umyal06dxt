<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Umyal Dixit's GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background: #2d3436;
            color: #fff;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
            overflow: hidden;
        }
        h1 {
            font-size: 3rem;
            color: #fd79a8;
            font-weight: 700;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 5px;
        }
        h2 {
            font-size: 1.5rem;
            color: #b2bec3;
            font-weight: 300;
            margin-bottom: 20px;
        }
        .intro {
            max-width: 600px;
            margin: 0 auto;
            font-size: 1.2rem;
            line-height: 1.6;
            color: #dfe6e9;
            margin-bottom: 30px;
        }
        .button {
            padding: 12px 25px;
            background-color: #0984e3;
            color: white;
            font-size: 1.1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }
        .button:hover {
            background-color: #74b9ff;
            transform: translateY(-3px);
        }
        .social-icons {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 25px;
        }
        .icon {
            font-size: 2rem;
            color: #fd79a8;
            transition: transform 0.3s ease;
        }
        .icon:hover {
            transform: scale(1.2);
            color: #00b894;
        }
        footer {
            position: absolute;
            bottom: 20px;
            font-size: 0.9rem;
            color: #b2bec3;
        }
        footer a {
            color: #0984e3;
            text-decoration: none;
        }
        footer a:hover {
            color: #fd79a8;
        }
        .highlight {
            color: #fd79a8;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Hi, I'm <span class="highlight">Umyal Dixit</span>!</h1>
    <h2>Welcome to my GitHub profile</h2>
    <div class="intro">
        I'm a passionate Computer Science student at LPU, focusing on Artificial Intelligence, human emotions, and innovative projects. I love solving problems with technology, especially when it has the potential to impact society in meaningful ways.
        <br><br>
        I believe in leadership through innovation and constantly push myself to learn and grow.
    </div>
    <button class="button" onclick="window.location.href='https://github.com/umyal'">Explore My Projects</button>
    <div class="social-icons">
        <a href="https://www.linkedin.com/in/umyal" class="icon" target="_blank">🔗</a>
        <a href="mailto:umyal.dixit@email.com" class="icon">📧</a>
        <a href="https://twitter.com/umyal" class="icon" target="_blank">🐦</a>
    </div>
    <footer>
        <p>I'm constantly learning, building, and collaborating. <br> Let's create something amazing together! <br><br> <a href="https://www.example.com" target="_blank">Visit my website</a></p>
    </footer>
</body>
</html>
