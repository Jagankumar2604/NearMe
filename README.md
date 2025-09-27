# Ex04 Places Around Me
## Date:27.09.2025

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

<body>
    <center><h1>Arni-Jagan kumar V(25012671)</h1></center>
</body>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="vembuli amman kovil" title="vembuli amman kovil" href="temple.html" coords="193,468,397,551" shape="rect">
    <area target="" alt="paary sweet" title="paary sweet" href="bakery.html" coords="424,676,728,680,671,792,481,734" shape="poly">
    <area target="" alt="old bus stand" title="old bus stand" href="bus stand.html" coords="664,414,125" shape="circle">
    <area target="" alt="rajeswari theatre" title="rajeswari theatre" href="theatre.html" coords="1013,887,100" shape="circle">
    <area target="" alt="poorvika mobiles" title="poorvika mobiles" href="shop.html" coords="716,551,978,649" shape="rect">
</map>

shop.html

<html>
    <head>
        <title>poorvika mobiles</title> 
    </head>
    <body bgcolor="lightgreen" text="black">
        <center>
            <h1>Arni - Poorvika Mobiles</h1>
        </center>
        <p>Poorvika Mobiles is one of India’s leading mobile retail chains,
         offering a wide range of mobile phones, tablets, laptops, and accessories.
        Known for competitive prices and attractive deals,
        Poorvika is a go-to destination for budget-conscious
         consumers looking for the latest gadgets
        </p>
        <h2>Price List:</h2>
        <ul>
            <li>Vivo t4x-17000</li>
            <li>Samsung A36-36000</li>
            <li>iphone 16 pro-65000</li>
            <li>iqneo10-18000</li>
            <li>poco m6-18000</li>
        </ul><br><br>
        <h3>Online shopping</h3>
        <ul>
            <li>Cash on delivery available</li>
            <li>Contact:63742*****</li>
            <li>mail:ja***12@gmail.com</li>
        </ul>
    </body>
    
</html>

bakery.html

<html>
    <head>
        <title>Bakery</title>
    </head>
    <body bgcolor="yellow" text="black">
        <center>
            <h1>Paary sweets and bakery</h1>
        </center>
        <hr>
        <p>Here’s info I found about Paary (or Paari) Sweets & Bakery in Arani, Tamil Nadu. If this is the same as “Paaru Sweet Shop” you meant, it seems likely. If not, I can try to dig up the exact one you had in mind.



Basic Details

Name: Paary Sweets & Bakery (also shown as Paari Sweets & Bakery) 

Address: 215-A, Gandhi Road, Market area, Near Arni Market, Arani H.O., Tiruvannamalai district, Tamil Nadu, 632301. 

Contact: +91 94433 08939 

Opening Hours: From around 5:00 AM to about 9:30 PM daily. 





What They Offer / What They're Known For

Wide variety of traditional sweets, bakery items, snacks, pastries, cakes, etc. 

Freshness is often praised: many reviews say sweets and snacks are fresh, good quality. 

Good atmosphere, fairly clean premises. 

Also cakes for special occasions (birthdays etc.). 





Pros / What Locals Like

Strong positive reviews for taste, variety. 

Many say prices are reasonable given what’s offered. 

Good service generally. 




Cons / Complaints

Some people feel the pricing is a bit on higher side for certain items. 

At times, popular snack items (like pakoda etc.) finish early in the day. 

Crowded at times; parking / space to move perhaps limited. 

One complaint: cake ordered was called one flavour but didn’t match in appearance or taste</p><br><br>
    <center>
        <h2>for contact: 87654*****</h2>
        <h2>Email address : paary@gmail.com</h2>
    </center>
    </body>
</html>

bus stand.html

<html>
    <head>
        <title>bus stand</title>
    </head>
    <body bgcolor="green" text="black">
        <center><h1>Bus Stand</h1></center>
        <hr>
        <p>Here’s what I found out about Arani Old Bus Stand (Arni, Tamil Nadu):




theatre.html

<html>
    <head>
        <title>Rajeswari Theatre</title>
    </head>
    <body bgcolor="red" text="white">
        <center>
            <h1>Rajeswari Theatre</h1>
        </center>
        <hr>
        <p>Here’s what I found out about Rajeshwari / Rajeswari / Shri Rajeswari Theatre / Cinema in Arani (Arni), Tamil Nadu:




Basic Details

Name: Rajeshwari Theatre A/C DTS / Shri Rajeswari Cinemas A/C 4K Dolby Atmos in Arani. 

Address: State Highway 4, Dr. Ambedkar Nagar, Arani, Tamil Nadu 632301. 

Other contact info listed: Phone number +91-94821 49419. 





Facilities & Features

It is an AC (air-conditioned) theatre. 

Sound: It is advertised as having DTS sound and also 4K video projection. 

It is listed on BookMyShow as Shri Rajeswari Cinemas A/C 4K Dolby Atmos. So Dolby Atmos is claimed. 

Seating: There are special/balcony seats, possibly family-section and normal. Some reviews mention “balcony price range from ₹150-200” approx. 




User Feedback — What People Like & What They Complain About

Positives:

Many reviews say it's “good theatre around Arni area” with clean ambience. 

The AC is appreciated, especially for hot weather. 

For Tamil movies, the sound & viewing experience is generally considered acceptable to good. 


Negatives / Issues:

Sound quality: Some reviews mention issues especially when background music is too loud, or dialogues aren’t as clear. 

Screen image: A few users say the screen isn’t very clear, e.g., “screen is shot” (i.e. maybe some visual defects) in some shows. 

Booking problems: Difficulty in modifying booking show date is noted by some users. 

Hygiene issues: Restrooms / toilets sometimes not clean; smell complaints. 




Pricing & Other Info

Balcony seats cost around ₹150-200 in some cases. 

Snack pricing: Popcorn etc. are considered fair by many. 

It’s one of the more reviewed / prominent theatres in Arani. 




If you like, I can also pull up the current shows, ticket prices, or seating map for Rajeswari Theatre. Do you want me to fetch that?</p><br><br>
    <center>
        <h2>for online booking</h2>
        <h3> contact : 87654*****</h3>
    </center>
    </body>

</html>

temple.html

<html>
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="purple">
        <center>
            <h1>Sri vembuliamman temple</h1>
        </center>
        <hr>
        <p>The Vembuli Amman Kovil is a Hindu temple located in the town of Arani, within the Tiruvannamalai district of Tamil Nadu. The temple is renowned for its annual grand festival, which attracts a large gathering of devotees. The festival is typically held in July, coinciding with the Aadi month. 
Key Aspects: 
Location: Arani town, Tiruvannamalai district, Tamil Nadu.
Deity: Goddess Vembuli Amman.
Annual Festival: A grand annual festival, also known as the Aadi festival, takes place in July.
Devotee Turnout: The festival draws a large crowd, with nearly one lakh people attending the temple on this occasion.
Recent Events: The temple recently celebrated its Maha Kumbabhishegam (consecration ceremony) and its 52nd Aadi Velli festival in July 2025.</p><br><br>
    <center>
        <h2>Address : East ground near ss school arni-632301</h2>
    </center>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot 2025-09-26 214113.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
