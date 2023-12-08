# Practical Assignment

Create a weather forecast application showing forecast for selected city for next 5 days .

## Functional requirements
*	Show forecast in form of list or a table
*	User can select city of interest in search box
*	Whisperer or autocomplete will help the user select a city when typing in the search box.
*	Application will respond to changing the city selection.
*	All times and values will be formatted based on browsers language

## Nonfunctional requirements
*	Single Page Application
*	Source code written in typescript
*	Application will store data in redux
*	Application will consume REST API of [Open Weather Map](https://openweathermap.org/api) (we provide API key)
•	Application will use redux-saga (preferably) or redux-thunk for handling API comunications
•	Autocomplete/whisperer can use of a predefined city list (available at [here](https://github.com/pavelbednar/weather-forecast-assignment/blob/main/city.list.json))

Bonus Task
•	Styles in LESS or SASS
•	Forecast in form of a chart
•	Use browser’s geolocation api to set initial data in app.

