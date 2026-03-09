**Smart Home with Google Assistant/Alexa**

**Overview**

This project is a smart home system built using NodeMCU ESP8266 and C++.

It allows home appliances to be turned on and off using Google Assistant, Alexa, or manual switches. The system connects to WiFi and uses Sinric Pro to link the hardware with cloud based voice control.

I built this project when I was in high school to learn how IoT systems work in real life. I wanted to understand how hardware, WiFi, and cloud services can work together to control devices remotely.

**My Role**

I built this project myself.

My work included:

- wiring the ESP8266 with the relay module
- setting up manual switches and relay outputs
- writing the control code in Arduino C++
- connecting the system to WiFi
- integrating Sinric Pro for voice assistant control
- testing both manual and remote switching

This project helped me understand how embedded systems connect with cloud platforms.

**Hardware Used**

- NodeMCU ESP8266
- 4-channel relay setup
- manual switches
- jumper wires
- WiFi network
- connected electrical loads or appliances

**Software and Tools**

**Programming language**

Arduino C++

**Development tool**

Arduino IDE

**Libraries and services used**

- ESP8266WiFi
- SinricPro
- SinricProSwitch
- Google Assistant

**How the System Works**

The ESP8266 connects to the local WiFi network.

Once connected, it communicates with Sinric Pro, which acts as the cloud service between the device and voice assistants like Google Assistant and Alexa.

Each relay is linked to a smart home device ID. When a voice command is sent, the cloud service passes the command to the ESP8266. The ESP8266 then switches the correct relay on or off.

The system also supports manual control using physical switches. If a switch is pressed, the relay state changes and the update is sent back so the cloud state stays in sync.

This means the appliances can be controlled in two ways:
- by voice command
- by manual switch

**Features**

- voice control using Google Assistant and Alexa
- manual control using physical switches
- WiFi based appliance control
- relay based switching for multiple devices
- cloud connected smart home system using Sinric Pro
- state sync between manual and remote control

**What I Learned**

From this project I learned:
- how IoT systems connect hardware with cloud services
- how ESP8266 handles WiFi communication
- how relays are used to control appliances
- how smart home systems manage device states
- how voice assistants can be integrated with embedded systems

**Future Improvements**

If I improve this project later, I would like to add:
- energy monitoring for each device
- a mobile dashboard for device status
- sensor based automation like temperature or motion control
- stronger home security features

**Why This Project Matters**

This project was important for me because it moved beyond basic Arduino work.

It helped me understand that programming is not only about code on a screen. It can also connect to real devices, wireless networks, and cloud platforms to solve everyday problems.
