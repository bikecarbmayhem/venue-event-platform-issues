### 1. Introduction 
This event & venue booking application serves to support venues and organizers (this includes musicians, public speakers and so on) by centralizing booking and organization into one platform. The app allows unregistered users to view upcoming events in a specific city (in this case, Sarajevo) as well as view the profiles of both venues and performers- upcoming and past events as well as the respective performers are displayed there. Account registration is limited only to venues and performers, with each role having separate , utilities and account creation requirements. Venues will be able to post their available time slots and requirements, whereas performers can browse said slots and submit proposals to venues they're interested in performing at/reserving outright. A rating and feedback system would allow for both parties to rate and review each other, providing valuable insights into future interactions.  

### 2. Features
The application will support the following features:
- Venue/performer search & discovery
- Event booking & scheduling
- Adding, updating and deleting venue listings
- Account registration

### 3. User Interface

 - Home page 
 - Login page
 - Venue marketplace page 
 - Venue marketplace page
 - Event page
 - Venue profile page
 - Performer profile page


### 4. Functionality

![alt text](https://github.com/bikecarbmayhem/venue-event-platform-issues/blob/main/sitemap.PNG "SiteMap")
#### 4.1 Home page 
The home page simply displays a list of upcoming events in the city, as well as additional filtering options such as the ability to filter by type (concert, workshop etc). Log in / Sign up buttons will be present in the header. 
#### 4.2 Event page
This page displays event data such as date, description, venue (as well as venue location) as well as the list of performers that will be present.  
#### 4.3 Venue advertisement setup page
This page allows a venue to specify their performance requirements for potential applicants, and requires the following parameters as input:
 - advertisement name
 - Type of event/performance
 - Date & Time
 - Description
#### 4.4 Venue marketplace
The venue marketplace is not accessible to unregistered users- it provides a list of venues that are open and accepting various types performers. Venue information 
#### 4.5 Venue profile page
The venue profile page displays basic information on the selected venue- information such as Venue name, address, location as well as a short description and pictures of said venue will be present. A list of upcoming and previous events hosted at the venue will be present on the right side of the screen, along with a thumbnail and short description. 
#### 4.6 Performer profile page
The performer profile page displays basic information on the selected venue- information such as performer name, type of activity/performance (free ball at this point- can be a musician, public speaker etc.) as well as pictures.. A list of upcoming and previous events featuring the performer will be present on the right side of the screen, along with a thumbnail and short description. 

#### 4.7 Login page

This page is sort of self-explanatory; this page simply allows for the user to log in and gain access to the venue marketplace. 

#### 4.8 Venue account creation page

Again, self-explanatory- allows a venue to create a profile through inputting the following parameters: 
 - Venue name
 - Address
 - Phone number
 - Email address
 - Website URL
 - Password

#### 4.9 Performer account creation page 

 - Name
 - Phone number
 - Performer type
 - Email address
 - Webiste URL
 - Password

### 5. Technical Requirements 

The project is built using the following technologies:

 - Backend: Java, Spring, PostgreSQL
 - Frontend: Angular

The app Frontend/Backend is hosted on a Heroku cloud server.
