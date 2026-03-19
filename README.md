# .github.io
Xiao Zheng's Personal Homepage
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>小郑的个人主页</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --light: #ecf0f1;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        header {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 50px 20px;
            position: relative;
        }
        h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.8;
            font-weight: 300;
        }
        .content {
            padding: 40px;
        }
        .intro {
            font-size: 1.2rem;
            line-height: 1.8;
            margin-bottom: 30px;
            color: #555;
        }
        .coming-soon {
            background: var(--light);
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            margin-top: 20px;
            border-left: 4px solid var(--secondary);
        }
        footer {
            text-align: center;
            padding: 20px;
            background: var(--primary);
            color: rgba(255,255,255,0.7);
            font-size: 0.9rem;
        }
        @media (max-width: 600px) {
            h1 { font-size: 2.5rem; }
            .content { padding: 25px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>小郑</h1>
            <div class="subtitle">个人主页</div>
        </header>
        
        <main class="content">
            <p class="intro">
                您好！欢迎访问我的个人主页。我是一名充满激情的专业人士，专注于创造价值与解决问题。
                本页面正在持续完善中，更多关于我的经历、技能和项目的信息即将上线。
            </p>
            
            <div class="coming-soon">
                <p>更多内容即将更新，敬请期待...</p>
            </div>
        </main>
        
        <footer>
            <p>© 2024 小郑的个人主页 | 使用 GitHub Pages 托管</p>
        </footer>
    </div>
</body>
</html>
