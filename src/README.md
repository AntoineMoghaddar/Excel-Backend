#Project Excel README

##Introduction

This is the Project folder for Module 3 - B-Create we are taking part in.
This project consists of 3 separate part which we will try to merge in the end.

The main purpose of this document is to define and summarize
* The idea of this project,
* The systems and software we will be using to realise this project,
* Some data about how to use this data.


##Problem statement 
The Enschede Marathon is a successful event, regarding the amount of people joining this event. The attendants are divided into three different categories: the athletes, the supporters and the general public. If we take the size, its’ inconveniences and the users’ wishes into account, the organisation of the Enschede Marathon poses the question how they can improve the user experience, with the use of technology, with the prospect of returning to this event. 
Moreover, the organisation of the Enschede Marathon is evaluating its’ identity and might be changing it. 

Our main concept is to make an application that provides a service rather than to entertain people. We will reduce the inconveniences by supplying information and details about the Enschede Marathon. Investigated will be the users’ and design preferences, which information is crucial to develop a successful application. 

To create Enschede Marathon a new identity, our concept could offer possibilities. At the moment, Enschede Marathon has only a website, but they could replace the website with the application, depending on the reviews, execution and additional requirements.

##Elaborated explanation about the application
By developing an application, we create one solution to improve the user experiences of the three different user categories (the athletes, the supporters and the general public). The fundamental basis of the application will be a detailed map of Enschede, as well as the marathon tracks. 

To further explain the concept, there has been made a distinction between the front end and the back end of the application. 

###Front-end 
The front-end is being defined as the part of the application, which the athletes, the supporters and general public can access. The following functionalities and features are accessible by the categories. 

###Functionalities
* Tracking runners 
Brief description: supporters and interested attendants of the event, can search for the contestant number of the top runners and family members, friends, which pinpoints a dot on the map of Enschede Marathon tracks. The goal is to let them be informed about the progress of the runners and the 

* A heat map of hotspots
Brief description: the heat map visualizes the most crowded spots along the tracks of the Enschede Marathon and the near area. The user can see where the majority of people are in order to be able to avoid crowded areas and to choose a different location to watch the marathon or enjoy the event where it is less crowded.

* Navigation 
Brief description: by enabling the GPS on the SmartPhone, supporters can easily and quickly go from A to B to watch at several spots along the tracks of the race. Moreover, offers the possibility to be navigated to the person, when the runner has finished. The functionality takes away the despair of not seeing the person finish and the miscommunication of actual location of both parties. 

* Donate to charity
Brief description: the Enschede Marathon has a partnership with “Stichting Kans voor een Kind”. Before making a subscription to the marathon, the runners are offered to donate to this foundation. By implementing this functionality, supporters and general public could also make a donation, with the prospect of generating more money that will be awarded to “Kans voor een Kind”.

Multiple payment methods will be revised, such as Mollie and Adyen. The chosen method will be based on price, privacy and usability. 

* Profiles 
Brief description: a user of the application can choose between options. The first option is to create a personal account. The runners are able to create a profile with this account, in which previous marathon events will be specified and data retrieved from this specific event, like finish and start time. On the other hand, the supporters are able to track runners, look into the biography of the runners, when they have created an account. The underlying theory is to create a tighter connection between the (top) runners and their audience. 

* Program 
Brief description: to be always aware of the activities organised during the day, the program will be added to the application. Besides, the runners will be finding information about the pick-up point of their contestant number and time schedule. 

* Stories
Brief description: to share the experiences of the event from different spots along the tracks, the users of the applications are able to upload pictures. These spots are tagged, so it’s easy to retrieve the location. This could lead to change in magnitude of the hotspots, because people will be more aware of the different activities. Next to this, it shows the atmosphere of the entire event. 

###Features 
Detailed map of the tracks
Brief description: the map will be showing the 5 courses the runners have signed up for. The colour scheme will be the same as on the website. 

* Sponsorships 
Brief description: in the application, a separate page will dedicated to the sponsors. Moreover, at the bottom of every page, the icons of the head sponsors will be displayed. 

* Terms and regulations
* Privacy statement
Brief description: since last year, the government of the Netherlands has implemented the “AVG”, which is a law that enforces organizations to properly secure data. 

###*Back-end*
The back-end of the application is being defined as the part of the application that only has been made available to the organization. If the organization wishes to update information about the program, the time schedule or any other particularity, they are being authorized to do so. One of the necessities to create the back-end of this system, is to be able to send notifications to people attending the event. 

Envision the following scenario: during the event, the temperature has risen. There is an upcoming dangerous heat stroke and the organization and public facilities are running out of water. They would like send everyone a message containing the information of cancelling the event. 

By creating the back-end system, the organization will be capable of sending this notification. 


##Technical aspects 
###Prototype 
* The prototype will only contain GPS trackers, enabled on the SmartPhone of the users. 
* The application can be downloaded in the Play Store; the prototype will be made for Android. 

###Final product
* To guarantee even more the privacy of the runners (and if necessary the supporters and the general public), bracelets with a NFC chip could be distributed. Our prototype uses the GPS sensors of the SmartPhone, of which the live location (coordinates) are being linked to the created profile. Moreover, this data is being sent to the server and can be retrieved by the supporters and the general public. The bracelets with an integrated NFC chip permite the athletes to be more invisible regarding the data saved and shared with the supporters and general public. The location still could still be retrieved, but only by contestant number. A profile of the person won’t be displayed. 
* The application will also be available in the AppStore, thus made for Apple Operating Systems

##Software 
As clarified in the project proposal we have thought of building an mobile (android) application in combination with a backend system for modifying and seeing through data.
This dashboard will be build using 
