#  Project #4: <u>HaroldCleworth.com</u>
### <u>Overview</u>

Homepage, is your NEW <b>HOMEPAGE</b>! 

Begin your daily routine with quick access to weather, google search, a random giphy display and jokes. This functionality uses requests to several APIs.

Members can log in via Facebook or they may enroll with their own email and password.


---

### <u>Live Link</u></br>

##<http://tba.com/></br></br>



---
### <u>Build Approach</u>


We met and conceptually decided upon building a <b>‘homepage’</b> because it would allow us the most opportunities to work with various APIs. We spent an afternoon producing wire frames and building out our basic architecture.

We divided up large tasks to begin building the major features of our project. We assisted, shifted, and modified roles as we encountered problems and leveraging strengths.

Begrudgingly, we had to cease work on the embedded Facebook and Twitter feeds.

---

### <u>Homepage Build Dependencies</u>

	Bcrypt-nodejs: 0.0.3
    Body-parser: 1.14.1
    Cookie-parser: 1.4.0
    Express: 4.13.3
    Jsonwebtoken: 5.4.0
    Mongoose: 4.1.9
    Morgan: 1.6.1
    Passport: 0.3.0
    Passport-facebook: 2.0.0
    Passport-local: 1.0.0

---

### <u>Homepage Metamorphosis</u>

Our original homepage layout included an embedded feed for a member’s own Facebook and Twitter account. However, it proved not to be viable for either embedded option. We could get our “own homepage app page” to display, but otherwise individual member feeds are locked down.

We also tried to incorporate geolocation to populate the weather display instead of manually asking for the member’s zipcode. Unfortunately, the weather app would not function correctly with exact member latitude and longitude coordinates.


---

### <u>User Stories</u></br>
![Jay Leno Pic](http://i2.cdn.turner.com/cnn/2010/images/11/08/t1larg.leno.turbine.cnn.jpg)


**User #1:** Jay Leno</br>
Celebrity and car enthusiast, Jay Leno, is curious about what new projects Harold has been working on lately.

Jay not only collects actual vintage cars but artwork of all kinds and varities.

- Jay is able to navigate to the new site for Harold Cleworth.
- Jay is able to access the "new" page.
- Jay is able to access the contact us page and obtian Harold's most current contact information (phone and email).
- Jay is able to add himself to Harold's mailing list.


---
![Mark & Betty Pic](http://www.foryourmarriage.org/wp-content/themes/marriage/scripts/timthumb.php?src=/wp-content/uploads/img_matureCouple.jpg&h=245&w=477&zc=1)
**User #2:** Mark & Betty Singleton</br>
Mark & Betty have been married for nearly 40 years. Betty would like to surprise Mark with a picture of a 1962 Thunderbird Convertible for their 40th wedding anniversary. Mark gave up the car as they had their second child.

- Betty is able to locate the website.
- Betty is able to read about the artists on the "about" page.
- Betty is able to navigate to the index page => the American Classics page => and locate the 1962 Thunderbird.
- Betty is able to read about the details of the painting.
- Betty is able to add the product to the shopping cart.
- Betty is able to put her shipping information in the site.
- Betty is able to use her credit card and purchase the image of the 1962 Thunderbird.
- Betty feels confident and secure about her online transaction.


---

![Harold Cleworth Pic](http://worldnewsvine.com/wp-content/uploads/2015/03/Artist-Harold-Cleworth-of-Venice-CA.jpg)</br>
**User #3:** Harold Cleworth</br>
As the owner of the site, Harold has administrative access to the site. 

- Harold is able to access the hidden admin login area.
- Harold can add a new item(image, title, description).
- Harold can update/edit an existing item.
- Harold can delete an item.
- Harold can pull a list of current orders, with customer info.
- Harold can access a list of email subscribers.

---
### <u>Wire Frames</u></br>

**Wire Frame 1.1** </br>
![Wire Frame 1.1](http://www.imageurlhost.com/images/lg2r0b8cqdzx3o464ml3_Wire-11.jpg)</br></br>

**Wire Frame 1.2** </br>
![Wire Frame 1.2](http://www.imageurlhost.com/images/r946m2m17zlzs2peg_Wire-12.jpg)</br></br>

**Wire Frame 1.3**</br>
![Wire Frame 1.3](http://www.imageurlhost.com/images/xmpvyyzdmgwwb8wk4rny_Wire-13.jpg)</br></br>

**Wire Frame 1.4**</br>
![Wire Frame 1.4](http://www.imageurlhost.com/images/piatfbe9jkral83mqz_Wire-14.jpg)</br></br>

**Wire Frame 1.5** </br>
![Wire Frame 1.5](http://www.imageurlhost.com/images/n43x7qxne7e1ktc8jtc4_Wire-15.jpg)</br></br>

**Wire Frame 1.6**</br>
![Wire Frame 1.6](http://www.imageurlhost.com/images/8kqw3mnbs8gyh181ajrs_Wire-16.jpg)</br></br>

Quick link to site:</br>
<http://koncieve.com/></br>

---
### <u>Future Phases</u></br>

For future phases, we would like to incorporate the following possible additions:

**Facebook Feed** (Member's)</br>
**Twitter Feed** (Member's</br>
**Sound Cloud**</br>
**Google Maps**</br>
**Geolocation for Weather App**(may use another API)</br>
**Theme(s)**</br>


---
### <u>Resource Links</u>

<https://developer.chrome.com/extensions/devguide></br>
<https://dev.twitter.com/overview/documentation></br>
<https://dev.twitter.com/web/overview></br>
<https://dev.twitter.com/oauth></br>
<https://developers.facebook.com/docs/plugins/page-plugin></br>
<http://openweathermap.org/appid></br>
<https://api.giphy.com/></br>

---

 
##Special thanks to our instructors:

 
 * **John McDonald**</br>
 * **Eric Hodonsky**</br>
 * **Blaise Thomas**</br>

Additional thanks to:

* All <b>GA WDI LA 18</b> class members!


Lastly,

Thank you to **Don Donsky**, **Brad Bakalar** & **Moki**, and **Wonder Woman/Marvel Commics** for our basis for user stories.

 