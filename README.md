# Welcome to ZoomParty

#### ZoomParty, a spinoff on Zoom and Houseparty, is a single-page application that allows users to have conversations using real-time video and voice chat.

## Technologies

### Frontend
 - JavaScript
 - HTML
 - CSS
 
### Backend
 - Flask
 - Python
 - Twilio Programmable Video JS SDK



## Features

Video Chat

 - Users can connect to the main room and have clear and consistent real-time video

Voice Chat

 - Be able to talk if user opts in not to use microphone or use a combination of both

Screen Share 

 - Users can share their screens and another video container will pop up, showing both the main camera and screen camera

![alt text](https://github.com/amanallahcode1/ZoomParty/blob/main/Capture.PNG)


## Local Setup Instructions

 - Create a Twilio account (if you don't have one yet). It's free!
 - Generate an API Key for your account.
 - Clone this repository
 - reate a virtualenv and install the requirements
 - Ceate a .env file by copying the .env.template file. Fill out the values for your Twilio account's SID, API Key SID and API Key Secret.
 - Execute python app.py to start the server.
 - Naigate to http://localhost:5000 on your web browser. Connecting to the service from a phone or another computer may not work, as browsers require a secure (HTTPS) connection to give access to the media APIs. In that case, I suggest you use ngrok to give your application a temporary HTTPS URL.



