# Hack-Week-Project
A group project made for our CS4830 class

## Introduction
Group Name: Error 404
Group Members: Lee Offir (back-end), Austin Parrish (back-end), Jack Huffman (front-end), John Lund-Molfese (front-end) 
Background Information: We loved the in-class examples of Socket.io and wanted to create our own version of a chat app
## Problem:
Our users need an application to communicate quickly via easy-to-read, short messages.
## Solution
The solution is to create a website that serves as a chatroom. We would be able to visit our website and send messages between all the visitors of the page.
## Implementation
Our chat app used a variety of frameworks to reach the final product. We decided to use a framework of Node.js called Express.js to deploy our project at our specified port. Communication between users was handled with Socket.io, a framework that allows communication via Websockets that work both ways between the client and the server. Styling was handled with Bootstrap, and thus allowed us to make a mobile-friendly application.

A big problem that we faced was moving the project from localhost onto our server. We checked the developer console in Chrome and found that the browser was unable to connect to the server. Solving this issue involved changing the Javascript address and port to specify the server rather than the localhost. Implementing Socket.io was incredibly easy, but styling the page was a bit of a pain. This was solved by simple trial and error.
## Knowledge Gained
Overall, we gained experience creating and deploying a project using Node and Express, as well as creating pipelines for communication between multiple users of a webpage. We also gained valuable experience implementing a clean UI and optimizing a webpage for mobile devices.
## Future Work
We would like to connect a database to store chat messages, such as MongoDB or MySQL. We would also like to include a Google sign in feature that would auto-populate the username field.
