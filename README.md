# Ex.06 Book Front Cover Page Design

## Date:15-11-2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
Developed by :Ashmi S
Register number: 212221040021
```
## cover.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 600px;
            height: 800px;
            color:rgb(15, 12, 12);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(opo.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: brown;

        }

        
        .hrstyle{
                        width:100px;
        }
        .author{
            color: rgb(18, 16, 16);
            display: inline;
            position: relative;
            color: rgb(172, 47, 18);
            top:460px;
            
            font-family:Georgia;
            font-size: 20px;
        }
        .booktitle{
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: -10px;
            left: 40px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:460px;
            color: rgb(15, 13, 9);
            
        }
        .pub{
            font-size: 20px;
            position: relative;
            top:425px;
            left:330px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            color: rgb(172, 47, 18);
        }
        .ed{
            color:blue;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:350px;

        }
        .subtitle{
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: large;
            position: relative;
            left: 200px;
            top: -25px;
            color: rgb(3, 3, 2);
        }
        .mypic{
            position: relative;
            top: 470px;
            left: 480px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(249, 245, 245);">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="ashmi.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(16, 12, 3);">
            </div>
            <div class="author">
               <p><b>Ashmi S</b></p>
            </div>
            <div class="pub">
                <b>SEC</b>
            </div>
            <div class="ed">
                <b>Fifth Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## OUTPUT:
![Screenshot (421)](https://github.com/selvasachein/cover/assets/103128410/a858b885-4275-4968-88de-a77f12ff61cb)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
