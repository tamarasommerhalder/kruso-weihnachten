# 🎄 KRUSO Weihnachten

Invitation page for the **KRUSO Christmas get-together**.

👉 **Live:** https://tamarasommerhalder.github.io/kruso-weihnachten

## Features

- 🎁 Festive single-page invitation with falling snow and an animated title
- 📝 RSVP form (name, yes/no, number of people, what you're bringing)
- 👥 Live guest list with head count
- 🧾 "Already being brought" note so food doesn't double up
- 📅 Add to calendar: Google, Outlook or `.ics` (Apple and others)
- 📱 Works on phone and desktop

## How the RSVP works

The page itself is static (GitHub Pages can't store data). Sign-ups are sent to a small **Google Apps Script** web app, which writes each entry to a private Google Sheet and returns the guest list to the page.

- No account needed for guests
- Sending the form again with the **same name** updates the existing entry
- Entries can be edited or deleted directly in the Google Sheet

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole page: layout, styles and script in one file |

## Updating the page

1. Edit or replace `index.html`
2. **Add file → Upload files → Commit changes**
3. The live page updates after 1–2 minutes

Changing the page does **not** affect existing sign-ups, which live in the Google Sheet.
