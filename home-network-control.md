# Home Network Control
Purpose of this project is to be able to control home network for:
* Guests
* Network performance
* Network usage control
* Filter Ads on the network level

### Features
We’re building a Raspberry Pi based project written in Python, that's able to:
##### Host a Guest network or act as a gateway to the existing guest network
* Connect the Pi to the modem/router and create a guest WiFi network, if no existing guest network exists.
* -> There should be no restriction to connect to the network, however if the user tried to use the network data, they should be redirected to a page for requesting access by entering a password given to them by the home-owner
* The home-owner should be able to change the password and have multiple passwords, if there are multiple guests
* -> Once a device signs-in, their access stays for rest of the day or 24 hour (depends)

##### Restrict device access
* -> Owner should be able to view the list of devices with name on the network
* -> Owner should be able to view the bandwidth consumption of each device in a given time-frame
* -> Owner should be able restrict bandwidth of certain devices or the network itself that the device is on.
* Owner should be able to block certain devices temporarily or permanently

##### Monitor network speed
* -> Device should be able to tell the incoming bandwidth right from the wire/modem
* -> Device should be able to store bandwidth data periodically to be analyzed later, if there are network problems at certain times or drop in bandwidth due to a certain user, etc
* -> Device should be able to tell bandwidth of the wireless network

##### Filter Ads to entire home network
* With click of a button, owner should be able to filter all the advertisement requests from a device.
* In case, some applications cannot run due to ad blocking, there should be a way to disable ad blocking for a certain device
* It’ll be nice to be able to group devices in category, so if all the media source like TV, etc needs to be able to show ad, in case everything stops working on them.
