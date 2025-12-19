# Ex.06 Book Front Cover Page Design
## Date:19-12-2025

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
  <title>BookCover</title>
  <style>
    body {
      display: flex;
      margin: 0;
      justify-content: center;
      align-items: center;
      height: 100vh; /* full screen height */
    }
    .BookCover {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background: url("https://img.freepik.com/premium-photo/anime-scene-castle-with-giant-spiral-staircase-leading-it-generative-ai_955884-20238.jpg?w=2000") no-repeat center center;
      background-size: cover; /* makes image fit nicely */
      color: cyan;
      height: 600px;
      width: 400px;
      font-size: x-large;
      text-align: center;
      padding: 20px;
    }
    h1 {
      margin-bottom: 20px;
      text-transform: uppercase;
      font-family: 'Cinzel Decorative';
    }
    h6 {
      margin-left: 0;
      font-family:  'Cinzel Decorative';
      text-transform: uppercase;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="BookCover">
    <h1><b><u>Chronicles of Beyond celestial</u></b></h1>
    <h6>Author Name<br> 
         -Mysterious chad</h6>
  </div>
</body>
</html>
```


## OUTPUT:
![alt text](<../Screenshot 2025-12-19 233737.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
