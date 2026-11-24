# Modular Programs with Arrays

## Do it first

A class's marks sit in an array; three jobs must be done on them: read them in, average them, print them. Malaysia's programming chapter finishes by building that program in modules. In this lesson you write one job per subprogram — and let the main program conduct.

## Sub lesson 1 — One job per subprogram

A **modular program** divides its work among **subprograms**, each doing **one job** well. Around an array, the natural modules are the array's career: a **fill** module that reads values into the array, a **process** module that works on them (a total, an average, a highest), and a **print** module that presents them. Each module is written and tested **on its own**, with the array handed to it — a module that fills must not also average, because a fault then has two homes and a test cannot tell them apart.

In your mind's eye: one job per subprogram.

## Sub lesson 2 — The main program conducts

The **main program** shrinks to a conductor: declare the array, then **call** the modules **in order** — fill, process, print — passing the array (and its size) to each. Values a module works out for the conductor are **returned** or left in shared results as the design states. Malaysia's gain is the chapter's closing argument for modules: change how printing looks and only the print module is opened; test the averaging and only the process module is run. The array is the shared stage; the modules are the actors; the main program is the order of the play.

In your mind's eye: the main program conducts.

## Say it to your companion

Tell your companion, in your own words: A **modular program** divides its work among **subprograms**, each doing **one job** well. Around an array, the natural modules are the array's career: a **fill** module that reads values into the array, a **process** module that works on them (a total, an average, a highest), and a **print** module that presents them. Each module is written and tested **on its own**, with the array handed to it — a module that fills must not also average, because a fault then has two homes and a test cannot tell them apart. The **main program** shrinks to a conductor: declare the array, then **call** the modules **in order** — fill, process, print — passing the array (and its size) to each. Values a module works out for the conductor are **returned** or left in shared results as the design states. Malaysia's gain is the chapter's closing argument for modules: change how printing looks and only the print module is opened; test the averaging and only the process module is run. The array is the shared stage; the modules are the actors; the main program is the order of the play. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Subprograms — each doing one job well. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Fill it, process it, print it — the array's career. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: On its own, with the array handed to it. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: A conductor — declare the array, call the modules in order. Do this with a real example of your own and write or say how you know it is right.
