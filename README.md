
# Sample pages.jsonl
![page1](https://user-images.githubusercontent.com/19539650/134803818-66fbdea9-c7da-4be2-a643-68202965d062.png)
![page2_1](https://user-images.githubusercontent.com/19539650/134803817-7ccf72c4-9f3f-4424-a586-bab6273c232d.png)
![page2_2](https://user-images.githubusercontent.com/19539650/134803816-bfcc5934-af8d-4ead-a68f-9c5bec7cef51.png)
![page3](https://user-images.githubusercontent.com/19539650/134803815-c16a5e9f-84d0-4f33-b1e7-6faf099be6f9.png)
![page4](https://user-images.githubusercontent.com/19539650/134803814-273313ad-9819-47a0-a6e2-b59fdedc6e58.png)

# openHASP_demo
Demo for openHASP config in OpenHab

Copy the respective files to the items, rules, sitemap, things and transform directory of your OpenHab server.
Make sure to update the IP-address for your MQTT-broker in the `openHASP_demo.things` file.

Once the files are loaded into OpenHab, go to the webpage on your openHASP esp. Navigate to `Configuration>MQTT Settings` and set the plate name to `openhasp` and update the MQTT Broker settings to your MQTT broker.
Restart the esp and the demo page should load automatically to your device.

More information can be found on the [wiki](https://haswitchplate.github.io/openHASP-docs/) of openHASP.

You need to have openweathermap and ntp binding installed. Edit openHASP-demo.items to fit your channels.

Weather Condition Icons are needed, else plate will end in rebootloop.
Download them from [here](https://haswitchplate.github.io/openHASP-docs/0.6.1/assets/users/openhasp-weathericons-day.zip), upload to plate, connect via telnet and run unzip /openhasp-weathericons-day.zip
