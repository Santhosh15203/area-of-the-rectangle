!<!DOCTYPE html>
<html lang="en">
<head>
    <title>Register Form</title>
    <link rel="stylesheet" href="register.css">
    
</head>
<body>
    <form class="form" action="">
    <h3 class="h1">INFORMATION</h3>
    <p class="para">A registration form is a list of fields that a user will input data <br>into and submit to a company or individual. There are many <br>reasons why you would want a person to fill out a registration<br> form.Companies use registration forms to sign up customers for subscriptions, services, or other programs or plans.
        <br> <br>On your registration pages, you shouldn’t have a large number <br>of links or unrelated content because this looks a lot like spam.  Keep it simple, and have only the form on there, along with your logo if you’d like.The registration page should be on your landing page and should not be listed on another website, for the best results. This way, your customer or client will not be tempted to leave your website before signing up.<br><br>A Login form is used to enter authentication credentials to access <br>a restricted page or form. The login form contains a field for the username and another for the password.When the login form is submitted its underlying code checks that the credentials are authentic, giving the user can access the restricted page.</p>
    <button class="but"><a href="index.html" class="li">Sign In</a></button>
    </form>  
    <form class="design" action="">
        <h3 class="head">REGISTERATION  FORM</h3> 
        <h4 class="h9">Please fill in this form to create an account. </h4>

        <span class="first"><label class="na" for=""> First Name</label><br>
        <input class="n2" type="text" placeholder="Enter First Name">
        </span>
       
        <span class="second"> <label class="s1" for="">Last Name</label><br>
        <input class="s2" type="text" placeholder="Enter last Name">
        </span><br>
        <span class="mail">
            <label class="m1" for="">E-mail ID</label><br>
            <input class="m2" type="mail" placeholder="xyz123@gmail.com">
        </span>
        <span class="gen" >
            <p class="gen1" >Gender <br><br>
                <input class="r1" type="radio" name="gender">
                <label for="">Male</label>
                <input class="r2" type="radio" name="gender">
                <label for="">Female</label>
                <input class="r3" type="radio" name="gender">
                <label for="">Others</label>
            </p>
        </span>
        <span class="pass">
            <label class="p1" for="">Password</label><br>
            <input type="text" class="p2" placeholder="Password">
        </span>
        <span class="phone">
            <label class="ph1" for="">Phone Number</label><br>
            <select class="ph2" name="" id="">
                <option >+93</option>
                <option >+61</option>
                <option >+880</option>
                <option >+32</option>
                <option >+55</option>
                <option >+1</option>
                <option >+86</option>
                <option >+45</option>
                <option >+20</option>
                <option >+358</option>
                <option >+33</option>
                <option >+49</option>
                <option >+30</option>
                <option >+299</option>
                <option >+852</option>
                <option >+354</option>
                <option >+91</option>
                <option >+62</option>
                <option >+964</option>
                <option >+353</option>
                <option >+972</option>
                <option >+39</option>
                <option >+81</option>
                <option >+60</option>
                <option >+52</option>
                <option >+95</option>
                <option >+977</option>
                <option >+31</option>
                <option >+64</option>
                <option >+850</option>
                <option >+92</option>
                <option >+63</option>
                <option >+48</option>
                <option >+7</option>
                <option >+966</option>
                <option >+381</option>
                <option >+65</option>
                <option >+27</option>
                <option >+82</option>
                <option >+34</option>
                <option >+94</option>
                <option >+268</option>
                <option >+41</option>
                <option >+886</option>
                <option >+66</option>
                <option >+90</option>
                <option >+380</option>
                <option >+44</option>
                <option >+1</option>
                <option >+84</option>
            </select>
            <input class="ph3" type="phone" placeholder="97*** *****"><br><br>
        </span>
        <span class="add">
            <label class="add1" for="">Address</label><br>
            <textarea class="add2"  name="address" placeholder="Permanent Address..." cols="30" rows="9"></textarea>
        </span>
        <span class="state">
            <label class="sa1">State</label><br>
            <input class="sa2" type="text" placeholder="State">
        </span>
        <span class="dist">
            <label class="di1">District</label><br>
            <input class="di2" type="text" placeholder="District">
        </span>
        <span class="pincode">
            <label class="pin1">Pincode</label><br>
            <input class="pin2" type="number" placeholder="Pincode">
        </span>
        <span class="last">
            <label class="la1">By creating an account you agree to our <a href="#" class="la2"> Terms & Privacy.</a> </label>
        </span>
        <button class="button" type="submit">Register</button>





    </form>
