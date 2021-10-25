# Google-Direcctions
Spring Application whcih takes LatLng points of two locations A & B and returns ‘real’ points on the road that connects A & B with some x distance between them. 


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
    <li><a href="#build and load">Build&Run with ghpages</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project is designed for the admin to manage the items in the cart for their online businesses. And this application mainly consists of 9 UI components mentioned below:
1) Login: Component used for authentication of the admin,
2) Header: Header of the application with the application logo and login/logout button,
3) Footer: Footer of the application with the application logo,
4) Items table: Component which is used to show the items list,
5) Home: Component used to show the list of items with the options of adding/deleting/updating the items in the cart,
6) Add item: Component which take cares of adding the item to the cart(validated based on the item_name which is treated as unique constraint),
7) Update item: Component which take cares of updating the item in the cart(validated based on the item_name which is treated as unique constraint),
8) Page not found: Component which is shown when the admin tries to access the page which is not available,
9) Confirmation dialog: Component used to show the confirmation dialogs when the admin wants to delete or update the item in the cart.

Time taken to implement: 4 hours

### Built With
* [SpringBoot](https://getbootstrap.com)

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

To get started please install the below:
* IntelliJ IDEA 
* npm
* Angular CLI

### Installation

* node.js -- https://nodejs.org/en/
* npm
  ```sh
  npm install npm@latest -g
  ```
* Angular CLI
  ```sh
  npm install -g @angular/cli
  ```
  
<!-- USAGE EXAMPLES -->
## Postman Curls : 
 curl --location --request GET 'http://localhost:8023/directions/lat-lng?origin_lat=12.93175&destination_lat=12.92662&distance=50&origin_lng=77.62872&destination_lng=77.63696'

How the application will be used is explained below:
1) After Successful cloning of project in to IntelliJ hit from postman specifying desired A and B points Latitude and Longitude and distance at which we require the LatLng points.
![image]()
2) Enabling the Submit button only if the necessary validations are passed for the username and password.
![image](https://user-images.githubusercontent.com/42332664/125819129-76ac6f41-35fd-43ea-b234-52771e4d7223.png)
3) Once the admin is logged in with keep me logged in then there will be no session timeout else the admin will be logged out automatically upon 30mins completion.
4) Once the admin is logged in sucessfully, homepage will be loaded with the list of items along with the add/update/delete options.
![image](https://user-images.githubusercontent.com/42332664/125819612-cdf61a13-2257-41a6-9447-0e75499abe0a.png)
5) Upon clicking the add button then the add-item page will be loaded with the form(which is set with required validations) to add item to the cart,
 
![image](https://user-images.githubusercontent.com/42332664/125820157-ebbecd04-e739-4d0d-8caf-2ef0e07618f2.png)
6) After filling the form with the item details,upon clicking the add button.
7) Clicking on the Go back button will redirect to the home page,
8) Clicking on the delete button(delete icon) will show a confirmation dialog to really want to delete the item or not? if yes is selected then the item will be removed from the cart.

![image](https://user-images.githubusercontent.com/42332664/125820958-23c22b0e-24a6-4d7e-a4af-4e8eeee40285.png)

9) Upon clicking the edit button(pencil icon) then the update-item page will be loaded with the prefilled form with the item details, if the update button is clicked then the confirmation dialog will be shown. After updating the item the page will be redirected back to the  homepage.

![image](https://user-images.githubusercontent.com/42332664/125821281-d3d86027-ed3b-4adf-98f6-d782b7c880f2.png)

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
2) Download Maven Sources and Documentation
3) Build and Run the Application
4) Then send the request using postman (Sharing curls)
5) Result will be in the form of List of LatLng.









