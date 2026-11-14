# Video script — Adding Audio to a Webpage

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Audio is added with the **`<audio>` element**: its `src` names the sound file (or `<source>` children offer formats), and the page's visitor plays it — when the **`controls`** attribute is present, with the browser's own play, pause and volume bar. Without controls there is no honest way to start or stop the sound, so Jordan's rule is the web's courtesy: **a page's sound is the visitor's to command** — autoplay that ambushes is a fault, not a feature.
Browsers speak different **formats** (MP3 nearly everywhere; others beside it), so pages offer **more than one source** and a **fallback message** for browsers that can play none. Audio's fit is judged like video's: the file's **weight** against its purpose (a greeting against a concert), a **transcript or text alternative** for those who cannot hear, and a reason the page needs sound at all. The lesson completes the multimedia pair of the unit: video for the eye's motion, audio for the ear — each added by an element, each governed by the visitor's control.
