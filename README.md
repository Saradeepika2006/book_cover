# Ex.06 Book Front Cover Page Design
# Date:29-11-2024
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
```<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Ari
            background-image:url(book.jpg);
            background-size: cover;
            color:rgb(1, 7, 9);


        }
            

        .insight{
            color:black;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size:600;
            font-weight :800;
            text-align: center;
            position: relative;
            top: 50px;
            color:rgb(1, 7, 9);
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-size:15px;
            position: relative;
            top:70px;
            color:rgb(1, 7, 9);
            text-align: center;
        }
        .mypic{
            position: relative;
            top: 170px;
            left: 300px;
            
            
            
            background-size: cover;
        }
        .page{
            position: relative;
           top:50px;
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
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Development</h1></div>
            <div class="subtitle">
                <p>WEB DEVELOPMENT</p>
            </div>
            <div class="page">
            <div class="mypic">
                <img src="deeps.jpg" width="100" height="100" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(208, 255, 0);">
            </div>
            <div class="author">
               <p><b>M Saradeepika (24010825)</b></p>
            </div>
          
          
           
            <div class="ed">
                <b>Extended Edition</b>
            </div>
            </div>
            
        </div>
    </body>
</html>
```
# OUTPUT:
![book cover pdf ](https://github.com/user-attachments/assets/3495b4a5-2327-49d0-a146-6c8d23e60195)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
