# Ex04 Places Around Me
## Date: 6.05.2025
## Name:MAHALAKSSMI MRIDULA.S.
## Reg no:212224220056
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
```
<html>
    <head>
        <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="darkred"><b>SIVAKASI</b></font>
        </h1>
        <h3 align="center">
            <font color="orange"><b>MAHALASSMI MRIDULA.S (212224220056)</b></font>
        </h3>
        <center>
            <img src="sivakasi_map.png" usemap="#MYCITY" height="610" width="1450">
            <map name="MYCITY">
                <area target="_parent" alt="FIREWORKS INDUSTRY" title="FIREWORKS INDUSTRY" href="fireworks.html" coords="1100,300,100" shape="circle">
                <area target="_parent" alt="KALISWARI TEMPLE" title="KALISWARI TEMPLE" href="temple.html" coords="950,400,50" shape="circle">
                <area target="_parent" alt="SIVAKASI BAZAAR" title="SIVAKASI BAZAAR" href="bazaar.html" coords="800,500,1200,580" shape="rect">
                <area target="_parent" alt="PAPER INDUSTRY" title="PAPER INDUSTRY" href="paper.html" coords="600,250,80" shape="circle">
            </map>
        </center>
    </body>
</html>

<html>
<head>
    <title>SIVAKASI</title>
</head>
<body bgcolor="lightyellow">
<h1 align="center">
    <font color="red"><b>FIREWORKS INDUSTRY</b></font>
</h1>
<h3 align="center">
    <font color="darkorange"><b>SIVAKASI SPECIALITY</b></font>
</h3>
<hr size="3" color="orange">
<p align="justify">
<font face="Arial" size="5">
Sivakasi is renowned for its vibrant fireworks industry, which accounts for a major share of India's firecracker production. The town has over 8,000 production units and provides employment to thousands of workers. The industry plays a key role in local and national festivals, especially Diwali. Despite facing challenges from environmental concerns and safety regulations, it remains a crucial part of Sivakasi's economy and identity.
</font>
</p>
</body>
</html>


<html>
<head>
    <title>SIVAKASI</title>
</head>
<body bgcolor="lightgrey">
<h1 align="center">
    <font color="darkblue"><b>SIVAKASI BAZAAR</b></font>
</h1>
<h3 align="center">
    <font color="black"><b>COMMERCIAL HUB</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Verdana" size="5">
Sivakasi Bazaar is the bustling heart of the town’s trade and commerce. From printing materials to firecracker supplies, the market offers a wide variety of goods. It’s not only a shopping destination but also a cultural melting pot, reflecting the entrepreneurial spirit of the town.
</font>
</p>
</body>
</html>

<html>
<head>
    <title>SIVAKASI</title>
</head>
<body bgcolor="honeydew">
<h1 align="center">
    <font color="darkgreen"><b>PAPER INDUSTRY</b></font>
</h1>
<h3 align="center">
    <font color="seagreen"><b>PRINTING POWERHOUSE</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Courier New" size="5">
The paper and printing industry in Sivakasi is a significant economic driver. Known as India’s printing capital, it produces a wide range of printed materials, including matchbox labels, wedding cards, and packaging. Modern technology and traditional craftsmanship blend here to create a thriving industrial ecosystem.
</font>
</p>
</body>
</html>
```




## OUTPUT
![Screenshot 2025-05-06 060113](https://github.com/user-attachments/assets/50530767-3fe2-4a0c-9d5b-303371196aef)
![Screenshot 2025-05-06 055036](https://github.com/user-attachments/assets/eb276f9e-b4d6-4d14-931a-dc685933fd1e)
![Screenshot 2025-05-06 055129](https://github.com/user-attachments/assets/4e50f298-f228-4ed2-9fc7-040ae62f73a6)
![Screenshot 2025-05-06 055230](https://github.com/user-attachments/assets/9e7ae15d-50b7-45c3-9865-26a0807e4af0)








## RESULT
The program for implementing image maps using HTML is executed successfully.
