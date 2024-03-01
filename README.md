# Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>HTML</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Page</title>
<style>
    body {
        background-color: #332F7D;
        font-family: 'Times New Roman', Times, serif;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }
    .container {
        background-color:#332F7D;
        padding: 10px;
        border-radius: 10px;
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    }
    input[type="text"],
    input[type="password"] {
        width: 100%;
        padding: 10px;
        margin: 10px 0;
        border: none;
        border-radius: 5px;
        font-size: 16px;
        color: black;
        background-color:#A1F949;
    }
    input[type="submit"] {
        width: 100%;
        padding: 10px;
        margin-top: 20px;
        border: none;
        border-radius: 5px;
        background-color:skyblue;
        color: #fff;
        font-size: 18px;
        cursor: pointer;
        font-family:Times 'Times New Roman', Times, serif
    }
 img {
            width:100px;
            height:100px;
            position: absolute;
            top: 20%;
            left: 50%;
            transform: translate(-50%, -50%);
    }
   h6 {
           text-align: center
   }
</style>
</head>
<body>
<div class="container">
        <img src="login.jpeg">
    <h6 style="color: black;">Welcome to stressslavvy site. Diacover techniques in overcoming stress</h6>
    <form action="#" method="post">
        <input type="text" name="username" placeholder="username"> 
        <input type="text" name="email" placeholder="Email">
        <input type="password" name="password" placeholder="Password">
        <input type="password" name="confirm_password" placeholder="Confirm password">
        <a href="home.html" type="submit" value="Login">login<a>
                
                <!--Tab to edit-->
        </a>
        
    </form>
</div>
</body>
</html>

  <!-- Project -->
  <script src="main.js"></script>
</body>
</html>
