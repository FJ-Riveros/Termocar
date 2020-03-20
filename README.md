# Termocar

Details:

-The code of this project must be uploaded and executed with the IDE from Arduino, otherwise it can't be uploaded to the Node MCU.

-The 2WD car can be controlled remotely with the direction buttons displayed in the local Web, as long as the car stays within the range of the WI-FI connection.

-The car contains numerous sensors: Temperature, Humidity and an Atmospheric pressure. The collected data from this sensors is displayed at the local Web in real time.

-It contains additionaly an Ultrasonic sensor, which allows the car to move freely without the risk of collision.

-An experimental Algorithm has been created to allow the car to patrol a single room at a time, collecting data via the sensors mentioned earlier.
This Algorithm is based on the lectures from the Ultrasonic sensor, everytime the car faces a wall, it decides what to do, based on the past movement and in the lecture of the distance at the time. (Doesnt matter the size or the shape of the room).

-Working at the moment in an Algorithm that makes the car search the highest temperature areas in a house.