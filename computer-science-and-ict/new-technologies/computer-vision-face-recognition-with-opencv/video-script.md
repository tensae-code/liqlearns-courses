# Video script — Computer Vision — Face Recognition with OpenCV

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**OpenCV** is a **library** — ready-made code a Python program imports — for working with images and video: reading a picture into the program, processing its pixels, and detecting the patterns vision is made of. Kuwait's AI projects import it as the modules lesson taught: someone else's solved problems, called by name. The face project is the import with a face: `import cv2`, and the program can suddenly work on photographs, not just numbers the user types.
The project's program runs the vision pipeline: **load** the image, **detect** the faces in it (the Haar-cascade craft the database project also uses — rectangles drawn where faces are), then **recognise** — compare a detected face against the faces the program knows, and name the match or honestly report a stranger. Kuwait teaches the honesty as part of the build: a recogniser that guesses a name for every face is worse than one that says 'unknown', because the project's output will be believed and acted on.
