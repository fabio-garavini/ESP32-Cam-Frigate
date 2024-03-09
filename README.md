# ESP32 Camera integration with ESPHome and Frigate
This is a project example on how to connect an esp32 camera to Frigate.
The esphome-config.yaml is made for an Ai-Thinker ESP32-CAM, if you are using a different board edit it.

# Requirements
In order for this to work you need to have installed:
- ESPHome
- Frigate

If you already have a Home Assistant server you can easily install then from the Addons Store page.

# Compile Firmware with ESPHome
- Add a new device from the dashboard
- Replace all the contents of you configuration file with the esphome-config.yaml
- Save and upload
- connect to your esp camera through wifi
- open http://192.168.4.1
- Setup your wifi credentials

# Frigate setup
- Find your esp camera ip address
- Add to you frigate.yaml config file the contents from this repository
- Edit mqtt server information with yours
- Replace the esp-cam ip address
- Restart Frigate