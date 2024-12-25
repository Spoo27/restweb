# Ex.07 Restaurant Website
## Date:25.12.24

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Savory spot</title>
    <style>
   *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; 
}

main {
    text-align: center;
    font-family:cursive;
    text-decoration:wavy
    padding: 40px 20px;
}

.banner {
    width: 100%;
    height: auto;
    max-height: 400px; 
    object-fit: cover; 
    margin-bottom: 30px;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    font:bold;
    text-decoration: underline;
    color: #095f16;
}

p {
    font-size: 1.2rem;
    color: #777;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Always Welcome</h1>
        <nav>
            <ul>
                <li><a href="home.html">home</a></li>
                <li><a href="menu.html">menu</a></li>
                <li><a href="administration.html">administrative</a></li>
                <li><a href="contact.html">contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2> <img src="Restuarent pic.jpg" alt="Restaurant Banner" class="banner">THE SAVORY SPOT</h2>
        <img src="Restuarent pic.jpg" alt="Restaurant Banner" class="banner">
        <p>TASTE THE BEST FOOD WITH US</p>
    </main>
    <footer>
        <p>Designed by[ATCHAYA B]</p>
    </footer>
</body>
</html>

menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Savory Spot</title>
   <style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
     }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #4e126a; /* Light orange on hover */
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #b11f80;
}

.menu-list {
    list-style-type: none;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    justify-items: center;
}

.menu-list li {
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 100%;
    text-align: center;
}

.menu-list img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 15px;
}

.menu-list li p {
    font-size: 1.1rem;
    color: #333;
    font-weight: bold;
}

.menu-list li:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}


footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administrative.html">Administrative</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Food Items</h2>
        <ul class="menu-list">
            <li><img src="Aloo-Gobi.jpg" alt="Food Item 1">Aloo-Gobi  - Rs 175</li>
            <li><img src="Butter chicken.jpg" alt="Food Item 2">Butter chicken - Rs 300</li>
            <li><img src="Chicken Kofta pulao.jpg" alt="Food Item 3">Chicken kofta Pulao - Rs 400</li>
            <li><img src="Chicken-Tikka.jpg" alt="Food Item 4">Chicken-Tikka - Rs 240</li>
            <li><img src="Falooda.jpg" alt="Food Item 5">Falooda - Rs 140</li>
            <li><img src="Ice cream.jpg" alt="Food Item 6">Ice Cream - Rs 50</li>
            <li><img src="Masala-Dosa.jpg" alt="Food Item 7">Masala-Dosa - Rs 60</li>
            <li><img src="Missi rotti.jpg" alt="Food Item 8">Misssi Rotti - Rs 70</li>
            <li><img src="Pani Puri.jpg" alt="Food Item 9">Pani Puri - Rs 40</li>
            <li><img src="Samosa.jpg" alt="Food Item 10">Samosa - Rs 60</li>
            <li><img src="South-Meals.jpg" alt="Food Item 11">South Meals - Rs 120</li>
            <li><img src="Tandoor chicken.jpg" alt="Food Item 12">Tandoori Chicken - Rs 240</li>

        </ul>
    </main>
    <footer>
        <p>Designed By : Spoorthi</p>
    </footer>
</body>
</html>

administrative.html

</html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Savory Spot</title>
    <style>
     *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #1a6798; 
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}


.team {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 30px;
    justify-items: center;
    margin-top: 30px;
}

.member {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 15px;
    border: 4px solid #089114; 
}

.member h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: #333;
}

.member p {
    font-size: 1.1rem;
    color: #777;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Administrative Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administrative</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Meet Our Team</h2>
        <div class="team">
            <div class="member">
                <img src="Atchaya...jpg" alt="Member 1">
                <h3>Atchaya B</B></h3>
                <p>CEO</p>
            </div>
            <div class="member">
                <img src="chief 1.jpg" alt="Member 2">
                <h3>Janani<h3>
                <p>Marketing Manager</p>
            </div>
            <div class="member">
                <img src="chief 2.jpg" alt="Member 3">
                <h3>Saral<h3>
                <p>Operations Manager</p>
            </div>
            <div class="member">
                <img src="chief 3.jpg" alt="Member 4">
                <h3>Jayasri<h3>
                <p>HR Manager</p>
            </div>
            <div class="member">
                <img src="chief 4.jpg" alt="Member 5">
                <h3>Henry<h3>
                <p>Executive Chef</p>
            </div>
            <div class="member">
                <img src="chief 5.jpg" alt="Member 6">
                <h3>kaviya<h3>
                <p>Customer Service Manger</p>
            </div>
        </div>
    </main>
</body>

contact.html

<body>
    <style>
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
  
  body {
    font-family: Arial, sans-serif;
    background-color: #11bdcd;
    color: #333;
  }
  #contact {
    background-color: #b73492;
    padding: 40px 20px;
    margin: 40px auto;
    max-width: 600px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
  }
  
  #contact h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #a90b0b;
  }
  
  #contact p {
    font-size: 1.2rem;
    margin-bottom: 20px;
    color: #555;
  }
  
  address {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #333;
  }
  
  address br {
    margin-bottom: 10px;
  }
  
  #contact:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
  }
    </style>
     <section id="contact">
    <h2>Contact Us</h2>
    <p>Visit us at:</p>
    <address>
      15\3 vinayagar street, Chennai.
      <br>
      Phone: 9027283890
      <br>
      Email: savoryspot@food.com
    </address>
  </section>
  </body>
  </html>
  ```



## OUTPUT:

![Screenshot 2024-12-25 133455](https://github.com/user-attachments/assets/ef8ca952-6f03-4a9f-8706-55db5a390b98)

![Screenshot 2024-12-25 133516](https://github.com/user-attachments/assets/df920890-e90b-4249-9b7e-d81887a9d1e9)

![Screenshot 2024-12-25 133541](https://github.com/user-attachments/assets/85aa5acb-95af-4936-a596-ead52d4d6874)

![Screenshot 2024-12-25 133627](https://github.com/user-attachments/assets/72718727-62f3-47fa-907d-44740dd08146)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
