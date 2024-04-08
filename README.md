# Ex04 Places Around Me
## Date: 01/04/2024
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

### map.html
```
<html>
    <head>
        <title>THIRUVANNAMALAI</title>
    </head>
    <body>
        <h1 align ="center">THIRUVANNAMALAI</h1>
        <h2 align ="center">ARAVIND R[212223230019]</h2>
   


<img src="thiru.png.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="The Mountain Retreat" title="The Mountain Retreat" href="mountain.html" coords="800,498,1071,583" shape="rect">
    <area target="" alt="Pushpa Mahal and Residency" title="Pushpa Mahal and Residency" href="pushpa mahal.html" coords="888,804,1121,904" shape="rect">
    <area target="" alt="Ashram" title="Ashram" href="greenland.html" coords="900,281,95" shape="circle">
    <area target="" alt="poorvika Mobile Shop" title="poorvika Mobile Shop" href="mobile.html" coords="1254,521,1511,586" shape="rect">
    <area target="" alt="Imagica Fun World" title="Imagica Fun World" href="fun.html" coords="1342,389,1223,325" shape="rect">

</map>
</body>
</html>
```

### fun.html
```
<html>
<head>
<h1><center>THIRUVANNAMALAI</center></h1>
<h3><center>IMAGICA FUN WORLD</center></h3>
<hr>
</head>
<body bgcolor="Green">
<p>
    Imagica Theme Park is India's first and only International standard Theme Park, offering fun, action, entertainment, dining and shopping at a single location. Imagica Theme park is no ordinary theme park. There's nothing of this scale, or anything close to it in India and the Subcontinent
    </p>
</body>
</html>
```
### mobile.html
```
<html>
<head>
<h1><center>THIRUVANNAMALAI</center></h1>
<h3><center>Poorvika Mobile Shop</center></h3>
<hr>
</head>
<body bgcolor="cyon">
<p>"Poorvika is the Largest Tech Retailer in India, spanning across 460+ showrooms in and around Tamil Nadu, Karnataka, Pondicherry, Mumbai and Pune, famous for their touch & feel Live Demo experience before buying. Poorvika sells a wide category of devices in its showrooms and Online portal, ranging from the Best Smartphones, Laptops, Computers, Smart Devices, and Smart TVs to Accessories. Smartphone lovers await an enthralling experience at Poorvika. Having served over 5 Crore+ Happy Customers, Poorvika takes pride in being India's leading retailer for Top Brands like Apple, Samsung, Oppo, Vivo, Xiaomi, OnePlus, Redmi, Realme, Nokia, etc."

    </p>
</body>
</html>
```
### greenland.html
```

<head>
<h1><center>THIRUVANNAMALAI</center></h1>
<h3><center> Greenland Ashram</center></h3>
<hr>
</head>
<body bgcolor="RED">
<p>
    Greenland Ashram stands out as a premier choice as a modern ashram, by being a sanctuary for comfortable stays and a guiding light for spiritual growth
    </p>
</body>
</html>
```
### pushpa.html
```
<head>
    <h1><center>THIRUVANNAMALAI</center></h1>
    <h3><center> Pushpa Mahal</center></h3>
    <hr>
    </head>
    <body bgcolor="pink">
    <p>
        Pushpa Mahal AC is an excellent venue with fully equipped restrooms available for guests. The facilities are well-maintained and ensure a comfortable experience for all attendees. With its convenient location and top-notch amenities, it`s the perfect choice for any event or gathering
    </p>
       
    </body>
    </html>
```
### mountain.html
```
<head>
    <h1><center>THIRUVANNAMALAI</center></h1>
    <h3><center> Mountain resort</center></h3>
    <hr>
    </head>
    <body bgcolor="blue">
    <p>
        A mountain resort is a place to holiday or vacation located in an elevated and typically at least relatively isolated area. The term resort implies integral hotel or inn accommodations, restaurants, and either or both sports facilities or scenic attractions. These can either be part of a "destination resort" that provides both accommodations and activities, or in a "resort town" that offers amenities near outdoor areas.
    </p>
       
    </body>
    </html>
```
## OUTPUT
### map.html
![Screenshot 2024-04-08 143023](https://github.com/ARAVIND23005370/NearMe/assets/148514836/2319fe63-11c3-42ee-9ba7-6d5b32cff7e5)

### mountain.html
![alt text](<Screenshot 2024-04-03 110423-1.png>)
### fun.html
![Screenshot 2024-04-03 110442](https://github.com/ARAVIND23005370/NearMe/assets/148514836/45678224-d54a-4c32-962d-ecc9812a5209)

### mobile.html
![alt text](<Screenshot 2024-04-03 110452-1.png>)
### pushpa mahal.html
![alt text](<Screenshot 2024-04-03 110506-1.png>)
### greenland.html
![alt text](<Screenshot 2024-04-03 110552-1.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
