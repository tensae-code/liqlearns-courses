# Linear Programming

## You do it first

A small workshop makes tables (x per day) and chairs (y per day).

- Wood: each table uses 2 units, each chair 1 unit; 100 units available.
- Time: each table takes 1 hour, each chair 1 hour; 60 hours available.
- Profit: RM40 per table, RM30 per chair.

How many of each should the workshop make for the most profit? Guess a mix, work out its profit, and see if your neighbour can beat it. Guessing will get you close — this lesson gives you the method that *proves* the best mix. (Malaysia, Additional Mathematics Form 5, Ch. 7 §7.3, printed pp. 234–244.)

## Sub lesson 1 — Writing the Limits

### Step 1 — The limits become inequalities

Every limit in the story becomes one inequality:

- Wood: 2x + y ≤ 100
- Time: x + y ≤ 60
- Counts cannot be negative: x ≥ 0, y ≥ 0

A set of inequalities that must all hold at once is a **system of linear inequalities**. (Malaysia, Additional Mathematics Form 5, Ch. 7 §7.3, printed pp. 234–237.)

## Sub lesson 2 — Drawing the Feasible Region

### Step 2 — The feasible region

Draw each boundary line: 2x + y = 100 (through (0, 100) and (50, 0)) and x + y = 60 (through (0, 60) and (60, 0)). A line is **solid** when the inequality allows equality (≤, ≥) and dashed when it does not (<, >). Test a point — the origin (0, 0) satisfies both limits, so the allowed side of each line is the origin side.

The overlap of all the allowed sides is the **feasible region**: here the four-cornered region with corners (0, 0), (50, 0), (40, 20) and (0, 60). Every point inside is a plan that breaks no limit. The corner (40, 20) is where the two lines cross — solve 2x + y = 100 with x + y = 60 and x = 40, y = 20 falls out. (Malaysia, Additional Mathematics Form 5, Ch. 7 §7.3, printed pp. 237–240.)

## Sub lesson 3 — Finding the Optimum

### Step 3 — The objective function

The thing you want to push to its best is the **objective function**. Here, profit:

    P = 40x + 30y

### Step 4 — The best point is a corner

The key fact of linear programming: **the optimum value of the objective function over a feasible region always occurs at a corner (vertex) of the region.** So there is no need to test the whole region — only the corners:

| Corner | P = 40x + 30y |
|---|---|
| (0, 0) | RM0 |
| (50, 0) | RM2000 |
| (40, 20) | RM2200 |
| (0, 60) | RM1800 |

The maximum profit is **RM2200**, at 40 tables and 20 chairs — the corner where both limits bite at once. Answer in the words of the problem: make 40 tables and 20 chairs a day. (Malaysia, Additional Mathematics Form 5, Ch. 7 §7.3, printed pp. 240–244.)

A minimum problem works the same way — the smallest corner value wins (a cheapest diet, a shortest route plan). If the region is unbounded, say so honestly: a maximum may then not exist, while a minimum still sits at a corner.

> **Tip — from us, not from the books:** when your feasible region has a corner that is not on an axis, it is always the crossing of exactly two boundary lines — solve that pair of equations and you have the corner. And if two corners tie, every point on the edge between them is equally good; say so in the answer.

## Say it to your companion

Explain to your companion why the workshop's best mix uses up all the wood AND all the time — and what it would mean if the best corner left one limit unused. Then have them explain why testing the corners is enough.

## Do It Yourself

1. A farmer plants x hectares of maize and y hectares of beans. Land: x + y ≤ 12. Labour: 2x + y ≤ 20. Profit: RM300 per hectare of maize, RM200 per hectare of beans. Write the system, shade the region, list the corners, and find the most profitable planting.
2. For the system x ≥ 0, y ≥ 0, x + 2y ≤ 16, 3x + y ≤ 18, find the maximum of C = 2x + 5y.
3. A diet must give at least 10 units of protein: 2x + y ≥ 10, with x, y ≥ 0 portions of two foods costing RM2 and RM3. Find the cheapest mix, and say why this region has no maximum cost.
