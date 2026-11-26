# Controlling a Robot Arm with an HMI

## Do it first

Pick up a cup. Your shoulder rotated, your elbow bent, your wrist turned, your fingers closed — and your eyes kept reporting, and your brain kept correcting, the whole way. Now hand the job to a machine of motors and code. Which parts of what you just did must a motor perform? Which must a program decide? What will the human still do, and through what controls? Write the three lists. Keep them — the lesson builds the arm the SNT book builds: servomotors for the joints, an Arduino for the decisions, and a Python window as the human’s hands.

## Sub lesson 1 — The arm, its servomotors and the Arduino

A robot arm like the book’s **Braccio** is a chain of joints, and at each joint sits a **servomotor**: a motor that turns to an **angle it is ordered to** and holds that angle against load. Base rotation, shoulder, elbow, wrist, and the gripper that opens and closes — five or six servos, each with its own range, together giving the arm its reach. No servo knows anything about cups: each knows only its angle. The choreography — shoulder to this, elbow to that, then close the gripper — is decided above them, by the **Arduino** board: the embedded microcontroller that receives commands, and drives the servos in sequence and in time, so the arm moves as one creature rather than six twitches. This is the embedded-systems pattern in its purest form: motors as actuators, the board as the brain, angles as the language between them.

In your mind's eye: a robot arm with each joint circled and labelled — base, shoulder, elbow, wrist, gripper. And the Arduino board drawn at its foot with wires to every servo.

[Picture 46926 — a robot arm with each joint circled and labelled — base, shoulder, elbow, wrist, gripper. And the Arduino board drawn at its foot with wires to every servo]

## Sub lesson 2 — The Python interface that drives it

The human’s place in the loop is the **HMI — the human–machine interface** (in French, IHM). In the book’s build it is a **Python** window made with **Tkinter**: a slider or buttons for each joint, showing its current angle. The user drags the elbow slider; the program sends the new target **over the serial link** (the USB cable, used as a serial connection) to the Arduino; the board drives that servo; the arm bends. Command by command, the user composes a grip: approach, align, close, lift. The interface is not decoration — it is the half of the system where judgement lives, because this arm has no eyes: the human sees the cup, judges the angles, and corrects. Automate the sequence later if you wish — record the angles of a successful grip and replay them — but the book’s order is the honest one: first a human driving through an interface, understanding every stage a command crosses: mouse, window, serial link, board, servo, joint.

In your mind's eye: the chain drawn left to right: a hand on a slider, the Python window, the USB cable, the Arduino, the arm bending — one arrow per stage.

[Picture 46927 — the chain drawn left to right: a hand on a slider, the Python window, the USB cable, the Arduino, the arm bending — one arrow per stage]

## Say it to your companion

Tell your companion, in your own words: each joint of the arm is a servomotor that turns to a commanded angle; the Arduino receives commands and drives the servos in sequence; the human drives through an HMI — here a Python Tkinter window sending orders over the serial link — and supplies the eyes and judgement the arm lacks. Trace one command from mouse to gripper as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: name the arm’s joints and say what a servomotor does at each. Do this with a real example of your own — on the real Braccio kit if one is available, or traced stage by stage on paper — and write or say how you know it is right.
2. Show it, don't just say it: explain the Arduino’s role between a command and a movement. Do this with a real example of your own — on the real Braccio kit if one is available, or traced stage by stage on paper — and write or say how you know it is right.
3. Show it, don't just say it: trace one command from the user’s mouse, through the Tkinter window and the serial link, to the gripper. Do this with a real example of your own — on the real Braccio kit if one is available, or traced stage by stage on paper — and write or say how you know it is right.
4. Show it, don't just say it: explain why the human is part of this control loop, and what the arm cannot do without them. Do this with a real example of your own — on the real Braccio kit if one is available, or traced stage by stage on paper — and write or say how you know it is right.
