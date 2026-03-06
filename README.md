# Human computer interaction support device for disabled person using inertial measurement unit.
Making devices using Arduino combined with sensors

## I. Introduction
- The device is based on the design of a pair of glasses that everyone can use.
- The device is integrated with many sensors such as MPU6050 sensor, FSR402 module, type C charging circuit. In addition, the device also uses Bluetooth HC-05 module for wireless connection, convenient for users.
- Computer interaction support devices for people with hand disabilities using accelerometer sensors are installed to help people with disabilities interact with computers more easily without having to depend on others.

## II. Operation Principle
<img width="690" height="370" alt="image" src="https://github.com/user-attachments/assets/b6afd145-4ab0-4911-aa2a-6ca9a3d4bedf" />

- The device consists of two parts, the transmitter part and the receiver part.
- On the transmitter side, the Arduino Pro Micro microcontroller reads and processes values from the MPU6050 acceleration sensor and pressure sensor. The value will then be sent to the receiver.
- On the receiving side, the signal will be processed to control the activities of the computer mouse.

## III. Results
<img width="548" height="293" alt="image" src="https://github.com/user-attachments/assets/13014993-1bf2-45ec-abdd-b1ee9cfbf0b2" />


<img width="1235" height="927" alt="image" src="https://github.com/user-attachments/assets/23fd2070-ef6e-47d9-a59d-6c96fb4fce86" />

### Advantages:
- We can apply this device in many different areas of life.
- The device can integrate many other useful features to optimize usage.
- The device is compact, easy to install and replace, and the price is not too high.
- Simple to use and install. We just need to plug the receiver into the device we want to control, then we just need to wear the device on our head and move. If we use it continuously for a short time, we can adapt to the way of use easily.
- The device can be installed quickly, is easy to carry, can be used many times and is of good quality with no errors.
### Disadvantages:
- It is not possible to set different sensitivity levels for each user's habits.
- Although the hardware has been optimized to make the device lighter, if used for a long time, it still causes fatigue in both ears.
- When you first start using it, it will be a bit difficult because you are not used to it, so you need to use it continuously for a short time when you first start using it.

## VI. Conclusion
- Through many experiments, the program runs stably, the mouse movement speed is moderate so users can use it easily. 
- At first, when you are not used to it, the device can be difficult to use, but after using it for a short time, you can get used to it easily.


