# Weather: iOS app for weather forecasting

Shows current weather of user's location. Connects with weather api to collect information. Show weather for current day. It shows the min and max temparature for the day

* Auto Layout is used to make the layout responsive for all iphone screen sizes of the app 
* Geolocatin is used to determine the position in Latitude/Longitude to determine the current position of the device.
* Weather data is derived from the Open Weather Map API (http://openweathermap.org/api) which is used to display weather information


Note: For this app to show a location on a simulator it must be set from the Debug menu from the Location option. When the current location of the device is requested permission can be granted by selecting 'Allow' from Settings or select "Allow" when prompted by the app the first time it is run.


## WeatherViewController.swift

Links the storyboard with weather and current location data and provides weather related services from getting the weather from open weather, fetching the current location to updating weather images


## DataModel
Contains a weather image updating function 


## Requirements

### Build

Xcode 8.0, iOS 10 or later

### Runtime

Xcode 8.0 Simulator (OS X 10.10.3)
iOS 10 or later

Copyright (C) 2017 DVT Inc. All rights reserved.
