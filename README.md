# EX-02 : COMMERCIAL WEBSITE 
## DATE : 11.03.2025

## AIM :
To create a commercial website using HTML and CSS Flexbox.

## ALGORITHM :
### STEP 1 :
Create an HTML file (index.html)

### STEP 2 :
Create a CSS file (style.css)

### STEP 3 :
Include a navigation bar with links to different sections.

### STEP 4 :
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5 :
Include social media links at the footer with copyright information.

### STEP 6 :
Define global styles for fonts, colors, and layout.

### STEP 7 :
Style the header, navigation bar, and sections.

### STEP 8 :
Use Flexbox for layout design.

### STEP 9 :
Add hover effects and transitions for interactivity.

### STEP 10 :
Add Images and Media.

### STEP 11 :
Use optimized images for a professional look.

### STEP 12 :
Open the HTML file in a browser to check layout and functionality.

### STEP 13 :
Fix styling issues and refine content placement.

### STEP 14 :
Deploy the website.

### STEP 15 :
Upload to GitHub Pages for free hosting.

## PROGRAM :

### index.html

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Recipe App - Home</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
  <header class="header">
    <img src="logo.jpg" alt="Profile Image" class="header-image">
    <h1 class="logo">I<span>nfiniti</span>C<span>ook</span></h1>
    <div class="navbar">
      <a href="index.html">Home</a>
      <a href="Login.html">Login</a>
      <a href="myrecipes.html">My Orders</a>
      <a href="profile.html">Profile</a>
    </div>
  </header>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="input-group my-4">
          <input type="text" class="form-control" placeholder="Search recipes...">
          <div class="input-group-append">
            <button class="btn btn-outline-secondary" style="background-color: black;color: aliceblue;" type="button">Search</button>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="sambar.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Sambar</h5>
            <p class="card-text">Sambar is a South Indian lentil and mixed vegetable stew that’s comfort food at its best. It’s hearty, super flavorful, and loaded with vegetables, spices, and herbs.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="mushroom.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Mushroom Biriyani</h5>
            <p class="card-text">Mushroom Biryani is a delightful rice dish made with fragrant basmati rice, mushrooms, and aromatic spices.it's heartly a treat for Vegeterians and also foodies.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="mangolassi.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Mango Lassi</h5>
            <p class="card-text">Mango is a delightful fruit! 🥭 Whether you’re enjoying it fresh, blending it into smoothies, or using it in cooking, mangoes bring a burst of tropical flavor.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="burger.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Burger</h5>
            <p class="card-text">Burgers are a classic comfort food, and making them at home is both fun and rewarding.It was the most favourite snack for the  World and Most flavorful.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="vegroll.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Veg Roll</h5>
            <p class="card-text">A veg roll is a delightful snack made with a variety of vegetables wrapped in a flatbread or pastry. It can be either sautéed or baked, and the filling .</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="bisibelabath.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Bisibelebath</h5>
            <p class="card-text">It’s a hearty and wholesome meal made with rice, lentils, mixed vegetables, and a super aromatic spice powder known as bisibelebath powder.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="pulao.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Pulao</h5>
            <p class="card-text">Pulao is a delightful one-pot Indian dish made with fragrant basmati rice, vegetables, and aromatic spices. It’s a versatile recipe that you can customize with your favorite veggies.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="coffee.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Coffee</h5>
            <p class="card-text">Coffee is a delightful beverage brewed from roasted coffee beans. It’s darkly colored, slightly acidic, and has a distinctive, somewhat bitter flavor. The stimulating effect of coffee primarily comes from its caffeine.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="chicken65.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Chicken 65</h5>
            <p class="card-text">Chicken 65 is a South Indian deep-fried chicken appetizer that originated in Hotel Buhari in Chennai. It’s a crowd-pleaser and has found a top place on restaurant menus.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="naan.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Naan</h5>
            <p class="card-text">Naan is a delightful Indian flatbread that pairs perfectly with curries or can be enjoyed on its own.It's a Punjabi food with variety of flavors In different styles.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="idli.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Idli</h5>
            <p class="card-text">Idli is a soft, pillowy steamed savory cake made from fermented rice and lentil batter. It’s a popular South Indian breakfast dish that’s naturally vegetarian, vegan, and gluten-free.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="chapathi.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Chapathi</h5>
            <p class="card-text">Chapathi (also known as roti or Indian flatbread) is a staple in Indian cuisine. It’s a simple yet delicious bread made from just a few basic ingredients. made by wheat Floor.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="footer">
    <div class="brand-name">Jayasree © 2024 InfinitiCook . All rights reserved </div>
    <ul class="social-icons">
        <li><a href="https://wa.me/8939238010" target="_blank"><i class="fab fa-whatsapp"></i></a></li>
        <li><a href="https://instagram.com/jayasree.2006" target="_blank"><i class="fab fa-instagram"></i></a></li>
        <li><a href="mailto:jayasree2403206@gmail.com"><i class="fas fa-envelope"></i></a></li>
        <li><a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a></li>
    </ul>
</footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@1.16.0/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

### styles.css

```
.recipe-card 
{
  margin-bottom: 40px;
  padding: 15px;
}
.navbar 
{  
  width: 100%;
  padding: 35px 0;
  background-color: black;
}
.navbar a 
{
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
.navbar a:hover 
{
  background-color: #ffffff;
  color: rgb(0, 0, 0);
}
.footer 
{
  background-color: #333;
  color: white;
  padding: 20px 0;
  text-align: center;
}
.footer .brand-name 
{
  font-size: 18px;
  margin-bottom: 10px;
}
.footer .social-icons 
{
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: center;
}
.footer .social-icons li 
{
  margin: 0 10px;
}
.footer .social-icons a 
{
  color: white;
  text-decoration: none;
  font-size: 20px;
}
.footer .social-icons a:hover 
{
  color: #ddd;
}
.logo 
  {
    color: #152bd2;
    font-size: 40px;
    font-weight: 700;
    letter-spacing: 3px; 
    font-family: 'Courier New', Courier, monospace;       
  }
  span 
  {
    color: rgb(252, 250, 250);
  }
  html
  {
    font-size: 72.5%;
    word-wrap: break-word;
    scroll-behavior: smooth;
  } 
  .header 
  {
    display: flex;
    align-items: center;
    background-color: #000000;
    padding: 10px;
    border-bottom: 1px solid #ddd;
  }
  .header-image
  {
    width:50px;
    height:50px;
    border-radius: 30%;
    margin-right: 20px;
    background-color: black;
  }
  @media (max-width: 768px) 
  {
    body
     {
      padding-top: 56px;
    }
  }

```

 
## OUTPUT :

![image](https://github.com/user-attachments/assets/4d9f1dc6-202a-481a-b2c0-90ba4a91171f)
![image](https://github.com/user-attachments/assets/65a316ba-07d8-4660-b747-bf4490b5bdf7)
![image](https://github.com/user-attachments/assets/8c43e161-a13c-4d56-a2c9-6d82be893415)





## RESULT :
The program for creating commercial website using CSS Flexbox is executed successfully.
