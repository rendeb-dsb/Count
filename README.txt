# Count

Version: v1

A Progressive Web App that stores Date and Time records in the browser's localStorage.

## Files
- index.html — application
- manifest.json — PWA manifest
- sw.js — offline service worker

## Data
Date is displayed/entered as MM/DD/YYYY and Time as 24-hour HH:MM.
The numeric keypad can be used because the application automatically inserts `/` and `:` while digits are entered.

## Import
Choose a CSV file using the device's file picker. CSV format:
Date,Time
09/12/2026,18:14

Import replaces all existing stored records.

## Export
Downloads `Count.csv`.

## Persistence
Records are stored in browser localStorage for this app/site. Closing the app or restarting the phone does not normally remove them. Clearing the browser/site data or uninstalling/resetting the browser can remove them.

## Hosting
For PWA installation, serve the files from HTTPS (for example GitHub Pages).
