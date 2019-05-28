# Week 7 Assignment

Your assignment for this week is to think of a final project idea and create a plan for the project.

## Final Project Requirements

* The project must be a React application, bootstrapped with `create-react-app`
* Your app must be created and visible in a Github repo under your Github account
* Your app must be your own work. You may have a partner if you'd like, but be aware that you'll need to come up with a strategy for working together. Most developers on small projects create branches for new features/fixes, then merge them back into the `master` branch. Merge conflicts can arise, and you'll need to know how to resolve them.
* Your app should be deployed onto a web server and publicly accessible
* Your app should be polished. Some recommendations for this requirement:
  * Remove `console.log` statements once you're finished with development
  * Utilize CSS and images to make your app look great
  * Check for any React errors in the console
  * Perform some basic user testing. Have other people use your app and receive feedback on usability
  * Keep your feature set small, so you'll have time to polish the app

Other than the above requirements, you're encouraged to be creative and create something you're proud of. It can be as simple or as complex as you want, and it should be high quality.

## Assignment Requirements

Above are the requirements for the project. For this week however, you'll need to create a plan for your project. More details are to come, but you'll need to create a pull request with the following:

* The name of your project
Calendar Viewer for Tasks

* An elevator pitch (a paragraph about what your project does). Be sure to address:
  * Who will use your project
  * The value that your project will provide to the end user
I will be the intended end user of this project. I currently use an online calendar to handle my schedule and would like to integrate task reminders into that flow. At the moment I have a duplicative way (adding a calendar event as a reminder and noting it down with pen and paper) of ensuring that I don't forget a task. It would be more ideal to have a single place to manage both events and tasks in a way that is customized to my preferences. For example, I sometimes know of a task in advance which I would like to be reminded of starting 2 weeks from the due date. Before 2 weeks, I would like to exclude this task from my "live" task list so these non-urgent tasks don't crowd up my immediate to-dos. However, once the task goes "live", I would like the calendar to push the event along each day as a "live and open" request until marked as "closed". Currently, the task manager in the calendar I use doesn't automatically handle the time-based categorization I am interested in without manual re-organization. This project's default view will be a full-month, in which each task has a "compact" view and a "detail" view with more information. Both will be interactive components where a task will have 1) task name, 2) due date, and 3) live date. Other items to include could be a) description and b) categorization/labeling of task type. In addition to the event having two view types, tasks could also be viewed in multiple ways. First, it could be viewed as a color-coded list based on "open and not live" (grey), "open and live" (blue), and "closed" (green) sections. There can also be a checkbox selection types of dates can be toggled on and off (e.g. it would be possible to see just events by due date without the reminder timing information).

* [Wireframes](https://en.wikipedia.org/wiki/Website_wireframe) to help visualize what your project will look like
  * These wireframes do not have to be high-fidelity. You're free to use boxes, hand drawings, etc.
* A list of dependencies you'll be using for your project (npm modules, APIs, Firebase, etc.)
  * This list will likely change as you work on your project, but listing your dependencies will help you visualize the complexity of the project
  react-calendar: https://www.npmjs.com/package/react-calendar

* A list of tasks that need to be completed for your project
  * calendar: default calendar view by month (extend: by week and day) 
  * calendar: add month picker to switch between months
  * storage: store tasks and their details in redux
  * task: create compact and expanded view
  * task: display a specific task's date information on the calendar using color-coding (1) task name, 2) due date, and 3) live date)
  * task list: create color-coded sections of tasks
  
* A plan for the next 3 weeks and what you plan to accomplish each week
  * week 1: create base for calendar and the month picker, create example list of tasks to use and store in redux
  * week 2: create compact task component and expanded task component (right-hand detail pane), make the components interactive for user input
  * week 3: create color-coded list format and refine interactions

## Recommendations

* Keep the scope of your project small. A small, completed project is much better than a large, incomplete project. You can create a list of "nice to have" features that you can work on if you have time.
* Ensure you have plenty of buffer time in your schedule. Life events pop up, and tasks usually take longer than initially estimated.

## Submitting your Project Idea

1. Fork this repository
2. Add your project name, elevator pitch, wireframes, dependencies, task list, and plan to the Github repo (you can add a markdown file + images or links to images)
3. Create a pull request
