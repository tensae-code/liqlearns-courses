# Video script — Simple Data Types and Their Ranges

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **simple (scalar) type** holds one value of one kind. The working family: **integer** (whole numbers), **real/floating** (numbers with a fraction), **character** (one symbol) and **string** (text), **Boolean/logical** (true or false), and in C++ the smaller and larger cousins — `short`, `long`, `float`, `double` — that trade range for memory. Armenia's Grade 10 book builds its 'Types. Composite structures' theme on them (Lesson 17): simple types first, then the composite types (array and structure) built from them.
A type stored in a fixed number of bits has a **range**: the smallest and largest values it can hold. An 8-bit signed integer holds −128…127; add 1 to 127 and it **overflows** — wrapping to −128 or behaving wrongly, silently. Reals trade differently: a huge range, but **limited precision** — digits beyond the type's count are rounded away. Choosing a type is therefore an engineering decision: big enough for the honest largest value (with room to spare), small enough not to waste memory, and its edges written into the program's tests.
