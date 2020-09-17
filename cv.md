# **Information**
## **Name**: Stanislav
## **Surname**: Cherednichenko
## **Contacts**: PardonneDP@gmail.com    +38-063-253-80-40
## **Skills**: HTML CSS JS Angular beginner level
## **Code**: 
``` 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Авторизация</title>
    <style>
        .form-container{
    
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0 auto;
            font-family: sans-serif;
        }
    
        h2{
            text-align: center;
        }
    
        form{
            flex-basis: 70vh;
            padding: 2em;
            background: #fff;
            box-shadow: 0 0 2em rgba(0,0,0,0.20);
            border-radius: 0.50em;
        }
    
        input{
            padding: 0.5em;
            font-size: 0.875em;
            background: #f4f4f4;
            border: 1px solid #ccc;
            border-width: 1px 1px 1px 0;
            border-radius: 0;
        }
    
        input:focus{
            background: #fff;
            box-shadow: inset 0.1em 0.1em 0.25em rgba(0,0,0,0.2);
        }
    
        .form-field{
            margin-bottom: 1em;
            display: flex;
        }
    
        .form-field label{
            flex: 0 1 4em;
            padding: 1em 2em;
            background: #fff;
            border: 1px solid #ccc;
            font-size: 0.75em;
            text-align: center;
            text-shadow: 0 1px 0 #fff;
            line-height: 1;
            border-radius: 0.25em 0 0 0.25em;
        }
    
        .form-field input{
            flex-grow: 1;
        }
    
        .input-right input, .multy-input input:last-child{
            border-radius: 0 0.25em 0.25em 0;
        }
    
        .submit-field{
            flex-direction: row;
            justify-content: center;
        }
    
        input[type="button"]{
            flex: 0 1 40%;
            padding: 0.8em;
            font-size: 1.2rem;
            background: #689CD2;
            border-radius: 0.25em;
            border: 0;
            transition: 0.3s;
            cursor: pointer;
        }
    
        input[type="button"]:hover{
            color: #fff;
        }
    
    </style>
</head>
<body>
    
    <div class = "form-container">
        <form action="">
            <h2>Авторизация</h2>
            <div class="form-field input-right">
                <label for="email">E-mail</label>
                <input type="email" name="email" id="email" placeholder="Введите email"">
            </div>
            <div class="form-field input-right">
                <label for="pass">Password</label>
                <input type="password" name="pass" id="pass" placeholder="Введите пароль"">
            </div>
            <div class="form-field submit-field">
                <input type="button" id="button" value="Войти">
            </div>
        </form>
    </div>

    <script>
        let email = localStorage.getItem('email');
        let password = localStorage.getItem('password');
        let trueFields;
        let isAuth = false;

        button.onclick = function(){
            trueFields = 0;
            if (document.getElementById('email').value.match(/^([a-z0-9]{4,10})+@([a-z]{4,10})+.([a-z]{2,5})$/i)){
                if (document.getElementById('email').value == email){
                       trueFields++;
                }
            }
            if (document.getElementById('pass').value.match(/^[A-Z0-9]{4,}$/i)){
                if (document.getElementById('pass').value == password){
                       trueFields++;
                }
            }
            if (trueFields == 2){
                localStorage.setItem('auth', true);
                location.href = 'profile.html'
            }
            
        }
        

    </script>

</body>
</html>
```

## **Expirience**: IMT Academy Cources, self education
## **Education**: IMT Academy Cources, self education
## **English lvl**: Pre-Intermediate