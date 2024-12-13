# Ex.07 Restaurant Website
## Date:12.12.2024

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
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASIAN RESTAURANT</title>
    
    <style>
        body {
            background-image: url(bg.png);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            background-attachment: fixed;
        }

        nav {
            margin-top: 5%;
            margin-right: 5%;
            justify-content: space-between;
            
        }
        nav ul{
            text-align: right;
        }

        nav ul li {

            display: inline;
            list-style-type: none;
            font-size: 24px;

        }

        nav ul li a {
            text-decoration: none;
            color: red;
            background-color: yellow;
            margin-left: 150px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            padding: 12px;
        }

        div h1 {
            margin-top: 15%;
            color: antiquewhite;
            margin-left: 12%;
            font-size: 72px;
            font-family: sans-serif;
            width: 50%;
            line-height: 2;
        }
        footer
        {
            background-color: rgba(0,0,0,0.5);
            color:white;
            font-size: large;
              
        }
        nav h1{
            color: white;
            margin-left: 5%;
            font-size: 28px;
        }
        .color
        {
            background-color: red;
        }
    </style>
</head>

<body>

    <nav >

        <h1>ASIAN RESTAURANT</h1>

        <ul>
            <li><a href="menu.html" class="menu" class="color">MENU</a></li>
            <li><a href="admin.html" class="admin" class="color">Administraion</a></li>
            <li><a href="order.html" class="order" class="color">Order</a></li>
            <li><a href="contact.html" class="contact" class="color">Contact Us</a></li>
        </ul>

    </nav>
    <div>
        <h1>ORDER HOMELY FOODS NOW</h1>
    </div>
    <footer align="center">
        Designed by Savish R &copy 2024
    </footer>
</body>

</html>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>order now</title>
    <style>
        body{
            background-color:whitesmoke;
        }
        #body
        {
            /* border: 5px solid black; */
           color: black;
           background-color:pink;
            /* border-radius: 25px; */
            height: 1000px;
        }
         img
        {
                margin-top: 100px;
                height: 200px;
                width: auto;
                margin-left: 25px;

        } 
        #fish
        {
            height: 200px;
            width: 300px;
        }
        .dish
        {
           margin-left: 240px;
        }
        #dish1
        {
            margin-left: 280px;
        }
        #dish2
        {
            margin-left: 30px;
        }
        p{
            margin-top: 75px;
            margin-left: 100px;
            font-size: 25px;
        }
        .img
        {
            border: 5px groove black;

        }
        h1
        {
            text-decoration:underline wavy red;
        }
    </style>
</head>
<body>
    <div id="body">
    <h1 align="center">Choose your best Choices</h1>
    <div>
        <img src="food 1.jpeg" class="img" alt="crab">
        
        <img src="food 2.jpeg" alt=""class="img">
        <img id ="fish" src="food 3.jpeg" alt=""class="img">
        <img src="food 5.jpeg" alt="" class="img">
        <img src="food 6.jpeg" alt="" class="img">
        <b class ="dish"  id="dish2"> burger </b>
        <b class ="dish" >barota</b>
        <b class ="dish " id="dish1" > chicken barota</b>
        <b class ="dish" >chicken gravy  </b>
        <b class ="dish" >Biryani</b>
        <p > - Sount India foods are available for you sir</p>
    </div>
    </div>
</body>
</html>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ocean Foods</title>
    <style>
        pre{
            border: 10px inset black;
            padding: 15px;
            font-size: large;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            
        }
       #order
        {
                display: inline;
                margin-left: 10px;
                color: blueviolet;
        }
        #h1
        {
            text-align: center;
            font-style: oblique;
            margin-top: 10px;
            padding: 25px;
            position: relative;
            top: 50px;
            left: 0px;
            background-color: red;
            color: yellow;
        }
        body
        {
            background-color: rgba(238, 207, 212,0.3);
        }
    </style>
</head>
<body >
    
    <h1 id="h1">WELCOME SIR/MAM</h1>
<pre>

Here’s a sample "About Us" page text for your restaurant, Asian Foods Bro:

About Us
Welcome to Asian Foods Bro, where flavor meets passion!

At Asian Foods Bro, we take you on a culinary journey across Asia, offering a delicious fusion of traditional recipes and modern flavors. Our mission is to bring authentic, <br> high-quality Asian cuisine to your plate, whether you’re craving the bold spices of Thailand, the comforting flavors of Chinese classics, <br>the delicate art of Japanese sushi, or the hearty soul of Indian curries.

We believe in crafting meals that don’t just satisfy hunger but create memorable experiences. Our ingredients are fresh,<br> our recipes are authentic, and our chefs are passionate about delivering the best every single time.

Whether you’re dining in, grabbing takeout, or ordering delivery, you’re always part of the Asian Foods Bro family. So come join us and explore a world of flavors that will make your taste buds dance!

