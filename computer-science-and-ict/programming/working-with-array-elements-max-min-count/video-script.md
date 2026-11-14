# Video script — Working with Array Elements — Operations, Largest, Smallest, Counting

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The pattern: an **accumulator** starts at its neutral value (0 for a sum), the loop visits **every** element, and each visit **folds** the element in — total += a[i]. The same walk with a different fold gives products, sums of squares, or a transformed second array (each element doubled, say). The array itself is only read, never changed, in this family of tasks.
For **largest**: set max = **a[0]** (never 0 — an all-negative array would break that), then each element that **beats** max replaces it. **Smallest** mirrors it. For **counting**: a counter rises by one **only when the element passes a test** (negative? even? above the average?) — same walk, conditional fold. The links-pass reading splits this material further: inserting elements, finding largest/smallest and counting each get their own stocked lessons beside this one.
