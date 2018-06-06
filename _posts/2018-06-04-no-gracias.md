---
layout: post
title:  "No Gracias"
date:   2018-06-04
excerpt: "A fun networked card game developed for Windows using socket programming and winforms"
image: "/images/pic02.jpg"
---

### Motivation

This project was for a software engineering class that I took in college. We worked as a team of three people to develop a digital version of the popular card game "No Thanks!" called "No Gracias" (you can check out the rules for the game [here](https://boardgamegeek.com/boardgame/12942/no-thanks))
The inspiration for this project came from a presentation our professor had done earlier during the semester using "No Thanks!" and we remembered it being really fun. 
The decision to develop a Windows application was actually due to the team's eagerness to undertake a C# based project. Our team name that semester was Purple C#bras and we thought it was about time we were true to our name! 
Obviously, playing a card game against yourself is not too terribly fun and we decided that we definitely had to add networking into the application to enable multiple people to enjoy a game of "No Gracias" together.

### Contribution

I was responsible for writing the server side game logic and making sure that the client side and server side variables were keeping the same values. I also programmed the 
communication between the server and the client during gameplay. Any interaction the user had with the game from the moment a game instance was launched to the moment the final score was displayed was my responsibility. We used sockets to listen and send data on both server and client side. We used a two message system for communicating data where the first message indicated what kind of data the socket should expect to receive in the following message and then the actual data was sent (properly formatted) in a following message.

### Skills

This project was my first time attempting to write a program that uses socket programming and multi-threading. I learned a lot about multi-threading and cross-threaded calls to functions. In the span of about two months I had to familiarize myself with socket programming and the nature and concept of multi-threaded applications as well as deliver a 
functional application with intuitive user controls.

### Lessons Learned

In hindsight, the team