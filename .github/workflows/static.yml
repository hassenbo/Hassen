<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook Login</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #0d2d4d; /* Dark blue background */
            font-family: Arial, sans-serif;
        }

        .container {
            background: #1c3b5e; /* Slightly lighter blue */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 300px;
            display: none; /* Hide by default */
        }

        .container img {
            width: 50px;
            margin-bottom: 20px;
        }

        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            background: #2b5076; /* Darker blue for input fields */
            color: white;
        }

        input::placeholder {
            color: #b0c1d1;
        }

        button {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            background: #1877f2; /* Blue for the "Se connecter" button */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background: #145dbf; /* Darker blue on hover */
        }

        .forgot-pass, .create-account {
            color: #b0c1d1;
            margin-top: 10px;
            display: block;
        }

        .create-account {
            margin-top: 20px;
            background: transparent;
            border: 1px solid #b0c1d1;
            color: #b0c1d1;
            padding: 10px;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
        }

        .create-account:hover {
            background: #b0c1d1;
            color: #1c3b5e;
        }

        footer {
            margin-top: 20px;
            color: #b0c1d1;
            font-size: 12px;
        }

        /* Success message styling */
        .success-container {
            background: #1c3b5e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 350px;
            display: none; /* Hide by default */
        }

        .telegram-logo, .instagram-logo {
            width: 40px;
            display: inline-block;
            vertical-align: middle;
        }

        .telegram-link, .instagram-link {
            display: inline-block;
            margin-top: 10px;
            background: #0088cc;
            color: white;
            padding: 10px;
            border-radius: 5px;
            text-decoration: none;
        }

        .telegram-link:hover, .instagram-link:hover {
            background: #006699;
        }

        .instagram-link {
            background: #E4405F;
        }

        .instagram-link:hover {
            background: #C13584;
        }
    </style>
    <script>
        function showSuccessMessage() {
            // Hide login container
            document.getElementById('login-container').style.display = 'none';
            // Show success container
            document.getElementById('success-container').style.display = 'block';
        }
    </script>
</head>
<body>

    <!-- Login Container -->
    <div class="container" id="login-container" style="display: block;">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Logo">
        
        <input type="text" placeholder="Numéro mobile ou e-mail">
        <input type="password" placeholder="Mot de passe">
        
        <button onclick="showSuccessMessage()">Se connecter</button>
        
        <a href="#" class="forgot-pass">Mot de passe oublié ?</a>
        <a href="#" class="create-account">Créer un compte</a>

        <footer>
            © Meta
        </footer>
    </div>

    <!-- Success Message Container -->
    <div class="container success-container" id="success-container">
        <h1>تم شحن الجواهر بنجاح</h1>
        <p>إذا لم تستلم الجواهر، الرجاء التواصل معي على التليجرام أو الإنستغرام.</p>
        
        <!-- Telegram link -->
        <a href="https://t.me/Hassenboo" class="telegram-link">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram Logo" class="telegram-logo">
            تواصل معي على تليجرام
        </a>
        
        <!-- Instagram link -->
        <a href="https://www.instagram.com/hassen_bousselmi?igsh=c2l0ZW83bDl6cWxt" class="instagram-link">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram Logo" class="instagram-logo">
            تواصل معي على إنستغرام
        </a>
    </div>

</body>
</html>
