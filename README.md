# Ex.07 Software Product Company Website
## Date: 20-04-24

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home design</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:rgb(155, 212, 212);
            color:white;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:60%;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: rgb(47, 47, 44);
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:rgb(71, 164, 231);
        
        }
        .heading1{
            color:black;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:rgb(5, 21, 23);
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
        .bottomdiv{
            background-color:rgb(50, 206, 206);
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 72px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="bg.jpeg">
    <div class="header">
        <nav id="nav">
            <h1>
                DEVICE DELIGHT
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
"Crafting digital dreams into innovation."<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                            Username:
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            Password:
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: black; color:aqua;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Designed by SWETHA A(212223220114) </p>
    </div>
</body>
<html>


product.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(90, 7, 55, 0.75),rgba(232, 150, 199, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-product {
                border: 1px;
                padding: 10px;
                color: black;
                background-color:skyblue;
                border-radius: 30px;
            }
            .logo {
                color:skyblue;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: hsla(0, 3%, 77%, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: black;
            } 
            ::placeholder {
                color: black;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: black;
                border-radius: 10px;
                background:rgb(171, 98, 249);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: black;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color:black;
                background-color:rgb(212, 56, 239);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: black;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid black;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color:rgb(143, 51, 235);
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: black;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color:skyblue;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">CodeHub</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/homepage.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html" class="bg-product"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/person.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact us</a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
              
                
                <div class="box">
                    <h3> Fusion Time </h3>
                    <p> Plot high-performance time-series visualizations. </p>
                </div>
                <div class="box">
                    <h3> Yellowfin BI and Analytics </h3>
                    <p> Powerful and flexible embedded analytics platform. </p>
                </div>
                <div class="box">
                    <h3> WebFlow Pro Studio </h3>
                    <p> Rapid low-code app creation. </p>
                </div>
                <div class="box">
                    <h3> DevInspect Test Kit </h3>
                    <p> Automated testing and debugging. </p>
                </div>
                <div class="box">
                    <h3> Fusion Grid </h3>
                    <p> Rocket fuel for data intensive applications with integrated charting. </p>
                </div>
                <div class="box">
                    <h3> SiteSphere CMS </h3>
                    <p> Streamlined web content management. </p>
                </div>
                <div class="box">
                    <h3> FusionCharts Suite XT </h3>
                    <p> Platform for data-driven maps. </p>
                </div>
                <div class="box">
                    <h3> CodeBoost Accelerator </h3>
                    <p> Optimized code efficiency tools. </p>
                </div>
                <div class="box">
                    <h3> WebScale Pro Manager </h3>
                    <p> Seamless high-traffic handling. </p>
                </div>
                <div class="box">
                    <h3> DevSphere IDE Suite </h3>
                    <p> Integrated tools for developers. </p>
                </div>

            </div>
              
            </div>
        </div>
    </div>
    <footer>
        <center> Designed by SWETHA A(212223220114) </center>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:rgb(209, 189, 233);
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:rgb(56, 177, 37);
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:teal;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:rgb(3, 23, 19);
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: yellow;
        }
        .table1{
            color:rgb(2, 7, 17);
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color: yellow;
        }
        .table2{
            color:rgb(23, 23, 24);
            font-size: large;
            background-color:rgb(95, 92, 92);
            border-radius: 5px;
            border-style:dotted;
            border-color: yellow;

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:teal;
            color:rgb(220, 230, 233);
            text-align: center;
            position:relative;
            display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="bg.jpeg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DEVICE DELIGHT</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        AGS Floor,Door No:3,2nd-Floor,2455A/119, M.T.H Road,karapakkam,Chennai-600049. 
                    </td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        near VR mall, next to sidco bus stop.
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        devicedelight@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9334678341
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
                            NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: lightskyblue; color: black;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Designed by SWETHA A(212223220114) </p>
        </div>
    </div>
</body>
</html>

person.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:rgb(5, 36, 50);
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:rgb(3, 8, 30);
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:rgb(7, 3, 39);
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:yellow;
        }
        .bottomdiv{
            background-color:teal;
            color:rgb(41, 7, 57);
            text-align: center;
            position:relative;
            display:block;
            margin-top: 163px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:rgb(19, 4, 44);
            text-align: center;
        }
    </style>
</head>
<body background="bg image.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DEVICE DELIGHT</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="blswe.jpg" class="MyPic">
                </td>
                <td>
                    <img src="p1.jpeg" class="sidsriram">
                </td>
                <td>
                    <img src="p2.jpeg" class="gv">
                </td>
                <td>
                    <img src="p3.jpeg" class="dhanush">
                </td>
                <td>
                    <img src="p4.jpeg" class="jonita">
                </td>
                <td>
                    <img src="p5.jpeg" class="dhee">
                </td>
            </tr>
            <tr>
                <td>
                    <b>SWETHA A</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>Ram kumar</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>Riot</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Pradeep kumar</b>
                    <p>CEO Director</p>
                </td>
                <td>
                    <b>Sid sriram</b>
                    <p>Asst.Director</p>
                </td>
                <td>
                    <b>Surya</b>
                    <p>Dy.Director</p>
                </td>
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
        <p>Designed by SWETHA A(212223220114)</p>
    </div>
</body>
</html>
```

## OUTPUT

![image](https://github.com/aswethaashok/softweb/assets/149987410/56d6844e-e8ac-4dd6-938c-4da6f067b3bd)


![Screenshot 2024-04-24 204853](https://github.com/aswethaashok/softweb/assets/149987410/38377d65-4c1b-495d-bcc5-38de65e23a30)

![Screenshot 2024-04-24 205301](https://github.com/aswethaashok/softweb/assets/149987410/bfbf50cf-3bdd-42fd-9b20-7d520b76db3a)


![Screenshot 2024-04-24 205505](https://github.com/aswethaashok/softweb/assets/149987410/07d84df7-4e2e-4a76-bd52-579c4e4b7285)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
