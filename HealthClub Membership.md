HealthClub Membership Management System - Team SSGG

[Link to Sprint Journal](https://docs.google.com/spreadsheets/d/1MdEVhpEMx-p_GFi4MJaIeXvuuJs_bqQ90AK59qRqIs0/edit?usp=sharing) 


[Link to Sprint Report](https://docs.google.com/spreadsheets/d/1nwmv9kunz8iIgvXmSPGLa6T65outaToUEaki6lPek0Y/edit#gid=0) 


[Deployed Application link](http://202shivakumar.s3-website-us-west-1.amazonaws.com/)

(Note: Open all sheets links using SJSU mail)


# Team Members:
1. Shivakumar
2. Sai Koushik
3. Geethika
4. Varshi Gadhamsetty

# Contributions

1. Shivakumar : Worked on backend - API calls for get class, add class, analytics, view all classes, log hours, enroll class.

2. Sai Koushik : Worked on backend - API calls for enroll- member and employee, check-in, check-out, view enrolled classes, view log hours.

3. Geethika : worked on frontend - created UI pages for the get class, add class, analytics, view all classes, log hours, enroll class

4. Varshi Gadhamsetty  : worked on frontend for member and employee, check-in, check-out, view enrolled classes, view log hours.

# Tech Stack:

- Frontend - ReactJS

- Backend - NodeJS

- Database - MongoDB

- Cloud Deployment - AWS

# Tools Used

- Version Control: Visual Studio Code, Git

- Tool used for drawing the Wireframes: page to wireframe

- Backend Deployment : AWS EC2 AutoScaling LoadBalance

# Scrum Meetings Schedule:
2 weeks Sprint - Every Friday 12:00 PM


# Documentation

- GitHub Repo
- Journal
- Project Dashboard for tracking tasks
- Sprint Sheet

# Diagrams

## Architecture Diagram:

image.png

## Deployment Diagram:

image.png

## Component Diagram:

image.png

## UseCase Diagram: - flow between the use cases happened between the registered users and admin.

image.png


# XP Core Values 

## Communication - 
I supported an XP core value throughout the project by contributing to the front-end development of the project. In addition, I took on the responsibility of overseeing all aspects of the team project's activities. This crucial concept aided us in completing the project's requirements within the designated timeframe and allowed us to track our progress at the end of each sprint.

## Simplicity - 
I played a significant role in upholding this XP principle by ensuring that the project's workflow was maintained throughout. Specifically, I was responsible for the program's backend and made sure that transparency, integrity, and dependability were maintained at all times. Drawing on my previous experience with the technological stack, I was able to help the team gain a better understanding of the project's overall concept. In addition, I provided guidance on task prioritization, leveraging my expertise to aid in the project's successful implementation.


## Feedback - 
I played a key role in promoting this XP core concept by providing regular feedback during the sprints. This helped us to generate new ideas and improve our work with each iteration. Additionally, I made a deliberate effort to reduce the time spent on interdependent tasks, leveraging my expertise and understanding to aid in the project's execution.

## Courage - 
I upheld this XP core principle by contributing to the project's front-end development. I value honesty and provided candid feedback to the team, offering practical advice to help us tackle each issue while considering all possible outcomes. I took the initiative to research and become familiar with the latest technologies required to complete the project, which proved useful during the initial setup phase. Additionally, I remained positive and motivated the team even in challenging situations, helping us to overcome obstacles and find solutions.

## Respect - 
We collectively upheld the XP principle of Respect by ensuring that every team member felt appreciated and valued while collaborating. All viewpoints and ideas were given equal respect and consideration, and each team member took the time to listen to one another. We all worked diligently to ensure that the project was of the highest quality and completed without delay. By embracing the other four XP values, we were able to create a culture that fostered respect for one another and ultimately led to our success.

# Steps to test and run the application

1. Clone the repository git clone 

2. Run server - node server.js
- For Backend Inside , run npm i then npm start

3. For Frontend Inside frontend folder, run npm install vue and run then npm start in client.js folder

4. The web application opens in the default browser


# AWS EC2 with Load Balancer Deployment Screenshots

## Amazon S3
![Screenshot (557)](https://github.com/varshishermi/testpro/assets/34976337/49c0e248-561e-4918-a8d5-39cacd259f8f)

## Elastic Beanstalk
Screenshot (558).png

Screenshot (559).png

Screenshot (560).png

## Auto-Scaling Group

Screenshot (561).png

# Why the MERN Stack
React JS is a highly efficient library for abstracting the UI layer, offering developers the flexibility to structure their code in a way that suits their needs. Compared to Angular, React's performance and rendering speed for UIs is superior.

MERN Stack's reliance solely on Javascript enables businesses to save time and money by hiring only Javascript experts, rather than specialists for each technology.

MERN Stack's use of open-source software and hardware provides developers with free access to a wealth of solutions for potential problems that may arise during a project. This functionality streamlines development by eliminating the need to reinvent the wheel.

# Why use MongoDB?

MongoDB provides support for multiple data hierarchies, allowing for greater flexibility in data modeling with the help of secondary indexes. With MongoDB's schemaless nature, there is no need to define the schema in advance. This enables developers to adapt and modify the data model as needed throughout the development process.

# Why NoSQL in a database?
NoSQL (Not only SQL) databases were developed to address the limitations of traditional relational databases in handling large-scale, high-velocity, and unstructured data. Unlike traditional relational databases that store data in tables with predefined schemas, NoSQL databases store data in a flexible and scalable format, such as key-value pairs, documents, or graphs.
One of the main advantages of NoSQL databases is their ability to handle unstructured and heterogeneous data types, such as social media posts, videos, and sensor data. They can handle large volumes of data, as well as support high-speed, low-latency operations, making them ideal for real-time applications.

# Hosting on Amazon EC2 with Load Balancer

Amazon EC2 (Elastic Compute Cloud) is a web service that provides scalable computing resources in the cloud. It allows you to create virtual servers in the cloud and run your applications on them. We can host your application on Amazon EC2 with Load Balancer and ensure high availability, scalability, and reliability.


# Feature Set

# Application Level - Health Club employee:

1. check in and check out members of the gym.

2. Signup non-members for free trails for new members.

3. Enroll new members and provide credentials to the user.

4. Analytics dashboard containing user activity summarized by location:
    - Number of visitors by hour each day, weekday, weekend
    - classes and enrollment by day/week
    - Hours spent by users in the gym - day, week, month



# Application Level - Enrolled and Logged in Members:

1. Each user has individual page containing individual class schedules that are added by health club employee.

2. sign up for classes in advance.

3. Log hours on Gym machines like Threadmill, Cycling, Weight training.

4. View Activities in the past week/month/last 90 days.

# Application Level - Non registered users:

Home page is viewed with Gym locations and classes alvailable, also membership details are also available.

## UI screenshots:

HomePage.png
login page.png
Enrol Member Page.png
Add Class Page.png
All Available classes.png
Showing Avilable classes based on date and place.png
Check In page based on phone number and gym address.png
Checkout page by gym address.png
log hours page.png
Activitys by week.png
activitys by month.png
Activitys by 90 Days.png



Visitors per day, weekday, weekend.png
Hours Spent by week.png
Hours Spent by month.png
Hours Spent by day.png
Classes Enrolment by day.png

















