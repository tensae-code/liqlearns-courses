# Video script — Showing Bangla on a Web Page — Charset and Language

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Characters travel as numbers (the character-codes lesson), and the browser must be told which code table the numbers use. The declaration lives in the head: **<meta charset="utf-8">** — 'this page is encoded in UTF-8', the Unicode form that holds Bangla and every other script. With it, the page's bytes are read as meant; without it, the browser guesses, and guesses fail exactly on the scripts that need the declaration most. The charset line goes first in the head, before anything it must protect.
The page's other declaration names its **language**: the **lang attribute** on the html element — `<html lang="bn">` for a Bangla page. Lang does quiet, essential work: screen readers pronounce by it, search engines file the page under its language, browsers offer translation and choose fonts and hyphenation by it. Together the two declarations are the page's passport: charset says how its letters are coded, lang says what language they speak — and a page that carries both can travel the whole web and be read as written, in Dhaka or anywhere.
