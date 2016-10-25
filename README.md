<h1>Inspiration</h1>
The imminently or newly homeless often need help immediately, and do not know what or where the resources are availability. We believe connecting these individuals with a nearby shelter and resources as quickly as possible, before situations get worse, can provide significant improvements in outcomes.

<h1>What it does</h1>
AngeLift offers a safe ride for people in need to a nearby shelter, by connecting at-risk individuals with qualified and vetted drivers that are the closest. Text SMS enables anyone, including good samaritans, to call an AngeLift ride for an at-risk person. No app, prior setup, or even Internet data service, is required of the caller. Inexpensive posters with simple instructions and a location identifier are placed around the community where need is anticipated. The location identifier is associated with the location where each poster is placed. When a text is received by AngeLift, it determines the drivers closest to the location. A web app is provided for the qualified and vetted driver to accept the ride request, and select among the nearest suggested shelters to get directions to take the client after pickup. AngeLift provides shelter operation staff to update their bed availability in real-time to enable AngeLift to best route upcoming demand.

<h1>How I built it</h1>
PHP5 server back-end software, running on Apache server provide URL API access to database based on MySQL. HTML/CSS responsive web app for drivers and shelter operation staff. Twilio SMS services API provide message routing to an interface URL to process incoming requests, as well as send alerts to drivers who have indicated availability to provide rides in their area. For the demonstration, the Project is deployed on a virtual server owned and maintained by one of our team members. The demo system also runs the MySQL database engine.

<h1>Challenges I ran into</h1>
Twilio API interface package recommended using PHPComposer to deploy. However, we found instructions on how to deploy the package manually.

<h1>Accomplishments that I'm proud of</h1>
We worked very well as a team, although we have known each other from a few weeks to just a few hours. The way we helped each other maintain energy, focus, and a sense of purpose -- related to both the project mission as well as to support each other -- made for an excellent and worthwhile experience.

<h1>What I learned</h1>
Although a couple of us had heard of Twilio, none of us had any prior direct experience actually interfacing to the Twilio API. We worked together well, at some times tag-teaming on tasks, to work through getting Twilio to actually work with out project.

<h1>What's next for H2H</h1>
Given the opportunity, we see great value in extending the reporting and analytics of AngeList. We believe that the data collected, including real-time needs and utilization data collection, especially involving geo-location data, provide for unprecedented responsive and potentially predictive insight value.
