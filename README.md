<table>
  <tr>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
  </tr>
  <tr>
        <td align="center" colspan=10><h3>Track Golf Carts on GCU Campus</h3></td>
  </tr>
  <tr>
    <td colspan=3><img width="250px" height="250px" src="https://user-images.githubusercontent.com/46502725/163734875-f011ef1d-7571-4269-8a33-b21253983285.png" alt="SofanaGPS LOGO"></td>
    <td colspan=4 align="center"><h1>SofanaGPS Project Portfolio</h1></td>
    <td colspan=3><img width="250px" height="250px" src="https://user-images.githubusercontent.com/46502725/163734875-f011ef1d-7571-4269-8a33-b21253983285.png" alt="SofanaGPS LOGO"></td>
  </tr>
  <tr>
    <td colspan=5 align="center"><h3>Safa Bayraktar</h3></td>
    <td colspan=5 align="center"><h3>Ana Sanchez Sanchez</h3></td>
  </tr>
    <tr>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
  </tr>
</table>

## Table of Contents
- [Introduction](https://github.com/goktan507/SofanaGPS/blob/main/README.md#introduction)
- [Requirements](https://github.com/goktan507/SofanaGPS/blob/main/README.md#requirements)
  - [Functional Requirements](https://github.com/goktan507/SofanaGPS/blob/main/README.md#functional-requirements)
  - [Non-Functional Requirements \[NFRs\]](https://github.com/goktan507/SofanaGPS/blob/main/README.md#non-functional-requirements-nfrs)
- [Technologies & Tools](https://github.com/goktan507/SofanaGPS/blob/main/README.md#technologies--tools)
- [Hardware Components](https://github.com/goktan507/SofanaGPS/blob/main/README.md#hardware-components)
- [Cloud Deployment](https://github.com/goktan507/SofanaGPS/blob/main/README.md#cloud-deployment)
  - [Frontend \[React App\] -> Heroku](https://github.com/goktan507/SofanaGPS/blob/main/README.md#frontend-react-app---heroku)
  - [Backend \[API\] -> Azure](https://github.com/goktan507/SofanaGPS/blob/main/README.md#backend-api---azure)
  - [Cross-Origin Resource Sharing \[CORS\]](https://github.com/goktan507/SofanaGPS/blob/main/README.md#cross-origin-resource-sharing-cors)
  - [Monitoring](https://github.com/goktan507/SofanaGPS/blob/main/README.md#monitoring)
- [Technical Approach](https://github.com/goktan507/SofanaGPS/blob/main/README.md#technical-approach)
- [Risks & Challanges](https://github.com/goktan507/SofanaGPS/blob/main/README.md#risks--challanges)
- [Contacts](https://github.com/goktan507/SofanaGPS/blob/main/README.md#contacts)


#### Introduction
 Grand Canyon University is in the heart of Phoenix Arizona, the hottest city in the country. Getting from point A to point B on GCU’s ever-growing developing campus can be a challenge. Currently, GCU operates golf carts to aid students in traversing the campus. Although these golf carts are tremendously helpful, there have been reports from students that they are unable to locate a golf cart promptly when needed. Team Sofana’s goal is to utilize technology and create software that aids students in locating a golf cart so they can arrive at their destination on time.  

> SofanaGPS Project Functional Demonstration
[![SofanaGPS Project Functional Demonstration](https://user-images.githubusercontent.com/46502725/163736787-685457fb-4dfe-4a56-917d-7cebd68269fa.png)
](https://www.youtube.com/watch?v=i2qrb46bWTI)



---
## Requirements
      
#### Functional Requirements
- React App \[[Frontend](https://sofanagps.herokuapp.com)]
  - Google's Map Implementation
    - Initialize Map
    - Update Map   
    - Display Golf Carts
- SofanaGPS-API \[[Backend](https://sofanagpsapi.azurewebsites.net/api/locations)]
  - Communication between Hardware - Software
- Arduino & Components \[Hardware]
  - Network Connectivity
    - Connect/Reconnect to LOPES Wi-Fi
  - Portability 
    - Ease of attaching to Golf Carts
    - Compact in size 


#### Non-Functional Requirements \[NFRs]
- Availability (Hosted)
- Storage (Database)
- Responsiveness
- Security (Authentication)
       
---
## Technologies & Tools
- React \[v17.0.2]
  - React Google Maps API \[v2.7.0]
  - Axios \[0.24.0]
- ASP .NET Core 3.1
  - MongoDB.Driver \[v2.15.0]
  - Newtonsoft.JSON \[v13.0.1]
  - NLog \[v4.7.15]
  - xUnit \[v2.4.1]
  - Moq \[v4.17.2]
- HTLM5
- CSS3
- C/C++
- JavaScript
-  MongoDB Atlas
- Arduino IDE \[v1.8.16]
  - TinyGPS++ \[v2.1]
  - ArduinoJson Library \[v5.13.3]
  - ESP8266Wifi \[3.0.2]
  - ESP8266HTTPClient & WifiClientSecureBear SSL
  - base64 \[v1.2.1]
- Bootstrap \[v5.1.3]
- Hosting
  - Azure App Service Hosting
  - Heroku Cloud Application Platform
- Other Tools
  - Postman \[v9.15.11]
  - Fritzing \[v0.9.9]
  - Swagger \[2.0]
  - UpTimeRobot Monitoring
  - LucidChart
  - Visual Studio Community 2019
  - VSCode IDE \[v1.66.1]

<table>
  <tr align="center">
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163749686-a5e71c2d-cbf6-4fda-848e-66aa401ac7ce.png"/>
    </td>
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163749726-8671e0c9-8f23-498a-ae26-57d025012d5f.png"/>
    </td>
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163749782-af9d2c43-428a-4eca-8c25-91f38cd0cb6c.png"/>
   </td>
  </tr><tr></tr>
  <tr align="center">
    <td align="center">
      <img width="200"  src="https://user-images.githubusercontent.com/46502725/163749847-f82ca1c2-e3fd-4eeb-aceb-d58dbf6589ae.png"/>
    </td>
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163749902-599ec4f6-6ff0-4db5-b8ac-cbb2f401f0d9.png"/>
    </td>
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163750038-d6cc7702-0dc3-4229-b589-dbe214418361.png"/>
    </td>
  </tr>
  <tr></tr><tr>
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163749821-fe70a10c-4ad6-43eb-a80b-7e213cab88d2.png"/>
      </td>
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163750598-3e74156e-dcc4-4f50-a103-a25249946e10.png"/>
    </td>
    <td>
      <img width="300" src="https://user-images.githubusercontent.com/46502725/163754996-d9329b6c-6f1e-47e8-89a8-74c7259d7d3e.png"/>
    </td>
  </tr>
</table>



---
## Hardware Components
<table>
  <tr align="center">
    <td>
      ELEGRO UNO R3
      <a href="https://www.amazon.com/ELEGOO-Board-ATmega328P-ATMEGA16U2-Compliant/dp/B01EWOE0UU/ref=sr_1_3?crid=1CJX7G5AY2430&keywords=elegoo+uno+r3&qid=1650299807&s=industrial&sprefix=elegoo+uno+r3%2Cindustrial%2C118&sr=1-3"><img width="250" src="https://user-images.githubusercontent.com/46502725/163751330-4599e1dc-f62d-402c-a9cd-d7a364b4ce48.png"/></a>
    </td>
    <td>
      NEO - 6M GPS Module
      <a href="https://www.amazon.com/Microcontroller-Compatible-Sensitivity-Navigation-Positioning/dp/B07P8YMVNT?th=1"><img width="300" src="https://user-images.githubusercontent.com/46502725/163751425-2d76818a-49ef-42c3-aa94-6e8b50353ddc.png"/></a>
    </td>
    <td>
      ESP8266 WIFI Module
      <a href="https://www.amazon.com/HiLetgo-Internet-Development-Wireless-Micropython/dp/B081CSJV2V/ref=sr_1_1_sspa?gclid=Cj0KCQjwmPSSBhCNARIsAH3cYgYx3fEWciGZxthskgqY5JzyWAUpI1U3WiM6KPYfYrmq4E_Db7HhWyUaAuhgEALw_wcB&hvadid=173542103964&hvdev=c&hvlocphy=9029979&hvnetw=g&hvqmt=e&hvrand=7631398929246534702&hvtargid=kwd-85230109726&keywords=esp8266%2Bwifi%2Bmodule&qid=1650299768&sr=8-1-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFPUFNHTjRJWkZPWDMmZW5jcnlwdGVkSWQ9QTAzMjcxNTMzMzE4OVJSVjQzTUVBJmVuY3J5cHRlZEFkSWQ9QTA1NjI2OTMxTlZMQjVKN0lROUMmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl&th=1"><img width="250" src="https://user-images.githubusercontent.com/46502725/163751582-26c44c0e-19ff-4a13-8e12-0707ad2c43b6.png"/></a>
    </td>
  </tr>

</table>

> The GPS tracking system is implemented by creating an embedded system that can be mounted on a GCU golf cart. SofanaGPS developed an embedded system by integrating a low-cost microcontroller board such as but not limited to an Arduino. The embedded system also consists of other components including a Wi-Fi module that is compatible with the chosen microcontroller board. Wi-Fi module that has been implemented is the ESP8266. The ESP8266 allows for the microcontroller board to connect to a network such as the GCU “Lopes” Wi-Fi that is accessible throughout the campus. The Wi-Fi board would ensure network connectivity for the embedded system and would enable Team Sofana to track the GCU golf carts. Another component of the GPS tracking system is a GPS module that is responsible for retrieving location through an antenna that will calculate and retrieve gps longitude and latitude coordinates from GPS satellites.GPS module that has been implemented is the ublox NEO-6M Module that is compatible with our chosen Arduino system. 

<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/46502725/163944571-526572ef-12e6-4a3a-b03a-f408d9118cba.png"/>
    </td>
    <td>
      <img width="350" src="https://user-images.githubusercontent.com/46502725/163945396-89c4e1bd-f092-4ad1-a586-e80a1d55c706.png"/>
      <img width="350" src="https://user-images.githubusercontent.com/46502725/163945486-1e2a913e-dbae-4a02-b9f5-c13310f4c506.png"/>
    </td>
  </tr>
</table>

!!! NARRATIVE HEAR !!! - How does system work? Implementation overview & purpose of each module...
*** Pictures of the actual system & 3D printed case  *** 

---
## Cloud Deployment
#### Frontend \[React App\] -> Heroku
``` 
Heroku is a cost effective and ease of use, user-friendly cloud service provider with many free services

CI/CD Pipeline Integration

Auto Deployment through GitHub Repository
```
![CI/CD](https://user-images.githubusercontent.com/46502725/163753329-5b310236-3aa4-41c2-a7ee-3823698ff26d.png)

![Auto Deployment](https://user-images.githubusercontent.com/46502725/163753272-ab3e5147-db77-42de-b8d4-9044010f4035.png)

#### Backend \[API\] -> Azure

 *** Similar display for Azure implementation on backend - used services etc. ***

#### Cross-Origin Resource Sharing \[CORS\]

What is CORS?
> CORS is an HTTP-header based mechanism that allows a server to indicate any origins (domain, scheme, or port) other than its own from which a browser should permit loading resources. In our case, because we are using separate backend and frontend technologies and hosted them separately on different cloud service providers, we are accessing each site through different ports which requires use of CORS to be enabled. 

*** SCREENSHOT OF AZURE CORS ENABLED ***

#### Monitoring

![UpTimeRobot](https://user-images.githubusercontent.com/46502725/163921127-dcbd2c5b-96d8-4be2-a1b8-e54b8d3b3ed2.png)

> Team Sofana is aiming to have the site up and running for 99% of the time out of maintenance time. Due to the purpose and the shifts for golf carts on campus limits the required time to have frontend to be available. Daily the site will be available between 8-12 hours and will be turned to maintenance due to resting host servers and not spending free dynos/credits for no reason.

**Benefits**
- Instant notification when site goes down
- Monitoring daily, weekly, and monthly uptime of the site
- Logging the exact timestamp of downtime for us

---
## Technical Approach

![SofanaGPS - High Level Solution](https://user-images.githubusercontent.com/46502725/163948106-3a236def-567f-4a2c-8ec2-960cf6352a15.png)

SofanaGPS consists of separate components that will interact with each other and work as a complete system. For example, Team Sofana has created components for the user-facing map web application, back-end API to persist and retrieve gps locations, and an embedded system to track the GCU golf carts.  

The system is highly depended on internet connectivitiy. To ensure connectivity between the GPS tracking embedded system and the web application, Team Sofana has created an API using .NET Core that handles the back-end functionality of the web application. This back-end is also consists of a database that collects the location data (longitude & latitude) using a NoSQL database such as MongoDB. The back-end API sends a request consisting of the location information to the front-end component of the web application. 

The front-end portion of the system is composed of the user-facing web application that is created using React. This web application consists of a Map UI component that is being updated frequently by the API in the back-end. GPS coordinates are being generated on a frequent basis by the GPS Module on the GPS system which in return flows through to the back-end API and updates the Map UI. To display an accurate and clean map, SofanaGPS leveraged the help of the React Google Map's API that is used to display a close-up map of the GCU campus with the location of the GCU golf cart marked. To ensure accessibility of the web app and GPS tracking service, both the back-end of the application and front-end are hosted to cloud service providers. The front-end web application is currently deployed and hosted on Heroku and the back-end .Net Core app is to Azure. 

![SofanaGPS - Physical Architecture Diagram](https://user-images.githubusercontent.com/46502725/163948435-71f7d148-6f78-4575-9c59-0731e3ad2c2d.png)

The Physical Solution Diagram shows specifications of the embedded system components that are being used in the SofanaGPS Project. The SofanaGPS has three embedded modules which are Arduino UNO R3, NEO - 6M GPS, and ESP8266 - WiFi. Arduino UNO R3 provides the necessary power to run GPS and WiFi modules and itself runs on a battery. Sofana Team designed and completely developed the web application which displays a map with all the golf carts on the GCU campus, this process requires receiving GPS locations instantly to provide a smooth user experience. ESP8266 - WiFi module sends an HTTP request to the SofanaAPI with the GPS location that was received from satellites by the GPS module. Once the HTTP request is received by the SofanaAPI, the location data is being stored in the SofanaGPSDb with the current time of the day, at the same time, it is being sent to the frontend of the project which is a React application, then the locations of the golf carts can be displayed on the map view. Throughout the entire process, the application status is being monitored by team Sofana using UpTimeRobot to avoid possible down status during day time. When everything is up and running, the users -GCU Students- can access to the web application through their devices of choice, the web application is responsive.

---
## Risks & Challanges

- Issues
- Solution

---
## Contacts
<table>
  
</table>

