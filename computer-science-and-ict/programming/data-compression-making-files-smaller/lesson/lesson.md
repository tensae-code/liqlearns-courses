# Data Compression — Making Files Smaller

## Do it first

Write the word 'ha' one hundred times on paper. Now write 'ha × 100'. Both say the same thing — one takes two lines, the other takes a breath. Files are full of the first kind of writing. This lesson is the art of finding it and rewriting it the second way — and of knowing when you may throw a little away on purpose.

## Sub lesson 1 — Why files can shrink — repetition and lossless compression

Real data is full of **repetition**: a photo's sky is the same blue for ten thousand pixels in a row; a text repeats its common words and letters; a sound holds one note. Compression stores the pattern once with a note of how many times it runs, instead of storing every copy. **Lossless** compression uses only tricks like this — it removes repetition but loses nothing: decompressing gives back the original **bit for bit**. That exactness is compulsory where every bit matters — a program, a document, a set of results — which is why archive formats such as ZIP are lossless.

[Picture — a long ribbon printed with the same blue square a hundred times being folded into one square with a tag reading '×100']

## Sub lesson 2 — Lossy compression — throwing away what barely matters

**Lossy** compression goes further: it permanently discards detail the senses hardly notice — very slight colour differences between neighbouring pixels in a photo, sounds at the edge of hearing inside loud music. The decompressed file is *not* the original; it is a close neighbour of it. The reward is size: photos and music shrink to a small fraction of their lossless size, which is why the formats people share every day — JPEG photos, MP3 music — are lossy. The rule for choosing: if every bit must survive (text, programs, data), compress losslessly; if the file is for eyes and ears and small losses pass unnoticed, lossy buys the small size. Never lossy-compress the only copy of something precious — what is thrown away cannot be brought back.

[Picture — a photograph being lossy-compressed step by step — the file size falling at each step while the picture stays the same to the eye, until the last step pushes too far and blocks appear]

## Say it to your companion

Tell your companion, in your own words: compression removes repetition to store data shorter; lossless restores the original exactly and suits text, programs and data; lossy discards detail the senses barely miss, shrinks photos and music far more, and can never be undone. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: explain why real files can be compressed: they carry repetition. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: say what lossless compression guarantees, and name work it suits (text, programs, data; ZIP). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: say what lossy compression discards, what it suits (photos, music; JPEG, MP3), and why it cannot be undone. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: choose the right kind of compression for a given file and defend the choice. Do this with a real example of your own and write or say how you know it is right.
