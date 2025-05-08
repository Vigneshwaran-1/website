# Ex.07 Restaurant Website
# Date:6/5/25
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
~~~
main.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to BERRY BLISS</h1>
        <nav>
            <ul>
                <li><a href="C:\Users\admin\Documents\menu.html">Menu</a></li>
                <li><a href="C:\Users\admin\Documents\about us.html">About Us</a></li>
                <li><a href="C:\Users\admin\Documents\about us.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h2>Experience the Best Cuisine</h2>
        <p>Join us for a delightful dining experience.</p>
    </section>
    
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\menu.html"><img src="C:\Users\admin\Documents\d.jpg" alt="sizzling brownie"></a>
            <h3>Desserts</h3>
        </div>
        <div class="menu-item">
           <a href="C:\Users\admin\Documents\menu.html"><img src="C:\Users\admin\Documents\cd.jpg" alt="Margherita Pizza"></a> 
            <h3>Cold Drinks</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\menu.html"> <img src="C:\Users\admin\Documents\b.jpg" alt="Caesar Salad"></a>
            <h3>Beverages</h3>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 My Restaurant. All rights reserved.</p>
    </footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Welcome to BERRY BLISS</h1>
    </header>
    <section id="menu">
        <h2>Desserts</h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\brownies.jpg"  alt="sizzling brownie">
            <h3>sizzling brownie</h3>
            <p>₹120</p>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\cake.html"><img src="C:\Users\admin\Documents\cake.jpg" alt="Caesar Salad"></a> 
            <h3>Cake</h3>
        </div>
        <div class="menu-item">
            <a href= "C:\Users\admin\Documents\falooda.html"> <img src="C:\Users\admin\Documents\falooda.jpg" alt="Grilled Salmon"></a>
            <h3>Falooda</h3>
        </div>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\tiramusu.jpg" alt="Grilled Salmon">
             
            <h3>Tiramusu</h3>
            <p>₹120</p>


        </div>
        <div class="menu-item">
            <a href= "C:\Users\admin\Documents\ice cream.html"><img src= "C:\Users\admin\Documents\ic.jpg" alt="Grilled Salmon"></a>
            <h3>Ice Cream</h3>
        </div>
    </section>
    <section id="menu">
        <h2>Cold Drinks</h2>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\cold drinks.html"><img src="C:\Users\admin\Documents\cold drinks.jpg" alt="sizzling brownie"></a>
            <h3>Carbonate Drinks</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\lassi.html"><img src="C:\Users\admin\Documents\lassi.jpg" alt="Margherita Pizza"></a>
            
            <h3>Lassi</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\fresh juice.html"> <img src="C:\Users\admin\Documents\fresh juice.jpg" alt="Caesar Salad"></a>
           
            <h3>Fresh Fruit Juice</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\Milkshake.html"><img src= "C:\Users\admin\Documents\milkshake.jpg" alt="Grilled Salmon"></a>
            
            <h3>Milkshake</h3>
        </div>
    </section>
    <section id="menu">
        <h2> Beverages</h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\hot chocolate.jpg" alt="sizzling brownie">
            
            <h3>Hot chocolate</h3>
            <p>₹150</p>

        </div>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\tea.jpg" alt="Margherita Pizza">
            <p>₹30</p>
          
            <h3>tea</h3>
             
        </div>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\coffee.jpg" alt="Caesar Salad">
           
            <h3>coffee</h3>
            <p>₹50</p>
        </div>
        <div class="menu-item">
             <img src="C:\Users\admin\Documents\cold  coffee.jpg" alt="Grilled Salmon">
           
            <h3>Cold coffee</h3>
            <p>₹150</p>
        </div>
    </section>

</body>
</html>

