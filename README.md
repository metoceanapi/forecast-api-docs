# Forecast API - documents

Welcome to MetOcean Forecast-API documention.

Here are some documention links:
* [forecast-docs.metoceanapi.com](https://forecast-docs.metoceanapi.com)
* [forecast-demo.metoceanapi.com](https://forecast-demo.metoceanapi.com)
* [swagger-ui](https://forecast-docs.metoceanapi.com/swagger-ui/)
* [swagger.yml](https://forecast-docs.metoceanapi.com/swagger.yml)

In this repo you will also find some examples of how to use the Forecast-API (this is a work in progress still).  
Python:  
* [point_time.py](examples/point_time.py) shows you the response from a basic point time response
* [point_time_masks.py](examples/point_time_masks.py) shows you how to deal with masks / no-data values and the reason for why data was NULL.
* [point_time_units.py](examples/point_time_units.py) basic unit converstion for the variable's data.
* [point_time_wind_vectors.py](examples/point_time_vectors.py) how to convert vectors like wind and ocean into magnitude and direction.
* [point_time_rain.py](examples/point_time_rain.py) say the chances of rain in text found from the variable `precipitation.rate`

To run the examples you will need to set the ENV `apikey` e.g.
```
apikey=MYAPIKEY python3 examples/point_time_wind_vectors.py
```

