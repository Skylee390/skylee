<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>贷款服务 - 快速获取贷款</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
        }
        .cta-button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
        }
        .cta-button:hover {
            background-color: #218838;
        }
        form {
            margin-top: 20px;
        }
        input[type="text"], input[type="email"], input[type="tel"] {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #555;
        }
        blockquote {
            margin-top: 20px;
            font-style: italic;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>快速获取贷款，解决燃眉之急</h1>
        <p>最低利率，无隐形费用，快速审批</p>
        <a href="#" class="cta-button">立即申请</a>
        <form action="submit_form.php" method="POST">
            <input type="text" name="name" placeholder="姓名" required><br>
            <input type="email" name="email" placeholder="邮箱" required><br>
            <input type="tel" name="phone" placeholder="电话" required><br>
            <button type="submit">提交申请</button>
        </form>
        <div>
            <p>客户评价：</p>
            <blockquote>"这是一家非常专业的贷款服务公司，他们的服务让我非常满意！" - 李四</blockquote>
        </div>
    </div>
</body>
</html>
