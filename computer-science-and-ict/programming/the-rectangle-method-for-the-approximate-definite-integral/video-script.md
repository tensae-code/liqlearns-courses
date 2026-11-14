# Video script — The Rectangle Method for the Approximate Definite Integral

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **definite integral** of f over [a, b] is the **area under its curve** (above the axis, on that span). The **rectangle method** cuts [a, b] into **n equal subintervals** of width **h = (b − a) / n**, stands a **rectangle** on each — its height a function value in that subinterval — and takes the **sum of the rectangles' areas** as the integral's approximation: Σ f(xᵢ)·h. As n grows and h shrinks, the staircase hugs the curve closer, and the sum approaches the true area — a method error the refinement literally pictures.
The height choice gives the method its three school forms: **left rectangles** take f at each subinterval's **left end** (under-shooting a rising function), **right rectangles** at the **right end** (overshooting it), and **midpoint rectangles** at the **centre** — whose errors from the two sides of the curve partly cancel, making it the most accurate of the three for smooth functions. For a monotone function, left and right sums **bracket the truth** between them — the integral's own separation interval — and their difference bounds the error of either.
