
# SheSecure
"She Secure" is a women's safety mobile application developed using Android Studio and Java. 
The app offers a range of unique features aimed at enhancing the safety of women.

## Key-Features

`Saved Contacts :` The app offers a dedicated section where users can add and manage phone numbers from their contacts as 
"Saved Contacts." These contacts are essential for the safety check-ins and emergency alert functionalities.

`Accelerometer :` The application utilizes an accelerometer to determine if the user is running or in a 
state of distress. If the app detects unusual activity, such as a sudden increase in movement, it 
automatically sends the user's location to their saved contacts. This feature ensures that help can 
be promptly dispatched if the user is unable to call for assistance.

`Safety-Tips :` The app offers valuable safety tips to educate users on various precautionary measures and best 
practices. This information serves as a resource to enhance personal safety and increase 
awareness of potential risks.

 `Panic Button :` It also incorporates video and audio recording capabilities, allowing users to capture 
evidence in case of emergencies. These recordings can be quickly shared with saved contacts, 
aiding in documenting incidents and seeking assistance.

`Alert Button :` The "She Secure" app includes an "Alert" button prominently displayed on the main interface. When the user presses
this button, the app instantly sends their current location's address to their saved contacts.



## Screenshots

### Splashscreen
<img src="https://github.com/karthiikJR/SheSecure/assets/115890844/b8238b45-0d53-4db8-9360-35cfc908695d" alt="Loading Page" style="width: 300px;"/>

### Wizard Page
<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/53aabfe6-45a0-4a9d-8b01-12cbff75a8da" alt="Wizard 1" style="width: 300px;"/>
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/0cd8bcf3-c40f-4ee1-b606-8ea9330f4b27" alt="Wizard 3" style="width: 300px;"/>
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/dc81e53e-7a80-40f2-9ace-5d248f1aa678" alt="Wizard 2" style="width: 300px;"/>
</div>

### Login / Sign Up

<div style="display: flex;">
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/e976ce7f-275e-45ca-bf72-fd1c678d71b0" alt="Login" style="width: 300px;"/>
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/ea8d43a9-aad0-48d3-a42a-a661fe1ea55a" alt="Signup" style="width: 300px;"/>
</div>

### Main pages

#### 1. Safety Tips
#### 2. Panic Button

<div style="display: flex;">
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/eedda214-6d89-47d6-b6a5-8a5b4da2130a" alt="Safety Tips" style="width: 300px;">
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/77611ce4-042c-4026-9b05-6fc35d020901" alt="Panic" style="width: 300px;">
</div>

#### 3. Map

<div style="display: flex;">
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/17a87d46-9c75-4b00-a862-221fa0612007" alt="Map Check-ins" style="width: 300px;">
  <img src="https://github.com/karthiikJR/SheSecure/assets/115890844/a275c396-a02b-4141-b0ab-6dfc4f05de8a" alt="List of Check-ins" style="width: 300px;">
</div>

#### 3a. Alert Button

<img src="https://github.com/karthiikJR/SheSecure/assets/115890844/74ff409c-3b9c-4d75-b68b-528a97ff8593" alt="Alert Button" style="width: 300px;">

#### 4. Settings

<img src="https://github.com/karthiikJR/SheSecure/assets/115890844/508824aa-05e6-45f0-b524-70592069e5c8" alt="Settings" style="width: 300px;">

#### 4a. Add/Remove Contacts

<img src="https://github.com/karthiikJR/SheSecure/assets/115890844/a0295fed-d1a1-45cb-aea6-4ba2d58bc18d" alt="Add_Remove_Contacts" style="width: 300px;">

### Accelerometer (When triggered)

<img src="https://github.com/karthiikJR/SheSecure/assets/115890844/dc899ff6-7888-4813-9c8e-7054103380b2" alt="Accelerometer" style="width: 300px;">



### Getting Started:

To clone and test the "She Secure" project on your local machine or device, follow these steps:

Clone the repository to your local machine using Git.

Open the Android Studio project.

In the `AndroidManifest.xml` file, locate the following code:
```
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_GMAPS_API_KEY" />
```
Replace `YOUR_GMAPS_API_KEY` with your own Google Maps API key. This is required to enable the real-time map functionality in the application.

#### Testing on a Mobile Device:

If you plan to test the app on your mobile device, you might need to adjust the accelerometer threshold for speed detection. Follow these steps:

Locate the `SpeedDetectionService.java` file in the `services` directory.

Inside the `SpeedDetectionService` class, find the variable:

```
private float thresholdSpeed = 0.1f;
```
Adjust the value of `thresholdSpeed` to suit your needs. This threshold determines how sensitive the app is to detect unusual activities, such as 
running or distress.

`Note:` It is essential to set up the Google Maps API key and, if necessary, adjust the accelerometer threshold to ensure proper functionality of the 
"She Secure" application on your device.

I hope you find "She Secure" valuable in promoting women's safety and personal empowerment. Thank you for your interest and support!
