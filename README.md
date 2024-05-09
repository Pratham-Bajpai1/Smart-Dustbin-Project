# Smart Dustbin Using IoT 🗑️🔧

Welcome to the Smart Dustbin project! This project aims to create a working model of a smart dustbin that opens up automatically when an object comes into proximity. We achieve this by utilizing an Ultrasonic sensor and a Servo motor connected to an Arduino Uno.

---

## How It Works

The Ultrasonic sensor emits sound waves at a frequency above the range of human hearing. It then measures the time lapses between sending and receiving the ultrasonic pulse to determine the distance to a target. On the other hand, the Servo motor operates on the PWM principle, where its angle of rotation is controlled by the duration of the applied pulse to its control PIN.

---

## Installation and Setup

1. **Prepare the Dustbin:** Make two holes in the dustbin to accommodate the ultrasonic sensor's emitter and receiver.

2. **Mount the Ultrasonic Sensor:** Attach the ultrasonic sensor inside the dustbin.

3. **Create the Rotatable Cap:** Design a rotatable cap for the dustbin to facilitate opening.
   
4. **Upload the Code:** Connect the Arduino Uno to your computer using a USB cable and upload the provided code.

5. **Assemble Components:** Solder the Arduino Uno and battery inside the dustbin near the ultrasonic sensor.

6. **Connect Servo Motor:** Attach the servo motor to the Arduino Uno and solder it onto the cap of the dustbin.
---

## Usage

Once the setup is complete, the Smart Dustbin is ready for use. When an object comes near the dustbin, the ultrasonic sensor detects its proximity and triggers the Arduino Uno. The Arduino then signals the servo motor to open the cap of the dustbin, allowing the user to dispose of the waste conveniently.

---

## Demo
![Smart Dustbin Image](https://github.com/Pratham-Bajpai1/Smart-Dustbin-Project/assets/124435912/6745a42b-30f0-457c-830c-01071bca14d6)

![Smart Dustbin Demo](https://github.com/Pratham-Bajpai1/Smart-Dustbin-Project/assets/124435912/3e105b7b-07ba-4d0e-b357-de54332a730a)

## Contributing

Contributions to improve the project are welcome! 
