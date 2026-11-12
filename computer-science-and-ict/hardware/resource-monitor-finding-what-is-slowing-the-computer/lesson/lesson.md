# Resource Monitor — finding what is slowing the computer

## Do it first

The Performance tab says the CPU is straining, but not WHO is straining it. You need names. Write the tool you would open to get them. Then follow the book's route and read its CPU tab like a detective.

## Sub lesson 1 — Opening Resource Monitor and reading the CPU tab

**Resource Monitor** tracks **CPU, network, memory and disk in depth**: which processes are pressing on the CPU, how memory is being used, disk activity, and live network connections — including **which process listens on which port**.

Open it the book's way: **search its name in the Windows search box** and open it.

Its **CPU tab** groups what it finds:

- **Processes** — coloured by state: **running in black, suspended in blue, not responding in red**.
- **Services.**
- **Associated handles** and **associated modules** — which fill in for whichever process is selected.

[Picture 17710 — the Resource Monitor CPU tab with a heavy process highlighted and the End process menu open]

## Sub lesson 2 — Fixing the slow machine

For a slow machine, the book's cure is direct:

1. Find the **heavy application in the CPU column**.
2. **Right-click it** and choose **End process** to stop it.

Meeting an application you do not know? **Right-click it and choose Search online** to learn what it is — before you end anything you cannot name.

## Sub lesson 3 — The guide's greedy-app fix (teacher guide — evidence)

The teacher guide keys the same cure for a computer slowed by **one greedy application**: open **Resource Monitor**, find the application taking the **large share of CPU and memory**, and **stop it or restart it** (teacher guide, printed pp. 97–98).

Two books, one cure: find the greedy one, and stop or restart it — never end processes at random.

## Say it to your companion

Explain how Resource Monitor goes deeper than the Performance tab, read the CPU tab's three colours aloud with their meanings, and give the slow-machine cure in order.

## Do It Yourself

1. Write how Resource Monitor is opened, and name its four groups on the CPU tab.
2. A process shows in red. Write what the colour means.
3. An unknown program takes half the CPU. Write your two right-click choices and which you use first, and why.
