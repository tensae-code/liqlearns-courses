# Video script — Robot Road Map — Several Sensors and Nested Conditions

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The road-map robot reads its **sensors together**: touch for contact, ultrasonic for the distance ahead, each sense answering its own question in the same moment of the journey. Measured **distances are kept in variables** — the gap to the wall, the length of the last leg — so the program can compare, remember and compute, instead of reacting only to the instant. A robot with variables has a short memory, and a road map needs one.
Road decisions are **nested**: **if** the way is clear, **then if** the distance is shrinking, slow — otherwise hold speed; **else** turn. A condition inside a condition is how a program answers a world that asks two questions at once. Kuwait places nesting here, in the robot, because the road makes its need visible: single conditions drive into walls that two questions would have avoided.