about us.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section id="about">
        <h2>About Us</h2>
        <p>We are dedicated to serving fresh, high-quality food in a warm and welcoming atmosphere. Our chefs use the finest ingredients to create mouthwatering dishes that you'll love.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@myrestaurant.com</p>
        <p>Phone: (123) 456-7890</p>
        <p>Address: 123 Main St, Hometown, USA</p>
    </section>
    <section id="table">
    <table style="background-color: beige; width: 100%; height: 500px;">
        <tr>
            <th style="font-size: xx-large;"><b>Follow us on:</b>
                <br>
          
                <a href="https://www.youtube.com/"><img src="youtube.jpg" title="youtube" style="width: 100px; height: 80px;"></a>
                <br>
                
                <a href="https://www.youtube.com/"><img src="insta.jpg" title="Instagram" style="width: 100px; height: 80px;"></a>
                <br>
                
                <a href="https://www.youtube.com/"><img src="fb.png" title="Face Book" style="width: 100px; height: 80px;"></a>
            </th>
        </tr>
    </table>
    </section>
</body>
</html>
cakes.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desserts</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Cakes</h1>
    </header>
    <section id="menu">
        <h2>BLack Forest Cake <br><p>₹1500</p><br><p>This Black Forest Cake combines rich chocolate cake layers <br>with fresh cherries, cherry liqueur, and a simple whipped cream frosting.</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\black forest.jpg"  alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>White Forest Cake <br><p>₹1200</p><br><p>This White Forest Cake combines rich  White cake layers <br>with fresh cherries, cherry liqueur, and a simple whipped cream frosting.</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\WHITE-FOREST.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Red Velvet Cake <br><p>₹1700</p><br><p>Red velvet cake is a moist, rich, and vibrantly colored layer<br> cake that's often topped with cream cheese frosting. </p></h2>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\red velvet.jpg" alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Chocolate Cake <br><p>₹1200</p><br><p>This Chocolate Cake combines rich chocolate cake layers <br>with fresh cherries, cherry liqueur, and a simple whipped cream frosting.</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\cho.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
falooda.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desserts</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> FaloodaSS</h1>
    </header>
    <section id="menu">
       <h2>Dry Fruit Falooda<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\dry friut.jpg"  alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Fruit Falooda<br><p>₹100</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\fruit faloo.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2> Chocolate Falooda<br><p>₹120</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\chocolate falooda.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Butter Scotch Falooda<br><p>₹110</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\butterscotch.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>

icecream.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desserts</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> Ice Cream</h1>
    </header>
    <section id="menu">
       <h2>Chocolate Ice Cream<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\chocolate ice cream.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Vannila Ice Cream<br><p>₹100</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\vannila.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Mango Ice Cream<br><p>₹120</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\mango.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Butter Scotch Ice Cream<br><p>₹110</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\bs icecream.jpg"alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>

carbonatedrinks.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> Carbonate Drinks</h1>
    </header>
    <section id="menu">
       <h2>Coke<br><p>₹50</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\coke.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>spirit<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\sprit.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Fanta<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\fanta.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Soda<br><p>₹50</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\soda.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
lassi.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> Lassi</h1>
    </header>
    <section id="menu">
       <h2>Mango Lassi<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\m lassi.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Strawberry Lassi<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\s lassi.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Chocolate Lassi<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\cho lassi.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Kesar Lassi<br><p>₹150</p></h2>
         <div class="menu-item">
            <img src= "C:\Users\admin\Documents\k lassi.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>

fresh juice.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Fresh Fruit Juice</h1>
    </header>
    <section id="menu">
       <h2>Orange Juice<br><p>₹50</p></h2>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\o juice.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Lemon Juice<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\l jucie.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2> WaterMelon Juice<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\w juice.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Apple Juice<br><p>₹150</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\a juice.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
milkshake.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Milkshake</h1>
    </header>
    <section id="menu">
       <h2>Mango Milkshake<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\m ms.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Strawberry Milkshake<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\s ms.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Chocolate Milkshake<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\c ms.jpg" alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Vannila Milkshake<br><p>₹150</p></h2>
         <div class="menu-item">
            <img src= "C:\Users\admin\Documents\v ms.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
styles.css

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: bisque;
    color: #140a0a;
}

