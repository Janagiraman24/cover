# Ex.06 Book Front Cover Page Design
## Date:14.05.2025

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
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background: #111;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    .cover {
      width: 420px;
      height: 600px;
      background: #2c2c2c url('backcover.jpg') no-repeat center/cover;
      position: relative;
      color: white;
      padding: 30px;
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.8);
    }

    .overlay {
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.7);
      padding: 30px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .top {
      font-size: 12px;
      color: lightgray;
      letter-spacing: 1px;
    }

    .title {
      font-size: 30px;
      font-weight: bold;
      margin-top: 20px;
      line-height: 1.2;
    }

    .subtitle {
      font-size: 14px;
      margin-top: 10px;
      color: #ddd;
    }

    .edition {
      color: orange;
      font-weight: bold;
      margin-top: 30px;
      font-size: 16px;
    }

    .bottom {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 20px;
    }

    .author {
      font-size: 16px;
      font-weight: bold;
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
    }

    .author-img {
      position: absolute;
      bottom: 25px;
      right: 25px;
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid white;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="overlay">
      <div>
        <div class="top">EXPERT INSIGHT</div>
        <div class="title">Responsive Web<br>Design with<br>HTML5 and CSS</div>
        <div class="subtitle">Develop future-proof responsive websites<br>using the latest HTML5 and CSS techniques</div>
        <div class="edition">Third Edition</div>
      </div>
      <div class="bottom">
        <div class="author">JANAGIRAMAN M(212224230101)</div>
        <div class="logo">Packt</div>
      </div>
    </div>
    <img src="author.jpg" alt="Author" class="author-img">
  </div>
</body>
</html>
```

## OUTPUT:
![Screenshot 2025-05-14 191831](https://github.com/user-attachments/assets/2c0aef25-5662-42f9-b5d6-8ec46a536911)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
