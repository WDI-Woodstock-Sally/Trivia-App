# TriviaBase

## Table Of Contents

### Timeline

###### Spiking
###### Instructor Approved
###### MVP
###### Blockers
###### Problem Solving
###### Wins
###### Tech-Required
###### Additional Tech/Resources Introduced
###### Scaleable Features
###### Outstanding Blockers
###### Resources
###### The Team

## Timeline

### Spiking

#### Brain-storming

##### Coming up with the an initial idea and technology to be implemented:

When we begun to spike on ideas for where our project should head, we each came in with very different ideas. Our common ground being — we wanted to make something that felt both current while being interactive for users. At first, our intent was to utilize Twilio, by having an application where you called/texted in to obtain desired information. We iterated though our initial spiking process, resulting in a strong desire to create something that was more robust.

Then, inspiration hit, we could create a trivia game, that pulled in an existing API.

Jeopardy (the beloved trivia game) has an API that we planned on using. However, as the project moved forward and we introduced new technologies, we ended up dropping the API strategy.

Firebase was the newest technology we would stitch into our project.

The rest of the process, was coming up with an MVP and mapping out our UX goals.

#### Instructor Approved

#### A quick chat/pitch session with our scrum-master

##### Getting James on board with our idea:

Our instructor, James, received our initial trivia application pitch (and ended up being our scrum-master). With much excitement and total encouragement, he gave us three web resources to look into before we came back on Monday morning to start working.

##### Polling/Sockets
##### Firebase

## MVP

### MVP

#### Defining the MVP:

To allow a user to sign up for TriviaBase with just a simple username and password function, allowing the user to distinguish if they would be the primary admin for the game at play or simply a user competing against other members of TriviaBase. The game is populated with questions from a custom dataset, thus actualizing an experience, that can not be achieved from other trivia applications in the marketplace.

## User stories for MVP:

- A user signs up, adds their friends and enjoys playing trivia with their friend(s).
- A user signs up, adds their friends and then gets value from using the trivia game to connect with friends.
- A user signs up, joins a new community of people and gets value from using the trivia game to connect with new people.
- A user signs up, joins a new community of people and gets value from using the trivia game to learn new facts.
- A user uses the app, opens it, and connects with friends. As they are playing, there is a chatroom function running – the chatroom updates every 10 messages in real time.
- A user uses the app, opens it, and connects with other users. As they are playing, they put down their phone/computer and walk away from the game – for over 30 seconds. The game iterates over their turn while no points are given but they continue to stay active in the game.
- A user uses the app, opens it, and connects with other users. As they are playing, they play a few rounds and need to stop playing the game. The user signs out of the game and can log back in when they desire.
- A user signs back into the app, maybe inviting some of their friends and continues to play the games.

## Github Repo:

https://github.com/WDI-Woodstock-Sally/Trivia-App

## Entity Relationship Diagram:

![Figure 1-1](http://i.imgur.com/EtAxxwY.png "Figure 1-1")


## Several Wireframes:

![Figure 1-2](http://i.imgur.com/GPpNuoQ.jpg "Figure 1-2")

## Blockers

### First:

Authentication for users.

### Second:

Implementing Firebase.

### Third:

Creating an admin controller.

### Fourth:

Checking answers and making the game function seamlessly.

### Fifth:

Having the timer show up for non-admin’s when a game is in play.

### Sixth:

Restructuring HTML to integrate better with the skeleton boilerplate.

## Problem Solving

#### Justifying our solutions to problems we encountered along the way.

### Monday:

Investigating how to successfully implement and use Firebase to create an effective chatroom for use during game play. The hurdle we needed to overcome was constructing a Firebase database that could be integrated into our application.

### Tuesday:

Getting a handle on Firebase and having it populate the same question to each individual user. Using web-kit animations and sass to work with various views. Creating fields in .erb files so the backend integrate with the front-end.

### Wednesday:

Merge conflicts and working through them. Establishing the admin user while also, setting up the view to match the questions that appear on display. Having a timer that refreshed every 20 seconds over the correct column and not get hidden when it auto-refreshes. Populating questions via firebase and having them appear on the view.

### Thursday:

Adding the hamburger back into the navigation bar and having it render to the view. Rerouting pages to create an effortless user experience.

### Friday:

Burning down all of the html files to restructure the layout and style while pulling in skeleton. Merge conflicts.

## Wins

Small/large victories that were achieved throughout the week.

### Monday:

The task over the weekend was – to work on overcoming the most challenging feature of the application – our group deemed authentication as that feature. Through the use of referencing past rails authentication examples, we were able to overcome the obstacle and make use of authentication in our application.

### Tuesday:

Having the answers to a question show up in a random order – each time a question appears on the page. Tying in styling, with the front-end, by using columns and manipulating divs to have the views render to a page. Working with skeleton to see if the code structure made sense in regards to our workflow.

### Wednesday:

Implementing the rake commands and having it be successful. Working through various routes, allowing for a better understanding of how pages in the game will link together. Finding a solution to the UX-hamburger that is not in bootstrap, thus fulfilling the requirements of sticking to the skeleton broiler plate.

### Thursday:

Incorporated backbone for the scoreboard feature and was able to have scores render to the page. Working through the changes skeleton made to the styling and coming up with a direction for the overall aesthetic feel of the application.

### Friday:

Adding more questions to firebase and feeling good about the theme the application was taking on. Rebuilding the main erb.html file to work seamlessly with skeleton.



## Tech-Required
### Complete

- Rails for back-end

- Project must include authentication

- Project must include the use of an external API and/or an existing dataset - | based on use of Firebase |

- Create at least two JSON API route

- Additional Tech/Resources Introduced
Not required but implemented into the project

- Firebase

- Skeleton

- A custom dataset hosted on Firebase

### Scaleable Features

- Have the game runs itself
- The admin feature will not be needed for a game to run
- The game will stop playing once all users are off the site
- More than one game played on the host
- Playing without a login
- Disabling the chat feature

### Outstanding Blockers

- More than one game played on the host
- Playing without a login
- All the pages are running application.js
- File organization/refactoring


## Resources

- | https://css-tricks.com |
- | http://sass-lang.com/guide |
- | http://stackoverflow.com |
- | https://www.firebase.com/docs |
- | https://developer.mozilla.org/en-US/docs/WebSockets |
- | https://developer.mozilla.org/en-US/docs/Web/API/Node/contains |
- | https://developer.mozilla.org/en-US/docs/Web/Guide/API/WebRTC/WebRTC_basics |
- | http://responsivedesign.is/resources/frameworks/skeleton |

## The Team

- [Nickolas Selesky](https://github.com/nselesky)
- [Charlie Powell](https://github.com/CharlesPowell)
- [Dakoda Wogan](https://github.com/ddakoda)
