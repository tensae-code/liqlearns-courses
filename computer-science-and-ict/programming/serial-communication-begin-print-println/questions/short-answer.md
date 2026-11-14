# Serial Communication — begin, print, println — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What is serial communication for an Arduino?**
**Answer: Its voice — a stream of characters between board and computer, watched in the Serial Monitor**

**2. (Sub lesson 1) What opens the channel?**
**Answer: Serial.begin(speed), called in setup()**

**3. (Sub lesson 1) What is the standing speed?**
**Answer: 9600**

**4. (Sub lesson 1) What happens if the two ends' speeds differ?**
**Answer: The stream arrives as garbage**

**5. (Sub lesson 1) Why is serial the programmer's window?**
**Answer: Without it, a fault inside loop() is invisible; with it, the board reports itself**

**6. (Sub lesson 2) What does Serial.print do?**
**Answer: Writes the value and stays on the same line**

**7. (Sub lesson 2) What does Serial.println add?**
**Answer: It moves to a new line after writing — a stream of readings becomes a readable list**

**8. (Sub lesson 2) What can the board report with them?**
**Answer: Anything it knows — sensor numbers, pin states, the step it is on**

**9. (Sub lesson 2) What is the debugging habit?**
**Answer: Make the program say what it is doing — print the value, watch the truth, fix the accused line**

**10. (Sub lesson 2) Where does Indonesia teach this?**
**Answer: Grade 12, Bab 3 H — serial in Arduino programs**
