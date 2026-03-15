# Ex.06 Book Front Cover Page Design
## Date:15.03.2026

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
<head>
    <title>Book Cover</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="cover">
        <div class="border">
            <h3 class="top">SEC Insights</h3>

            <h1>INFORMATION TECHNOLOGY INFRASTRUCTURE<br>AND IT'S MANAGEMENT</h1>

            <p class="sub>Technology is the best when it brings people together<br>BEST SELLER</p>

            
                <div class="left">
                 <h4>SPECIAL EDITION</h4>
                    <div class="name">
                          <p>ASHLEY ANTONY</p>
                    
                         <div class="right">
                            <img src= "ashley.jpg"alt ="Author Photo">
                            <hr class="line">
                            <div class>
                                <p>SEC</p>
                            </div>

                          </div>
                    </div>
                </div>

body {
    background-color: #cc00cc;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.cover {
    width: 400px;
    height: 550px;
    background:url(background.png);
    background-size:cover;
    background-position:center; 
    position: relative;
    text-align: center;
    color: black;
    font-family: 'Times New Roman',sans-serif;
    box-shadow: 0 0 10px rgba(0,0,0,0.3);
}

.border {
    border: 4px solid green;
    margin: 25px;
    height: 85%;
    padding: 15px;
    position:relative;
}

.top {
    position:relative;
    bottom:20px;
    right:120px;
    margin:0;
    padding:6px 8px 6px 0;
    display:inline-block;
    font-size: 16px;
    border-bottom: 1px solid black;
    color:solid red;
}

h1 {
    font-size: 24px;
    margin-top: 30px;
    font-weight: bold;
}

.sub {
    font-style:italic;
    font-size: 15px;
    margin-top: 20px;
}

.left h4 {
    position:relative;
    top:150px;
    right:70px;
    font-size:18px;
    font-style:unset;
    font-weight:bold;
    margin:0;
}

.left p {
    position:relative;
    top:220px;
    right:100px;
    font-size: 20px;
    margin-top:5px;
}

.right img {
    position:relative;
    top:5px;
    left:90px;
    width: 130px;
    height: 150px;
    border: 2px solid black;
}

.line {
    height:2px;
    width:100%;
    background-color:black;
}

.right p {
    font-style:initial;
    font-size:larger;
    top:8px;
    left:100px;
    margin-top: 5px;
    font-weight: bold;
}


```
## OUTPUT:
![alt text](<Screenshot (24).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
