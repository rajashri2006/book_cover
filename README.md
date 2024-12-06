# Ex.06 Book Front Cover Page Design
# Date:30-11-2024
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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: "Apple" "Chancery", "cursive";
            
        }
        .cover {
            width: 400px;
            height: 600px;
            border: 3px solid  #241d1d;
            background-color: #edf4f7;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            background: linear-gradient(rgba(48, 32, 32, 0.605),rgba(194, 99, 99, 0.7)),url(images.jpg);
        }
        .title {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 20px;
            color:  #a09494;
        }
        .subtitle {
            font-size: 24px;
            margin-bottom: 40px;
            color: #555;
        }
        .author {
            font-size: 18px;
            font-style:"Chancery" ;
            color: #a09494;
        }
        .bottom-text {
            margin-top: auto;
            font-size: 14px;
            color: #231e1e;
        }
    </style>
</head>

<body>
  
    <div class="cover">
        <div class="title">The Night's Dream</div>
        
        <hr>
        <div class="author">by william shakespeare</div>
        <hr>
        <div class="bottom-text">"It's Very Easy To Give Example But Its Very Difficult To Become An Example"</div>
    </div>
</body>

</html>
```

# OUTPUT:
![book](https://github.com/user-attachments/assets/cd3fdee1-51c4-401e-99ef-703c65cd1b62)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
