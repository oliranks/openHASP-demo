
# Sample pages.jsonl
![page1](https://user-images.githubusercontent.com/19539650/134781562-0b878060-aa78-46f2-8cb5-b7b7111e92a5.png)
![page2_1](https://user-images.githubusercontent.com/19539650/134781565-e700238f-060d-4741-a30b-9993e601d86c.png)
![page2_2](https://user-images.githubusercontent.com/19539650/134781747-3cc26a72-0cc6-4bc5-82c6-f06c0290b8a0.png)
![page3](https://user-images.githubusercontent.com/19539650/134781567-f9900ea1-a813-48f2-b873-92e440b5c17d.png)
![page4](https://user-images.githubusercontent.com/19539650/134781569-8913b774-fe14-4191-9962-51c5447eb7a0.png)

# openHASP_demo
Demo for openHASP config in OpenHab

Copy the respective files to the items, rules, sitemap, things and transform directory of your OpenHab server.
Make sure to update the IP-address for your MQTT-broker in the `openHASP_demo.things` file.

Once the files are loaded into OpenHab, go to the webpage on your openHASP esp. Navigate to `Configuration>MQTT Settings` and set the plate name to `openhasp` and update the MQTT Broker settings to your MQTT broker.
Restart the esp and the demo page should load automatically to your device.

More information can be found on the [wiki](https://haswitchplate.github.io/openHASP-docs/) of openHASP.
