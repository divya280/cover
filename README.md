# Ex.06 Book Front Cover Page Design
## Date: 14.11.2024

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book cover</title>
  <style>
   
    .cover-container {
      position: relative;
      width: 400px;
      height: 600px;
      margin: 0 auto;
      color:aquamarine;
      font-family: 'Georgia', serif;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.6);
    }

  
    .cover-image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      filter: brightness(1.3); /* Increase brightness */
    }

 
    .gradient-overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.6)); /* Lighter overlay */
    }

  
    .author-image {
      position: absolute;
      top: 20px;
      left: 30px;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      border: 2px solid burlywood; /* Gold border around the image */
      box-shadow: 0 0 8px rgba(255, 215, 0, 0.8);
    }
    .author-title {
      position: absolute;
      top: 20px;
      width: 100%;
      text-align: center;
      font-size: 1.5em;
      font-weight: bold;
      color:lightskyblue; /* Gold color for author text */
      font-family:cursive;
      letter-spacing: 2px;
      text-shadow: 0px 0px 8px rgba(11, 10, 0, 0.018);
    }
    .subtitle-line {
      position: absolute;
      top: 50px;
      width: 40%; /* Adjust width for smaller line */
      left: 30%; /* Center align */
      border-top: 1px solid lightskyblue;
      opacity: 0.8;
    }
    .main-title {
      position: absolute;
      bottom: 120px;
      width: 100%;
      text-align: center;
      font-size: 2.8em;
      font-weight: bold;
      color:powderblue; /* Vibrant orange-red color for main title */
      letter-spacing: 3px;
      text-shadow: 0px 0px 12px rgba(255, 69, 0, 0.8), 2px 2px 6px black;
      font-family: 'Palatino', serif;
    }
    .series-title {
      position: absolute;
      bottom: 80px;
      width: 100%;
      text-align: center;
      font-size: 1.2em;
      color:powderblue;
      font-style:normal;
      letter-spacing: 1px;
      text-shadow: 1px 1px 4px black;
    }
   
  </style>
</head>
<body>
  <div class="cover-container">
    <img src="C:\Users\admin\Downloads\hyyyy.jpg" alt="Book Cover Image" class="cover-image">
    <div class="gradient-overlay"></div>
    <img src="C:\Users\admin\Downloads\Photo from Divyashree__.jpg" alt="Author Image" class="author-image">
    <div class="author-title">DIVYASHREE V</div>
    <div class="subtitle-line"></div>
    <div class="main-title">THE GIRL<br>WITHOUT</div>
    <div class="series-title">A NAME</div>
  
  </div>
</body>
</html>
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/f48b4a06-d99d-48db-b315-01ecd2291b00)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
