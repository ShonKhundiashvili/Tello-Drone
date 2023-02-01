# Tello Drone with Hand Recognition
This project utilizes a Tello drone and hand recognition technology to control the drone through hand gestures.

# Summary
The code uses OpenCV, MediaPipe and DJITelloPy libraries to control a Tello drone using hand gestures. The MediaPipe library is used to detect the hand landmarks in real-time from the drone's camera feed, and the detected hand landmarks are then used to determine the state of the fingers (raised or not) and the direction of the fingers (left, right, up or down). The DJITelloPy library is used to establish a connection to the Tello drone and control its movements based on the finger state and direction determined by the MediaPipe library. The code runs in an infinite loop as long as the drone is connected and sends commands to the drone based on the finger state and direction.
