# Weather fetcher

## Requirements
1. Create a command line utility that by given a place ('TelAviv IL') it will 
retrieve the current temperature in celsius for that place.
You can retrieve the temperature from Yahoo service or from a local file 
2. Continuously print dots while retrieving the temperature
3. Allow test mode: by given a --dummy flag, retrieve predefined temperature after 10 seconds

### Example usages
```
<app> TelAviv IL
<app> NewYork NY
<app> --dummy
```

## Yahoo API for weather
https://developer.yahoo.com/weather/

## Apache http client quick start 
https://hc.apache.org/httpcomponents-client-ga/quickstart.html

