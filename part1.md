
# Local Weather Part 1: Working with APIs

## Requirements

### API Information
Use the [OpenWeatherMap](http://openweathermap.org/API) API to build an application that meets the criteria listed in the User Stories section below.

Example API route:
```http://api.openweathermap.org/data/2.5/weather?q=London&appid=XXXXXX&units=imperial```

**Quick note about this API:** Temperature is returned in Kelvin. You will need to add to the query string to get results in Fahrenheit and Celsius.

* Fahrenheit: units=imperial
* Celsius: units=metric

### User Stories

**given** a user wants to view weather information<br/>
**when** the user visits your initial view<br/>
**then** there should be an input field to accept a zip code value

**given** a user wants to view weather information<br/>
**when** the user visits your initial view<br/>
**then** there should be a submit button next to the zip code field

**given** a user has entered in some text into the zip code field<br/>
**when** the user presses the enter key<br/>
**or** the user clicks the submit button<br/>
**then** the value should be validated as a zip code (5 digit number)

**given** the user has entered a valid zip code<br/>
**when** the user presses the enter key<br/>
**or** clicks the submit button<br/>
**then** the current weather for the provided zip code should be displayed, which includes

1. Temperature
1. Conditions
1. Air pressure
1. Wind speed
1. An affordance to view the forecast for the current day, or the next 5 days

**given** the user is viewing the current forecast<br/>
**when** the user clicks on the link to view the 5 day forecast<br/>
**then** the current data (see above), and the data for the next 5 days should be displayed


##### BONUS: 
**given** the user is viewing the current forecast<br/>
**when** the user clicks on the link to view the 3 day forecast<br/>
**then** the current data (see above), and the data for the next 3 days should be displayed

Hint: You might need to look into [MomentJS](https://momentjs.com/) for the bonus.


### Requirements
Make use of technologies we have used in class (jquery, grunt, browserify, and bootstrap) to build a site that satisfies the six user stories above.

You have free reign on styling but we do expect your project to look good (like portfolio worthy).  Use the bootstrap grid system to lay everything out.

Your code should be clean and readable, with single responsibility principle.

Spend a good amount of time on the API docs - figure out which API url you should use.  Use postman to test that route and see what is returned to you.  You get A LOT of information back.  You are welcome to display more of that information if you would like.
