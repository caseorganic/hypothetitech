# Hypothetitech - A Hypothetical Vacation App

Hypothetitech™ is a Twilio Studio Flow program that allows anyone to record their own low-tech stories for loved ones that may not have access to a stable web connection. This Twilio experience allows listeners to simply call a number and experience a story. We’ve included a sample story to listen to for inspiration before they record their own story. 

The experience of this app is simple. You can check out the demo by calling 503-455-7353.  

This app was created at for the first Twilio x DEV community hackathon!

## Getting Started
Can check out the demo by calling the number below. 

## Test the app - Call 503-455-7353
Follow the instructions below to import the script into your Twilio account for editing. 

### Prerequisites
You’ll need a Twilio account and number to run this app. You’ll need access to Twilio studio, a basic understanding of JSON, and the ability to import JSON into Twilio studio. You’ll need basic access to an audio recorder and a server to host your own files. 

### Installation and Story Editing 

* Download the JSON file in this Github repo to your computer. You’ll be uploading this to your Twilio account in Studio. 

* Log into your Twilio account and go into Studio. Go to All Products & Services >> Runtime >> Studio

* Create a new Flow, Create a new Flow, and select Import from JSON. 

* Click Next. You will be presented with a code window to paste valid Flow JSON.

* Click Next to create the new Flow once the JSON definition is added.

* You should now have a template project that you can use to build your own short story, or add your own branches. Just record your own audio, upload it to your server, and reference it in each Chapter module, or edit JSON file to update it with the location of your audio files. 

### Deployment 
Once you’re happy with your changes, click Publish, and go into All Products and Services >>> Phone Numbers. Register a number if you don’t already have one. Once you have a number, click the number itself to go into the number configuration. Scroll down to Voice and Fax. Under “A Call Comes In” Choose Studio Flow, and the title of your Studio Flow story. Press SAVE. 

Call the number you set your story to, and you should be able to hear your story! If you don’t make any changes to the files within the JSON or Studio Flow, then you can listen to the stories in the example app. 

## Built With

* [Twilio Studio](https://www.twilio.com/studio) - To build the logic for the interactive phone tree app and to create the JSON for sharing. 
* [Twisted Wave](https://twistedwave.com/) - All audio files were recorded onto iPhones using TwistedWave, an high quality audio audio recorder and editor app.
* [Audacity](https://www.audacityteam.org/) - Post-audio processing to get it to sound good over a telephone line. 

### Authors
* Caseorganic - Initial coding work, audio editing and voiceover - [Caseorganic](http://www.caseorganic.com/) 
* B. Greenstein - Initial concept and voiceover - [manofsuit](https://github.com/manofsuit) 

### License
This project is licensed under the MIT License - see the LICENSE.md file for details

### Acknowledgments
* Thanks to Twilio for the hackathon!
* Thanks to B. Greenstein for the initial email that kicked this off a few weeks ago. 
* Twilio studio! 
