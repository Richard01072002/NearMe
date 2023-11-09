# Ex04 Places Around Me
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
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>My Home Town</title>
  </head>
  <body>
    <h1 align="center">
      <font color="black">
        <b>MY HOME TOWN</b>
      </font>
    </h1>
    <h3 align="center">
      <font color="black">
        <b>RICHARDSON A (23000803)</b>
      </font>
    </h3>
    <center>
      <img src="MY_MAP.png" usemap="#image-map" height="100%" width="100%" />

<map name="image-map">
    <area target="" alt="THE BIG MARKET" title="THE BIG MARKET" href="/Users/apple/Desktop/web/EXP4/THE_BIG_MARKET.html" coords="904,566,963,637" shape="rect">
    <area target="" alt="DINE SPOT" title="DINE SPOT" href="/Users/apple/Desktop/web/EXP4/pizzahut.html" coords="1315,664,1266,596" shape="rect">
    <area target="" alt="KFC" title="KFC" href="/Users/apple/Desktop/web/EXP4/kfc.html" coords="1720,685,1673,608" shape="rect">
    <area target="" alt="BUS STOP" title="BUS STOP" href="/Users/apple/Desktop/web/EXP4/buss_stop.html" coords="1448,630,1503,685" shape="rect">
    <area target="" alt="SWEET HOME" title="SWEET HOME" href="/Users/apple/Desktop/web/EXP4/pizzahut.html" coords="1494,960,1411,923" shape="rect">
    <area target="" alt="PIZZA HUT" title="PIZZA HUT" href="/Users/apple/Desktop/web/EXP4/pizzahut.html" coords="511,568,573,630" shape="rect">
    <area target="" alt="" title="" href="" coords="" shape="0">
</map>
    </center>
  </body>
</html>


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>THE BIG MARKET</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>YELAHANKA BANGALORE</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>THE BIG MARKET</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
One of the best places in Bangalore for shopping .
We can get most of the things what is required. It is near main road too.
We can get all kind of transport services too from there.\
Best service from servers in the market. 153/2, Bagalur Main Rd, Vinayak Nagar, Kattigenahalli, Bengaluru, Karnataka 560063. </font>
    </p>
  </body>
</html>

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KFC</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>YELAHANKA BANGALORE</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>KFC</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        KFC Corporation, doing business as Kentucky Fried Chicken, is an American fast food restaurant chain headquartered in Louisville, Kentucky, that specializes in fried chicken. It is the world's second-largest restaurant chain after McDonald's, with 22,621 locations globally in 150 countries as of December </font>
    </p>
  </body>
</html>


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>BUS STOP</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>YELAHANKA BANGALORE</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>BUS STOP</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        The movie's producer Bellamkonda Suresh announced that the film will be released across the state on 11 November 2012. But earlier on 10 November, he told the media that a few multiplexes will begin screening the film from today itself and the bookings for the evenings shows of Bus Stop are expected to open shortly.    </p>
  </body>
</html>

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>PIZZA HUT</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>YELAHANKA BANGALORE</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>PIZZA HUT</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Pizza Hut was launched on May 31, 1958,
        by two brothers, Dan and Frank Carney, both Wichita State students, as a single location in Wichita, Kansas.
        Six months later they opened a second outlet, and within a year they were operating six locations. </font>
    </p>
  </body>
</html>


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>SWEET HOME</title>
  </head>
  <body bgcolor="lime">
    <h1 align="center">
      <font color="red"><b>YELAHANKA BANGALORE</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>SWEET HOME</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
One of the best places in Bangalore for shopping .
We can get most of the things what is required. It is near main road too.
We can get all kind of transport services too from there.\
Best service from servers in the market. 153/2, Bagalur Main Rd, Vinayak Nagar, Kattigenahalli, Bengaluru, Karnataka 560063. </font>
    </p>
  </body>
</html>


```


## OUTPUT

![image](https://github.com/Richard01072002/NearMe/assets/141472248/fa0d0e69-bdc0-4ebf-8f33-b9e044b7b2de)

![image](https://github.com/Richard01072002/NearMe/assets/141472248/e376c156-f9b3-4697-bd40-d569ebf18de6)

![image](https://github.com/Richard01072002/NearMe/assets/141472248/9de43ec9-f172-4423-a45e-7726a5eee280)

![image](https://github.com/Richard01072002/NearMe/assets/141472248/ea94c57c-5b45-47eb-a46d-c032aac51d5c)

![image](https://github.com/Richard01072002/NearMe/assets/141472248/89d9cd42-2922-4b98-9bec-9b069206047a)


## HTML VALIDATOR


## RESULT
The program for implementing image maps using HTML is executed successfully.
