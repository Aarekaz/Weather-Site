# A simple Weather Site!
This is a Simple project that I did using [Free Code Camp Weather API](https://fcc-weather-api.glitch.me/). Its a basic way to interact with a API. 

The site sends the Longitude and Latitude to the api as ```https://fcc-weather-api.glitch.me//api/current?lon=:longitude&lat=:latitude```. Then the API sends back a respose like :

```"coord":{ "lon":159, "lat":35 }, "weather":[ { "id":500, "main":"Rain", "description":"light rain", "icon":"https://cdn.glitch.com/6e8889e5-7a72-48f0-a061-863548450de5%2F10n.png?1499366021399" } ], "base":"stations", "main":{ "temp":22.59, "pressure":1027.45, "humidity":100, "temp_min":22.59, "temp_max":22.59, "sea_level":1027.47, "grnd_level":1027.45 }, "wind":{ "speed":8.12, "deg":246.503 }, "rain":{ "3h":0.45 }, "clouds":{ "all":92 }, "dt":1499521932, "sys":{ "message":0.0034, "sunrise":1499451436, "sunset":1499503246 }, "id":0, "name":"", "cod":200 }```.

You can see it in action here: https://aarekaz.github.io/Weather-Site/

It is very easy to use and fun to play around with.
