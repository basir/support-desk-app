# Build & Deploy Support Desk By Socket.IO & React.JS

![amazona](/frontend/public/support-desk.png)

## Features:

- beautiful UI by react bootstrap
- display chat button on public website to start chat
- browse website while chatting with admin
- pause/resume chat with admin
- display admin dashoard
- show all users with their status (online, offline, new message)
- enable live chat with selected user
- flag new messages from online users
- support multiple users from one single page by admin

## Run

```sh
# clone project in a folder
$ git clone git@github.com:basir/support-desk-react-socket-io-final.git
# open folder in vs code
$ cd support-desk-react-socket-io-final
$ code .
# run backend
$ cd backend
$ npm install
$ npm start
# run frontend in a new terminal
$ cd frontend
$ npm install
$ npm start
```

### Chat with admin

- open http://localhost:3000
- click on Chat with us
- send message to admin

### Admin dashboard

- open http://localhost:3000/admin
- select user in left panel
- send message to user

## Lessons

1. create-react-app
   - creating support-desk-app in desktop
   - npx create-react-app frontend
   - creating layout using react-bootstrap bootstrap
2. add routing
   - create home page
   - create admin page
3. create chatbox component
   - add chat with us button
   - handle click on button
   - show support box
   - create footer section for support box
4. create web server
   - create backend folder
   - npm install socket.io express
   - create express app
   - server html files in build folder
5. create socket server
   - handle connection to the server
   - define users array
   - handle onLogin
   - handle disconnect
   - handle onMessage
   - handle onUserSelected
6. Finish chatbox
   - handle login user
   - handle list messages
   - handle send message
7. create admin dashboard
   - handle login user
   - handle list messages
   - handle send message
8. publish to heroku
   - push to github
   - create heroku account
   - connect to github
   - deploy app

## Intro

Hello and Welcome to my coding course to build a support desk system from scratch . In this course You will learn the essential tools and skills to design, develop and deploy a support desk system website using React.js in frontend and Socket.io in backend.

My name is Basir and I’ll be your instructor in this course. I have 17 years of coding experience in international companies like ROI Vision in Montreal,
and now I am a coding instructor with more than 50 thousands students around the world.

I designed this course for anyone seeking to develop a support desk website. By the end of this course you’ll be able to design a responsive web site, implement a user-friendly frontend and build a scalable backend. Also you can deploy the website on cloud servers.

You need to open a code editor along with me and start coding throughout this course.
I teach you:

- Creating functional components by React
- Defining different screens from normal users and admins using React Router Dom
- Using React hooks to handle form inputs and scroll in elements
- Building real-time backend to exchange messages between users and admin by Socket.io

Also you will learn how to use deploy this applicaton in heroku and share your work on internet

I have used the latest version of react, node.js and socket.io in this course.

I designed this course for web developers and entrepreneurs.

If you are or want to a web developer, take this course to become a professional web developer, have a great project in your portfolio and get a job in 22 million job opportunities around the world.

If you are a entrepreneurs, take this course to to launch your startup and sell your products and services using this fully-functional ecommerce website and earn money from your idea.

The only requirement for this course is having basic knowledge on React js and Node.js

Feel free to take a look at the course preview and enroll if it is along with your ambitions.
