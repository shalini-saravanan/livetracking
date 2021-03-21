<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a>
    <img src="assets/images/logo.png" alt="Logo" width="100" height="60">
  </a>

  <h3 align="center">REAL-TIME PACKAGE TRACKING PROTOTYPE</h3>

  <p align="center">
    Apogee 2021 - IOT Project Hackathon
    <br /><br />
    
    
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#software required">Software Required</a></li>
    <li><a href="#How it works ?">How it works ?</a></li>
    <li><a href="#Advantages">Advantages</a></li>
    <li><a href="#TEAM POIUYTRE - DETAILS">TEAM POIUYTRE - DETAILS</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<a><br />
<img src="https://github.com/shalini-saravanan/livetracking/blob/main/assets/images/Screenshot1.png" alt="Webpagescreenshot">
</a>

<a><br />
<img src="https://github.com/shalini-saravanan/livetracking/blob/main/assets/images/Screenshot2.png" alt="Webpagescreenshot">
</a>

<a><br />
<img src="https://github.com/shalini-saravanan/livetracking/blob/main/assets/images/Screenshot3.png" alt="Webpagescreenshot">
</a>
 
 
   Package location is tracked by means of carrier’s (Truck Driver or local Delivery person's) mobile GPS in a chained network as the Product ID  is embedded with driver’s GPS data in the database.

We should specify the packages and their unique ID's to the particular driver's GPS enabled Mobile App. The customers can track their packages in Real-Time by tracking the driver's location. Since the packages have unique ID's, When the package is shifted to the next driver, the new driver's location is tracked and the current driver's location is cut-off. Thus, the packages are tracked in a chained network in the Real-Time process.


## Software Required

*  A Mobile Application for the drivers ( Package carriers )
      * Flutter
      * Dart

*  A Web App for the customers ( Clients )
      * HTML
      * CSS
      
*  Backened Technologies
      * Firebase (Database)
      * Javascript
      * JQuery

<!-- GETTING STARTED -->
## How it works ?

Since the entire project is a working model (Prototype), the package ID's are already linked with the specific driver's accounts. All you need to do is login to the website with login credentials (email : sample@gmail.com and password : sample ) and click track button of your products.

The front end is completely built with HTML and CSS. For the database, we used 'FIRESTORE real time database'.
The front end part is connected to the database and it is accessed by json coding.

First, we have to login to our account.For that,  We use the already registered login credentials (here I use 
sample@gmail.com as the username and sample as the password).

Once the login details match with the already registered data in the database, we will be directed to our orders 
page directly.

In the order page, what are all the products ordered by the particular user will be displayed along with its 
details and a 'Track order' button.

When we click on that button, we will be directed to another page where the google map live location of that 
particular product is shown.

As a part of the backend process, we will be installing an app in the carrier's mobile phone in order to track the location of products.

The app is made using flutter and dart languages. We have choosen this because Flutter is Google's mobile app SDK, complete with a framework, 
widgets, and tools, that gives us an easy way to build and deploy visually attractive,fast mobile apps on both Android and iOS platforms.

The app collects the latitude and longitude data with help of google maps and GPS and sends that data to firebase. Then the data is retrieved 
from the firebase into the web application which is then displayed to the client.

So, the users can track their product locations in a much simpler way. 

## Advantages

* <b>Low Cost</b> - 
    Since there is no requirement for any hardware products, our application is highly cost effictive. Also we will be using inbuilt GPS for tracking purposes, which further reduces the cost of installation of any external GPS modules.  
    
* <b>High Latency</b> - 
    Since Real-Time database is used, location is fast & accurate.

* <b>Scalability</b> - 
    Idea can further be extended in all means - Roadways, Railways, Waterways & Airways as well.

* <b>Uniqueness</b> - 
    Mobile GPS is used for tracking instead of using separate GPS.
    

<!-- TEAM -->
## TEAM POIUYTRE - DETAILS

 * Vaishaal Krishna VS - [Linkedin](https://www.linkedin.com/in/vaishaal-krishna-vs-21222b117/)
 
 * Vijayvenkatajalapathi G - [Linkedin](https://www.linkedin.com/in/vijayvenkatajalapathi/)
 
 * Shalini S - [Linkedin](https://www.linkedin.com/in/shalini-saravanan/)
 




<!-- MARKDOWN LINKS & IMAGES -->

[product-screenshot1]: assets/images/screenshot1.png
[product-screenshot2]: assets/images/screenshot2.png
[product-screenshot3]: assets/images/screenshot3.png

