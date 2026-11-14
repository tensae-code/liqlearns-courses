# Breadth-First Search — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Why does breadth-first search need a queue rather than any pile of nodes?**
**Answer: The queue's first-in-first-out order forces fairness: nodes are worked on in the order they were discovered, so all of one layer is finished before the next layer starts — which is what makes the distances shortest.**

**2. (Sub lesson 2) Name one real job breadth-first search is right for, and say why.**
**Answer: Any 'fewest steps' job on an unweighted network — e.g. fewest stops between two stations, or the shortest chain of people joining two strangers — because the layer of first discovery is the smallest possible number of edges.**
