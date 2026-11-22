# Controlling a Robot Arm with an HMI — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 2) Trace one command — "bend the elbow" — through every stage from the user’s hand to the movement.**
**Answer: The user drags the elbow slider in the Tkinter window; the Python program sends the target angle over the serial (USB) link; the Arduino receives it and drives the elbow servomotor to that angle; the joint bends and holds. The user watches the result and judges the next command.**
