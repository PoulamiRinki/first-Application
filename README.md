<!DOCTYPE html>
<html lang="en">
<head> 
<meta charset="UTF-8"> 
<meta http-equiv="X-UA-Compatible" content="IE=edge"> 
<meta name="viewport" content="width=device-width, initial-scale=1.0">
 <link rel="stylesheet" href="login.css" /> 
<title>Login Page</title>
</head>
<body>
 <form>
 <!-- maxlength="10" --> 
<!-- pattern="" -->
 <!-- abcd@email.com ✔ // abcd ❌--> 
<h1>Login</h1> 
<input type="text" placeholder="username" /> 
<input type="password" placeholder="password" />
 <p>Enter Password: 4 character, 2 special character, 3 number</p> <!-- Tooltip --> 
<a href="registration.html">Click here to register</a>
 <br />
 <button type="submit">Login</button> 
</form>input { 
display: block; 
margin-top: 10px;
 margin-bottom: 10px;
}
h1{
 font-weight: 200;
}
body {
 background-color: pink;
}
a {
text-decoration: none;
}
button { 
margin-top: 10px;
}

</body>
</html>
