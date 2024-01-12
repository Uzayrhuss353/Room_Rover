# Room_Rover
As first year engineering students transitioning into university, we found ourselves struggling to manage time in between our professional academic lives and our day-to-day routines. More specifically, our lives had now consisted of having to clean our rooms and ensure no waste is left on our floors. Thus, in search of devising a solution to this common household chore, we took it upon ourselves to build and program an autonomous robotic cleaner that has the ability to pick up and store any waste left on the floor in a given room or space. Ultimately, the robot would allow for greater efficiency in our lives as it would simply require the user to turn the robot on, place it within a four-walled room and empty the waste bin at the end of the robot’s cleaning cycle.

## Key Features
- **Multi-scenario Exit Protocols:** If the bucket is full, robot travels until the end of the room, or there is an interruption during object detection, exit procedures occur, returning the robot to its start position.
- **Selective Object Detection Function:** Room Rover uses selective object scanning, minimizing the amount it has to travel (increasing time efficiency).
- **Spacing Function:** Developed space management algorithms, allowing the robot to navigate tight corners and confined spaces with adaptive turning and distance calculations, preventing wall collisions.
- **Perimeter Mapping:** During the initialization sequence, the rover traverses the perimeter of a confined space, mapping out room dimensions which are later used throughout object detection.
- **Claw Attachment:** Uses a custom-designed claw with a medium technic motor for picking up objects and dropping them into a bucket attachment.

## Specifications
- LEGO Mindstorms EV3 with touch, ultrasonic, and gyro sensors for object detection and precise turning
- Motor encoder values for large servo and technic motors used for maneuvering through room and for claw pickup precision.

<br>
![IMG_7891](https://github.com/Uzayrhuss353/Room_Rover/assets/98598868/e53916af-a1e3-497f-9de0-f4e152c04adc)
