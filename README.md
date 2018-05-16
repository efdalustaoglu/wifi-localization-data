# WiFi Localization Data
This dataset represents bluetooth fingerprint that is collected in "Münchner Freiheit" Munich, Germany. It is collected with the device "Samsung Galaxy S6 Edge" by [Nikos Tsiamitros](https://github.com/ntsiam) and stored under Firebase Realtime Database. While collecting the data, "Dead Reckoning" technique is used and user's position is analysed carefully to make sure being at the same location in each visits.
The data collected only on 1 route but 20 different visits and each instance has
* Latitude
* Longitude
* Timestamp
* Normalized signal strengths of each wireless access points (if it's not seen on that visit, then the value is "-1")