</body>
</html>
---------------------------------------------------egister.html--------------------------------------------------------------------------
body{
    margin: 0%;
    padding: 0%;
    background-image:url("image/register.png");
    background-position: cover;
}
.form{
    top: 0%;
    color: white;
    background-color: #125688;
    position: absolute;
    width: 540px;
    height: 100vh;
}
.h1{
    padding-top: 20px;
    color:white;
    text-align: center;
}
.para{
    color: white;
    padding-top: 35px;
    padding-left: 45px;
    font-size: large;
    line-height: 20px;
}
.but{
    margin-left: 45px;
    width: 80px;
    height: 5vh;
    background-color: rgb(189,0,0);
    border-bottom: none;
    border-top: none;
    border-left: none;
    border-right: none;
    border-radius: 5px;
    font-size:smaller;
}
.li{
    color: white;
    text-decoration: none;
    border-color: #125688;
    cursor: pointer;
}
.but:hover{
    background-color:  rgb(175, 54, 54);
}
.design{
    top: 0%;
    right: -20px;
    color: white;
    background-color: transparent;
    position: absolute;
    width: 760px;
    height: 100vh;
}
.head{
    color: white;
    text-align: center;
    margin-top: 30px;
}
.first{
    padding-left: 80px;
    margin-top: 10px;
    position: absolute;
    
}
.n2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
}
::placeholder{
    color: white;
    opacity:0.5;
}
.second{
    padding-left: 400px;
    margin-top: 10px;
    position: absolute;
}
.s2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
}
.mail{
    padding-left: 80px;
    margin-top: 55px;
    position: absolute;
}
.m2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
}
.pass{
    padding-left: 400px;
    margin-top: 60px;
    position: absolute;
}
.p2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;

}
.h9{
    text-align: center;
}
.gen{
    padding-left: 80px;
    margin-top: 110px;
    position: absolute;
}
.gen1{
    width: 250px;
    height: 4vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    
    color: white;
}
.na{
    font-size: 15px;
    font-weight:400;
}
.add{
    padding-left: 80px;
    margin-top: 190px;
    position: absolute;
}
.add2{
    width: 580px;
    height: 8vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white;
    color: white;
    margin-top: 15px;
    font-size: 15px;
    font-weight: 190px;
}
.phone{
    padding-left: 400px;
    margin-top: 130px;
    position: absolute;
}
 .ph2{
    width: 60px;
    height: 5vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: rgb(73, 90, 154);
    border-bottom: 1px solid white;
    color: white;
    margin-top: 7px;
    font-size: 15px;
    font-weight: 190px;
 }
 .ph3{
    width: 185px;
    height: 5vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white;
    color: white;
 }
 .state{
    padding-left: 80px;
    margin-top: 290px;
    position: absolute;
 }
 .sa2{
    width: 180px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
 }
 .dist{
    padding-left: 280px;
    margin-top: 290px;
    position: absolute;
 }
 .di2{
    width: 180px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
 }
 .pincode{
    padding-left: 480px;
    margin-top: 290px;
    position: absolute;
 }
 .pin2{
    width: 180px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
 }
 .last{
    padding-left: 80px;
    margin-top: 380px;
    position: absolute;
 }
 .la2{
    color: rgb(191, 255, 0);
 }
 .button{
   
    margin-top: 420px;
    position: absolute;
    text-align: center;
    width: 600px;
    margin-left: 70px;
    height: 5vh;
    background-color:  rgb(189,0,0);
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
 }
 ------------------------------------------------------------------register.css-----------------------------
 <!DOCTYPE html>
<html lang="en">
<head>
    <title>Website</title>
    <link rel="stylesheet" href="stylesheet.css">
    <script src="https://kit.fontawesome.com/c127414c8b.js" crossorigin="anonymous"></script>
  
</head>
<body>
    <form class="form" action="">
        <h2 class="num0">Sign In</h2><br>
        <span class="num2"><i class="fa-solid fa-user"><input class="num22" type="text" placeholder="username or email"></i></span><br><br>
        <span class="num3"><i class="fa-solid fa-key"><input class="num33" type="password" placeholder="password" id="h0"></i></span>
        <span class="eye" onclick=" myfunction()">
            <i id="h1" class="fa-solid fa-eye"></i>
            <i id="h2" class="fa-solid fa-eye-slash"></i></span><br><br>
        <a href="#" class="wrd">Forget  Password?</a>
        <button class="click">Login</button>
        <p class="para">Don't have an account?<a href="register.html" class="sign">Register</a></p><br>
        <p class="para1">----------------   or connect with  -------------------</p>
        <a href="#" class="google"><i class="fa-brands fa-google"></i>Sign in with   Google+ </a><br><br>
        <a href="#" class="fb"><i class="fa-brands fa-facebook"></i>Sign in with   Facebook</a><br><br>
        <a href="#" class="insta"><i class="fa-brands fa-instagram"></i>Sign in with   Instagram</a>
    

       
    </form>



    <script>
        function myfunction(){
            var x=document.getElementById('h0');
            var y=document.getElementById("h1");
            var z=document.getElementById("h2");
            if(x.type==="password"){
                x.type="text";
                y.style.display="block";
                z.style.display='none';
            }
            else{
                x.type="password";
                y.style.display="none";
                z.style.display="block";
            }
        }
    </script>
    
