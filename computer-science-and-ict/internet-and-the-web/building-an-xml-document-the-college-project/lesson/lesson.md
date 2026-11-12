# Building an XML document — the college project

## Do it first

Start building now, before anything is explained: open a text editor, write the declaration, and write a College root element — not html, College. Save it under your own name with an .xml ending. You have just done stages 1 and 2. This lesson walks the whole build, stage by stage, in the book's order.

## Sub lesson 1 — Stages 1–3 — declaration, College root, empty departments (doing)

Build in stages, **saving after each step under your own name with an .xml extension**.

**Stage 1 — the declaration:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
```

**Stage 2 — the root.** A **College** root element — **instead of html**; this is an XML document, not a web page:

```xml
<College>
</College>
```

**Stage 3 — three empty Department sub-elements** inside the root:

```xml
<College>
  <Department/>
  <Department/>
  <Department/>
</College>
```

Save. You have a skeleton: one root, three empty branches.

[Picture 30914 — the college document at four growth stages, root to full departments]

## Sub lesson 2 — Stage 4 — names, numbers and data types (doing)

**Stage 4 — fill in each department.** Each department gets its **name** and its **number**, **attaching a data type to values — the number as an integer attribute**:

```xml
<Department>
  <Name>Computing</Name>
  <Number datatype="integer">1</Number>
</Department>
```

Do the same for the other two departments — their own names, their own numbers, the same shape. Save after this stage, and look at the growing document in **XML Notepad**: root, departments, and now names and numbers on each branch.

## Sub lesson 3 — Stages 5–6 — courses, then teachers and students (doing)

**Stage 5 — courses.** Grow each department with **courses**. Each course carries its **name**, its **number/code**, its **credit hour**, and its **teacher — with the teacher's name and ID number**. **Empty student and teacher elements** stand in the structure at this stage:

```xml
<Course>
  <Name>Web Authoring</Name>
  <Code>IT101</Code>
  <CreditHour>3</CreditHour>
  <Teacher>
    <Name>Example Teacher</Name>
    <Id>101</Id>
  </Teacher>
</Course>
```

**Stage 6 — people in full.** Finally add the **teachers' and students' own sub-elements, such as name, sex and age**:

```xml
<Student>
  <Name>Example Student</Name>
  <Sex>female</Sex>
  <Age>18</Age>
</Student>
```

Save the final document. View it in **XML Notepad** once more and watch the tree — as the GIF grows it, **department by department** — until the whole college stands structured in one document.

[GIF 30923 — the college tree growing department by department]

## Say it to your companion

Tell your companion the stages in order, as if guiding them to build the same document from nothing.

## Do It Yourself

1. Build a one-department version of the college document from nothing, in stages, saving each stage under a new name.
2. Add a fourth department to your project document, in the same shape as the other three.
3. Open your final document in XML Notepad and draw its tree on paper; check the tree against the document.
