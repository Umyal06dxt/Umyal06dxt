<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Umyal Dixit's GitHub</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #74b9ff, #a29bfe);
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            flex-direction: column;
            text-align: center;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            font-weight: 300;
        }

        .container {
            max-width: 800px;
            width: 100%;
            padding: 20px;
            border-radius: 10px;
            background-color: rgba(0, 0, 0, 0.6);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
        }

        .intro {
            margin-bottom: 20px;
            font-size: 1.2rem;
        }

        .icons {
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .icon {
            font-size: 2rem;
            transition: transform 0.3s ease-in-out;
        }

        .icon:hover {
            transform: scale(1.2);
            color: #ff7675;
        }

        .button {
            padding: 10px 20px;
            border: none;
            background-color: #0984e3;
            color: white;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #74b9ff;
        }

        footer {
            margin-top: 40px;
            font-size: 0.9rem;
            color: #b2bec3;
        }

        .highlight {
            color: #fd79a8;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Hi, I'm <span class="highlight">Umyal Dixit</span>!</h1>
        <h2>Welcome to my GitHub profile</h2>
        <div class="intro">
            I'm a passionate Computer Science student focused on AI, human emotions, and innovative projects like AI-driven facial expression recognition and micro-climate control systems. Let's connect and explore more together!
        </div>
        <button class="button" onclick="window.location.href='https://github.com/umyal'">Check out my projects</button>
        
        <div class="icons">
            <a href="https://linkedin.com/in/umyal" class="icon">🔗</a>
            <a href="mailto:umyal.dixit@email.com" class="icon">📧</a>
            <a href="https://twitter.com/umyal" class="icon">🐦</a>
        </div>
    </div>

    <footer>
        <p>I'm constantly learning and building. <br> Join me on my journey!</p>
    </footer>

    <script>
        // You can add any cool animations here later on!
        setTimeout(() => {
            document.body.style.background = "linear-gradient(135deg, #e84393, #6c5ce7)";
        }, 5000);
    </script>

</body>
</html>
