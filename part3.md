# Local Weather Part 3: Working with Authentication

## Prerequisite

> :warning: [Local Weather Part 2](part2.md) exercise

### You will be working off of your previous iteration of your Local Weather site.

## Requirements

### User Stories
**given** a user wants to view their weather information<br/>
**when** the user visits your application<br/>
**then** they should be presented with an authentication mechanism that allows login via email and password.

**given** a user wants to see saved forcasts<br/>
**when** the user visits your application<br/>
**then** they should only be able to see forcasts that they have saved.

**given** a user wants to delete saved forcasts<br/>
**when** the user visits your application<br/>
**then** they should only be able to delete forcasts that they have saved.

### Requirements
Make use of technologies we have used in class (jquery, grunt, browserify, and bootstrap) to build a site that satisfies the six user stories above.

You have free reign on styling but we do expect your project to look good (like portfolio worthy).  Use the bootstrap grid system to lay everything out.

Your code should be clean and readable, with single responsibility principle.

Spend a good amount of time on the API docs - figure out which API url you should use.  Use postman to test that route and see what is returned to you.  You get A LOT of information back.  You are welcome to display more of that information if you would like.



## Challenge: OAuth
**given** a user wants to view weather information<br/>
**when** the user visits your application<br/>
**then** they should be presented with an authentication mechanism that allows login via Google, Twitter, Facebook, or Github. Pick one, at a minimum, but if you want to add all, that would be impressive.