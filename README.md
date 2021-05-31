# BDD

# FEATURE 1: FILTER EVENTS BY CITY
## Scenario 1: When user hasn’t searched for a city, show upcoming events from all cities.
### SCENARIO 1: WHEN USER HASN’T SEARCHED FOR A CITY, SHOW UPCOMING EVENTS FROM ALL CITIES.
* Given user hasn’t searched for any city
* When the user opens the app
* Then the user should see a list of all upcoming events
## Scenario 2: User should see a list of suggestions when they search for a city.
### SCENARIO 2: USER SHOULD SEE A LIST OF SUGGESTIONS WHEN THEY SEARCH FOR A CITY.
* Given the main page is open
* When user starts typing in the city textbox
* Then the user should see a list of cities (suggestions) that match what they’ve typed
## Scenario 3: User can select a city from the suggested list.
### SCENARIO 3: USER CAN SELECT A CITY FROM THE SUGGESTED LIST.
* Given the user was typing “Berlin” in the city textbox and the list of suggested cities is showing
* When the user selects a city (e.g., “Berlin, Germany”) from the list
* Then their city should be changed to that city (i.e., “Berlin, Germany”) and the user should receive a list of upcoming events in that city

# FEATURE 2: SHOW/HIDE AN EVENT’S DETAILS
## Scenario 1: An event element is collapsed by default.
## Scenario 2: User can expand an event to see its details.
## Scenario 3: User can collapse an event to hide its details.

# FEATURE 3: SPECIFY NUMBER OF EVENTS
## Scenario 1: When user hasn’t specified a number, 32 is the default number.
## Scenario 2: User can change the number of events they want to see.

# FEATURE 4: USE THE APP WHEN OFFLINE
## Scenario 1: Show cached data when there’s no internet connection.
## Scenario 2: Show error when user changes the settings (city, time range).

# FEATURE 5: DATA VISUALIZATION
## Scenario 1: Show a chart with the number of upcoming events in each city.