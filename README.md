
# Friend Finder - Node & Express Servers

## Live Site
https://still-stream-13278.herokuapp.com/
---

## Overview
- A Node & Express based web application that simulates a Spongebob Squarepants themed dating app.  A full-stack site that uses Express to handle routing.  
   
Friend Finder Home Page<a href="https://gyazo.com/87a52638a457384ebbcf6cf30613db16"><img src="https://i.gyazo.com/87a52638a457384ebbcf6cf30613db16.jpg" alt="Image from Gyazo" width="1872"/></a>

## Description
- Friend Finder implements friend matching based on the user's responses to a ten-question survey. The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). 

Friend Finder Survey Page<a href="https://gyazo.com/b958d3b97896c60924a78d5a94e8623f"><img src="https://i.gyazo.com/b958d3b97896c60924a78d5a94e8623f.png" alt="Image from Gyazo" width="1869"/></a>

- When the survey is submitted, the existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined.

Friend Finder Best Match<a href="https://gyazo.com/96a9ce6edbecc342c7c35441483d1c3a"><img src="https://i.gyazo.com/96a9ce6edbecc342c7c35441483d1c3a.jpg" alt="Image from Gyazo" width="1016"/></a>


## See All Friends
- The user can link to a view of all friends via the homepage.  
All Friends<a href="https://gyazo.com/cfeaaa1c4994ea6241a7f558a1178b06"><img src="https://i.gyazo.com/cfeaaa1c4994ea6241a7f558a1178b06.png" alt="Image from Gyazo" width="1025"/></a>

## Technologies Used
- Node.js
- express NPM Package https://www.npmjs.com/package/express
- path NPM Package https://www.npmjs.com/package/path
