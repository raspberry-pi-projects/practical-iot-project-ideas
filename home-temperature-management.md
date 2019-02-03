# Home Temperature Management
Purpose of this project is:
* Collect all temperature and humidity data and store periodically (indoors and outdoors)
* Be able to generate statistics on the data based on weather/season
* Be able to measure temperature drop-rate or rise-rate based on the weather/season
* Be able to talk to the thermostat
* Be able to recommend temperature settings and other feedback based on learnings from the data.

## Features

##### Device must be able to collect temperature and humidity readings from multiple locations via sensors
* Device should be able to connect with multiple sensors located in different parts of the house
* Device should have a good range to be able to connect with sensors in distant location
* Device should be able to notify if one of the sensor does not work anymore or frequently disconnects
* Sensor’s location are three bedrooms, two common areas, kitchen, basement, garage and one for outdoors
* Device should be able to gather accurate temperature readings from the sensors

##### Device must store the data in SD card
* Data must be stored in a database
* Data should be accessible only by select applications
* Data retrieval should be fast if the device has collected say one year of data already
* Device should not fail if the database is not found, instead setup the database
* Device should be able to notify of low memory in SD card

##### Device must be able to connect with home thermostat (Nest)
* Device should be flexible with the thermostat available.
* Device should be able to change thermostat settings including temperature and fan
* Connection with thermostat should be via a web app or mobile app

##### Device must be able to respond back via audio to owner only
* Device should be trained on owner’s voice during setup
* If this feature is turned off, device should be able to talk to anyone
* Device should be able to identify if the user is home
* Device should be able to lookup weather forecast for now, today, and whole week

##### Device must be able to send notifications to cell phone
* Owner must be able to setup notification on any device (Android/iOS)
* Owner must be able to setup notification on any number of devices
* Notifications can be text, WhatsApp or even push notification or anything else

##### There should be a phone application to provide summary, stats on data stored on the device
* This is a nice to have feature. I have an android phone.
* App should be able to communicate over WiFi
* Owner should be able to change settings that are permitted or the device is capable of.
* App should also be able to communicate when not at home

##### There must also be a web interface to show summary and stats
* Owner should be able to access the stats when not at home
* Owner should be able to change settings that are permitted or the device is capable of.

##### Learning
* Device should be able to schedule temperature changes based on user’s request
* Device should be able to make recommendations based on historical data
* Recommendation should be displayed on a periodic basis or user’s request
* Recommendations should be separate for the fan as well as temperature change
* Owner should be able to maintain the house temperature within certain range
* Outdoor temperature should contribute in the device’s suggestions
