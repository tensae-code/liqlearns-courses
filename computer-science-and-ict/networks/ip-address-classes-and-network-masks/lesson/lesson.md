# IP address classes and network masks

## Do it first

Take three addresses and look only at the first number of each. That first number alone tells each address's class — its family, its size, its mask. Learn the five families.

## Sub lesson 1 — Five classes by first octet

The IPv4 space is divided **by first octet** into five classes: **A (first octet 0–127** — the **first octet only is the network part**: **few networks, very many hosts**), **B (128–191** — **two network octets**), **C (192–223** — **three network octets**: **many networks, few hosts each**), **D (224–239, multicast)** and **E (240–255, experimental)**. Only **A, B and C serve as host addresses**.

[Picture 14538 — the five-row IP class chart]

## Sub lesson 2 — Network masks — network from node

A **network mask separates the network portion from the node portion**, with defaults **255.0.0.0 for A, 255.255.0.0 for B and 255.255.255.0 for C**. The exercises **find the class of given addresses, rewrite addresses in binary, and read a real networked computer's class and mask**. The guide's key works class-finding **two ways — by first-byte range (128–191 = B, 192–223 = C, 240–255 = E) and by leading bits (0 = A, 110 = C, 1110 = D)** (teacher guide — evidence).

## Say it to your companion

Explain ip address classes and network masks back in your own words — the one thing, the picture part by part, and one example of your own. Your companion asks one question; answer it from the lesson.

## Do It Yourself

1. Give the first-octet range of classes B and D.
2. State the default masks of A, B and C.
3. Find the class of 137.142.208.49 two ways: by range and by leading bits.
