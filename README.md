# Ex.06 Book Front Cover Page Design
## Date: 28.04.2025

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
<html>

<head>
    <title>Dune</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #111;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            padding: 20px;
            position: relative;
            background-image: url('back.jpg'); 
            background-size: cover;
            background-position: center;
            border-radius: 0px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.6);
        }

        .booktitle {
            color: white;
            font-family: 'Cinzel', serif; 
            font-size: 48px;
            text-align: center;
            position: absolute;
            top: 11px;
            width: 90%;
            text-shadow: 3px 3px 12px rgba(0, 0, 0, 0.7);
        }

        .subtitle {
            text-align: center;
            font-size: 22px;
            color: white;
            position: absolute;
            top: 80px;
            width: 90%;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);
        }

        .mypic {
            position: absolute;
            top: 450px;
            right: 55px;
            width: 60px;
            height: 100px;
            background-size: cover;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.6);
        }

        .author {
            text-align: right;
            color: #FFD700; 
            font-family: 'Andale Mono', monospace;
            font-size: 16px;
            font-weight: lighter;
            position: absolute;
            top: 530px;
            right: 24.5px;
            width: 100%;
            text-shadow: 1px 1px 4px rgba(241, 245, 246, 0.682);
        }

        .id {
            width: 90%;
            position: absolute;
            top: 530px;
            margin: 0 auto;
            color: white;
        }

        .end {
            color: white; 
            font-size: 20px;
            font-family: 'Cinzel', serif;
            text-align: center;
            position: absolute;
            bottom: 10px;
            width: 90%;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);
            -webkit-text-stroke: 0.4px white;
        }

        hr {
            border: none;
            border-top: 2px solid #FFD700;
            margin-top: 50px;
            margin-bottom: 50px;
        }
    </style>
</head>

<body>
    <div class="bookpage">
        <div class="booktitle">
            <h1>DUNE</h1>
        </div>

        <div class="mypic">
            <img src="myphoto.jpg" width="110" height="120"> 
        </div>

        <div class="id">
            <hr style="color: #FFD700">
        </div>

        <div class="author">
            <p><b><font color="WHITE">Adithya s</font></b></p>
        </div>

        <div class="end">
            <b>"He who controls the spice controls the universe."</b>
        </div>
    </div>
</body>

</html>
```

## OUTPUT:
Adithya sivakumar 212224040013

![alt text](<Screenshot (431).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
