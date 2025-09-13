![Logo](images/F498E0E6-CF5C-4971-8338-FA385F59BA8C.png "Logo")

# Home Assistant Setup

If you don't know how to setup an ESP device in Home Assistant, you're in the right place.   I won't go into how to setup ESPBuilder (there are plenty of other guides for this, but once that is available, here is how to setup SaltOwl



## Prerequisites

Before you begin, make sure you have:

* A compatible ESP device (ESP8266, ESP32, etc.)
* A USB cable to connect the device to your computer (Pro Tip: Be careful to have on that caters for data, and not just power, as this may trip you up for far too long...!)
* Home Assistant - already set up
* Your Wi-Fi network name (SSID) and password
* Google Chrome or Microsoft Edge (required for web flashing)



## Setup

### 1. Open ESPHome Builder
   From within Home Assistant, select ESPHome Builder from the left hand Menu in your browser.
   This tool allows you to compile and flash ESPHome firmware directly from the browser — no additional software needed.
   WIth ESPHome Builder selected, you should be presented with a screen _like_ this

![Adding a new ESP Device](../images/ESP-Home-1.png "Adding a new ESP Device")




### 2. Setup basic configuration
Once you add a new ESP degvice, you will be presented with the following screens.  

![Adding a new ESP Device](../images/ESP-Home-2.png "Adding a new ESP Device") | 
![Create Base Configuration](../images/ESP-Home-3a.png "Create Base Configuration") |
![Create Base Configuration](../images/ESP-Home-4.png "Create Base Configuration") |
![Configuration Created](../images/ESP-Home-5.png "Configuration Created")

Here you will have an opportunity to copy your encryption key.   While essential to keep private, there is no need to write this down, as you will have access to it later.

   
### 3. Connect Your ESP Device
   Plug your ESP device into your computer via USB.
   Click the "Continue" button on the ESPHome Web page.

> [!Note]
Your browser may ask for permission to access the USB device — allow it.

![Connecting to an ESP device](../images/ESP-Home-6.png "Connecting to an ESP Device")

![Download and Install Firmware to an ES{ device](../images/ESP-Home-7.png "Download and Install Firmware to an ES{ device")


### 4. Select Your Device
   Choose the correct serial port/device from the list and click Connect again.
   Once connected, the tool will show the status of the device.


> [!Note]
You may need to install a serial driver to find the relevant serial port and the ESP.  Installing these drivers are not unique to SaltOwl and guides are freely available to achieve this.

When complete, download the project and click Open ESPHome Web

![Connect to ESPHome Web](../images/ESP-Home-8.png "Connect to ESPHOme Web") |
![Select the Serial Port Connection](../images/ESP-Home-9.png "Select the Serial Port Connection")


### 5. Install ESPHome Firmware
   This will likely be the first time using the ESP device, so click "Install ESPHome" or "Install ESPHome on this device."
   This installs the ESPHome bootloader and prepares the device for configuration.


> [!Note]
This process may take a few minutes. Wait for the confirmation message once complete.

![Install Project File](../images/ESP-Home-10.png "Install Project File") |
![Install Project File](../images/ESP-Home-11a.png "Install Project File")

![Install Project File](../images/ESP-Home-13.png "Install Project File") |
![Congratulations](../images/ESP-Home-14.png "Congratulations")