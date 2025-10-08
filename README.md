# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
HOME>HTML
<html>
<head>
    <title>My Resturant</title>
    <link rel="stylesheet" href="home.css">
</head>
<body>
    <div class="head">
        <h1>GOPINATH RESTAUNT</h1>
    </div>
    <div class="list">
        <ul
            <li><a href="home.html">HOME||||/a></li>
            <li><a href="menu.html"> MENU||||</a></li>
            <li><a href="admin.html"> ADMIN||||</a></li>
            <li><a href="contact.html"> CONTACT||||</a></li>
        </ul>
    </div>
    <hr>
    <div class="center">
        <P class="type">RICH-EXQUISITE-DELIGHTFUL</P>
        <h1 class="quote">&QUOT;A taste of Indian tradion in every bite - Taste the tradion<br>of tamil culture.&QUOT;</h1>
        <p>You're invited to GOPINATH RESTAURANT join us for unexpectable flavours,warm vibes, and a side of fortune. 
           From crispy spring rolls to sizzling stir-fries, GOPINATH  Restaurant serves up This
           kind of delious that makes hand optional(but recomanded)</p>
    </div>
    <div class="bottom">
        <img src="gopi1.png" alt="interior" width="400" height="200">
    </div><hr>
    <h3 class="foot">&copy;GOPINATH S(25012981)</h3>
</body>
</html>

HOME.CSS
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    background-image:url(background1.png);
    height: 100%;
    width: 100%;
    background-size: cover;
    background-position: center;
}
.head,.list,ul,li{
    display: inline-block;
}
ul{
    margin-left: 100%;
    display: flex;
}
li{
    background-color: pink;
}
li:hover{
    background-color: grey;
    border-radius: 0px;
}
h1{
    color:rgb(0, 255, 34);
    margin: 20px;
}
.type{
    margin-right: 70%;
}
p{
    color: rgb(255, 255, 255);
    font-size: 20px;
    margin: 20px;
    text-align: center;
}
.quote{
    text-align: center;
}
.bottom{
    margin-left: 35%;
}
.foot{
    text-align: center;
    color: rgb(255, 255, 255);
}
MENU.HTML
<html >
<head>
    <title>Menu Page</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <div class="head">
    <h1>Our Menu</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME||||</a></li>
            <li><a href="menu.html"> MENU||||</a></li>
            <li><a href="admin.html"> ADMIN||||</a></li>
            <li><a href="contact.html"> CONTACT||||</a></li>
        </ul>
        <h2>Foood Items</h2>
        <div class="food-item">
            <div class="food">
                <img src="idlyimage.png" alt="Idly" width="200" height="150">
                <h3> Idly</h3>
            </div>
            <div class="food">
                <img src="dosaimage.png" alt="Dosa" width="200" height="150">
                <h3>masal Dosa</h3>
            </div>
            <div class="food">
                <img src="kharapongal.png" alt="Pongal" width="200" height="150">
                <h3>khara Pongal</h3>
            </div>
            <div class="food">
                <img src="samabarvadai.png" alt="Sambar Vada" width="200" height="150">
                <h3>Sambar Vadai</h3>
            </div>
            <div class="food">
                <img src="fullmeal.png" alt="Full Meel" width="200" height="150">
                <h3>Full Meel</h3>
            </div>
            <div class="food">
                <img src="pooriimage.png" alt="Poori" width="200" height="150">
                <h3>Poori</h3>
            </div>
            
        
    </div>
    <h3 class="foot">&copy;GOPINATH S(25012981)</h3>
</body>

