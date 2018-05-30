# Local Weather Part 2: Working with Firebase

## Prerequisite

> :warning: [Local Weather Part 1](./part1.md) exercise

### You will be working off of your previous iteration of your Local Weather site.

## Requirements

### User Stories

**given** a user wants to save weather information<br/>
**when** the user visits your initial view<br/>
**then** there should be an affordance (e.g. a star or link) that allows them to save a day's forecast

**given** a user wants to view all saved forecasts<br/>
**when** the user performs a gesture on an element that clearly states its purpose is to view saved data<br/>
**then** the user should be shown a list of all saved forecasts

**given** a user wants to delete one of the saved forecasts<br/>
**when** the user performs a gesture on an element that clearly states its purpose is to delete saved data<br/>
**then** the data should be deleteted and the user should be shown the list of all their remaining forecasts

**given** a user gets scared by the weather forcast<br/>
**when** the user performs a gesture on an element that clearly states its purpose is to be scared<br/>
**then** the data (use isScarry boolean) should be updated and the user should be shown the list of all their remaining forecasts

**given** a weather event is scarry<br/>
**then** the forcast should have a red background

### Requirements
Your app should have full CRUD!!!!
* **C**reate - Save a forcast
* **R**ead - display the list of saved forcasts
* **U**pdate - update isScarry boolean
* **D**elete - remove a forcast

Make use of technologies we have used in class (jquery, grunt, browserify, and bootstrap) to build a site that satisfies the five user stories above.

You have free reign on styling but we do expect your project to look good (like portfolio worthy).  Use the bootstrap grid system to lay everything out.

Your code should be clean and readable, with single responsibility principle.
