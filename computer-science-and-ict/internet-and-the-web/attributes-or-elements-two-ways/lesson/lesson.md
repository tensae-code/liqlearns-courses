# Attributes or elements? Carrying the same information two ways

## Do it first

Two records, one fact — a person's gender. In the first, gender rides on the person element as an attribute. In the second, gender sits inside as its own element. Which one is correct? Hold your answer. This lesson's answer may surprise you.

## Sub lesson 1 — Attributes — the pair, and the quote rescue

An **attribute** is a **key-value pair on an element**, and its value is **always quoted — in single or double quotes**.

One craft case matters. If the value **itself contains double quotes** — a singer's name written with quotation marks inside it, for example — then **single quotes are used instead** to wrap the value:

```xml
<singer name='The "Star" Singer'></singer>
```

The inner double quotes survive because the outer pair is single. The value is unchanged; only its wrapping changed.

[Picture 30909 — two person records side by side, gender as attribute in one and as element in the other]

## Sub lesson 2 — The same information, two ways — and no rule

The same information can be carried **either way**. Gender, first as an **attribute** on a person element:

```xml
<person gender="female">
</person>
```

And the same gender as a **child element**:

```xml
<person>
  <gender>female</gender>
</person>
```

Both documents carry exactly the same fact. And here is the honest rule: **XML has no rule for when to use attributes versus elements.** The choice is the author's — make it, keep it consistent, and either writing is correct.

## Say it to your companion

Tell your companion both writings of one fact of your own, and the honest answer to 'which should I use?'

## Do It Yourself

1. Write a person record with gender as an attribute, then the same record with gender as an element.
2. Write a singer element whose name value contains double quotes, using single quotes around the value.
3. State the rule for choosing attribute or element. (There is none — say so.)
