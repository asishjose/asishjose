<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Okinea Dev</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.2/p5.min.js"></script>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #0d1117;
            color: #c9d1d9;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            overflow-x: hidden;
        }
        .container {
            text-align: center;
            padding: 40px 20px;
            position: relative;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        h1 span {
            margin-right: 10px;
        }
        p {
            font-size: 1.1em;
            line-height: 1.6;
            max-width: 600px;
            margin: 0 auto 20px;
        }
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        #canvas {
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            z-index: -1;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><span>Hi 👋</span>, I'm Asish</h1>
        <p>I'm currently diving deep into Machine Learning and exploring exciting fields like NLP, Data Science, and Computer Vision</p>
        <p>I enjoy working on ML projects, experimenting with datasets on Kaggle, and contributing to open-source whenever I can.</p>
        <p>My focus is on building practical solutions and growing step by step in the world of AI.  </p>
    </div>
    <div id="canvas"></div>

    <script>
        let angle = 0;

        function setup() {
            let canvas = createCanvas(600, 600);
            canvas.parent('canvas');
            background(13, 17, 23);
            noFill();
            stroke(201, 209, 217);
        }

        function draw() {
            background(13, 17, 23, 20); // Semi-transparent background for motion effect
            translate(width / 2, height / 2);
            for (let i = 0; i < 360; i += 15) {
                let rad = radians(i);
                let r = 200 + sin(rad + angle) * 30; // Dynamic radius for wave-like motion
                let x = r * cos(rad);
                let y = r * sin(rad);
                strokeWeight(2);
                point(x, y); // White dots with motion
            }
            angle += 0.03; // Adjust speed of rotation
        }
    </script>
</body>
</html>
-    "We live in the time of cutting edge obsolescence"

## 🛠️ Tech Stack
| Skills 💡 | Tools ⚙️ | Learning 📚 |
|----------|-----------|-------------|
| ![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python) ![JS](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript) | ![Django](https://img.shields.io/badge/-Django-05122A?style=flat&logo=django) ![Postgres](https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql) | ![ML](https://img.shields.io/badge/-Machine%20Learning-05122A?style=flat&logo=scikit-learn) ![NLP](https://img.shields.io/badge/-NLP-05122A?style=flat&logo=ai) |
| ![HTML](https://img.shields.io/badge/-HTML5-05122A?style=flat&logo=html5) ![CSS](https://img.shields.io/badge/-CSS3-05122A?style=flat&logo=css3) | ![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git) ![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github) | ![Docker](https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker) |

## 📈 GitHub Stats
![Asish's GitHub Stats](https://github-readme-stats.vercel.app/api?username=asishjose&show_icons=true&theme=radical)


<p align="center">
  <img src="https://img.shields.io/badge/Quote-First%2C%20solve%20the%20problem%2C%20then%20write%20the%20code.-blueviolet?style=for-the-badge&logo=python&logoColor=white" alt="quote badge"/>
</p>

<!---
asishjose/asishjose is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
