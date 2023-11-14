# Ex.07 Software Product Company Website
### Date : 31-10-2023

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

### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O+ Solutions </title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #f1f1f1;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color:gray;
            height: 500px;        
            overflow: hidden;
            line-height: 30px;
        }

        h1,h2{
            text-align: center;
        }

        .image1 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
        }

        .image3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 250px;
            left: 600px;
        }

        .image2  img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        footer{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <div class="logo">
            <a><img src="logo.png" alt="logo" border="2"></a>
        </div>
        <a class ="cname"><h1>O<sup>+</sup> SOLUTIONS</h1></a>
        <div class="header-right">
            <a class="active" href="index.html">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <h1>``HELLO DUDES``</h1>
        <h2>"O Grade Solutions for All Grade Problems"</h2>
        <div class="image1">
            <img src="index1.png" alt="image1">
        </div>
        <div class="image2">
            <img src="index2.png" alt="image2">
        </div>
        <div class="image3">
            <img src="index3.png" alt="image3">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
    </footer>
</body>
</html>
```

### product.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O+ Solutions</title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #f1f1f1;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: gray;
            height: 1500px;        
            overflow: hidden;
            line-height: 30px;
        }
        
        .prod1 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 280px;
        }

        .prod2 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        .prod3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .prod4 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
        }

        .prod5 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
            left: 650px;
        }

        .prod6 img{
            padding: 50px;
            height: 300px;
            width: 500px;
            position:absolute;
            top: 740px;
            left: 1100px;
        }

        .prod7 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 1140px;
        }

        .prod8 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 1140px;
            left: 1170px;
        }

        .prod9 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 1140px;
            left: 650px;
        }

        .quote{
            text-align: center;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
            color: khaki  ;
        }

        footer{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.png" alt="logo" border="2"></a>
        <a class ="cname"><h1>O<sup>+</sup> SOLUTIONS</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a class="active" href="product.html">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="quote">
            <h3>"Software is a gas; it expands to fill its container." - Nathan Myhrvold</h3>
        </div>
        <div class="prod1">
            <img src="prod3.png" alt="prod3">
        </div>
        <div class="prod2">
            <img src="prod2.png" alt="prod2">
        </div>
        <div class="prod3">
            <img src="prod1.jpg" alt="prod1">
        </div>
        <div class="prod4">
            <img src="prod4.jpg" alt="prod4">
        </div>
        <div class="prod5">
            <img src="prod5.jpg" alt="prod5">
        </div>
        <div class="prod6">
            <img src="prod6.jpg" alt="prod6">
        </div>
        <div class="prod7">
            <img src="prod7.png" alt="prod7">
        </div>
        <div class="prod8">
            <img src="prod8.png" alt="prod8">
        </div>
        <div class="prod9">
            <img src="prod9.png" alt="prod9">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
    </footer>
</body>
</html>

```

### people.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O+ Solitions</title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #f1f1f1;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: gray;
            overflow: hidden;
            line-height:normal;
        }
        .person {
            text-align: center;
        }

        p{
            font-size: 20px;
        }
        .person img {
            display:grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            margin: 0 auto;
            height: 340px;
            padding-top: 40px;
        }

        .person p.name {
            font-weight: bold;
            margin-top: 10px;
            color:black;
        }

        .person p.desig {
            font-weight: bold;
            margin-top: 10px;
            color:crimson;
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:maroon  ;
        }
        
        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.png" alt="logo" border="2"></a>
        <a class ="cname"><h1>O<sup>+</sup> SOLUTIONS</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a class="active" href="people.html">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>MEET THE TEAM</h3>
        </div>
        <div class="image">
            <div class="person">
                <img src="Anbu.jpg" alt="Anbuselvan">
                <p class="name">ANBUSELVAN A</p>
                <p class="desig">MANAGING DIRECTOR</p>
            </div>
            <div class="person">
                <img src="Mani.jpg" alt="Manikandan">
                <p class="name">MANIKANDAN P</p>
                <p class="desig">CEO</p>
            </div>
            <div class="person">
                <img src="Sudhar.jpg" alt="Sudharsanan">
                <p class="name">SUDHARSANAN V</p>
                <p class="desig">GENERAL MANAGER</p>
            </div>
            <div class="person">
                <img src="Kaushik.jpg" alt="Kaushik">
                <p class="name">KAUSHIK R</p>
                <p class="desig">MARKETING HEAD</p>
            </div>
            <div class="person">
                <img src="Ashika.jpg" alt="Ashika Jubi">
                <p class="name">ASHIKA JUBI R</p>
                <p class="desig">HR MANAGER</p>
            </div>
            <div class="person">
                <img src="Sherin.jpg" alt="Sherin Joys Catherina">
                <p class="name">SHERIN JOYS CATHERINA J</p>
                <p class="desig">REGIONAL MANAGER</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
    </footer>
</body>
</html>

```

### contact.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O+ Solutions</title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #f1f1f1;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: gray;
            overflow: hidden;
            line-height:normal;
        }
        
        .contact-container {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 50px;
        }

        .contact-image {
            flex: 1;
            text-align: center;
        }

        .contact-image img {
            max-width: 100%;
            height: auto;
        }

        .contact-details {
            flex: 1;
            padding: 50px;
            font-size: 25px;
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:maroon;
        }

        footer{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.png" alt="logo" border="2"></a>
        <a class ="cname"><h1>O<sup>+</sup> SOLUTIONS</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a class="active" href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>CONTACT US</h3>
        </div>
        <div class="contact-container">
            <div class="contact-image">
                <img src="company.jpg">
            </div>
            <div class="contact-details">
                <p><strong>Email:</strong> oplussolns@gmail.com</p>
                <p><strong>Phone:</strong> +144 8897 6554</p>
                <p><strong>Address:</strong> 11/227,Street No 5, Anna Nagar West, Chennai</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
        </footer>
</body>
</html>

```

## OUTPUT:

![image](https://github.com/Anbuselvan04/softweb/assets/119410896/7830d709-2715-465f-9580-117aedaa87d0)
![image](https://github.com/Anbuselvan04/softweb/assets/119410896/d335cc88-1abc-4951-b24f-0bc5a89dc38f)
![image](https://github.com/Anbuselvan04/softweb/assets/119410896/f47c564a-f0c6-4af0-8996-c29757c22676)
![image](https://github.com/Anbuselvan04/softweb/assets/119410896/f74fa7dd-f47d-4e97-a904-3d8d93f4855a)
![image](https://github.com/Anbuselvan04/softweb/assets/119410896/ed4cf566-3d8a-4000-bc05-80140fc9fe37)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
