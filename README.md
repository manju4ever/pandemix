# Pandemix

> A contact tracing application to avoid infected zones near you.

### [Click here to watch the demo !](https://youtu.be/k4Y7OJoEiTk "redirects to youtube...")

## Background

In the face of rapidly rising numbers of infected Covid-19 cases globally and the various mitigation approaches adoption by different countries, timely/early detection is the key and technology can be an efficient and scalable tool to arm the common people, the authorities, health professional and the government in establishing a way to enable ‘contact tracing’ which today is a tedious manual process and requires a huge amount of time and investment with inherent delays preventing the tracking of possible infected cases from day zero.

The proposed ‘Pandemic Tracker’ will help in easy ‘contact tracing’ to identify a possibly infected person from Day Zero and also provide a common user and authorities app notifications of such contact in the last 14 days, instead of waiting for symptomatic alerts which appear only after 4-5 days of infection. It will provide real time, automated notifications and reports to an individual user based on his/her contact network as well as real time, aggregated reports to the authorities.

## Challenge

The challenge for Indian and Karnataka Government is, tracking the people who came in contact with COVID-19 positive person in past 14 days.

## Solution

An application called 'Pandemic Tracker' is developed. The Goal is to track the people who were in contact with the COVID-19 positive tested person in the past 14 days.

## Application Workflow

- User Downloads the Application.
- A unique identification number is tagged to the user.
- Registers with his mobile number. (We want to avoid this going forward)
- Login.
- Turn-on GPS Location.
- Redirect to the Landing page.
- Our application scans his surrounding to check if the user is surrounded by any COVID-19 person.
- Minute the user login into our application, we start continuously track his location.
- When the user updates the COVID-19 status to positive, in the backend we fetch the users who were at 2 meters distance from him in the last 14 days with respect to the time and travel history.
- A notification (via call & text message) will be sent to all the users who were at 2-meter distance.
- The same report will be sent to concerned government authority.
- The Web application is being developed by the team, only for government officials to keep track of the COVID-19 positive people and all the possible victims in real-time.
  - The officials can filter the data according to State/ City/ Postal Code. (This is under development)

## Advantages

The application is beneficial to both government and public.

- It adds value to the government in the following areas:
  - To do root cause analysis of the person might have got contagious.
  - Example: After a week a particular street is marked danger zone, we can figure out who were the people who were exposed in that particular area in the past N number of days.
  - The web application will be provided to the responsible government officials to pull the results of the facts mentioned in the above point.
  - Trace out all the possible victims (users who might have come in contact with COVID19 +ve person in past 14 days) immediately. Concerned authorities get all the victim’s mobile numbers. This Information is not reviled to the user.
  - Track the real-time movements of the COVID-19 positive person and Victim.
  - Age of the users who were most affected.
  - If the user was suffering from any chronic diseases before.
  - What was the primary symptoms the user started showing.
  - All the possible ad-hoc analysis on the data we collect. Helps us to make quick data driven decisions.
  - It adds value to the Public in the following areas:
  - Get the latest updates from the Governments, This helps the user listen only true facts.
  - Check if the area user is travelling is safe or not or How safe it is?
  - Get real-time notifications if the user has crossed the paths with COVID-19 person.
  - Check how many COVID-19 victims the user is surrounded with at his current location.

## Caveats

There are few limitations of the application we have developed. Few of them can be achieved with the help of Government and few are really very tough to overcome.

- It is responsibility of the user to be very careful before user updates the COVID-19 Status to positive.
- Difficult to find the location history of the people who are already COVID-19 positive.
- Zero network coverage area
- Human errors
- GPS switched off
- Switched off Phone
- Movement without phones
- USER Acceptance to install the application
- No update or False Update. This might be a serious threat. (We have the work around for it but requires a bit of extra efforts.) (Strongly educate the people on it)
- Inability to track from Contact Surfaces (e.g. live virus on a metal surface)

## What we need from you?

- Kindly share this with your friend and family who might be interested to contribute for the welfare of the society.
- We are highly motivated to share our codebase with the community and request you to improve in any way possible.
- Develop a calling facility within the application. Ex: if we detect any person was in contact with COVID-19 positive person in past 14days, we would like to alert him by providing in app calling facility. By this we can achieve the highest security level, by not collecting any information (phone number, email id) from the user.

> This is implemented through react-native. The Android build is ready and IoS build will be ready soon.
