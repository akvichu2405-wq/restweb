# Ex.06 Restaurant Website
## Date:24/12/2025

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
home.html
<html>
    <head>
        <title>KYOTO DELIGHT </title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <h2 class = "name">KYOTO DELIGHT</h2>
        <h1 class ="tagline">"Pure Japanese Flavor. Pure Delight."</h1>

       <div class="items">
          <a href="home.html">HOME </a>
           <a href="menu.html">MENU </a>
          <a href="admin.html">ADMIN </a>
          <a href="contact.html">CONTACT</a>
       </div> 
    </body>
</html>

style.css

body{
    background-image:url(background.jpg);
    position: absolute;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
    backdrop-filter: 20px;
}


h1{
    font-size: 70px;
    font-weight: bolder;
    position: relative;
    top: -200px;
    left: 150px;
    color: beige;
    text-shadow: 4px 4px 0px black;
}

h2{
    font-size: 100px;
     color: beige;
    font-weight: bold;
    position: absolute;
    top: -550px;
    left: 12px;
    padding:40px;
    position:centre;
    text-shadow: 5px 5px 0px black;
}



.items{
        font-weight: bold;
    font-size: 20px;
    position: relative;
    letter-spacing: 3px;
    word-spacing: 5px;
    left: 950px;
    top:-600px;
    gap:10px;
}
.items a{
    text-decoration: none;
    color: bisque;
    text-shadow:1px 1px 0px white;
    background-color: black;
}

menu.html

<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="menu.css">
</head>

<body>
    


    
    <div class="menu-container">

        <div class="card">
            <img src="miso ramen.jpg">
            <h3>Miso Chicken Ramen</h3>
            <p>Rs: 700</p>
        </div>

        <div class="card">
            <img src="miso soup.jpg">
            <h3>Miso Soup</h3>
            <p>Rs: 350</p>
        </div>

        <div class="card">
            <img src="sushi.jpg">
            <h3>Sushi Platter</h3>
            <p>Rs: 800</p>
        </div>

        <div class="card">
            <img src="takoyaki.jpg">
            <h3>Prawn Takoyaki</h3>
            <p>Rs: 500</p>
        </div>

        <div class="card">
            <img src="tempura.jpg">
            <h3>Tiger Prawn Tempura</h3>
            <p>Rs: 340</p>
        </div>

        <div class="card">
            <img src="tonkotsu ramen.jpg">
            <h3>Chicken Tonkotsu Ramen</h3>
            <p>Rs: 500</p>
        </div>

        
    </div>
    
<div class="items">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

</body>
</html>

menu.css

body{
    background-image:url(background.jpg);
    position: absolute;
    width:700px;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
    backdrop-filter: 20px;
}

.items{
        font-weight: bold;
    font-size: 20px;
    position: relative;
    letter-spacing: 3px;
    word-spacing: 5px;
    left: 950px;
    top:-600px;
}
.items a{
    text-decoration: none;
    color: bisque;
    text-shadow:1px 1px 0px white;
    background-color: black;
}



.menu-container{
    position: center;
    top: 1px;
    display: flex;
    justify-content: left;
    gap: 25px;
}


.card{
    background-color: #516750;
    padding: 15px;
    text-align: center;
    border-radius: 20px;
}

.card img{
    width: 200px;
    height: 250px;
    border-radius: 15px;
}
 
admin.html

<html>
<head>
    <title>Admin</title>
    <link rel="stylesheet" href="admin.css">
</head>

<body>
    
    <div class="menu-container">

        <div class="card">
            <img src="me.jpeg">
            <h3>Vishnu Priya A K</h3>
            <p>CEO</p>
        </div>

        <div class="card">
            <img src="jk.jpg">
            <h3> Jeon Jung Kook </h3>
            <p>Chief Marketing Officer</p>
            
        </div>

        <div class="card">
            <img src="mingyu.jpg">
            <h3>Kim Min Gyu</h3>
            <p>Chief Operating Officer</p>
        </div>

        <div class="card">
            <img src="iu.jpg">
            <h3>Lee Ji Eun</h3>
            <p>Chief Techonology Officer </p>
        </div>

        <div class="card">
            <img src="lee.jpg">
            <h3>Lee Jang Wook</h3>
            <p>General Manager</p>
        </div>

        <div class="card">
            <img src="ji.jpg">
            <h3>Ji Jang Wook</h3>
            <p>Executive chef</p>
        </div>


    </div>

     <div class="items">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

</body>
</html>

admin.css

body{
    background-image:url(background.jpg);
    position: absolute;
    width:700px;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
    backdrop-filter: 20px;
}

.items{
    font-weight: bold;
    font-size: 20px;
    position: relative;
    letter-spacing: 3px;
    word-spacing: 5px;
    left: 950px;
    top:-600px;
}
.items a{
    text-decoration: none;
    color: bisque;
    text-shadow:1px 1px 0px white;
    background-color: black;
}



.menu-container{
    position: center;
    top: 1px;
    display: flex;
    justify-content: left;
    gap: 25px;
}


.card{
    background-color: #516750;
    padding: 15px;
    text-align: center;
    border-radius: 20px;
}

.card img{
    width: 200px;
    height: 250px;
    border-radius: 15px;
}
 
contact.html

<html>
    <head>
        <title>KYOTO DELIGHT </title>
        <link href="contact.css" rel="stylesheet">
    </head>
    <body>
        <h1>CONTACT</h1>
        <h2>Visit us on:kyoto_delights25</h2>
        <h3>For Any Queries:Ph:4585489549</h3>
               <div class="items">
          <a href="home.html">HOME </a>
           <a href="menu.html">MENU </a>
          <a href="admin.html">ADMIN </a>
          <a href="contact.html">CONTACT</a>
       </div> 
    </body>
</html>

contact.css

body{
    background-image:url(background.jpg);
    position: absolute;
    background-size: cover;
    background-repeat: no-repeat;
    bottom: 80px;
    backdrop-filter: 20px;
}


h1{
    font-size: 60px;
    font-weight: bolder;
    position: relative;
    top:-300px;
    left: 100px;
    color: beige;
    text-shadow: 4px 4px 0px black;
}

h2{
    font-size: 35px;
     color: beige;
    font-weight: bold;
    position: absolute;
    top:-100px;
    left:190px;
    padding:40px;
    position:centre;
    text-shadow: 5px 5px 0px black;
}

h3{
    font-size: 35px;
     color: beige;
    font-weight: bold;
    position: absolute;
   top:-200px;
    left: 190px;
    padding:40px;
    position:centre;
    text-shadow: 5px 5px 0px black;
}


.items{
        font-weight: bold;
    font-size: 20px;
    position: relative;
    letter-spacing: 3px;
    word-spacing: 5px;
    left: 950px;
    top:-600px;
    gap:10px;
}
.items a{
    text-decoration: none;
    color: bisque;
    text-shadow:1px 1px 0px white;
    background-color: black;
}


```


## OUTPUT:

![alt text](<Screenshot 2025-12-24 112754.png>)
![alt text](<Screenshot 2025-12-24 112805.png>)
![alt text](<Screenshot 2025-12-24 112817.png>)
![alt text](<Screenshot 2025-12-24 112827.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
