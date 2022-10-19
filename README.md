# ESPHome OpenTherm

This is an example of a integration with a OpenTherm boiler using ESPHome and the Ihor Melnyk or DIYLESS OpenTherm Adapter
Based on rsciriano. For Bosch Gaz 6000 WBN 24H

Installation
Copy the content of this repository to your ESPHome folder
Make sure the pin numbers are right, check the file opentherm_component.h in the esphome-opentherm folder.

Edit the opentherm.yaml file:
Make sure the board and device settings are correct for your device
Flash the ESP and configure in Home Assistant. It should be auto-discovered by the ESPHome Integration.

