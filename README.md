# Fire-Alarm-system

Overview:

Fire Alarm System is a device that can capable of detecting the outbreak Of fire at any point in an instant time by monitoring environmental conditions associated with flames such as changes in temperature and gas levels. The project applies an Arduino microcontroller, temperature sensor, and a gas sensor got to work with respect to the arrangement of hints for detecting that there is fire.

Working Principle:

The Fire Alarm System continues working by checking the surroundings for any sudden rise in temperature or the presence of potentially dangerous gases. Sensors pass normal or digital notifications to Arduino, which then checks those values against predefined limits.
- Temperature Control: The temperature sensor constantly measures the room temperature. If the temperature exceeds a certain threshold, suggesting a fire, the Arduino triggers an alarm.
- Gas Detection: The gas sensor detects the concentration of gases in the air. If the gas concentration crosses an allowable limit, the system triggers an alarm, indicating a potential fire hazard.

System Operation:
1. Start: Powering on the Arduino initiates the sensors and other components.
2. Data Acquisition: The temperature and gas sensors continuously send data to the Arduino.
3. Data Processing: The Arduino compares the sensor data with predefined threshold values.
4. Alarm Activation: If the temperature or gas concentration crosses the threshold, the Arduino activates the alarm and notifies users through LEDs if it surpasses certain points.
5. Display: The LCD screen displays real-time temperature and gas levels, providing context on the environment.

Applications:
- Domestic Safety: This system is essential in homes, detecting fires early and providing instant alarms.
- Industrial Safety: It is used in factories and warehouses where the risk of fire is higher due to the materials handled.
- Public Buildings: Deployed for comprehensive fire prevention in schools, hospitals, and offices.

Advantages:
- Cheap: Uses inexpensive, easily available components.
- Real-Time Monitoring: Continuously monitors environmental conditions.
- Configurable: Threshold values can be adjusted based on specific needs or regulations.
