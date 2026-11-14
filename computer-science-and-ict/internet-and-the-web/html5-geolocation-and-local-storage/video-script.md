# Video script — HTML5 Geolocation and Local Storage

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Geolocation** asks the browser for the device's position — **latitude and longitude** — gathered from GPS, Wi-Fi or network signals. The browser **always asks the user first**; refuse, and the page gets nothing. Pages use it for maps, local search and delivery estimates, and a careful page must still work for users who say no.
**Local storage** gives each website a small store **in the browser**: **key–value pairs** of text (a name for each value, like a labelled drawer) saved by the page's code and **still there** after the tab closes and the browser restarts — settings, drafts and preferences live there. Its cousin **session storage** forgets when the tab closes. Storage is per-site: one site cannot read another's drawers.
