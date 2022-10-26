# HomeWizard-Wifi-Watermeter
A Python plugin for Domoticz that creates several devices for the HomeWizard Wifi Watermeter.

![HomeWizard Wi-Fi Watermeter](https://www.homewizard.com/wp-content/uploads/2022/06/Watermeter_front-400x400.png)

The [HomeWizard Wi-Fi Watermeter](https://www.homewizard.com/nl/watermeter) is a device that can be placed onto your watermeter. By default it sends all of its data to the HomeWizard servers but thanks to its local API you can read the device locally too. With this plugin you can use Domoticz to read the meter and store the data without using your internet connection.

# Devices

The plugin creates a total of 3 devices.
 1. An watermeter that shows your daily water usage in liters and totals in cubical meters.
 2. An watermeter that shows your current water usage in liters.
 3. A Wi-Fi signal strength meter that shows the current signal strength from the Wi-Fi Watermeter.

# Configuration

The configuration is pretty self explaining. You just need the IP address of your Wi-Fi P1 meter. Make sure the IP address is static DHCP so it won't change over time. Also don't forget to turn on the local API in the Homewizard Energy app.

| Configuration | Explanation |
|--|--|
| IP address | The IP address of the Wi-Fi Watermeter |
| Port | The port on which to connect (80 is default) |
| Data interval | The interval for the data devices to be refreshed |
| Debug | Used by the developer to test stuff |
