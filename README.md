# Ex04 Places Around Me
## Date: 24.09.2025

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
        <title>sample page</title>
        <link rel="stylesheet" href="stylecss">
    </head>
<body>
    <img src="C:\Users\acer\NearMe\vishnu\mapapp\static\Screenshot 2025-09-22 091523.png"usemap="#image-map">

<map name="image-map">
    <area target="" alt="annamalaiyar nagar" title="annamalaiyar nagar" href="C:\Users\acer\NearMe\vishnu\mapapp\static\tiruvannamalai.html" coords="595,110,817,151" shape="rect">
    <area target="" alt="tiruvannamalaiu" title="tiruvannamalai" href="C:\Users\acer\NearMe\vishnu\mapapp\static\tiruvannamalaiu.html" coords="1006,452,993,388,766,387,742,439,873,484" shape="poly">
    <area target="" alt="nallavanpalayam" title="nallavanpalayam" href="C:\Users\acer\NearMe\vishnu\mapapp\static\nallavanpalayam.html" coords="533,706,96" shape="circle">
    <area target="" alt="vengikkal" title="vengikkal" href="C:\Users\acer\NearMe\vishnu\mapapp\static\vengikkal.html" coords="736,270,991,328" shape="rect">
    <area target="" alt="tiruvannamalai" title="tiruvannamalai" href="C:\Users\acer\NearMe\vishnu\mapapp\static\tiruvannamalai.html" coords="827,614,103" shape="circle">
</map>
</body>

</html>
```


## OUTPUT

![alt text](<vishnu/mapapp/static/Screenshot 2025-09-22 091523.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