header {
    background-image: url("bb2.jpg");
    color: #0b063d;
    text-align: center;
    padding: 40px;
    font-family:'Times New Roman';
    background-size: contain;
    font-size: x-large;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #040c06;
    text-decoration: none;
    font-size: x-large;
    background-color: #ffffff;
}

#hero {
    background-image: url("avout.png");
    color: rgb(6, 15, 45);
    padding: 50px 0;
    text-align: center;
    font-size: x-large;
    background-size: cover;
}

#hero .btn {
    background: #35424a;
    color: #a70fe8;
    padding: 8px 15px;
    text-decoration: none;
}

#menu {
    padding: 15px;
    margin: 30px;
    background: #0e0558;
    border-radius: 8px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    color: white;
}

.menu-item {
    text-align: center;
    margin: 15px;
}

.menu-item img {
    width: 250px;
    height: 250px;
    border-radius: 8px;
}

h2 {
    margin-bottom: 15px;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: aliceblue;
    border-radius: 8px;
    color: rgb(174, 12, 109);
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #35424a;
    color: #ffffff;
    position: relative;
    bottom: 0;
    width: 100%;
}

styles1.css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: bisque;
    color: #140a0a;
}

header {
    background-image: url("bb2.jpg");
    color: #0b063d;
    text-align: center;
    padding: 70px;
    font-family:'Times New Roman';
    background-size: contain;
    font-size: x-large;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #040c06;
    text-decoration: none;
    font-size: x-large;
    background-color: #ffffff;
}

#hero {
    background-image: url("avout.png");
    color: rgb(6, 15, 45);
    padding: 100px 0;
    text-align: center;
    font-size: x-large;
    background-size: cover;
}

#hero .btn {
    background: #35424a;
    color: #a70fe8;
    padding: 10px 20px;
    text-decoration: none;
}

#menu {
    padding: 50px;
    margin: 50px;
    background: #0e0558;
    border-radius: 8px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    color: white;
}

.menu-item {
    text-align: center;
    margin: 15px;
}

.menu-item img {
    width: 250px;
    height: 250px;
    border-radius: 8px;
}

h2 {
    margin-bottom: 15px;
}

section {
    padding: 40px;
    margin: 40px;
    background-color: aliceblue;
    border-radius: 8px;
    color: rgb(174, 12, 109);
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #35424a;
    color: #ffffff;
    position: relative;
    bottom: 0;
    width: 100%;
}
~~~
# OUTPUT
![image](https://github.com/user-attachments/assets/d3947c39-e781-49d6-99ca-8e1168cb90f8)
![image](https://github.com/user-attachments/assets/5f8baef5-549d-448d-ab19-67c54d9d88f1)
![image](https://github.com/user-attachments/assets/757e2cfe-4a59-4150-8f02-ea33dbda9d90)
![image](https://github.com/user-attachments/assets/07afdfbd-807b-412a-b323-511dcdfbe968)
![image](https://github.com/user-attachments/assets/0901ef89-7fcd-4189-b9c1-32534a1758ba)
![image](https://github.com/user-attachments/assets/b40590f7-cdf5-44de-adc5-70d7b29168b8)
![image](https://github.com/user-attachments/assets/6f014391-3910-445e-90cb-a16caae01f21)
![image](https://github.com/user-attachments/assets/9a833554-9d7e-4e03-9b9f-72e1aef88e9c)
![image](https://github.com/user-attachments/assets/b8cb326b-a923-4946-af97-64905ea4d8ae)
![image](https://github.com/user-attachments/assets/66d43e7e-db86-49ed-9ba7-416e6968930c)
![image](https://github.com/user-attachments/assets/2e69ea6a-2229-4488-a343-a28b0eb1ff54)
![image](https://github.com/user-attachments/assets/658a90de-31fd-44a4-ad8b-0edbc5525a49)
![image](https://github.com/user-attachments/assets/3ee8d3b5-bf25-4f4d-9c67-161c3c4a7b3b)
![image](https://github.com/user-attachments/assets/ffb6fe54-4346-437d-a59c-9c835b244c27)











# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