</body>
</html>
----------------------------------------------------------------------------index.html---------------------------------------------------
body{
    background-image: url('image/hostel.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
}
.form{
    background-color: rgb(103, 143, 236);
    width: 350px;
    height: 480px;
    border-radius: 5px;
    box-shadow:2px 2px 4px;
    margin-top: 100px;
    margin-left: 700px;
}
.num0{
    text-align: center;
    padding-top: 15px;
    color: white;
    border-color: white;
    background: linear-gradient(to right,#dd4b39,rgb(0,0, 225));
    padding-bottom: 5px;
    border-radius: 2px 2px 5px 5px;
}
.num22{
    width: 230px;
    height: 30px;
    padding: px;
    border: none;
    border-radius: 5px;
    margin-left: 15px;
    outline: none;
}
.num33{
    width: 230px;
    height: 28px;                               
    padding: 3px;
    border: none;
    border-radius: 5px;
    margin-left: 15px;
    outline: none;
}
.num2{
    background-color: white;
    width: 400px;
    height: 50px;
    padding: 10px;
    margin-left: 30px;
    border-radius: 5px;
    outline: none;
}
.eye{
    margin-left: -30px;
    position: absolute;
    margin-top: 11px;
}
#h1{
    display: none;
}
.num3{
    background-color: white;
    width: 380px;
    height: 50px;
    padding: 10px;
    margin-left: 30px;
    border-radius: 5px;
}
.wrd{
    
    margin-left: 200px;
    color: black;
    border-color: black;
}
.wrd:hover{
    cursor: pointer;
    color: #d14835;
}
.click{
    background-color:rgb(189, 0, 0);
    color: rgb(226, 229, 237);
    text-align: center;
    border-bottom: none;
    border-radius: 8px;
    height: 8vh;
    box-shadow: none;
    width: 280px;
    height:30px;
    margin: 30px;
    border-color: rgb(103, 143, 236) ;
    font-size: medium;
    font-family: Arial, Helvetica, sans-serif;
}
.click:hover{
    cursor: pointer;
    background-color: rgb(175, 54, 54);
}
.para{
    text-align: center;
    margin-top: -10px;
    font-size: large;
}
.sign{
    color: rgb(189, 0, 0);
    border-color: black;
    font-size: large;
    font-weight: bold;
    text-decoration: none;
    margin-left: 5px;
}
.sign:hover{
    cursor: pointer;
    color: #d14835;
}
.para1{
    text-align: center;
    margin-top: -15px;
    font-weight: bold;
}

.google{
    background-color: #dd4b39;
    color: white;
    padding-left: 10px;
    padding-right: 95px;
    padding-top: 5px;
    padding-bottom: 5px;
    text-decoration: none;
    margin-left: 35px;
    border-radius: 5px;
    border-color: rgb(103, 143, 236) ;
    
}
.google:hover{
    cursor: pointer;
    background-color: #d14835;
}
.fa-google{
    width: 30px;

}
.fa-facebook{
    width: 30px;
}
.fb{
    background-color:#3B5998;
    color: white;
    padding-left: 10px;
    padding-right: 90px;
    padding-top: 5px;
    padding-bottom: 5px;
    text-decoration: none;
    margin-left: 35px;
    border-radius: 5px;
    border-color: rgb(103, 143, 236) ;
}
.fb:hover{
    cursor: pointer;
    opacity: 0.9;
}
.fa-instagram{
    width: 30px;
}
.insta{
    background-color:#125688;
    color: white;
    padding-left: 10px;
    padding-right: 90px;
    padding-top: 5px;
    padding-bottom: 5px;
    text-decoration: none;
    margin-left: 35px;
    border-radius: 5px;
    border-color: rgb(103, 143, 236) ;
}
.insta:hover{
    cursor: pointer;
    background-color: #206a9f;
}
