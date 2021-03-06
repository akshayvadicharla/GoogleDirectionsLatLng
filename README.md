# Location Simulator
Spring Application whcih takes LatLng pairs of two locations A & B and returns the ‘real’ points on the route that connects A & B with some distance(x) between them. 


<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#build and load">Build&Run with IntelliJ</a></li>
    <li><a href="#results">Results</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project is designed to return the ‘real’ points on the route that connects A & B with some distance(x) between them:
1) A & B locations should be in the form of LatLng pairs and distance(x) in metres.
2) Result will be in the form of latlng pairs of all real points in between A & B in the form of a list.

Time taken to implement: 4 hours

### Built With
* Java using SpringBoot Framework

<!-- GETTING STARTED -->
### Prerequisites

To get started please install the below:
* IntelliJ IDEA 

### Installation

* Install and launch Intellij
  
<!-- USAGE EXAMPLES -->
## Postman Curls : 

 curl --location --request GET 'http://localhost:8023/directions?origin_lat=12.93175&destination_lat=12.92662&distance=50&origin_lng=77.62872&destination_lng=77.63696'

How the application will be used is explained below:
1) After Successful cloning of project in to IntelliJ hit from postman specifying desired A and B latlng pairs and distance at which we require the LatLng points.
<img width="1440" alt="Screen Shot 2021-10-28 at 11 29 32 PM" src="https://user-images.githubusercontent.com/54843732/139310654-02b1c367-0b15-4f82-9260-93296262bfa8.png">
**NOTE:**
JDK Required 1.8



<!-- CONTACT -->
## Contact

Your Name - Vadicharla Akshay

Email - akshayvadicharla1@gmail.com


<!-- Build&Run with IntelliJ -->
## Build&Run with IntelliJ
Use Master branch to clone the project: "https://github.com/akshayvadicharla/GoogleDirectionsLatLng.git"
Open IntelliJ:
1) clone the project using link "https://github.com/akshayvadicharla/GoogleDirectionsLatLng.git",
<img width="805" alt="Screen Shot 2021-10-25 at 10 55 45 AM" src="https://user-images.githubusercontent.com/54843732/138639117-51bfb9ac-5b51-42fe-ba67-db5f8bb9cfd9.png">
2) Download Maven Sources and Documentation
<img width="1440" alt="Screen Shot 2021-10-25 at 10 58 37 AM" src="https://user-images.githubusercontent.com/54843732/138639963-729042b6-0ed5-46b1-9226-4fee1b72a144.png">
3) Build and Run the Application
<img width="1432" alt="BuildRun" src="https://user-images.githubusercontent.com/54843732/138640206-cbd0b230-99f0-4227-8532-94d897582102.png">
4) Then send the request using postman (Shared curl)
 <img width="1440" alt="Screen Shot 2021-10-28 at 11 29 32 PM" src="https://user-images.githubusercontent.com/54843732/139310273-147844a2-462d-4e86-83e1-3ac27a8eb701.png">

5) Result will be in the form of list of LatLng pairs.


<!-- RESULTS -->
## Results : 
<img width="1433" alt="result1" src="https://user-images.githubusercontent.com/54843732/138645603-abb30d00-4cb9-4294-9f93-cb9fe959af48.png">
<img width="1436" alt="result2" src="https://user-images.githubusercontent.com/54843732/138645746-aa8ddea8-7dd6-4e8b-95a4-74b137c4b53f.png">










