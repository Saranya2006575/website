# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
hotel.html
<!DOCTYPE html>
<html lang="en"?>
    <head>
        <title>Tasty Treasures</title>
        <link rel="icon" href="fast food logo.webp">
    </head>
    <style>
        body{
            background-image: url(backgroundimg.jpg);
            background-size: cover;
            background-position: center;
        }
        .nav-list{
            position: absolute;
            top: 30px;
            left: 80%;
            transform:  translatex(10%);
        }
        .nav-list a{
            display: inline blocks;
            margin: 0 10px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: white;
        }
        .nav-list a:hover{
            color: blue;
        }
    </style>
        <div class="nav-list">
        <a href="#">Home</a>
        <a href="file:///C:/Users/admin/Desktop/quartus/html/sara.html/sara.html/menu.html">Menu</a>
        <a href="file:///C:/Users/admin/Desktop/quartus/html/sara.html/sara.html/contact.html">contact</a>
        </div>
    <body style="color: white;">
        <center>
        <img src="fast food logo.webp" style="height: 150px;">
        </center>
        <center>
            <h1 style="color:black; font-size: 50px;">TASTY TREASURE🍔</h1>
        </center>
    <table> 
        <tr>
            <td><img src="burger.jpg" style="width:350px;"></td>
            <td><img src="pizza.jpg" style="width:350px;"></td>
            <td><img src="chiken noodles.jpg" style="width:350px;"></td>
            <td><img src="friedrice.jpg" style="width:350px;"></td>
        </tr>
        <tr>
            <td><h3 style="color:white;"><center>Burger</center></h3></td>
            <td><h3 style="color:white;"><center>Pizza</center></h3></td>
            <td><h3 style="color:azure;"><center>Chicken Noodles</center></h3></td>
            <td><h3 style="color:azure;"><center>Fried Rice</center></h3></td>
        </tr>
    </table>
    <h2>Interior Design:
        <h2><center>Decor:</center></h2>
    </h2>
        <p style="font-family: 'Times New Roman',Times, serif";><center>Warm colors,comfy seating,with beautiful appearance</center>
            Come on down to our new fast food restaurant in the area! indulge in mouth
            watering burgers,crispy fries,juicy chicken,pizza,noodles,fried rice and more! our menu is packed with flavorfuln options that will
            satisfy your hunger cravings ,a limited,standardized menu with items that are quick to prepare and serve.the focus is on convenience,speed and 
            affordability,with little emphasis on nutritional valve ornculinary creativity.fast food is about more than just nutrition 
            Although imposing higher tax on fast food could have some positive effects,these would be overweighted by the drawbacks.

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>The Best Tasting Experience!</center></h4></td>
        </tr>
    </body>        
</html>

menu.html

<!DOCTYPE html>
<html>
    <head>
        <title>Menu</title>
    </head>
    <body>
        <style>
             body{
            background-image: url(backgroundimg.jpg);
            background-size: cover;
        }
        </style>
        <center>
        <h1 style="color: aliceblue;">FOOD MENU</h1>
    </center>
    <table>
        <tr>
        <th><img src="french.avif" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;">French Fries<br>Rate:50/-</td><br></tr>
        <tr>
        <th><img src="chiken noodles.jpg" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;">chicken noodles<br>Rate:130/-</td></tr><br>
        <tr>
        <th><img src="davey gravy.avif" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;">Davey gravy<br>Rate: 200/-</td><br>></tr>
        <tr>
        <th><img src="nuggets.avif" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;">Chicken nuggets<br>Rate: 250/-</td><br></tr>
        <tr>
        <th><img src="sharwma.jpg" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;"> sharwma<br>Rate: 80/-</td><br></tr>
        <tr>
        <th><img src="momos.avif" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;">momos<br>Rate: 100/-</td><br></tr>
        <tr>
        <th><img src="pizza.jpg" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;"> pizza<br>Rate: 250/-</td><br></tr>
        <tr>
        <th><img src="ice1.jpg" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;"> Ice cream<br>Rate:70/-</td><br></tr>
        <tr>
        <th><img src="ice2.jpg" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;">Ice cream2<br> Rate:80/-</td><br></tr>
        <tr>
        <th><img src="juice.jpg" style="height: 250px; width: 500px;"></th><td style="color: aliceblue; font-size: larger;">Juice<br> Rate:60/-</td><br></tr>
    </table>



        
    </body>
</html>

contact.html

<html>
    <head>
        <title> CONTACT </title>
    </head>
    <style>
        body{
        
            background-image: url(backgroundimg.jpg);
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            color: black;
            position:absolute;
            top: 200px;
        }
    </style>
    <center>
        <section id="contact">  
            <h1 style="color:black">contact<h1>
            <h4  style="color:black">+91 7874325687 <br> |tastytreasure@gmail.com</h4>
            <P  style="color:black">Address: 9th street Avenue Park, <br>
                Trichy 625620<br> contact us to place the order<br>
            <hr> THE BEST TASTING EXPERIENCE
            </P>
         </section> 
    </center>
    </body>

</html>
```

# OUTPUT:

![Screenshot 2024-12-06 234921](https://github.com/user-attachments/assets/96001cfa-6bab-429b-9df2-2e258d0fcb92)

![Screenshot 2024-12-06 234934](https://github.com/user-attachments/assets/9aa916db-9b33-4286-80a3-af421ce674ab)

![Screenshot 2024-12-06 234948](https://github.com/user-attachments/assets/183bb3ff-65b9-4179-be0d-08edc78c9b45)

![Screenshot 2024-12-06 235002](https://github.com/user-attachments/assets/d1b2e425-ce09-42d8-809e-4887e1c2147e)

![Screenshot 2024-12-06 235014](https://github.com/user-attachments/assets/d9a588d5-06bb-4d7c-b983-854267bcf6b5)

![Screenshot 2024-12-06 235030](https://github.com/user-attachments/assets/d84f79f6-2bd8-4c30-a8e2-5eb2385121f0)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
