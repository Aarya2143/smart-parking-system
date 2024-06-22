Smart car parking system
ABSTRACT 
The proposed project aims to develop an automobile parking system using RFID technology and a PIC16 microcontroller. The system includes an RFID reader, an LCD screen, an IR sensor.The microcontroller checks the RFID tag's unique ID attached to the vehicle and signals the servo motor to open the gate if the ID is approved. The LCD display shows the availability status of parking spaces, and the IR sensor at the exit gate detects the vehicle's presence and updates the display accordingly. The system improves the parking slot's security, accuracy, and speed, and it is suitable for managing parking spaces in busy areas such as shopping malls, airports, and hospitals. The PIC16 microcontroller-based RFID-based auto parking system is a reliable and effective solution for parking lot management.

Scope of the Project
The project encompasses the design and development of an automated car parking system that leverages RFID technology and a PIC16 microcontroller. 
The system will incorporate key components such as an RFID reader, an LCD display, a servo motor, and an IR sensor. The RFID reader will be responsible for reading RFID tags attached to vehicles, while the LCD display will provide real-time parking status updates.
 The servo motor will control the gate, and the IR sensor will detect vehicle presence. Furthermore, the system will incorporate a database for storing vehicle information.

Algorithm:
1	Start.
2	A vehicle approaches the entrance gate.
3	Check if the parking slot is empty.
4	If the parking slot is empty, display a message on the LCD.
5	Deduct parking charges.
6	If the parking slot is not empty, display a message "Parking slot full."
7	End.

Result and Disscussion
Case 1. Parking is available: In the case where parking is available, an authorized vehicle (e.g., Srikanth) approaches the entrance gate. The RFID reader reads the vehicle's tag and displays a message on the LCD screen, such as " parking slot is empty " Srikanth can then view the available parking slots and choose an empty slot to park his car.
Case 2: Parking is not available: In the case where parking is not available, when all the parking slots are occupied, the LCD screen displays a message, such as "Slots Full”. In this situation, the gate of the parking lot remains closed and the vehicle cannot enter.

Future modifications:
1. Replace GSM SIM instead of RFID technology for managing parking by allowing only authorized vehicles to enter and displaying available parking slots for customers to quickly find an empty one.
2. Integration with a mobile app enhances the system by enabling users to reserve parking spaces in advance, receive real-time updates on availability, and make payments through their mobile devices.


 

                                            



