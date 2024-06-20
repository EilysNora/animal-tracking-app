<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animal Tracker Login</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
        }
        .login-container {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .login-container h1 {
            margin-bottom: 20px;
        }
        .login-container input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .login-container button {
            width: 100%;
            padding: 10px;
            background-color: #28a745;
            border: none;
            border-radius: 4px;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }
        .login-container button:hover {
            background-color: #218838;
        }
        .login-container a {
            color: #007bff;
            text-decoration: none;
        }
        .login-container a:hover {
            text-decoration: underline;
        }
        .login-container .footer {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <div>
            <img src="https://img.icons8.com/ios-filled/50/000000/paw.png" alt="Paw Icon" width="40">
        </div>
        <h1>Welcome to Animal Tracker</h1>
        <form>
            <input type="email" placeholder="Enter your email" required>
            <input type="password" placeholder="Enter your password" required>
            <button type="submit">Login</button>
        </form>
        <div class="footer">
            <a href="#">Forgot Password?</a><br>
            New to Animal Tracker? <a href="#">Contact us</a>
        </div>
    </div>
</body>
</html>
