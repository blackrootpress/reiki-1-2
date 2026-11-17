# Reiki courses — free public lessons

This public GitHub Pages site hosts **free Reiki Levels 1 and 2 only**. The Reiki Level 3 (Master / Shinpiden) course is a **separate paid course**, and must not be stored in the public repository.

## Files
- `index.html` — free course landing page plus Level 3 PayPal enrollment instructions and classroom link
- `reiki-level-1.html` — free Level 1 (Shoden)
- `reiki-level-2.html` — free Level 2 (Okuden)

## Reiki Master enrollment
Level 3 is a $33.33 minimum donation, paid through PayPal. The homepage shows the PayPal QR code (`paypal-qr.png`) and asks students to email a screenshot of their payment to editor@theblackrootpress.com; Luke then sends them access to the private Wix classroom.

Each free course embeds its own PayPal QR code for the $10 minimum distance attunement donation.

Classroom link: https://www.theblackrootpress.com/reiki-master-classroom-shinpiden

Never commit the classroom password or the Level 3 course HTML to this public repository.

## Publishing
In **Settings → Pages**, select **Deploy from a branch**, **main** and **/(root)**.
Website: https://chestnutcowboy.github.io/reiki-levels-1-and-2/

## Important security
The old public repository history included Level 3. Removing that file does not erase history. This new repository was created without Level 3 in its history. Host Level 3 *only* behind a paid access system. Historical copies may persist elsewhere.

## Notes
- Both free courses are self-contained HTML.
- Progress saves automatically in the learner's browser (localStorage). Nothing is sent to a server, and there are no accounts.
- **My progress** shows a short resume code (for example `L2-0860-RS7Z-1Z6G`) that restores completed lessons, current page and best quiz score on another device. A downloadable progress file also backs up the practice log.
- Clicking **Next** at the end of a lesson marks it complete automatically (learners can still unmark it). The final quiz unlocks when every lesson is complete.
- **Practice log** records practice sessions; learners can print it or email it to the teacher.
- Finishing a **follow-along** session (with at least a minute on the timer) logs it automatically, with an optional note; learners can still add sessions by hand.
- If the browser blocks storage (for example private browsing), the course still works and tells the learner to use the resume code.
- Quiz scoring is client-side; GitHub does not record results.