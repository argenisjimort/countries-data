# Countries-dara-standalone

## URL
https://countries-data-standalone.fly.dev

PROJECT MADE WITH REACT,etting a countries list from helsinki's API
using a search field, whe you type caracters into in the text is compared ot the list of countries
if there are too many matches, then it asks you to type more
when the coincidences are 5 or less with a conditional if showsm you the name of the countries
with a button that give you the option to see that one country
when you select a country, or when there is only one coincidence then it display the country's info

it the info from the country itself its on the list previously gotten
however it as you see it will also render the country's capital's weather
they that done is by getting the coordinates on the capital (this is in the list)
and then with a weather API (openweathermap) it does a get request
and after getting the weather info, wiht another conditional it display it
showing a brief description, the temperature, and the wind speed
all in metric units btw.

also, it will get a little icon from the same openweathermap page
that matches the weather of the capital