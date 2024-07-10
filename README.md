<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Login</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fafafa;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .login-container {
            background-color: #fff;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            width: 350px;
            text-align: center;
        }
        .login-container h1 {
            margin-bottom: 20px;
            color: #262626;
            font-size: 28px;
        }
        .login-container input[type="text"],
        .login-container input[type="password"] {
            width: calc(100% - 20px);
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #dbdbdb;
            border-radius: 4px;
            font-size: 14px;
        }
        .login-container input[type="submit"] {
            background-color: #3897f0;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 14px;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .login-container input[type="submit"]:hover {
            background-color: #38a1f0;
        }
        .login-container .forgot-password {
            font-size: 12px;
            color: #003569;
            text-decoration: none;
            margin-top: 10px;
            display: inline-block;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h1>Instagram</h1>
        <form action="https://www.instagram.com/accounts/login/" method="post">
            <input type="text" name="username" placeholder="Username or Email" required>
            <br>
            <input type="password" name="password" placeholder="Password" required>
            <br>
            <input type="submit" value="Log In">
        </form>
        <a href="#" class="forgot-password">Forgot password?</a>
    </div>
</body>
</html>