# File paths — absolute and relative

## Do it first

A music file sits four folders down on a school computer. A friend is standing at the top drive, seeing none of them open. Write the directions you would give your friend — every folder to open, in order — on paper. You have just written what this lesson names.

## Sub lesson 1 — Absolute paths — the full route from the root

A **path** lists, from a drive letter, which folders to open to reach a file. The full pathname is the chain of directory names ending in the filename.

[Picture 14106 — one file, two paths]

[GIF 14121 — following a path down the tree]

Walk the worked route slowly: start at the drive letter, open the first folder, then the next, then the next, until the filename at the end of the chain is the file you want. A pathname written this way — complete, from the root — is an **absolute pathname**. It works **from anywhere**, because it never depends on where you are standing.

One consequence matters: **identical filenames are allowed in different directories**, because their pathnames differ. Two files can both be named *song.mp3* and still be two different files — the chain of folders before the name tells them apart.

## Sub lesson 2 — Relative paths — from where you stand

A **relative pathname** is given from the **current (working) directory** — the folder you are standing in now. It names only the folders above or below that folder which lead to the file. It is shorter, but it only works from that one standing place: move to a different folder, and the same relative path leads somewhere else, or nowhere.

One trap, keyed in full (teacher guide — evidence in the lesson plan's words; the teaching is this): a **drive-relative** path such as *D:sources* — a drive letter with no root slash — still leans on a remembered current directory on that drive. Join it carelessly with that directory and the path **doubles**, becoming like *D:\sources\sources* — a common source of errors in programs and scripts. When a path must work from anywhere, write the absolute one.

## Say it to your companion

Read one absolute pathname to your companion, folder by folder, from the drive letter to the filename. Then stand in a folder you name and give the same file's relative pathname. Your companion says which is which, and why.

## Do It Yourself

1. On a real computer, open one file four folders down. Write its absolute pathname.
2. Stand in its grandparent folder. Write the same file's relative pathname.
3. The worked table — write each path's drive, folder, subfolder, file and extension: C:\Games\Solitaire\Solitaire.exe; E:\Assignment\IT\hardware.docx; C:\Program Files (x86)\Calculator.exe (teacher guide — evidence: the guide's worked key).
