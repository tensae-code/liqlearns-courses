# Writing and running a Python script

## Do it first

In the shell, every line needed its own Enter. Now the bigger move: write FOUR lines first, save them once, and run them ALL with a single command. Before you read on, guess: after that one command, where will the answer appear - in the window where you wrote, or back in the shell? The steps below are in the exact order to do them.

## Sub lesson 1 - New File - writing in the editor

**Step 1.** In the interpreter window, choose **New File** from the **File** menu. An **editor window** opens.

**Step 2.** Write your code in the editor window. Notice: **no `>>>` prompt appears there** - you are writing a document, not having a conversation.

Code written in the text editor is called a **script**, kept in a **script file**.

## Sub lesson 2 - Saving the script as a .py file

**Step 3.** Save the script from the **File** menu, with the **`.py` extension** - the ending that marks a file as Python. A script is not ready to run until it is saved.

## Sub lesson 3 - Run Module - the output appears in the shell

**Step 4.** Run the script with **Run Module** from the **Run** menu. The **output appears back in the IDLE shell** - not in the editor.

The worked script finds the area of a circle of **radius 3**:

```python
pi = 3.14
radius = 3
area = pi * radius * radius
print(area)
```

Four statements, run by **one command** - and **only the last statement produces output**:

```
28.26
```

[Picture 18107 - the four steps: New File, write, save as .py, Run Module]

[GIF 18108 - the Run Module click and the output appearing in the shell]

## Say it to your companion

Tell your companion the four steps in order - New File, write, save as .py, Run Module - and answer their two traps: "Where is the >>> in the editor?" (nowhere) and "Where does the output appear?" (back in the shell).

## Do It Yourself

1. Write the four steps in order on paper, from opening the editor to seeing output, with the menu names.
2. Write the circle script from the lesson, then say which of its four statements is the only one that produces output - and the exact output.
3. Your script will not run. It was never saved. What must you do, and with what extension?
