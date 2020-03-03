# DH150 Assignment 8: High-Fidelity Interactive Prototype

### _by Tasia Mochernak // Digital Humanities 150 at UCLA, Winter 2020 // Dr. Sookie Cho // 03.03.2020_


<p align="center">
  <img width="430" height="330" src="pmlogo.png">
</p>

## Overview

**Purpose:** The purpose of creating this high-fidelity prototype is to visualize the functional and UX/UI-related improvements I would like to make to the ParkMobile application in a format that users can easily test.

**Process:** This high-fidelity, interactive prototype was created based on several steps throughout the design process. First, the interactions included in this prototype were chosen based on observations made during usability testing and contextual analysis. Next, I created 3 user personas and assigned each one to 1 of 3 interactions, based on how much benefit it could bring to them related to their personal characteristics. Then, I hand-drew wireframes and wireflows as part of a low-fidelity prototype, which I tested with two users. Feedback from both users informed changes I made to my original plans for certain interactions, especially the second one about receiving recommendations on places to visit. I incorporated these changes into my high-fidelity, interactive prototype that I made using Figma, with a mix of new interface designs and screenshots from the ParkMobile and Google Maps applications. 

## Tasks

**Task 1: Seeing the price/hour of parking prior to clicking into parking “zone”**
>In this task, Katie (the associated user persona) opens ParkMobile and sees several nearest “zone” numbers appear. If each zone number is pressed, a bubble with $3, $4, or $6, which represents price/hour, will appear about each zone number. Katie can compare various bubbles in the same vicinity based on the $ amounts and choose which one fits her needs best. After clicking on her chosen zone, Katie proceeds through the ParkMobile time selection and payment screens as usual.

**Task 2: Receiving recommendations on places to visit**
>In this task, Taryn (the associated user persona) opens ParkMobile to the “Park” screen and receives a pop-up box in the top middle of the screen saying “Welcome back, Taryn! Have you  considered checking out a show at the Hollywood Pantages Theatre? Based on your parking history, we think this is a place you’ll enjoy!?” Hollywood Pantages is a location in LA with ParkMobile parking available that Taryn has not yet visited (paid for parking or indicated in survey that she's visited), but the notifications can include different locations for different users based on their personal user history. Taryn clicks on the notification and is taken to a screen with a list of shows currently showing at that location, where she can see if she is interested in attending any of them and proceed through the process of choosing parking to reserve ahead of time. She can exit this "guided" exploration at any time.

**Task 3: Integrating with Google Maps**
>This task spans 2 applications. Jake (the associated user persona) opens Google Maps on mobile and receives a reminder about his flight at LAX at 5 pm today. He either clicks the notification or the "Search" bar to put in his destination (LAX) in order to receive directions. Google Maps shows LAX and due to ParkMobile integration, also shows green ParkMobile logo on the screen indicating nearby PM locations. Jake selects a ParkMobile location as his destination instead and navigates to it. Once arrived, he receives a notification to “Pay in ParkMobile,” which takes him to the ParkMobile app and allows him to pay for parking. 

More information on original user personas and task scenarios can be found [here](https://docs.google.com/presentation/d/11dz4WrX4rDA3PaPw3xPM0CvFOS7pzUTsdDXwr7nQLl4/edit?usp=sharing). The low-fidelity prototype version of this project can be found [here](https://docs.google.com/presentation/d/1BiwPBoQVrLznBH7h3skdUHdgDHVBF0VkMs-a9-DKQRk/edit?usp=sharing).

## Wireframes

**Paying for Parking in 2 Zones**
<p align="left">
  <img width="330" height="500" src="Paying for Parking in 2 Zones.png">
</p>

**Closing a Notification**
<p align="left">
  <img width="600" height="400" src="Closing a Notification.png">
</p>

**Getting Directions to LAX**
<p align="left">
  <img width="600" height="400" src="Getting Directions to LAX .png">
</p>

### Graphical Interface Design Explanation
The base of the interface of this prototype comes directly from the existing application, ParkMobile. As a result, I primarily built on the app's existing color scheme to choose the colors for the additional elements I added into the design. In the first two interactions, the colors I utilized were primarily green, white, and black. Because I also used screenshots of the Google Maps interface in the third interaction, another color I added was the blue color native to Google Maps. The elements I added into the existing interface in order to create this prototype include buttons, notifications, bubbles with the dollar amount for parking, and the ParkMobile logo. All of these added elements are mostly rounded in shape in order to best align with the existing elements in the ParkMobile and Google Maps interfaces.

I did try to test my prototype for color accessibility, but because I was utilizing screenshots of ParkMobile and Google Maps, rather than completely re-designing the interface, the test was not applicable. However, because I primarily used the same colors as those already used in ParkMobile and Google Maps, I feel that the interface is likely to have a relatively high level of accessibility.

## Wireflows

**Task 1**
<p align="left">
  <img width="400" height="600" src="Interaction 1 Wireflow.png">
</p>

**Task 2**
<p align="left">
  <img width="500" height="600" src="Interaction 2 Wireflow.png">
</p>

**Task 3**
<p align="left">
  <img width="600" height="400" src="Interaction 3 Wireflow.png">
</p>

## Interactive Prototype

* [Task 1 Prototype](https://www.figma.com/proto/cS0luA6QUbMQqn4F48rpfN/Interaction-1?node-id=1%3A26&scaling=scale-down)

* [Task 2 Prototype](https://www.figma.com/proto/Fg2RfJ8fe7vmDP34aUQK0Z/Interaction-2?node-id=1%3A2&scaling=scale-down)

* [Task 3 Prototype](https://www.figma.com/proto/s64UzL7U2dSK0CuWdyOrxw/Interaction-3?node-id=1%3A2&scaling=scale-down)

## Changes from Previous Iterations

For Task 1, the interface logistics and design elements that I initially conceptualized remained essentially the same throughout the prototyping process. However, one change I made was removing the "maximum amount of time to park" in the bubbles that appear above each zone number, which I had included in my low-fidelity prototype. This way, the user is not overwhelmed with too much information and can make a decision based on the most important factor, price.

Out of all three tasks, Task 2 was the one that was met with the most struggle from users I worked with to test the low-fidelity prototype. I realized that the logic I employed to move from the initial screen to the next by immediately showing the user available parking rather than informing them about the suggested destination did not make sense. As a result, with feedback from my classmate, I changed the wireflow to go from the initial screen to immediately showing information about the suggested venue, followed by directing the user to explore the available parking options. This way, the user also feels that ParkMobile is truly making a recommendation rather than just a money-grab.

Task 3 was relatively self-explanatory and also remained approximately the same as the low-fidelity counterpart, though I added more detailed steps to the "navigating to a ParkMobile" location section of this interaction.
