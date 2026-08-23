RUNLU Invoice V4.1 — One-Tap Share & Email

Changes from V4.0 Build009:
- New "One-Tap Share & Email" button on the Send page: on iPhone/Android
  this opens the native Share Sheet with the Word invoice already
  attached — pick "Mail" and it drops straight into a new email with
  the file loaded, no manual "download then attach" step.
- Recipient / CC / Subject / Body are automatically copied to the
  clipboard at the same time, so you just paste them into the new
  email instead of retyping.
- "Copy To/CC/Subject/Body" button added for re-copying anytime.
- "Download Attachment Only" and the old mailto flow are kept as a
  fallback for browsers/desktops that don't support file sharing.

Previous V4.0 Build009 changes:
- Automatically switches to the new calendar month when the previous workspace is archived.
- Preserves saved email contacts during the transition.
- Advances invoice numbering by two per elapsed month.
- Moves the completed month into History and creates a fresh current-month workspace.
- If the prior month is unfinished, it stays open and shows a warning instead of switching.
- Shows a one-time welcome card after an automatic month transition.

Note: true "fully automatic, no-tap" sending from a personal Hotmail/
Outlook account isn't possible from a browser page — that would
require storing your email password/token in the page, which isn't
safe. This update gets you as close to one-tap as the platform allows.