MENU.CSS

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-image:url(menubackground.png);
    background-size: cover;
    background-attachment: fixed;
    text-align: center;
    line-height: 1.6;
}
h2{
    color: rgb(137, 6, 224);
}
h3{
    color: rgb(46, 25, 235);
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
h1{
    color: rgb(212, 7, 127);
    background-color: rgb(14, 197, 230);
}

.food{
    border: 2px solid pink;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    background-color: rgb(142, 5, 221);
    display: inline-block;
}
.food:hover{
    background-color: lightgreen;
    transform: scale(1.1);
    transition: 0.3s;
}
.food-item h3{
    color: white;
}   
ADMIN.HTML
<html>
<head>
    <title>Admin page</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <div class="head">
    <h1>Administration Team</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME|</a></li>
            <li><a href="menu.html"> MENU|</a></li>
            <li><a href="admin.html"> ADMIN|</a></li>
            <li><a href="contact.html"> CONTACT|</a></li>
        </ul>
    </div>
    <h2>Meet our Team</h2>
    <div class="team">
        <div class="member">
            <img src="rururaj.png" alt="Admin 1" width="200" height="200">
            <h3>RUTURAJ GAIKWAD</h3>
            <p>CEO</p>
        </div>
        <div class="member">
            <img src="mastervijay.jpg" alt="Admin 2" width="200" height="200">
            <h3>thalapathy.VIJAY</h3>
            <p>Marketing Manager</p>
        </div>
        <div class="member">
            <img src="SUNDARPICHAI.png" alt="Admin 3" width="200" height="200">
            <h3>SUNDAR PICHAI</h3>
            <p>Operation manager</p>
        </div>
        <div class="member">
            <img src="author.png" alt="Admin 4" width="200" height="200">
            <h3>Gopinath s</h3>
            <p>HR manager</p>
        </div>
        <div class="member">
            <img src="hardikpandya.png" alt="Admin 5" width="200" height="200">
            <h3>HARDIK PANDYA</h3>
            <p>Head Chef</p>
        </div>
        <div class="member">
            <img src="SURESHRAINA.png" alt="Admin 6" width="200" height="200">
            <h3>SURESH RAINA</h3>
            <p>Customer Service Manager</p>
        </div>
    </div>
    <hr>
    <h3 class="foot">&copy;Gopinath s(25012981)</h3>
</body>
</html>
ADMIN.CSS
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-color: rgb(14, 240, 6);
    color: red;
    line-height: 1.6;
    text-align: center;
}
.member{
    border: 2px solid rgb(11, 66, 216);
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    background-color: rgb(233, 218, 248);
    display: inline-block;
}
.member:hover{
    background-color: rgb(83, 13, 66);
    color: rgb(221, 157, 162);
    transform: scale(1.1);
    transition: 0.3s;
}
.list,ul,li{
    display: inline;
    background-color: white;
}
li:hover{
    background-color: lightgrey;
}
.team{
    background-color: rgb(224, 9, 142);
}
CONTACT.HTML

<html >
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <div class="head">
    <h1>Contact Info</h1>
    </div>
    <div class="list">
        <ul>
            <li><a href="home.html">HOME||||</a></li>
            <li><a href="menu.html"> MENU||||</a></li>
            <li><a href="admin.html"> ADMIN||||</a></li>
            <li><a href="contact.html"> CONTACT||||</a></li>
        </ul>
    </div>
    <div class="content">
        <h2>Contact Us</h2>
        <p>If you have any questions or would like to make a reservation,<br>please contact us using the information below:<br>
           Phone: (123) 456fjbf-7890<br>Email: ruturaj@gmail.com<br>
           Visit us at: 1698800 west Street, TamilNadu, India<br></p>
    </div>
    <h3 class="foot">&copy;GOPINATH S(25012981)</h3>
</body>
CONTACT.CSS
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
body{
    background-image: url(contactbg.png);
    background-size: cover;
    background-position: center;
    text-align: center;
}
h1{
    text-align: center;
    padding: 20px;
    color: rgb(89, 8, 240);
    font-size: 40px;
}
h3{
    color: #1974c9;
}
.list,ul,li{
    display: inline;
    background-color: rgba(255, 255, 255, 0.178);
}
li:hover{
    background-color: lightgrey;
}
.content{
    border: 2px solid rgb(230, 98, 120);
    color: white;
    font-size: 20px;
    margin: 20px;
    padding: 20px;
    background-color: rgba(182, 163, 207, 0.788);
    border-radius: 10px;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-10-08 133409.png>)
![alt text](<Screenshot 2025-10-08 133536.png>)
![alt text](<Screenshot 2025-10-08 133700.png>)
![alt text](<Screenshot 2025-10-08 133742.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
