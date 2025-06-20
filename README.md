# Smart-Street-Light 💡
**Introduction**
>Smart street lights are intelligent lighting systems that use IoT technology to enhance efficiency, safety, and sustainability in urban areas. They are equipped with sensors, communication modules, and software to collect and analyze data...

**Components Used:**

* NodeMCU
* Power Supply
* Light Dependent Resistor
* Relay
* IR sensor
* Light

**Platform Used:**

<li>Blynk with ios</li><li>ArduinoIDE</li>
<br>

**Operation:**

<li>The LDR sensor is used to detect whether it is daytime or night time. Since LDR sensor generates variable resistance based on the amount of light falling on it, it has to be connected like a potentiometer.</li>

<li>NodeMCU has one ADC pin (A0) which is connected to point between fixed resistance and one end of the LDR sensor. Since the LDR sensor gives variable resistance therefore variable voltage will be generated at A0 according to the amount of light falling on LDR.</li>
<li>IR sensors are used to detect if someone is crossing the street or not. It detects the obstacle or motion in the surrounding. The transmitter will transmit IR rays which will be reflected back if it falls on some object like person, animal, vehicles, etc. This method will save significant amount of electricity as the street light will only turns on if there is someone present in the Street.</li>
<li>The output of IR sensor gets high if detects presence of some object. This pin is connected to GPIO pin of NodeMCU so whenever the IR sensor detects someone passing through the street it triggers the Street light. In our case one LED will be turned on.</li>
<br>

**Key Features:**
>> <b>1. Energy Efficiency:</b> Smart street lights can adjust their brightness based on the time of day, weather conditions, or traffic volume, reducing energy consumption.

>> <b>2. Automated Lighting:</b> They can automatically turn on/off or dim based on ambient light levels or motion detection.

>> <b>3. Remote Monitoring:</b> Smart street lights can be monitored remotely, allowing for real-time monitoring and maintenance.

>> <b>4. Data Collection:</b> They can collect data on traffic patterns, pedestrian activity, and environmental conditions.

**Benifits:**
1. Reduced Energy Consumption: Smart street lights can significantly reduce energy consumption, leading to cost savings and a lower carbon footprint.
2. Improved Safety: They can improve visibility and safety for pedestrians and drivers, especially in areas with high crime rates or poor lighting.
3. Increased Sustainability: By reducing energy consumption and promoting efficient use of resources, smart street lights contribute to a more sustainable urban environment.
