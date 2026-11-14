# Video script — Creating an Application or Applet

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A Java **application** is a standalone program: it is started from the computer (in this course, run from NetBeans or the command line) and runs in its own right, opening with its **main method** — public static void main(String[] args) — the door every application enters by. Creating one means building the project, writing its classes with their main method, and running it to its own window or console. Nothing else hosts it: the application carries its own start and its own finish.
An **applet** is a Java program made to run **inside a web page**, hosted by the browser: it has **no main method** — instead the browser calls its life-cycle methods (it is initialised, started, painted, stopped) as the page is visited and left. Creating one means writing the applet class and naming it in the page that hosts it. Malaysia teaches the pair as the two deliveries of the SDLC's final work: the same language, the same care — one program stands alone, the other is a guest in a page, and the creator chooses by where the users will meet it.
