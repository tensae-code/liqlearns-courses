# Subtotals and Grand Totals in a Worksheet

## Do it first

Take a list you know — the marks of a class, the sales of a market stall for a week, the harvest from several shambas. On paper, draw the list and mark where a total for each group would sit, and where one total for everything would sit. Do not name them yet. Keep the drawing — the lesson gives those two kinds of total their names and shows how a spreadsheet builds them for you.

## Sub lesson 1 — What subtotals and grand totals are

A long list answers one question badly: *how much in all?* is easy, but *how much per class? per shop? per month?* means adding the list in pieces. A **subtotal** is the sum of one piece — one group of rows that belong together. The **grand total** is the sum of the whole list, and it equals the subtotals added together.

In Microsoft Excel the **Subtotal** tool (on the Data tab) builds both for you. You tell it three things: the column to group by ("at each change in…"), the function to use (usually Sum), and the column to add up. Excel then inserts a subtotal row after every group and a grand total row at the end. Each inserted row uses the **SUBTOTAL** function, not plain SUM — SUBTOTAL deliberately ignores other SUBTOTAL rows inside its range, which is exactly why the grand total stays honest and never double-counts.

Kenya's Form 2 spreadsheet unit teaches subtotals inside worksheet data management, right after sorting and filtering — because a subtotal is a summary of groups, and groups only exist once the list is in group order.

In your mind's eye: a worksheet list of exam marks grouped by class, with a bold subtotal row after each class and a grand total row at the bottom.

[Picture 45706 — a worksheet list of exam marks grouped by class, with a bold subtotal row after each class and a grand total row at the bottom]

## Sub lesson 2 — Building subtotals — sort first, then outline and remove

Subtotals have one golden rule: **sort first**. The Subtotal tool starts a new group every time the grouping column's value changes as it walks down the list. On an unsorted list, the same class appears in five separate runs, so you get five wrong "subtotals" for it. Sorted by the grouping column first, each group is one unbroken run and every subtotal is true.

Once subtotals are in, Excel draws an **outline** at the left of the sheet. The level buttons do the summarising for you: level **1** shows only the grand total, level **2** shows the subtotals and the grand total — the summary view a head teacher or a shop owner actually reads — and level **3** shows every row again. The + and − buttons open and close single groups.

To undo, open the Subtotal tool again and choose **Remove All**: the inserted rows disappear and the plain list comes back, untouched. Subtotals are a view you build on a list, never a change to the data itself.

In your mind's eye: the left edge of a worksheet showing outline level buttons 1, 2 and 3 and plus/minus group buttons.

[Picture 45707 — the left edge of a worksheet showing outline level buttons 1, 2 and 3 and plus/minus group buttons]

## Say it to your companion

Tell your companion, in your own words: A subtotal is a total for one group of rows inside a list — sales for one class, one shop, one month — and the grand total is the total of all the subtotals together; a spreadsheet can insert them for you, but only after the list is sorted by the grouping column, and it writes them with the SUBTOTAL function so the outline can collapse and expand without breaking the sums. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: explain the difference between a subtotal and a grand total, with an example. Do this with a real example of your own, and write or say how you know it is right.
2. Show it, don't just say it: sort a list by its grouping column and insert subtotals with the spreadsheet's Subtotal tool. Do this with a real example of your own, and write or say how you know it is right.
3. Show it, don't just say it: use the outline levels to show only the subtotals, or the subtotals and the grand total. Do this with a real example of your own, and write or say how you know it is right.
4. Show it, don't just say it: remove subtotals cleanly and say why the list must be sorted first. Do this with a real example of your own, and write or say how you know it is right.
