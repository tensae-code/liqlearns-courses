# Video script — Local and Global Variables in Functions

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Variables declared **inside** a function (and its parameters) are **local**: each call gets its **own fresh copies**, no other function can see or change them, and they **stop existing** when the function returns. That privacy is a feature — functions cannot accidentally wreck each other's working values, which is why most variables should be local.
A **global** variable is declared **outside** every function and lives for the **whole run**: every function can read and **change** it, so a change made anywhere shows up everywhere — convenient for true whole-program data, dangerous as a habit, because any bug can come from any function. If a local variable shares a global's **name**, inside that function the name means the **local** one (the global is shadowed).
