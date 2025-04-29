# Ex.06 Book Front Cover Page Design
# Date:24.04.2025
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
<html>
<head>
<title>CSE</title>
<style>
.bookpage{
width: 400px;
height: 600px;
color:rgb(232, 233, 217);
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: ' Arial, sans-serif';
background-image: url(cover.png);
background-size: cover;
}
.author{
display: inline;
position: relative;
color:rgb(153, 26, 91);
top:190px;
font-family:Georgia;
font-size: medium;
}
.booktitle{
color:rgb(24, 102, 102);
font-family: Roquen;
font-size: larger;
text-align: center;
position: relative;
top: 30px;
}
.id {
width:400px;
position: relative;
top:180px;
}
.ed{
color:rgb(193, 186, 198);
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
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
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="booktitle">
<h1> <FONT color="white">The power of Subconscious mind</h1></div></FONT>
<br>
<div class="subtitle">
<center><font color="pink">The conscious mind is editor ,subconscious mind is writer </center></font>
</div>
<br>
<br>
<br>
<br>

<div class="mypic">
<img src="Screenshot 2025-04-22 110257.png" width="90" height="90" >
</div>
<div class="id">
<hr style="color:rgb(213, 217, 127)">

</div>
<div class="author">
<p><b>Joseph Murphy</b></p>
</div>
<div class="ed">
<b>Step to Success</b>
</div>
</div>
</body>
</html>
```
# OUTPUT:
![Screenshot 2025-04-28 212541](https://github.com/user-attachments/assets/e9c37339-21d6-4097-8cb5-0870360718a2)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
