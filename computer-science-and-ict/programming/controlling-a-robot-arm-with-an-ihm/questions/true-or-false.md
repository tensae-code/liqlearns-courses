# Controlling a Robot Arm with an HMI — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) One command from the interface moves the whole arm to "grab" in a single step.**
**Answer: False — The arm knows only per-servo angles; a grip is a choreography of single-joint commands in sequence.**

**2. (Sub lesson 2) The Python window and the Arduino are the same machine doing the same job.**
**Answer: False — The window runs on the computer (the human’s side); the Arduino is the embedded board at the arm, driving the servos.**
