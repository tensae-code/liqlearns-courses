# Command-line tools — tracert, nslookup and netstat

## Do it first

A website's name will not turn into a connection, and packets to a distant host vanish somewhere on the road. Write which question each failure asks — where do they vanish, and what address does that name own? Then meet the three tools.

## Sub lesson 1 — tracert and nslookup — the road and the name

**tracert determines the route data takes to a particular destination**, helping **find where packets are lost and where problems sit**.

**nslookup** is the **DNS utility** displaying the **IP address of a hostname, or the reverse** — useful for **DNS name-resolution problems**. The book shows it with **Google's DNS, 8.8.8.8**.

[Picture 31318 — a route drawn hop by hop, with one hop marked as where packets vanish]

## Sub lesson 2 — netstat — and standalone applications

**netstat shows the status of each active network connection** and **what services are running on a system**.

Many more tools exist **per operating system** — the Windows commands **change on Linux/Unix or Macintosh**, whose equivalents should be looked up. Beside the command line stand **standalone applications**: **packet sniffer, port scanner, protocol analyzer and Wi-Fi analyzer**.

> **Teacher evidence (teacher guide — evidence, printed pp. 111–112):** the guide's review set names the command-line network tools together — **ipconfig, ping, tracert/traceroute, netstat and nslookup**.

## Say it to your companion

Give your companion each tool's one question: tracert, nslookup, netstat. End with the guide's five-tool set in one breath.

## Do It Yourself

1. Write what each of the three commands shows, in one line each.
2. Packets die at the fourth hop. Write the tool that found it and what it proves.
3. Name the four standalone applications.
