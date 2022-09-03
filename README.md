<!DOCTYPE html>
<html lang="en">
<head>
    <title>Website page</title>
    <link rel="stylesheet" href="stylesheet.css">
</head>
<body>
   
    <form class="form" action="">
        <h1 class="reg">Register Form</h1>
        <label class="f1" for="">First Name</label><br>
        <input class="f2" type="text" placeholder=" Enter First Name"><br><br><br>
        <label class="l1" for="">Last Name</label><br>
        <input class="l2" type="text" placeholder="Enter Last Name"><br><br><br>
        <label class="pass" for="">Password</label><br>
        <input class="p1" type="password" placeholder="Password"><br><br><br>
        <label class="p3" for="">Confirm Password</label><br>
        <input class="p4" type="password" placeholder="Confirm Password"><br><br>
        <input type="radio" name="gender">
        <label>By signing up,you agree to <br> <a href="terms.html" class="">Play Terms of Service</a></label><br><br>
        <button type="submit"  class="sub"> <a href="login.html" class="li"> Register</a> </button>
    </form>
   
</body>
</html>
---------------------------index.html--------------
body{
    margin: 0%;
    padding: 0%;
    background-image: url("image/kumar.jpg");
    background-position: center;
    background-size: cover;

}
.reg{
    color: aliceblue;
}
.form{
    text-align: center;
    margin-top: 150px;
    border-radius: 5px;
    background-color: rgb(19, 141, 141);
    width: 250px;
    height: 65vh;
    margin-left: 900px;
    padding-top: 2px;
}
.f2{
    border: none;
    border-bottom: 1px solid black;
    outline: none;
    background: transparent;
    color: white;
}
::placeholder{
    color: white;
    opacity: 0.9;
}
.l2{
    border: none;
    border-bottom: 1px solid black;
    outline: none;
    background: transparent;
    color: white;
}
.p1{
    border: none;
    border-bottom: 1px solid black;
    outline: none;
    background: transparent;
    color: white;

}
.p4{
    border: none;
    border-bottom: 1px solid black;
    outline: none;
    background: transparent;
    color: white;
}
.f1{
    margin-left: -100px;
}
.l1{
    margin-left: -100px
}
.pass{
    margin-left: -110px
}
.p3{
    margin-left: -50px
}
.sub:hover{
   background-color: rgb(25, 111, 240);
   color: white;
}
.li{
    color: black;
    text-decoration: none;
}
------------------------------cs----------------
