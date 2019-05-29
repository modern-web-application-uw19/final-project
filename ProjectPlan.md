SCHEDULE ME APP
Personal Goals:
Use Redux
Use Router
Use an API
OAuth 2.0 (requirement of Google calendar)
Use Flexbox

Stretch Personal Goals:
Use OAuth
Save client info to a database
Elevator Pitch:
Create a webapp that will be fake website for someone who provides services that require appointments, i.e. acupuncture, facials, massage, nail design. I know a fair number of small business owners who have businesses in this space and they are the most likely to ask for help with website design. This market is people who are professionals in spaces that are often disconnected from tech, often leading them to feel uncomfortable using Squarespace, Wix, etc. My eventual goal is to have a template that works for this type of business and be able to easier assist friends that are looking for website assistance. As a first step, I will be creating this simple app which will route between several pages of About, List of Services and a Scheduling component. The main focus of this app will be the integration of Google Calendar API to allow clients who are logged in view OAuth to view available appointment slots and select an appointment time.

Details:
The app have several pages:
Pages:
About
Services (description of services)
Book an appointment
The pages will use Routers to move between pages
The content on the About and Services pages will be minimal (maybe lorem ipsum), as the objective is to work with React Router on these pages
The content on these pages will be styled using Flexbox
Use Google Calendar API to book appointments
https://developers.google.com/calendar/create-events
On the provider’s side:
Only available during business hours
Only shows time slots that are not taken
When a customer books an appointment, the calendar is updated
On the customer’s side:
Show a list of available appointments within a timeframe
Look at the API and see what is possible
Can it be by week or by day?
Easy to click through to the next week or day?
Can this week/day view only show open slots?
Some confirmation that the appointment has been booked - either in the web app or email (stretch goal)
Calendar stretch goals:
Send a confirmation email to customers on booking their appointment

STRETCH GOALS:
Email confirmation after booking an appointment
Adding a “Login/Logged in” aspect to NavBar
When not logged in, will have text that reads “Login” and click will take to the Oauth page
When logged in. will display text that reads “Logged in” ( or userName) and an image that further shows logged in, click will not take anywhere (will be disabled)
Client database

DEPENDENCIES
React
https://reactjs.org/
React-router
https://www.npmjs.com/package/react-router-dom
Google Calendar API
https://developers.google.com/calendar/
OAuth 2.0
https://developers.google.com/identity/protocols/OAuth2
Heroku
I presume - or whatever other web-hosting is presented in class
Firebase (if client database stretch goal is reached)
https://firebase.google.com/

TASKS
Set up basic pages that route between each other ~ (3.5hrs)
✅ Create-react-app
✅ Make components that display on main page
Dummy data and images
Set up routers and links for each page
✅ Create components for the linked pages
Dummy data and images
Set up OAuth ~ (3.5 hrs)
Need to read up on this to break down into further steps
Get API working
Identify which API endpoints I will need and what information they need for the calls ~ (1-1.5 hrs)
Be able to hit APIs and receive information in return and console.log it
Start with most basic API call - set up and get return ~ (3.5 hrs)
Set up remaining API calls and get return ~ (.75 hours each)
Break these down into separate tickets
View calendar
Create event
Display the API returns on page ~ ( 2 hrs)
CSS styling ~ (3 hrs)

PLAN
Set up basic structure of the app with routes between the main pages
Set up OAuth
Get API calls working and logging returns as expected
Display information returned from the API on the page
Polish Styling across the webapp


WIREFRAMES:
Home Page:
https://www.lucidchart.com/documents/edit/02f2299b-76fc-449f-9540-04f155c35c1b/0
About Me and Services Page:
https://wireframepro.mockflow.com/editor.jsp?editor=on&publicid=Mafa327188384e2aec3f0900f63f06deb1558595637723&perm=Create&projectid=Mb7bfdb2ed04ed9acf0cb0cfc4661dde81558595657712&ptitle=Scheduling-App&bgcolor=white&category=featured#/page/6019b9dd9fd8453fb442453915f07c22
Calendar Page:
Will depend on further investigation from what is possible when using Google Calendar
OAuth Page:
Will depend on further investigation and what is possible when using OAuth2
