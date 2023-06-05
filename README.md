# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
Step 1:
Create a new django project and app

Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.

Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click

Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked

Step 5:
Include pictures and contents for your subpages and map them using urls and views

##Code:
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    Image Map Of My Home Town
            </font>


            
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            RAHUL.B(22001882)
        </font>
            
        </h3>
        <center>
        <img id="Image-Maps-Com-image-maps-2023-06-05-141040" src="map1.jpg.jpeg" border="0" width="1828" height="788" orgWidth="1828" orgHeight="788" usemap="#image-maps-2023-06-05-141040" alt="" />
<map name="image-maps-2023-06-05-141040" id="ImageMapsCom-image-maps-2023-06-05-141040">
<area  alt="" title="stadium" href="stadium.html" shape="rect" coords="693,401.00001525878906,743,451.00001525878906" style="outline:none;" target="_self"     />
<area  alt="" title="stadium" href="stadium.html" shape="rect" coords="493,418,668,665" style="outline:none;" target="_self"     />
<area  alt="" title="temple" href="temple.html" shape="rect" coords="1381,184,1456,276" style="outline:none;" target="_self"     />
<area  alt="" title="mosque" href="mosque.html" shape="rect" coords="942,453,1017,545" style="outline:none;" target="_self"     />
<area  alt="" title="theater" href="theater.html" shape="rect" coords="1831,302,1874,353" style="outline:none;" target="_self"     />
<area  alt="" title="postoffice" href="postoffice.html" shape="rect" coords="1801,479,1844,530" style="outline:none;" target="_self"     />
<area shape="rect" coords="1918,1078,1920,1080" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>
        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>


    </body>
</html>


## Output:

![Screenshot (90)](https://github.com/RAHUL-22001882/places-around-me/assets/123528986/09e40feb-90d6-4bd0-9b7b-6eb73ee477bd)

## Result:
Thus a website is developed to display details about my school near my house.
