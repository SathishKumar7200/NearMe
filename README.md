# Ex04 Places Around Me
## Date: 17-11-2025

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

```
<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body>

    <h1 align="center">
        <font color="red"><b>Pudhukkottai</b></font>
    </h1>

    <h3 align="center">
        <font color="blue"><b>Sathish kumar M(24900774)</b></font>
    </h3>

    <center>
        <img src="Screenshot 2025-11-17 003115.png" usemap="#MyCity" height="610" width="1450">

        <map name="MyCity">
            <area shape="rect" 
                  coords="100,100,900,900" 
                  href="home.html" 
                  title="My Home Town">
        </map>
    </center>

</body>
</html>

```

sittanavasal.html 

```

<html>
    <head>
        <title> SITTANAVASAL</title>
    </head>
    <body bgcolor="#FFD1DC">
        <h>SITTANAVASAL</h>
        <p> Sittanavasal was a major Jain center from the 1st century BCE to the 10th century CE.
Ancient Jain monks lived, meditated, and practiced ascetic life in these hills. Fresco paintings from the Pallava period (7th century CE)
Similar in technique to Ajanta paintings (but older in South India)
Natural colors made from minerals, plants, and lime plaster.</p>
    <img src="Sittanavasal.jpg" usemap="sittanavasal">
    </body>
</html>

```

aranmanai.html

```

<html>
    <head>
        <title>PUDHUKKOTTAI ARANMANAI</title>
    </head>
    <body bgcolor="#C1E1C1">
        <h2>PUDHUKKOTTAI ARANMANAI</h2>
        <p> The Pudukottai Palace, also known as the Pudukottai Aranmanai, is a historical palace located in the town of Pudukottai in Tamil Nadu, India. It was built during the reign of the Thondaiman kings, who ruled the princely state of Pudukottai from the 17th century until India's independence in 1947. The palace is an architectural marvel that showcases a blend of traditional Tamil and colonial styles. It served as the royal residence for the Thondaiman rulers and their families. The palace complex includes several buildings, courtyards, and gardens, reflecting the grandeur and opulence of the era. Today, the Pudukottai Palace stands as a significant cultural and historical landmark, attracting tourists and history enthusiasts interested in exploring the rich heritage of the region.</p>
 </p>
    <img src="aranmanai.jpg" usemap="aranmanai">
    </body>
</html>

```

thirumayam.html

```

<html>
    <head>
        <title>THIRUMAYAM</title>
    </head>
    <body bgcolor=" #A2D2FF">
        <h>THIRUMAYAM</h>
        <p>Thirumayam Fort Built in 1687 CE by Vijaya Raghunatha Sethupathi, the Raja of Ramnad. played a role in the Polygar Wars. Oomathurai, the brother of the famous chieftain Veerapandiya Kattabomman, was captured at this fort. The fort has shrines to guardian deities: Hanuman, Sakthi, Ganapathi, Karuppar, and a shrine to Bhairava.  </p>
    <img src="thirumayam fort.webp" usemap="thirumayam">
    </body>
</html>


```

clg.html

```

<html>
    <head>
        <title>RAJA'S COLLEGE</title>
    </head>
    <body bgcolor="#F2E4D5">
        <h2>RAJA'S COLLEGE</h2>
        <p>  H.H. The Rajah’s College an autonomous arts & science college in Pudukkottai, Tamil Nadu Established in 1857 Affiliated to Bharathidasan University. The college traces its roots to 1857, when it was founded as the Maharajah’s Free English Medium School.</p>
        <img src="clg.jpg" usemap="college">
    </body>
</html>


```


## OUTPUT

map

![alt text](<Screenshot 2025-11-17 003115.png>)


sittanavasal

![alt text](Sittanavasal.jpg)


aranmanai

![alt text](aranmanai.jpg)


thirumayam

[text](thirumayam.html)


clg

![alt text](clg.jpg)




## RESULT
The program for implementing image maps using HTML is executed successfully.
