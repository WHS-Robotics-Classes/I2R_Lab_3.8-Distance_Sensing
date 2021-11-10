# Arduino 3.8 - Distance Sensing
## For this programming assignment we will use the HC-SRO4 distance sensor to initiate a change in a light display based on distance to an object.

### The conditionals `if()`, `else if()` and `else` will be needed to solve this problem.  Additionally, be sure to look up how to use the [HC-SR04 Ultrasonic Sensor](https://www.sparkfun.com/products/15569) before proceeding.  There are many tutorials on the internet that help you figure out how to use it.
---

### Step One: Build and Test the Circuit

As mentioned above, there are many tutorials available to learn to use this sensor.  Hook it up according to those instructions.  If you have not done so already, use the Serial Monitor to print the value recorded in centimeters from the sensor.  

In addition, connect a red, yellow and green LEDs to the Arduino to three digital output pins of your choosing.  Remember the resistors.

### Step Two: Write the Code

You functioning prototype should do the following:

- Print the dinstance in centimeters in the Serial Monitor in the manner shown below:
- Turn on the various lights according to the following rules (only one color is on at a time):
   - Green is on when distance is greater than 30 cm
   - Yellow is on when distance is between 10 and 30 cm
   - Red is on when distance is less than 10 cm.

![LEDs](https://user-images.githubusercontent.com/22602103/141160587-bc7c7cf3-101c-4bfb-af45-fff4f5441ba1.png)

### Step Three: Debug and Submit

Make sure your prototype behaves according to those directions above and as the demo in class does.   As in the previous assignments, make a new file here on GitHub. Name it 3.8-Distance_Sensing.ino and Commit it to the repository.  Record a video of your working prototype and submit on Canvas.

### Additional Challenges

For some extra credit, use the RGB LED instead of three individual LEDs but accomplish the same result.  Another option could be to initiate a change in another output device which we have previously used like a servo or one we have not like the piezo buzzer.  All requirements above should be met in additon to any extra actuators.
