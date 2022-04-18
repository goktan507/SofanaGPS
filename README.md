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
- [Introduction]()
- [Requirements]()
  - [Functional Requirements]()
  - [Non-Functional Requirements \[NFRs\]]()
- [Technologies & Tools]()
- [Hardware Components]()
- [Cloud Deployment]()
  - [Frontend \[React App\] -> Heroku]()
  - [Backend \[API\] -> Azure]()
  - [Cross-Origin Resource Sharing \[CORS\]]()
  - [Monitoring]()
- [Technical Approach]()
- [Risks & Challanges]()
- [Contacts]()


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

!!! NARRATIVE HEAR !!! - How does system work? Implementation overview & purpose of each module...
*** Pictures of the actual system & 3D printed case  *** 

![SofanaGPS - Circuit Diagram](https://user-images.githubusercontent.com/46502725/163845799-41b3c485-0cc4-4b7f-a5fd-c71aba36e46a.png)

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

*** UpTimeRobot Screenshot once it monitors for a while ***
---
## Technical Approach



---
## Risks & Challanges

- Issues
- Solution

---
## Contacts
<table>
  
</table>

