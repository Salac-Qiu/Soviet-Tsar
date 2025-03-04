<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>属于沙皇</title>
    <style>
        /* 确保页面全屏显示并且有渐变背景 */
        html, body {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
        }
        body {
            background-image: linear-gradient(to right, #ff0000, #ffd700);
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }
        h1 {
            font-size: 3em;
        }
        .section {
            height: 100vh; /* 每个部分的高度设置为视口高度 */
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .section:nth-child(1) {
            background-color: #ff7e5f; /* 第一部分的背景 */
        }
        .section:nth-child(2) {
            background-color: #feb47b; /* 第二部分的背景 */
        }
        .section:nth-child(3) {
            background-color: #6a82fb; /* 第三部分的背景 */
        }
        a {
            color: white;
            text-decoration: none;
            font-size: 1.5em;
            margin-top: 20px;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="section">
        <div>
            <h1>苏维埃沙皇</h1>
            <p>理想、体验和一切</p>
            <a href="#section2">下一部分</a>
        </div>
    </div>
    <div class="section" id="section2">
        <div>
            <h1>游戏主旨</h1>
            <p>这部分介绍游戏的主要内容和玩法。</p>
            <a href="#section3">下一部分</a>
        </div>
    </div>
    <div class="section" id="section3">
        <div>
            <h1>制作团队</h1>
            <p>这里列出参与游戏制作的团队成员。</p>
            <a href="#">返回顶部</a>
        </div>
    </div>

</body>
</html>
