# Video script — Installing External Libraries in Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**External libraries** are packages written by others, beyond the standard library — for data work, the table and charting libraries of this unit. They live in a public **index (PyPI)** — a warehouse of packages, each with a name, versions and authors — and are fetched from it by name. Installing one makes its modules importable like any standard module; the difference is only the journey: standard modules arrive with Python, external ones are fetched, chosen and trusted by you.
The installer is **pip**: `pip install <name>` fetches and installs; the import in the program then works as usual. The care around it: install the **named** package (sound-alike names are a known trap — a mistyped name can fetch a stranger's, even a hostile, package), mind **versions** (a program may need the version its book used), install into the environment the work actually uses, and record what was installed so the work can be rebuilt on another machine. Jordan places installing inside the data lesson because the unit's first practical act is exactly this: before the data, the tools; before the tools, the trust.
