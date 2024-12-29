# Arduino Radar Project

Welcome to the **Arduino Radar Project** repository! This project demonstrates the creation of a functional radar system using an Arduino microcontroller, ultrasonic sensor, and servo motor. The radar provides a visual representation of objects detected within a predefined range, showcasing real-time scanning and distance measurement capabilities.

## Features

- **Object Detection**: Detects objects within a specified range using an ultrasonic sensor.
- **Real-Time Scanning**: Continuously scans a nearly 180-degree area with precise angular control.
- **Visual Output**: Displays data on a graphical interface for easy interpretation.
- **Customizable Range**: Adjustable parameters for detection range and sensitivity.
- **Efficient Code**: Compact and optimized Arduino sketch.

## Components Used

- **Arduino Board**: Compatible with Arduino Uno, Mega, and other models.
- **Ultrasonic Sensor**: HC-SR04 or similar for distance measurement.
- **Servo Motor**: Controls the rotation of the ultrasonic sensor.
- **Optional Components**:
  - Breadboard and jumper wires for connections.
  - External display or computer interface for visualizing radar data.

## How It Works

1. The servo motor rotates the ultrasonic sensor to scan a nearly 180-degree arc.
2. At each step, the sensor measures the distance to the nearest object.
3. Data is sent to the Arduino's serial interface or a connected display.
4. A graphical interface can be used to visualize the scanning area and detected objects.

## Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/timurmert/embedded-arduino.git
   ```
2. **Upload the Code**:
   - Open the `radar.ino` file in the Arduino IDE.
   - Connect your Arduino board to your computer.
   - Select the correct board and port from the Tools menu.
   - Click the Upload button.
3. **Assemble the Circuit**:
   - Connect the components as per the schematic provided.
   - Ensure proper power supply and connections.
4. **Run the System**:
   - Monitor the serial output or use a custom GUI to observe the radar's performance.

## Applications

- Educational purposes to learn about sensors and microcontrollers.
- Object detection for small-scale robotics projects.
- Real-time scanning demonstrations.
- Interactive exhibits and DIY projects.

## Author

- **[Timur Mert USTA]** - Computer Engineering student with a passion for embedded systems and robotics.
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/timur-mert-usta)

---
