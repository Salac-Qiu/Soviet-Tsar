# Soviet-Tsar
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>属于沙皇</title>
    <style>
        body {
            margin: 0;
            height: 100vh; 
            background-image: linear-gradient(to right, #ff0000, #ffd700); 
            font-family: Arial, sans-serif;
            color: #fff; 
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            margin: 0;
        }
    </style>
</head>
<body>
    <h1>苏维埃沙皇</h1>
</body>
</html>
<html>
    <head>
    </head>
    <body>
        <h1>理想 体验和一切</h1>
    </body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的网站</title>
    <style>
        /* 设置整个页面的布局，保证页面根据内容自动调整 */
        html, body {
            margin: 0;
            padding: 0;
            height: 100%;
        }
        body {
            background-image: linear-gradient(to right, #ff7e5f, #feb47b);
            min-height: 100%;  /* 页面至少是100%高度 */
        }
        .content {
            padding: 20px;
            font-size: 18px;
            color: white;
        }
        .content h1 {
            font-size: 3em;
        }
        .scrollable {
            max-height: 100vh; /* 使页面最大高度等于视口高度 */
            overflow-y: auto;  /* 自动启用竖直滚动条 */
            padding-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="scrollable">
        <div class="content">
            <h1></h1>
            <p></p>
            <p>游戏主旨</p>
            <p>制作团队</p>
            <p></p>
            <p></p>
            <p></p>
            <p></p>
            <p></p>
            <p></p>
        </div>
    </div>
</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>超链接示例</title>
    <style>
        .scrollable {
            width: 100%;
            height: 300px;
            overflow: auto;
            background-color: lightyellow;
        }
        .content {
            height: 800px; /* 内容高度超过滚动区域 */
            background-color: lightcoral;
        }
        /* 给链接一些样式 */
        a {
            color: blue;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#game-purpose">游戏主旨</a></li>
            <li><a href="#team">制作团队</a></li>
        </ul>
    </nav>
    <div class="scrollable">
        <div class="content">
            <h1>欢迎来到游戏介绍页面</h1>
            <p>这是一个简单的网页示例。</p>
            <p>点击下面的链接进行跳转：</p>
            <!-- 目标区域（你要跳转到的地方） -->
            <h2 id="game-purpose">游戏主旨</h2>
            <p>这里描述了游戏的主旨内容。</p>
            <h2 id="team">制作团队</h2>
            <p>这里介绍了游戏的制作团队。</p>
        </div>
    </div>

</body>
</html>
