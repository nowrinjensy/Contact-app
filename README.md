# Contact-app
<!DOCTYPE html> 
<html> 
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title> Registration page</title>
<style> 
Body {
  font-family: Calibri;
  background-color: white;
}
button { 
       background-color: #4CAF50; 
       width: 100%;
        color: white; 
        padding: 15px; 
        margin: 10px 0px; 
        border: none; 
        cursor: pointer; 
         } 
 form { 
        border: 3px solid #f1f1f1; 
    } 
 input[type=text], input[type=password] { 
        width: 100%; 
        margin: 8px 0;
        padding: 12px 20px; 
        display: inline-block; 
        border: 2px solid black; 
        box-sizing: border-box; 
    }
 button:hover { 
        opacity: 0.7; 
    }  
 .container { 
        padding: 150px; 
        background-color: white;
    } 
</style> 
</head>  
<body>  
    <center> <h1> Sign In </h1> </center> 
    <form>
        <div class="container"> 
            <label>Username : </label> 
            <input type="text" placeholder="Enter Username" name="username" required>
            <label>Password : </label> 
            <input type="password" placeholder="Enter Password" name="password" required>
            <button type="submit">Sign In</button> 
            <a href="#"> Forget passsword?</a>
            <div class="bottom-links">
        <p>Don’t have an account? <a href="#"> Sign up</a></p>
      </div
        </div> 
    </form>   
</body>   
</html>



















































