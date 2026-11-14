# Video script — Sign-Up and Login with Server Scripting

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Sign-up** (daftar) collects the new user's details on a form, **validates** them on the server (present, well-formed, the name **not already taken** — checked by querying the store), and **stores the account** as a record in the server file: name, email, and the password kept for checking. Sign-up is the unit's whole craft in one act: a form, a gate, a stored line. Its answer to the user is one of two — an account made, or the field-by-field reasons it was not.
**Login** takes a sent name and password and **checks them against the stored record**: the program queries the file for the name, compares the password with the stored one, and on a **match** lets the visitor in **as that user** — the following pages are built for them, their name at the top, their data the one shown. On a **mismatch** the login refuses with one careful message ('name or password not recognised') that does not say **which** part failed — a courtesy to the honest and a wall to the guesser. Malaysia's closing caution belongs to the real world: passwords in this unit's plain text files are a **school model** of the shape; real systems store passwords protected, never readable — the shape is what is taught, and the caution travels with it.
