<html>
<head>
    <title>Sign in to Twitter</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #ffffff;
        }
        .container {
            text-align: center;
            width: 300px;
        }
        .twitter-logo {
            font-size: 40px;
            color: #1DA1F2;
        }
        h1 {
            font-size: 24px;
            font-weight: bold;
            margin: 20px 0;
        }
        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
        }
        .btn-google {
            background-color: #ffffff;
        }
        .btn-apple {
            background-color: #ffffff;
        }
        .btn-google i, .btn-apple i {
            margin-right: 10px;
        }
        .or {
            margin: 20px 0;
            color: #657786;
        }
        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .btn-next {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            background-color: #000000;
            color: #ffffff;
            border: none;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
        }
        .forgot-password {
            margin: 10px 0;
            color: #1DA1F2;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="twitter-logo">
            <i class="fab fa-twitter"></i>
        </div>
        <h1>Sign in to Twitter</h1>
        <div class="btn btn-google">
            <i class="fab fa-google"></i> Sign in with Google
        </div>
        <div class="btn btn-apple">
            <i class="fab fa-apple"></i> Sign in with Apple
        </div>
        <div class="or">or</div>
        <input type="text" class="input-field" placeholder="Phone, email, or username">
        <button class="btn-next">Next</button>
        <div class="forgot-password">Forgot password?</div>
    </div>
</body>
</html>
