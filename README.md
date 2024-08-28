# login-form
we  are using to create html and css

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<style>
body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: linear-gradient(135deg, #a8d3a8, #a8e0e8);
    font-family: Arial, sans-serif;
}

.login-container {
    background: rgba(255, 255, 255, 0.7);
    border-radius: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.2);
    padding: 40px 50px;
}

.login-form {
    display: flex;
    flex-direction: column;
}

.login-form input[type="text"], 
.login-form input[type="password"] {
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 10px;
    margin: 10px 0;
    font-size: 16px;
}

.login-form button {
    background-color: #58C9EF;
    color: white;
    border: none;
    border-radius: 5px;
    padding: 10px;
    font-size: 18px;
    cursor: pointer;
    margin: 20px 0;
}

.login-form button:hover {
    background-color: #3BA9D5;
}

.extra-options {
    text-align: center;
    margin-top: 10px;
}

.extra-options a {
    color: #333;
    text-decoration: none;
}

.extra-options a:hover {
    text-decoration: underline;
}



</style>

    <div class="login-container">
        <form class="login-form">
            <input type="text" placeholder="username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
            <div class="extra-options">
                <a href="#">Forgot password?</a> or <a href="#">sign Up</a>
            </div>
        </form>
    </div>
</body>
</html>
