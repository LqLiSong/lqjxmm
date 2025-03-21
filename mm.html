<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>查看密码与授权码</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .result {
            margin-top: 20px;
            font-size: 16px;
        }
        .error {
            color: red;
        }
    </style>
</head>
<body>
    <h1>密码验证</h1>
    <input type="password" id="password" placeholder="请输入密码">
    <button onclick="checkPassword()">验证</button>
    <div class="result" id="result"></div>

    <script>
        const encodedUrl = "aHR0cHM6Ly9scWxpc29uZy5naXRodWIuaW8vbHFqeG1tL3NxbS5qc29u";
        const jsonUrl = atob(encodedUrl); // 解码为原始URL
        async function fetchData() {
            const response = await fetch(jsonUrl);
            return await response.json();
        }
        function getDayOfYear() {
            const now = new Date();
            const start = new Date(now.getFullYear(), 0, 0);
            const diff = now - start;
            const oneDay = 1000 * 60 * 60 * 24;
            return Math.floor(diff / oneDay);
        }
        async function checkPassword() {
            const password = document.getElementById('password').value;
            const data = await fetchData();
            const x = getDayOfYear();
            const a = data[x - 1] || ['000', '000', '000'];
            const b = data[x] || ['000', '000', '000'];
            const c = data[data.length - 1];

            const resultDiv = document.getElementById('result');
            if (password === c[2]) {
                resultDiv.innerHTML = `
                    <p>今日密码，上午：${a[0]}，下午：${a[1]}，授权码：${a[2]}</p>
                    <p>明日密码，上午：${b[0]}，下午：${b[1]}，授权码：${b[2]}</p>
                `;
            } else {
                resultDiv.innerHTML = `<p class="error">密码错误！</p>`;
            }
        }
    </script>
</body>
</html>



                    
                
