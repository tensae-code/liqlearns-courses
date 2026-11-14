# Dijkstra's Algorithm — the Shortest Path — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 2) Why is it safe to declare the cheapest unsettled node's distance final?**
**Answer: Any other route to it must step out of the settled region through an unsettled node whose tentative distance is already at least as large, and the remaining edges add non-negative weight — so no undiscovered route can undercut it.**

**2. (Sub lesson 1) In the example, A's distance fell from 4 to 3. What route produced the 3, and why did the direct edge lose?**
**Answer: The route S → B → A costs 1 + 2 = 3. The direct edge S–A costs 4, so going the 'longer-looking' way through B is cheaper — edge count is not cost.**
