# Ex.06 Book Front Cover Page Design
# Date:21.04.2025
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
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('pngtree-blue-bubble-effect-background-with-golden-stripes-book-cover-page-poster-image_902262.png');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .insight {
            color: black;
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color:black;
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: "Courier New", Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 180px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .ed {
            color: black;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
    </style>
    <title>Responsive Web Design Book</title>
</head>
<body>
    <div class="bookpage">
        <div class="insight">
            SEC
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>RESPONSE WEB DESIGN WITH HTML5 AND CSS</h1>
        </div>
        <div class="subtitle">
            Develop future-proof responsive web applications with HTML5 and CSS
        </div>
        <div class="mypic">
            <img src="67735c7ff6d442370387ccb9.png" width="130" height="145" alt="My Picture">
        </div>
        <div class="id">
            <hr style="color: orange;">
        </div>
        <div class="author">
            <p><b>DHARUN ARULSELVAN</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>3rd Edition</b>
        </div>
    </div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2025-04-21 203559.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
