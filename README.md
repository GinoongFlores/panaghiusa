> You may clone this repository and only run the App and  the Dashboard on your local machine. You may also disregard the Landing-page. 
> 
> Listed below are the main features and instructions on how to run the App and the Web dashboard.

# Panaghiusa App  

Login | Impact | Rewards
--- | --- | --- 
![](https://raw.githubusercontent.com/GinoongFlores/panaghiusa/main/landing-page/img/app-img/login.png) | ![](https://raw.githubusercontent.com/GinoongFlores/panaghiusa/main/landing-page/img/app-img/impact.png) | ![](https://raw.githubusercontent.com/GinoongFlores/panaghiusa/main/landing-page/img/app-img/rewards.png)

## Features 
- User Signup and Login
- Plastic Contribution that uses Teachable Machine powered by Tensorflow Lite
- Organic Waste Contribution
- User impact based on their contribution

## Panaghiusa Courier App
We have also included the courier app as one of the scalability soon. We plan to collaborate with courier carriers who will assist us in scanning user's plastic contributions, and contributions data will retrieve in the app. 
## App Installation

We highly encourage you to install the latest Android Studio to run the App, version of Bumblebee, or later. You can install the latest version of Android Studio, command-line tools, and SDK from the [Android Studio Website](https://developer.android.com/studio). 

### Running the app in Android Studio

After cloning the repository, launch Android Studio and navigate to the ```Panaghiusa-app``` folder. To run one of the applications, select between these two folders ```Solution_Challenge_App```, the Panaghiusa app, and the ```Panaghiusa_CourierApp```, the courier's app.

### APK Files are also available

APK file for the Panaghiusa app is available [here](https://drive.google.com/file/d/1K1Rr32NnYCVmwMZXGoz4b7iieusuScxX/view?usp=sharing). 

APK file for the Courier app is available [here](https://drive.google.com/file/d/11GowqiVtVS1I0lf32OFkT5ehMqlR2nDe/view?usp=sharing).


<br />

# Panaghiusa Web dashboard
Dashboard | Delivery Confirmation | User details
--- | --- | --- 
![](https://raw.githubusercontent.com/GinoongFlores/panaghiusa/main/landing-page/img/dashboard-img/dashboard.png) | ![](https://raw.githubusercontent.com/GinoongFlores/panaghiusa/main/landing-page/img/dashboard-img/delivery.png) | ![](https://raw.githubusercontent.com/GinoongFlores/panaghiusa/main/landing-page/img/dashboard-img/user.png)

Panaghiusa dashboard is built with React and this dashboard is only intended for admins who track the progress of a user that interacts with the app.

## Features 
- Retrieve user data
- Contribution confirmation
- User details

## Dashboard Installation and Configuration
 - Install node.js if you don't have it already
 - When you clone the repository, navigate to the root folder of the dashboard, and you will need to install the dependencies by running: 
    ```
    npm install
    ```
  - In the dashboard directory, you can run: 
    ```
    npm start
    ```
  - If face some issues like "react-scripts" is not recognized as internal or external command" error. Install the react-scripts by running: 
    ```
    npm install react-scripts --save
    ```
    - Another way to fix this error is to reinstall packages. By running: 
     ```
    npm audit fix
    ```
      or 
    ```
    npm update
    ```
## Landing Page 
The landing page provides an overview of the app, its goals, the selection of United Nations Sustainable Development Goals (SDG), descriptions of its primary features, and information about the app's development team.

To know more about the Panaghiusa app, visit its website [here](https://panaghiusa.netlify.app/). 

