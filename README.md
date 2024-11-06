This project is designed to promote better ergonomics while using a laptop by alerting users when they are too close to the screen. It does this by monitoring the distance between the user’s face and the laptop and sounding a buzzer if the user is closer than 30 cm, reminding them to sit back for a healthier posture. An ultrasonic sensor measures the distance, while the buzzer provides the alert.

### Features

- **Distance Monitoring**: Continuously monitors the distance between the user's face and the laptop screen using an ultrasonic sensor.
- **Buzzer Alert**: Sounds a buzzer if the user is within 30 cm of the screen to encourage a safer sitting distance.
- **Flexible Sensor Integration**: Uses an analog-to-digital converter (ADC) for additional sensor input, such as a flex sensor, for further customization.

### Components

- **Ultrasonic Sensor (HC-SR04)**: Measures the distance between the user's face and the laptop.
- **Buzzer**: Provides an alert when the user is too close to the screen.
- **Flex Sensor (Optional)**: Can be added to provide additional ergonomic feedback.
- **Microcontroller (e.g., Raspberry Pi Pico)**: Controls the components.

### Prerequisites

- Microcontroller (e.g., Raspberry Pi Pico)
- Ultrasonic Sensor (HC-SR04)
- Buzzer
- Optional: Flex Sensor and additional wires for connections

### Circuit Diagram

- **Ultrasonic Sensor**: Connect the trigger pin to GPIO 21 and the echo pin to GPIO 20.
- **Buzzer**: Connect to GPIO 8.
- **Flex Sensor**: Connect to ADC pin 26.
- **Switch**: Connect to GPIO 9 to enable/disable the buzzer.

### Usage

1. **Power the Circuit**: Connect the microcontroller to a power source.
2. **Start Monitoring**: The system begins monitoring distance as soon as it is powered on.
3. **Listen for Alerts**: If the buzzer sounds, adjust your seating position to be at least 30 cm away from the laptop screen.

### Conclusion

This project encourages better posture and ergonomic habits by providing real-time alerts when a user is too close to their laptop screen. Simple components and code make it an effective solution for promoting healthy computing habits.

### Future Enhancements

- **Additional Sensors**: Add sensors to monitor other ergonomic factors, like seating position.
- **Smart Alerts**: Implement more subtle alert options, such as gentle vibrations or visual indicators, in place of the buzzer.
