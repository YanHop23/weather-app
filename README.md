# weather-app
# How to make an API call 
# API call:
# http://api.openweathermap.org/geo/1.0/direct?q= {city name},{state code},{country code}&limit={limit}&appid={API key}
# "q"	required	City name, state code (only for the US) and country code divided by comma. Please use ISO 3166 country codes.
# "appid"	required	Your unique API key (you can always find it on your account page under the "API key" tab)
# "limit"	optional	Number of the locations in the API response (up to 5 results can be returned in the API response)
# form: http://api.openweathermap.org/geo/1.0/direct?q= {London} &appid={Api Key}
# Mu API Key "0a9501768bda819080aef6b9b0a12c9b"
# Example: https://api.openweathermap.org/data/2.5/weather?q=london&units=metric&appid=0a9501768bda819080aef6b9b0a12c9b