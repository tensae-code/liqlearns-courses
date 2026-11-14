# Conditional Statements in PHP

## Do it first

Egypt's Grade 11 book names this topic in the language of its Arabic twin — transactions and conditional sentences in PHP. It is the project's decision layer: the PHP page that checks before it stores, chooses what to show, and answers differently according to what it finds.

## Sub lesson 1 — If in PHP — the page decides

A PHP page without conditions does the same thing for every request; most real pages must **decide**. The **if statement** runs its block only when its condition is true, **else** offers the other road, and **elseif** chains further choices — the same add-decide pattern this course teaches in every language, now wearing PHP's clothes and standing in a web page. In the dictionary project the decisions are the site's manners: **if** the submitted term is empty, refuse it with a message; **else if** the term already exists, say so; **else** store it and confirm. Each branch is a promise the site makes about one case — and the cases must cover the world the page will actually meet.

[Picture — If in PHP — the page decides]

## Sub lesson 2 — Conditions on web data — presence, equality, permission

Web conditions have their own daily family. **Presence**: was this field sent at all, and is it empty? **Equality and comparison**: does this term already exist in the table; is this number in range? **Permission**: is this visitor the authorised user allowed to add — the condition that separates the Add_Term page's public face from its working face. The faults are the family's too: a condition written `=` where `==` was meant (assigning instead of comparing), branches in the wrong order so the general case swallows the specific one, and the case nobody wrote a branch for arriving on the first day. Egypt teaches conditionals inside the project, at the moment the pages first need to judge, because a conditional is only understood when something real depends on the branch taken.

[Picture — Conditions on web data — presence, equality, permission]

## Say it to your companion

Tell your companion, in your own words: A PHP page without conditions does the same thing for every request; most real pages must **decide**. The **if statement** runs its block only when its condition is true, **else** offers the other road, and **elseif** chains further choices — the same add-decide pattern this course teaches in every language, now wearing PHP's clothes and standing in a web page. In the dictionary project the decisions are the site's manners: **if** the submitted term is empty, refuse it with a message; **else if** the term already exists, say so; **else** store it and confirm. Each branch is a promise the site makes about one case — and the cases must cover the world the page will actually meet. Web conditions have their own daily family. **Presence**: was this field sent at all, and is it empty? **Equality and comparison**: does this term already exist in the table; is this number in range? **Permission**: is this visitor the authorised user allowed to add — the condition that separates the Add_Term page's public face from its working face. The faults are the family's too: a condition written `=` where `==` was meant (assigning instead of comparing), branches in the wrong order so the general case swallows the specific one, and the case nobody wrote a branch for arriving on the first day. Egypt teaches conditionals inside the project, at the moment the pages first need to judge, because a conditional is only understood when something real depends on the branch taken. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Runs its block only when its condition is true. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Else offers the other road; elseif chains further choices. Do this with a real example of your own and write or say how you know it is right.
6. Show it, don't just say it: It separates the page's public face from its working face — only the authorised user may add. Do this with a real example of your own and write or say how you know it is right.
7. Show it, don't just say it: Assigning instead of comparing — the condition stops testing and starts setting. Do this with a real example of your own and write or say how you know it is right.
