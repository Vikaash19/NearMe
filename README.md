# Ex04 Places Around Me
## Date: 22/03/2024

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
map.html
<html>
    <head>
        <title>Chennai</title>
    </head>
<body align="center"> 
        <h1><b>Chennai</b>
        </h1>
        <h3 align="center">
        <b>Vikaash K S(212223240179)</b>
        </h3>
    <img src="map exp 4.jpeg" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="Parvathy Hospital " title="Parvathy Hospital " href="hospital.html" coords="586,73,728,115" shape="rect">
        <area target="" alt="NSN Memorial School" title="NSN Memorial School" href="nsnschool.html" coords="718,385,33" shape="circle">
        <area target="" alt="Madras Institute of Technology" title="Madras Institute of Technology" href="mitcollege.html" coords="814,55,51" shape="circle">
        <area target="" alt="Madras Christian College" title="Madras Christian College" href="mccollege.html" coords="409,567,38" shape="circle">
        <area target="" alt="Olive Public School" title="Olive Public School" href="opschool.html" coords="1007,364,39" shape="circle">
    </map>
</body>
</html>

hospital.html
<html>
    <head>
        <title>Parvathy Hospital </title>
    </head>
    <body bgcolor="green">
        <h1 align="center"> 
        <font color="black"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="Yellow"><b>Parvathy Hospital</b></font>
        </h3>
        <hr size="4" color="red">
    <p align="justify">
    <font face="Georgia" size="4">
        Parvathy Hospital is accredited by the National Accreditation Board for Hospitals & Healthcare (NABH). 
        This accreditation indicates the facility passed a rigorous series of recognized standards and 
        demonstrates the commitment of our surgeons and staff to provide the highest possible level of safe 
        and effective treatment.
    </font>
    </p>
    </body>
</html>

mccollege.html
<html>
    <head>
        <title>Madras Christian College</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center"> 
        <font color="yellow"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="Orange"><b>Madras Christian College</b></font>
        </h3>
        <hr size="4" color="White">
    <p align="justify">
    <font face="Georgia" size="4">
        Madras Christian College (MCC) is a liberal arts and sciences college in Chennai, India.
        Founded in 1837, MCC is one of Asia's oldest extant colleges. The college is affiliated 
        to the University of Madras but functions as an autonomous institution 
        from its main campus in Tambaram, Chennai.
    </font>
    </p>
    </body>
</html>

mitcollege.html
<html>
    <head>
        <title>Madras Institute of Technology</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center"> 
        <font color="purple"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="red"><b>Madras Institute of Technology</b></font>
        </h3>
        <hr size="4" color="green">
    <p align="justify">
    <font face="Georgia" size="4">
        Madras Institute of Technology (MIT) is an engineering institute located in Chromepet, Chennai, India. 
        It is one of the four autonomous constituent colleges of Anna University. 
        It was established in 1949 by Chinnaswami Rajam as the first self-financing engineering institute 
        in the country and later merged with Anna University. The institute was among 
        the first educational institutions in India to offer new areas of specialization,
         such as aeronautical engineering, automobile engineering, electronics engineering and instrumentation technology. 
        Madras Institute of Technology (MIT) was the first self-financing institute opened in India.
    </font>
    </p>
    </body>
</html>

nsnschool.html
<html>
    <head>
        <title>NSN Memorial School</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center"> 
        <font color="green"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="violet"><b>NSN Memorial School</b></font>
        </h3>
        <hr size="4" color="white">
    <p align="justify">
    <font face="Georgia" size="4">
        It is a co-educational school which aims to provide a full, liberal and comprehensive education. 
        The object is to turn out young men and women with a keen sense of discipline, responsibility, 
        initiative, self-reliance, integrity and loyalty.
    </font>
    </p>
    </body>
</html>

opschool.html
<html>
    <head>
        <title>Olive Public School</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center"> 
        <font color="black"><b>Chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="orange"><b>Olive Public School</b></font>
        </h3>
        <hr size="4" color="yellow">
    <p align="justify">
    <font face="Georgia" size="4">
        We are living in an accelerating world of change in every area of life.We in 
        Olive Public School believe that such changes call for new ways of learning and thinking 
        if we are to thrive in the world during the eras to come. The directions our society 
        is taking and the future of our planet demands such new minds able to explore 
        creative alternatives for problems that cannot be anticipated.
    </font>
    </p>
    </body>
</html>
```
## OUTPUT
![alt text](<exp4 map.png>)
![alt text](<exp4 hp.png>)
![alt text](<exp4 mcc.png>)
![alt text](<exp4 mit.png>)
![alt text](<exp4 nsn.png>)
![alt text](<exp4 olp.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.