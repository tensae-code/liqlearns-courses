# Identifiers - the rules for naming variables

## Do it first

Judge these four names before you read a single rule: `2age`, `my*name`, `for`, `total&`. Something is wrong with every one of them - can you feel what? And is `student_name` fine? This lesson gives the four rules that decide every name, then returns to exactly these examples.

## Sub lesson 1 - The naming rules - first character, later characters

A variable's name is an **identifier**. It is valid only if:

- its **first character is a letter or an underscore** `_`;
- any **later characters are letters, numbers or underscores**.

Nothing else may appear in a name - no spaces, no symbols like `*` or `&`.

## Sub lesson 2 - Keywords and case

Two more rules:

- The name must **not be one of Python's keywords** - the **reserved words with predefined meanings** that the language keeps for itself.
- The name must **respect case**: **`x` and `X` are different identifiers**. Python treats a capital and a small letter as different characters.

> **Tip:** In the Python 3 this course teaches, `print` is **not** a keyword - it is a built-in function (that is why earlier lessons could use it as one). An old keyword list that still names `print` and `exec` as keywords is carrying Python 2 wording; the naming rules themselves stand exactly as taught here.

## Sub lesson 3 - Valid or invalid - and choosing good names

Now the worked judgements:

- `2age` - **invalid**: it starts with a digit.
- A name starting with `*` - **invalid**: `*` is not a letter or underscore.
- A keyword used as a name - **invalid**: keywords are reserved.
- A name ending in `&` - **invalid**: `&` may not appear in a name.
- `age`, `student_name`, `_mark` - **valid**.

And the style rule that follows the legal rules: **choose self-descriptive names** - names that say what the variable holds - **so programs stay understandable**.

[Picture 18111 - a row of names with ticks and crosses and the broken rule under each cross]

## Say it to your companion

Tell your companion the four rules in order, then judge four names they invent - for each invalid one, name the broken rule. Finish with the style rule and why it matters.

## Do It Yourself

1. Write three valid identifiers and three invalid ones; beside each invalid one, write the rule it breaks.
2. Is Total the same identifier as total in Python? Write the answer and the rule behind it.
3. Rename these variables self-descriptively: a holds a pupil's age, b holds a circle's radius. Write the new names and check each against all four rules.
