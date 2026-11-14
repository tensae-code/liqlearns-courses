# Subrange Data Types in Pascal — sub lessons and depth

This file is the lesson's depth record, expressed as its SUB LESSONS. Practice is tied to the learner's skill number. The questions live in the type files; this file is the by-sub-lesson view.

## Sub lesson 1 — A slice of a type — first..last
Sub lesson 1 questions from the type files. Pass mark: By its first and last values — type TDayNum = 1..31;; Ordinal types — integer, char, boolean, enumerations; 'A'..'Z'; The data's real limits — the promise the type makes; No — only 1 to 31.

## Sub lesson 2 — The guard at the border — range checking
Sub lesson 2 questions from the type files. Pass mark: The guard that stops the program with an error when a value steps outside the slice; An error at that line — the program stops instead of carrying a poisoned value; Hold it silently — the error would surface far away, unfindable; Errors are cheapest where they are made; No — it borrows its host ordinal type's values, sliced.
