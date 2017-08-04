# weather_on_trip
A tool to check weather for a destination in a defined date range
- API used: Dark Sky API (https://darksky.net/dev/) 
- complete tutorial: http://www.codeastar.com/easy-python-weather-forecast-tool/
- around 40 lines of code in total (excluding space) 
- usage: python weather_on_trip.py [address] [Start Date in YYYY-MM-DD] [End Date in YYYY-MM-DD]

## Example
input:
_python weather_on_trip.py "paddington, london" 2017-08-05 2017-08-07_

output:
>Location: Paddington, Westminster, London, Greater London, England, United Kingdom
>
>
>2017-08-05 Saturday
>
>Min temperature: 12.73°C
>
>Max temperature: 18.25°C
>
>Summary: Partly cloudy in the morning.
>
>Chance of rain: 10.00%
>
>
>2017-08-06 Sunday
>
>Min temperature: 10.85°C
>
>Max temperature: 19.44°C
>
>Summary: Partly cloudy starting in the afternoon.
>
>
>2017-08-07 Monday
>
>Min temperature: 13.67°C
>
>Max temperature: 19.5°C
>
>Summary: Drizzle overnight.
>
>Chance of rain: 2.00%
