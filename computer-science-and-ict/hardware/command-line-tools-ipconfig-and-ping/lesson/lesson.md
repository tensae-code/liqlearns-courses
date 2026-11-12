# Command-line tools — ipconfig and ping

## Do it first

A lab computer will not reach the shared printer. You want its network address and proof of whether the gateway answers. Write any tool names you know — then open the prompt.

## Sub lesson 1 — Opening the prompt — and ipconfig

On Windows, the **Command Prompt** is found by **searching the Start menu**, or by typing **"cmd" in the Run window**.

**ipconfig** is the **TCP/IP utility that verifies network settings and connections**. It tells a host's **IP address, subnet mask and default gateway**, among other information.

> **Teacher evidence (teacher guide — evidence, printed p. 110):** pupils practise the common network troubleshooting tools for real — **getting their own IP address and other network information from the command line** — and record the practical work in the laboratory.

[Picture 31317 — a command window showing an address block, beside a ping packet bouncing back]

## Sub lesson 2 — ping — send a datagram, get it back

**ping transmits a datagram to another host** named in the command — and **if the network works properly, the receiving host returns it**. The book pings the **default gateway: 192.168.0.1** in its figure. A returned ping proves the road between the two hosts is open; silence sends you back to the six basic problems.

[GIF 31335 — a ping packet travelling out to the gateway and its reply returning]

## Say it to your companion

Open the prompt for your companion — in words — read an ipconfig block aloud, then explain a ping to the gateway and what its return proves.

## Do It Yourself

1. Write both ways to open the Command Prompt.
2. Write the three things ipconfig tells about a host.
3. A ping to 192.168.0.1 returns; a ping beyond it fails. Write what that tells a troubleshooter.
