# Ex.06 Book Front Cover Page Design
## Date:06.12.2024

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
yellove.html

<html>
    <head>
        <title>Book Cover</title>
        <style>
             .bookpage{

             width: 400px;
             height: 600px;
             color:black;
             margin-left: auto;
             margin-right: auto;
             padding: 20px;
             font-family: ' Arial, sans-serif';
             background-image: url("coverhai.png");
             background-size: cover;
        }


        .insight{
        color:azure;
        font-family: Trebuchet MS;

        }


        .hrstyle{
         width:100px;
        }
        .author{
        
        display: inline;
        position: relative;
        color:rgb(255, 255, 255);
        top:170px;
        
        font-family:Georgia;
        font-size: medium;
    }
        .booktitle{
        color:azure;
        font-family: 'Times New Roman', Times, serif;
        font-size: larger;
        text-align: left;
        position: relative;
        top: 30px;
    
    }
        .id {
        width:400px;
        position: relative;
        top:180px;
        
    }
        .pub{
        color:azure;
        font-size: medium;
        position: relative;
        top:155px;
        left:330px;
    }
        .sub{
        color:azure;
        font-family:Arial, Helvetica, sans-serif;
        font-size: large;
        position: relative;
        top:340px;
        }
        .ed{
            color:rgb(132, 241, 209);
            font-size: medium;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position:relative;
            bottom:200px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .sub{
            color:azure;
            font-family:Arial, Helvetica, sans-serif;
            font-size: large;
            position: relative;
            top:340px;
        }

        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }


        </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">

            </div>
            <div class="hrstyle">
                <hrstyle="color : green">
            
            </div>
            <div class="booktitle">
                <h1 style="font-family: 'Times New Roman', Times, serif;color: bisque;">Introduction to ROS and RoboDK</h1>
            </div>
            <div class="subtitle" style="text-align: left;color: antiquewhite;">
                Develop your Imagination into reality
            </div>
            <br>
            <div class="subtitle" style="color: aliceblue;text-align: left;">NEW AND REVISED VERSION</div>
            <div class="sub" style="color: beige;text-align: left;">For the Love of Robotics</div>
            <div class="mypic">
                <img src="dekhmeraphoto.png" width="120 px" height="120">
            </div>
            <div class="id">
                <hrstyle="color : red">
            </div>
            <div class="author">
                <p><b>ELFREEDA JESUSHA J(24900146)</b></p>
            </div>
            <div class="ed">
                <b>FIFTH EDITION</b>
            </div>
        </div>
    </body>
</html>

```


## OUTPUT:

![alt text](Bookcoverpage.png)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
