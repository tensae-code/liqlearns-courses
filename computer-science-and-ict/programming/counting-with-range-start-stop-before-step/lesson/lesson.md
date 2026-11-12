# Counting with range() — start, stop-before, step

## Do it first

Before you run anything, guess: what does `range(5)` give? Most people say 1 to 5, or 0 to 5. Run this:

```python
print(list(range(5)))
```

Output: `[0, 1, 2, 3, 4]` — verified. It starts at 0 and **stops before** 5. That stop-before rule is the whole lesson — and the mistake everyone makes once.

## Sub lesson 1 — The three forms of range()

**range()** returns consecutive integers. By default it **starts at 0**, **steps by 1**, and **stops before the specified end**. It takes one, two or three parameters:

```python
print(list(range(5)))
print(list(range(2, 5)))
print(list(range(1, 10, 2)))
```

Outputs — all verified:

```
[0, 1, 2, 3, 4]
[2, 3, 4]
[1, 3, 5, 7, 9]
```

So a range of 5 produces 0 to 4 — five numbers, none of them 5. A range can also start at a set value: starting at 5, it steps by 1 up to 8 in the keyed example — meaning range(5, 9). Watch the GIF: the counter steps along the number line and stops BEFORE the last number.

[Picture 31708 — three number lines, one per range form, with the end number faded as not included]

[GIF 31724 — a counter stepping along a number line, stopping before the last number]

[GIF 31731 — a counter adding 1 again and again inside a loop arrow until it reaches its target]

## Sub lesson 2 — Keyboard input is text — cast with int() first

Anything typed at the keyboard **arrives as a string** — text — even when the user types digits. Before text can be passed to `range()` as a number, it must be **converted with `int()`**:

```python
n = int(input("How far? "))
for i in range(1, n + 1):
    print(i)
```

With 5 typed, this prints 1, 2, 3, 4, 5 — verified. Note the `n + 1`: because range stops before its end, reaching the typed number itself needs the end set one higher.

Practice shapes from the unit: generate 51 to 70 with `range(51, 71)`, and steps of 10 from 10 to 100 with `range(10, 101, 10)`.

## Say it to your companion

Explain stop-before to your companion with the GIF: the counter climbs and halts before the end number — then say why counting TO a typed number needs n + 1.

## Do It Yourself

1. Write the output of range(5), range(2, 5) and range(1, 10, 2) from memory, then check with list().
2. Write a loop printing 51 to 70.
3. Write a loop printing 10, 20, … 100 — and explain the 101.
