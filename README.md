# Product Card Design with Hover Effect using CSS
## Date:

## AIM:
To design a Product Card for an E-commerce website using HTML and CSS and apply hover effects, transitions, and styling techniques to create an interactive user interface.

## DESIGN STEPS:

### Step 1:
Create a basic HTML structure using ```<!DOCTYPE html>, <html>, <head>, and <body>```.

### Step 2:
Add a container div for the product card.

### Step 3:
Insert the product image using the ```<img>``` tag.

### Step 4:
Add product name, description, and price using ```<h3>``` and ```<p>``` tags.

### Step 5:
Create an Add to Cart button using the ```<button>``` tag.

### Step 6:
Style the product card using CSS by applying:
<ul>
  <li>width</li>
  <li>padding</li>
  <li>border-radius</li>
  <li>box-shadow</li>
</ul>

### Step 7:
Align the card content using text-align and spacing properties.

### Step 8:
Add hover effects using :hover selector.

### Step 9:
Apply transform: translateY() to move the card slightly upward on hover.

### Step 10:
Increase the box-shadow to create a lifting effect.

### Step 11:
Add transform: scale() to slightly zoom the product image on hover.

### Step 12:
Apply transition property to make the hover animation smooth.

### Step 13:
Create a footer section at the bottom of the page.

### Step 14:
Display Learner Name and Register Number inside the footer.

### Step 15:
Style the footer using background color and center alignment.

### Step 10:
Test your webpage in a browser.

## PROGRAM:
<html>
<head>
    <title>Product Card</title>
    <style>
        body{
            background-color: #eeeeee;
            font-family: Arial;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .card{
            width: 300px;
            background-color: white;
            border-radius: 10px;
            margin: 50px auto;
            box-shadow: 2px 2px 10px grey;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover{
            transform: translateY(-5px);
            box-shadow: 4px 4px 20px grey;
        }

        .card img{
            width: 100%;
            height: 230px;
            transition: transform 0.3s;
        }

        .card:hover img{
            transform: scale(1.05);
        }

        h2{
            font-size: 20px;
        }

        p{
            font-size: 14px;
            color: grey;
            padding: 0 10px;
        }

        .price{
            font-size: 20px;
            color: rgb(0, 255, 13);
            font-weight: bold;
        }

        button{
            background-color: rgb(36, 0, 128);
            color: white;
            border: none;
            padding: 10px 25px;
            font-size: 14px;
            border-radius: 5px;
            margin-bottom: 20px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .card:hover button{
            background-color: darkgreen;
        }

        footer{
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <h1>my Products</h1>

    <div class="card">
        <img src="c:\Users\acer\Downloads\Screenshot 2026-03-09 142343.png" alt="watch">
        <h2><T-shirt></T-shirt></h2>
        <p>Stylish streachable T-shirt .</p>
        <p class="price">399</p>
        <button>Add to Cart</button>
    </div>

    <footer>
        <p>Name: ANISH K B</p>
        <p>Register Number: 25019112</p>
    </footer>

</body>
</html>
## OUTPUT:

<img width="1920" height="1080" alt="Screenshot 2026-03-09 143039" src="https://github.com/user-attachments/assets/3edff5da-0b0a-4075-92be-aadf6eb4f8a3" />

## RESULT:
The Product Card with Hover Effect was successfully designed using HTML and CSS.
