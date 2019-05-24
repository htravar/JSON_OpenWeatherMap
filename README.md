# JSON_OpenWeatherMap
#code for current weather conditions

[jsoncontentimporter url=https://api.openweathermap.org/data/2.5/weather?q=Ljubljana,Slovenia&units=imperial&APPID=INSERTYOURAPIKEYHERE] {subloop-array:weather:0} {weather.description} {/subloop-array:weather}[/jsoncontentimporter]

#code for current temp in Fahrenheit

[jsoncontentimporter url=https://api.openweathermap.org/data/2.5/weather?q=Ljubljana,Slovenia&units=imperial&APPID=YOURAPPIKEYHERE] {subloop:main:-1}{main.temp} degrees{/subloop:main.temp}{/subloop:main}[/jsoncontentimporter]

