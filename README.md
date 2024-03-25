# Ex04 Places Around Me
## Date: 

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

## OUTPUT

<!DOCTYPE html>
<html>
    <title> images demo </title>
</html>
<body>
    <h1> imagemaps demo</h1>
    <img src="kishore-hometown.png" usemap="#image_map">
    <map name="image_map">
    <area alt="TV MALAI BUS STAND" title="Bus Stand" href="busstand.html" coords="778,229,915,339" shape="rect">
    <area alt="railway station" title="railway station" href="station.html" coords="941,300,979,343" shape="rect">
    <area alt="temple" title="TIRUVANNAMALAI TEMPLE" href="temple.html" coords="731,381,949,469" shape="rect">
    <area alt="college" title="GOVERMENT COLLEGE" href="college.html" coords="759,724,883,823" shape="rect">
    <area alt="mountain" title="TV_MOUNTAIN" href="mountain.html" coords="534,225,617,279" shape="rect">
    </map>

</body>





## RESULT
The program for implementing image maps using HTML is executed successfully.
