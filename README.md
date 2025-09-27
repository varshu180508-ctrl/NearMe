# Ex04 Places Around Me
## Date:26.09.25 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

map.html

<html>
    <head>
        <title>My City</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <h1 align="center">
    <font color="red"><b>Karur</b></font>
    </h1>
    <h3 align="center">
    <font color="green"><b>Dhanvarsini S (25012184)</b></font>
    </h3>
    <center>
    <img src="map.png" usemap="#image-map">
    <map name="image-map">
    <area target="" alt="atlas arangam" title="atlas arangam" href="atlas.html" coords="252,93,441,161" shape="rect">
    <area target="" alt="kamakshi amman temple" title="kamakshi amman temple" href="temple.html" coords="1120,268,121" shape="circle">
    <area target="" alt="karur medical college" title="karur medical college" href="college.html" coords="753,537,808,529,934,599,837,667,756,659,640,604,752,537" shape="poly">
    <area target="" alt="aarunya clinic" title="aarunya clinic" href="clinic.html" coords="428,283,608,340" shape="rect">
    <area target="" alt="balasubramaniyan temple" title="balasubramaniyan temple" href="kovil karur.html" coords="742,172,170" shape="circle">
    </map>
    </center>
    </body>
    </html>
temple

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="orange">
    <h1 align="center">
    <font color="red"><b>Karur</b></font>
    </h1>
    <h3 align="center">
    <font color="black"><b>Kamakshi Amman temple</b></font>
    </h3>
    <hr size="4" color="black">
    <p align="justify">
    <font face="georgia" size="6" color="white">
       The Sri Kamakshi Amman temple is loacted in the serene village of panchamadevi near karur.It is a sacred abode dedicated to Goddess Kamakshi.
    </font>
    </p>
    </body>
    </body>
</html>

atlas

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="purple">
    <h1 align="center">
    <font color="yellow"><b>Karur</b></font>
    </h1>
    <h3 align="center">
    <font color="red"><b>Atlas Mahal</b></font>
    </h3>
    <hr size="4" color="black">
    <p align="justify">
    <font face="georgia" size="6" color="white">
       Atlas mahal is likely a Atla Kalaiarangam ,a versatile event and conference venue in karur.It is located in vengamedu karur and established by local community
    </font>
    </p>
    </body>
    </body>
</html>

kovil karur

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="lime">
    <h1 align="center">
    <font color="purple"><b>Karur</b></font>
    </h1>
    <h3 align="center">
    <font color="cyan"><b>Balasubramania Temple</b></font>
    </h3>
    <hr size="4" color="black">
    <p align="justify">
    <font face="georgia" size="6" color="white">
     The Arulmigu  Balasubramaniya temple is located in vennamalai karur.It is dedicated to lord murugan .It is known as vennamalai Murugan temple.
    </font>
    </p>
    </body>
    </body>
</html>

college

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="grey">
    <h1 align="center">
    <font color="white"><b>Karur</b></font>
    </h1>
    <h3 align="center">
    <font color="black"><b>Medical College</b></font>
    </h3>
    <hr size="4" color="black">
    <p align="justify">
    <font face="georgia" size="6" color="white">
        karur mediacl college is a prestigious college in karur.This institution affiliated to the tamilnadu DR.MGR medical university       
    </font>
    </p>
    </body>
    </body>
</html>

clinic

<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
    <font color="violet"><b>Karur</b></font>
    </h1>
    <h3 align="center">
    <font color="black"><b>Aaranya clinic</b></font>
    </h3>
    <hr size="4" color="black">
    <p align="justify">
    <font face="georgia" size="6" color="white">
      Aaranya clinic is located in thitta salai road karur near amaravathi river.Make quick treatment by the doctor.the clinic has very welcoming atmosphere ,well maintainted and with good facilities.     
    </font>
    </p>
    </body>
    </body>
</html>



## OUTPUT
![alt text](<Screenshot (2).png>)
![alt text](<Screenshot (3).png>)
![alt text](<Screenshot (4).png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (7).png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
