# Alexa-Covid-Consultant
With the help of natural language processing and Voiceflow, CovidConsultant is a voice interaction app that identifies user's symptoms for COVID and assess what's the best next 
course of action

Created using **Wit.Ai, NPL, AI, APIs, Node.JS, &amp; VoiceFlow**

## Usage

You can ask the consultant things such as **"I feel sick"** or **"I have a headache"** or **"I minor fever. should I be worried?"**
If you decide to take the Self-Assessment test, you will be asked a series of questions that were taken from the Provincial Covid-19 Self-Assessment Test.

Your answers will be stored with the correct intention using Wit.ai, and the program will decide what to advice you to do according to the Official Provincial Test. At the end, 
the assessment will be sent to the user's email. This was implemented with Node.js & API.

[Project Link](https://creator.voiceflow.com/prototype/60030f0b8cc35e0006e1b0ae)


### Inspiration
It goes without saying that everyone have been affected by the pandemic, obviously the virus itself is deadly but we believe the fear of catching the virus and how to approach this virus are just as scary. Therefore we hope to make an interaction application to give users on what their next steps should be regarding COVID-19 based on their initial symptoms and situation.

### What it does
It takes in user input and with the help of Wit.ai it would be able to recognize the intent of user and recognize covid symptoms keywords from users. Based on that information the app will make a judgement if the user should seek immediate help, go for testing or keep monitoring. The app will generate a PDF that has the summary of the assessment and user will have the option to send it to a clinician for recommendation.

### How We built it
We used voice flow and JavaScript to build the voice interaction app that deals with all the prompts and logic that's involved in it. We used Node.js to build a back end server for PDF generation and sending email. We used Wit.ai to train the app to recognize intent and entities from user input.

### Impact it could make
Right now users would be able to do the assessment using their phone and computer. We believe by incorporating the assessment into a voice control interactive device like Amazon Alexa, it would make the assessment kit a lot more accessible especially to people with visual impairment or elderlies who do not use electronic devices. This will also free up time from the human labor of taking the assessment and prevent unnecessary visit to hospitals and clinics which would alleviate some of the burden to our healthcare workers. Hopefully this will also lead to more people taking the assessment and go for testing or seek medical help if necessary to control the pandemic.

### What's next for CovidConsultant
We hope to keep training our AI model to will better understand the intent and recognize the entities from users. We also hope to expand our functions to cover more COVID related questions that users will have, for example, recommend closest testing center based on user's location and reporting latest COVID numbers in the user's region.
