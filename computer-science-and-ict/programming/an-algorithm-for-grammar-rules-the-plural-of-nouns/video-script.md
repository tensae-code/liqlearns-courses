# Video script — An Algorithm for Grammar Rules — The Plural of Nouns

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The inquiry asks for the plural **by algorithm**: start with the general rule (add -s), then branch on endings — nouns in **-al** mostly go to **-aux** (cheval → chevaux) with exceptions (bal → bals); **-eau, -eu, -au** take -x; seven famous families in -ou take -x too (bijou, caillou, chou, genou, hibou, joujou, pou) while their cousins take -s. The grammar lesson and the programming lesson are the same lesson: a rule, its cases, its exceptions — a decision structure wearing a French accent.
The inquiry builds the rule's synthesis tool — the **logigramme**: start with the word, test its ending diamond by diamond, exit with the plural. Building it forces completeness: every ending the class can find must have a path, and every exception its own labelled branch — a flowchart with a hole in it fails exactly the word that falls through. Grammar, drawn this way, stops being taste and becomes engineering: testable, completable, improvable.
