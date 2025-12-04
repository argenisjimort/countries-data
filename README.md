# Countries-dara-standalone

## URL
https://countries-data-standalone.fly.dev

PROJECT MADE WITH REACT,getting a countries list from helsinki's API.

Using a search field, whe you type caracters into in the text is compared ot the list of countries
if there are too many matches, then it asks you to type more

When the coincidences are 5 or less with a conditional if shows you the name of the countries
with a button that gives you the option to see that one country
when you select a country, or when there is only one coincidence then it display the country's info

If the info from the country itself its on the list previously gotten
however it as you see it will also render the country's capital's weather
they that done is by getting the coordinates on the capital (this is in the list),
and then with a weather API (openweathermap) it does a 'GET' request
using a private key for the API, and the latitude and logitude on the URL of the request.
After getting the weather info, with another conditional it displays it,
showing a brief description, the temperature, and the wind speed.
All in metric units btw.

Also, it will get a little icon from the same openweathermap page
that matches the weather of the capital