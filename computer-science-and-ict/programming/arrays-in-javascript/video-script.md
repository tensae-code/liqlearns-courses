# Video script — Arrays in JavaScript

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A JavaScript **array** holds **many values under one name**, in order: let marks = [70, 85, 60, 92];. Each value is reached by its **index** — its position counted **from 0**: marks[0] is 70, marks[1] is 85. The array's **length** (marks.length) counts its values, so the last index is always length − 1. An index outside the array answers **undefined** — JavaScript does not stop the script, which makes index discipline the programmer's own duty: indexes run 0 to length − 1, never 1 to length.
Arrays are worked **by loop**: a for loop running i from 0 to length − 1 visits every value in order — the shape behind totalling, searching and printing a list. Arrays **change**: a value is replaced by assignment (marks[2] = 65;), new values are added at the end with **push**, and removed from the end with **pop**. Malaysia's scripts put array and loop together for the page's real work — a class's marks totalled, a list of names printed, a highest mark found — the array is the script's memory of many, the loop its way of visiting them all.
