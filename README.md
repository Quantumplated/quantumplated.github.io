# Report for Project 2 - Remixify
###### Introduction/Background 
The team was required to create a web-based or Android application. Team 7 came together to create an efficient, user-friendly, and high-quality application through which users will be able to connect their Spotify account and create or join groups to make a shared music playlist. Remixify automatically creates the shared playlists of groups, which are not able to be edited by users after they are created. Users’ favorite songs are queried directly from their Spotify account via the Spotify API and are specified by the user directly.

###### Motivation, Project Scope, Project Management 
Team 7 wanted to create a space for users to be able to access automatic collaborative playlists through Spotify. Remixify is perfect for late night jams with friends who want to quickly create an instantly enjoyable playlist or for discovering new songs from groups online. The project consists of a login page, a dashboard where users can connect their Spotify account and access the shared playlists of the groups that they are part of, and a search page where users can query the shared playlist of a group by name, even if they are not part of the group. 

###### Literature Review (What are related work out there?) 
We didn't find anything similar to our idea in terms of its simplicity in straightforwardness. Remixify helps multiple people in creating shared playlists.

###### Software Technologies 
Remixify required a variety of technologies for its successful completion. 

The frontend used React.js alongside VS Code as the IDE for development. We used a number of React libraries in order to implement the functionality needed, such as react-router-dom. To prototype the frontend, Figma was used to plan out all of the pages required and finalize the visual design for each webpage, which was then imported into the React project. The frontend interfaced with the backend for API calls and displayed the information received in its components.  

The backend used Express.js for simple routing, which called the Spotify Web API. Remixify was registered on the Spotify Developer Portal and users could authenticate directly with the service to avoid security vulnerabilities. The Express endpoints included endpoints for getting a Spotify user’s details, creating a playlist, adding songs to a playlist, getting a user’s top songs, and finally remixing the users’ top songs together. 

For testing we used a combination of selenium, postman and junit technologies. 

###### Project Lifecycle 
<img src="https://github.com/Quantumplated/quantumplated.github.io/blob/main/agile.jpg?raw=true" width=30% height=30%>

Team 7 utilized the Agile project lifecycle. Especially in the beginning, we focused heavily on code rather than design; we aimed to push out working software quickly in order to evolve quickly. In this sense, we greatly valued simplicity and speed. The team strived to keep “people over process” in mind and put ourselves in the consumers’ shoes throughout each iterative approach - this obligated us to keep in mind requirements will change which made us value responding to change over following a plan. 

###### Requirements (Functional and Non-Functional) 
The 

###### Design - Architecture and low-level level diagrams 
![alt text](https://github.com/Quantumplated/quantumplated.github.io/blob/main/diagrams.jpg?raw=true)

###### Testing - Test Strategy, test cases and outcomes 
Our testing strategy is a mixture of white box and black box testing. We utilized selenium for integration testing and postman for API testing for our Spotify Web API. 
This fell under our plan to test our application as functional black box. For white box testing, we are mostly focusing on unit testing and utilizing Junit to do that.
Integration testing will focus on different aspects of the application like finding playlists, finding friends, adding playlists to spotify from remixify, etc. Unit testing is focused on code logic and functionality. Things like when we remix friend playlists we don't add songs that are duplicates.

###### UI
The


