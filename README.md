# Neatly GO forms

Client questionnaires. Static HTML, no build step.

**backyard-questionnaire** — live at https://YOURNAME.github.io/neatlygo-forms/
Submissions go to a Google Apps Script (script.google.com → "Neatly GO forms"),
which files photos in Drive and emails me.

To edit questions: open the page, switch to "Edit questions", make changes,
Save file, then paste the new JSON into the defaults() function.
Remember: after editing the Apps Script, redeploy — saving isn't enough.
