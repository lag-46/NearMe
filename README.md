# Ex04 Places Around Me
## Date: 13-11-2025

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
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Pandeeswaran N (212224230191)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" width="1601" height="768">
<map name="MyCity">
<area shape="rect" coords="1170,530,1230,570" href="taj.html" title="Taj tyres">
<area shape="circle" coords="530,270,40" href="park.html" title="Children's park">
<area shape="circle" coords="1210,400,45" href="museum.html" title="Government museum">
<area shape="circle" coords="720,350,35" href="boys.html" title="Black boys thapset">
<area shape="rect" coords="540,410,660,450" href="ind.html" title="Indira nagar">
</map>
</center>
</body>
</html>
```

boys.html

```
<html>
<head>
<title>Black boys</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>KRISHNAGIRI</b></font>
</h1>
<h2 align="center">
<font color="darkblue"><b>Black boys thapset</b></font>
</h2>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
"Krishnagiri Black Boys Thapset" appears to be a name or reference related to a specific entity or group in Krishnagiri, 
Tamil Nadu, likely associated with drumming or dance performances.The name suggests they are based in or associated with Krishnagiri.
"Black Boys" seems to be the group's name, and "Thapset" might refer to their specific service, style, or perhaps a location/venue related to their business. 
</p>
</body>
</html>
```

ind.html

```
<html>
<head>
<title>indira nagar</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>KRISHNAGIRI</b></font>
</h1>
<h2 align="center">
<font color="darkblue"><b>Indira Nagar</b></font>
</h2>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
Indira Nagar is a small Village/hamlet in Krishnagiri Block in Krishnagiri District of Tamil Nadu State, India. 
It comes under Peddanapalli Panchayath. It is located 2 KM towards west from District head quarters Krishnagiri. 
268 KM from State capital Chennai.Indira Nagar Pin code is 635001 and postal head office is Krishnagiri .
Indira Nagar is surrounded by Bargur Block towards East , Veppanapalli Block towards North ,
Kaveripattinam Block towards South , Karimangalam Block towards South .Tirupathur , 
Dharmapuri , Vaniyambadi , Robertson Pet are the near by Cities to Indira Nagar.
</p>
</body>
</html>
```

museum.html

```
<html>
<head>
<title>Museum</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>KRISHNAGIRI</b></font>
</h1>
<h2 align="center">
<font color="darkblue"><b>Government museum</b></font>
</h2>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
Krishnagiri Museum is located near Apsara Theatre on Gandhi Road. It was opened as 12th District Museum in the year 1993. 
This Museum exhibits objects of Art and Archaeology, Anthropology, Geology, Botany and Zoology disciplines.
Most important exhibits of this Museum are the Hero Stones, which were collected from different parts of this district.
Visitors can have the Knowledge of history of Krishnagiri district from as early as Paleolithic period through Neolithic and 
Megalithic to modern period by the exhibits displayed here. Paleolithic tools collected from Varattanappalli and Kappalvadi, 
Neolithic tools collected from Katheri, Gangaleri, Thogarapplli, Paiyur, Kokkikalpodu, Modhur, Gollahalli and Vellolai are displayed.
</p>
</body>
</html>
```

park.html

```
<html>
<head>
<title>Park</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>KRISHNAGIRI</b></font>
</h1>
<h2 align="center">
<font color="darkblue"><b>Children's park</b></font>
</h2>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
This park is situated within the district stadium complex and offers various sports and recreational facilities. 
District Stadium Complex, Rayakottai Rd, Wahab Nagar, Krishnagiri, Tamil Nadu 635002.4:00 AM to 7:00 PM, daily.
The park includes a skateboard area, a swimming pool, courts for badminton and tennis, and a walking track. 
This is a smaller park that some reviews indicate may be in need of maintenance. 

</p>
</body>
</html>
```

taj.html

```
<html>
<head>
<title>Taj</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>KRISHNAGIRI</b></font>
</h1>
<h2 align="center">
<font color="darkblue"><b>Taj tyres</b></font>
</h2>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
Taj Tyres is a tyre dealership located in the Krishnagiri district of Tamil Nadu.
They deal in both new and second-hand tyres. Address (Thiruvalluvar Nagar): Thiruvalluvar Nagar, 
Krishnagiri, Tamil Nadu, 635001. Another listed address is No 115 Madras Road, New Pet, Krishnagiri Courts (Opposite Bus Depot).
The specific brands available may vary, but they are mentioned in the context of dealers who might stock Apollo and MRF tyres. 
Customers are advised to contact the shop directly to confirm the availability of a particular brand.
</p>
</body>
</html>
```


## OUTPUT

![alt text](mapp/mapapp/static/map.png)

![alt text](<Screenshot 2025-11-10 125252.png>)

![alt text](<Screenshot 2025-11-10 125311.png>)

![alt text](<Screenshot 2025-11-10 125331.png>)

![alt text](<Screenshot 2025-11-10 125353.png>)

![alt text](<Screenshot 2025-11-10 125409.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
