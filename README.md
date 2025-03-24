<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ibrahim's Profile</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #1e1e2e;
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 90%;
            max-width: 800px;
            background: #2a2a3a;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        h1 {
            color: #ffcc00;
            margin-bottom: 10px;
        }
        .badges img {
            width: 100px;
            margin: 5px;
        }
        .section {
            margin-top: 20px;
            padding: 15px;
            border-radius: 8px;
            background: #3a3a4a;
        }
        .skills, .tools, .languages {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .tag {
            background: #ffcc00;
            color: #1e1e2e;
            padding: 8px 15px;
            margin: 5px;
            border-radius: 20px;
            font-weight: 600;
        }
        .connect a {
            text-decoration: none;
            color: #ffcc00;
            font-weight: bold;
            margin: 10px;
        }
        .connect a:hover {
            color: #ffa500;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>👋 Hi, I'm Ibrahim!</h1>
        <p>AI enthusiast | Data Scientist | Software Developer</p>
        
        <div class="section">
            <h2>🧠 AI & Data Science Skills</h2>
            <div class="skills">
                <div class="tag">Machine Learning</div>
                <div class="tag">Deep Learning</div>
                <div class="tag">Data Science</div>
                <div class="tag">Data Analysis</div>
            </div>
        </div>

        <div class="section">
            <h2>🛠 Tools & Libraries</h2>
            <div class="tools">
                <div class="tag">Pandas</div>
                <div class="tag">NumPy</div>
                <div class="tag">Matplotlib</div>
                <div class="tag">Seaborn</div>
                <div class="tag">Scikit-Learn</div>
                <div class="tag">TensorFlow</div>
                <div class="tag">Keras</div>
            </div>
        </div>

        <div class="section">
            <h2>💻 Programming Languages</h2>
            <div class="languages">
                <div class="tag">Python</div>
                <div class="tag">Java</div>
                <div class="tag">JavaFX</div>
                <div class="tag">JavaScript</div>
                <div class="tag">HTML5</div>
                <div class="tag">CSS</div>
                <div class="tag">PHP</div>
            </div>
        </div>

        <div class="section connect">
            <h2>📫 Let's Connect!</h2>
            <a href="#">LinkedIn</a>
            <a href="#">GitHub</a>
            <a href="#">Portfolio</a>
        </div>
    </div>
</body>
</html>
