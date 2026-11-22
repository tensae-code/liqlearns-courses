# Ethernet Frames and How Data Travels — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) What comes first in an Ethernet frame?**
a) The data  b) The preamble  c) The check sequence  d) The source address
**Answer: b) The preamble — The repeated opening bytes warn the receivers and synchronise them before anything else arrives.**

**2. (Sub lesson 1) The two addresses inside an Ethernet frame are —**
a) IP addresses  b) Web addresses  c) MAC addresses  d) Email addresses
**Answer: c) MAC addresses — The frame carries the physical MAC addresses of the sender and the receiver, six bytes each.**

**3. (Sub lesson 1) What does the type field of a frame announce?**
a) The size of the data  b) What kind of data is carried inside  c) The speed of the network  d) The name of the sender
**Answer: b) What kind of data is carried inside — For example, the code for an IPv4 packet, so the receiver knows which protocol takes over.**

**4. (Sub lesson 2) What are the last bytes of a frame, the frame check sequence, for?**
a) They are extra data  b) They are the address of the next network  c) They let the receiver detect a damaged frame  d) They carry the password
**Answer: c) They let the receiver detect a damaged frame — The receiver repeats the calculation; a different result means the frame is thrown away.**