Why Choose Us?
Authentic Recipes: Every dish is crafted with care, inspired by traditional Asian cooking.
Fresh Ingredients: We use only the freshest produce and highest-quality ingredients.
Warm Hospitality: Our friendly team is dedicated to making you feel right at home.
Diverse Menu: From spicy street food to comforting family favorites, there’s something for everyone!
Thank you for choosing Asian Foods Bro. We can’t wait to serve you!
</pre>

</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">  
    <style>
      *{
        font-family: Arial, Helvetica, sans-serif;
      }
        #contact
        {
            display: flex;
            font-size: 30px;
            gap: 10px;
            background-color:	rgba(250, 235, 215,0.2);
            height: 800px;
        }
        #contact>div{
            width: 30%;
            /* border: 5px solid pink; */
            padding: 50px;
        }
        pre{
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        }
        #div1
        {
            position: absolute;
            top:40px;
            right: 100px;
            border: 50px groove red;
            background-color: whitesmoke;
            border-radius: 50px;
        }
        input{
            font-size: 25px;
            margin-left: 30px;
        }
        #textarea
        {
          margin-left: 25px;
          padding: 20px;
          border: #FFFFFF;
          padding: 10px;
          border-radius: 10px;
          font-size: 20px;
        }

        #submit
        {
          background-color: yellow;
          color: red;
          border-radius: 10px;
        }
        #label2
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;

        }
        #label1
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;
        }
        #info
        {
          padding: 20px;
          
        }

    </style>
    <script>
            function f1()
            {
                document.getElementById("label3").innerHTML="Informations are saved";
            }
    </script>
    
</head>
<body>
    <div id="contact">
      
           <div id="info">
              <b style="text-decoration: underline ;">ASIAN RESTAURANT</b>
              <br>
              <br>
              <b style="font-size: 50px; color: red;">Customer <br> Support</b>
              <br>
              <p>Email:suppor@asianrestaurent.in</p>
              <br><br>
    <pre>
    Corporate Office
    No. 55, Survey No. 8-14, Ground Floor,
    I&J Block, Embassy TechVillage,
    Outer Ring Road, Devarbisanahalli,
    Bengaluru - 560103, Karnataka, India
    
    Corporate Identity Number: U74110KA2013PLC096530
    Registration Number: 096530
    
    Let me know if you like another variation!
</pre>
            </div>
        <div  id="div1">
            <hr style="font-style: italic;">
            <b align="center"> Get in touch </b>
            <br>
            <br>

            <label id="label2"><input type="text" id="label2" placeholder="Enter Name"></label>
            <br>
            <br>
            <label id="label1"> <input type="text" id="label1"  placeholder="Enter Number"></label>
            <br>
            <br>
            <label ><textarea  id="textarea" placeholder="Enter Message"  rows="10" cols="50"></textarea></label>
            <br>
            <br>
            <label id="label3"> <input type="submit"  id="submit" placeholder="Enter" onclick="f1()"></label>
            <hr>
        </div>

    </div>
</body>
</html>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administraion</title>
    <style>
        body
        {
            background-color:cadetblue;
        }
        #container
        {
            display: flex;
            height: 1000px;
            width: auto;
            justify-content: space-evenly;
            border-radius: 100px;
        }
        #main
        {
            border: 1px solid black;
        }
        .box
        {
            position: relative;
            display: inline-block;
            top: 150px;
            height: 300px;
            width: 300px;
            border: 2px solid black;
            background-color: pink;
            border-radius: 50%;
        }
        #head
        {
            text-align: center;
            font-size: 40px;
            font-family: 'Times New Roman', Times, serif;
            font-weight: 700;
            background-size:cover ;
        }
        #name
        {
            justify-content: space-evenly;
        }
        #n1
        {
            position: absolute;
            bottom: 170px;
            left: 100px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n2
        {
            position: absolute;
            bottom: 170px;
            left: 410px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n3
        {
            position: absolute;
            bottom: 170px;
            left: 700px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n4
        {
            position: absolute;
            bottom: 170px;
            left: 1000px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n5
        {
            position: absolute;
            bottom: 170px;
            left: 1350px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
    </style>
    
</head>
<body>
    <div align="center" id="head">Exprenced Chef's in our restorent</div>
    <div id="container">

            <div ><img src="imd1.jpeg" alt="" class="box"></div>
            <div ><img src="img 3.jpeg" alt="" class="box"></div>
            <div ><img src="img 4.jpeg" alt="" class="box"></div>
            <div ><img src="img2.jpeg" alt="" class="box"></div>
            <div ><img src="WhatsApp Image 2024-12-12 at 22.33.43_81c4b8b0.jpg" alt="" class="box"></div>
    </div>
    <p id="n1">chef-1 </p> 
        <p id="n2">chef-2</p>
         <p id="n3">chef-3</p>
        <p id="n4">chef-4</p>  
        <p id="n5">Savish</p>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (71).png>)
![alt text](<Screenshot (72).png>)

![alt text](<Screenshot (73).png>)
![alt text](<Screenshot (74).png>)

![alt text](<Screenshot (76).png>)
![alt text](<Screenshot (77).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
