# Ex.06 Book Front Cover Page Design
# Date: 03-10-2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: auto;
      padding: 0;
      background: #f2f2f2;
      font-family: 'Georgia', serif;

    }
    .book-cover {
      width: 400px;
      height: 600px;
      margin: 50px auto;
      background-image: url(gurl.jpg);
      color: white;
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 40px;
      text-align: center;
      border-radius: 10px;
    }

    .book-title {
      font-size: 36px;
      font-weight: bold;
      margin-bottom: 20px;
      background-color: rgb(202, 199, 186);
      color: black;
    }

    .book-subtitle {
      font-size: 20px;
      font-style: italic;
      margin-bottom: 30px;
      background-color: rgb(180, 180, 171);
      color: black;
      text-align: right;
      text-shadow: 0cap;
    }

    .author {
      font-size: 18px;
      margin-top: auto;
      font-style: italic;
      background-color: rgb(195, 195, 186);
      color: rgb(160, 153, 153);
      color: black;
      text-align: right;  
  }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="book-title">The Life of a girl</div>
    <div class="book-subtitle">Freedom and fire</div>
    <div class="author">by: Tharani Rameshbabu</div>
  </div>

</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot (43).png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
