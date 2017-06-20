# AutonomousRCCar-CommunicationBridgeModule
This is a RTOS repository used for Autonomous RC Car

* Target platform for this RTOS was NXP 1769 based microcontroller board.The core of this project is based on FreeRTOS.
* The development platform was interfaced with an HC-05 bluetooth module and CAN transceiver MCP2551. 
* Bluetooth module communicates via UART protocol and the communication with Master, Motor, Obstacle avoidance sensor is achieved via CAN protocol
