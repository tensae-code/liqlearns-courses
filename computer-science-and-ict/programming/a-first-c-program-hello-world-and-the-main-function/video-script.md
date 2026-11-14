# Video script — A First C Program — Hello World and the main Function

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A C program begins with **header lines** — `#include <stdio.h>` borrows the standard input-output library, the toolbox holding printf and scanf. Below it stands the **main() function**: `int main()` — the function the machine **starts at**, every time; a C program may hold many functions, but execution begins at main or nowhere. The function's body lives between **braces { }**, and each statement inside ends with a **semicolon** — C's full stop.
The first program's whole work is one statement: `printf("Hello World");` — print the words between the quotes to the screen. The book writes and runs it in **Code::Blocks**, the free development environment of the HSC course: create the project, type the program exactly, **build** (the compiler translates it — the translator lesson at work), **run**, and read the greeting in the console window. When the greeting fails to appear, the compiler's error list is the first debugging text a C programmer learns to read: it names the line, and the fault is almost always a missing semicolon or brace — the skeleton's small bones, already teaching their importance.
