# Academic Dashboard 2026-27

**Ajeenkya D Y Patil University · School of Engineering**

One page to monitor and open every student submission portal:

| Portal | Students | Faculty |
|---|---|---|
| DSL Lab Projects (SY, Div A–M) | https://atul1986.github.io/DSL26/ | https://atul1986.github.io/DSL26/admin.html |
| TE Research Papers (TE, Div A–E) | https://atul1986.github.io/ResearchPaper-26/ | https://atul1986.github.io/ResearchPaper-26/admin.html |

Live dashboard: **https://atul1986.github.io/AcademicDashboard26-27/**

🔐 **Private:** the page opens with a sign-in screen. Use your DSL Lab faculty console username and password (checked by the DSL backend, logged in its audit log). Auto sign-out after 20 minutes idle.

**Front page (public):** a live snapshot of submissions, students, days left and active divisions for each portal, with the admin sign-in beside it.

**After sign-in:** a simple home screen with one tile per portal (submissions, days left, divisions pending). Click a tile for full details: division chart, deadline, all links, QR code and WhatsApp share. A Tools tile holds the Google and GitHub links.

It shows each portal's online status, submission and student counts, division-wise bars, deadline, and links to GitHub, the Apps Script backends, Sheets and Drive. It also has WhatsApp share buttons and printable QR codes.
Counts are read live from each portal's public `init` API (no student personal data is shown).

To add another portal later, add an entry to the `PORTALS` list in `index.html`.
