### IotaWatt 4.8

This is forked from [boblemaire's github](https://github.com/boblemaire/IoTaWatt)

Changes to main repository:
* Changed the PCB to fit a ESP32 (In case one day) and to get the silk screen to show in the generated gurbers
* Created a sample config to integrate with HomeAssistant. This integration uses the rest sensor in HA and query’s the JSON data every few seconds. You are able to get all your channels as well as any output calculated values you have setup.

NOTE: The PCB s using a 1v refrence shunt so you need to edit the config.txt to add a refvolts item under the device.

>{
>	"device": {
>		"refvolts": 1.0,

Go to the main repository as boblemaire is doing some amazing work with this project.
