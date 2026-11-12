# Top-down — modules and modularisation

## Do it first

One labourer's wages: you can already chart it — you built it in Flowgorithm practice. Now there are ten labourers. Do you copy the chart ten times? Or build the wage part once, as a module, and call it ten times? This lesson takes the second road, and names the thinking behind it.

## Breaking the big problem down

The top-down approach starts with the most general modules and works toward the specific: a bigger problem, hard to manage whole, is decomposed into smaller, manageable sub-problems, each solved individually as a module, then integrated into the complete solution. Dividing a problem this way is modularisation.

[Picture 20941 — Top-down — one wage problem, two modules]

## The ten-labourer wage build

The worked example upgrades the single-labourer wage chart into wages for 10 labourers as two modules: a CalculateWage subroutine — called with the flowchart CALL / subroutine symbol — that computes one net pay, and a main module that loops, calling CalculateWage ten times. One wage problem, solved once, used ten times: the module is the saving.

## Say it to your companion

Tell your companion, in your own words: top-down solving starts with the most general modules and works toward the specific — the ten-labourer wage problem becomes a main loop calling a CalculateWage module ten times. Then name the key words of this lesson — top-down solving, modularisation, a module, CalculateWage — and say what each one means.

## Do It Yourself

1. Break 'run the school shop for a day' into four modules.
2. Explain why CalculateWage is written once, not ten times.
3. Say where the loop lives in the wage build, and where the wage maths lives.
