AMCHAM GALA BALL — IPHONE CHECK-IN PWA

WHAT THIS IS
- A single-user, phone-local check-in app.
- No Python server, laptop, account, cloud database, or venue Wi-Fi is needed after installation.
- Guest data and check-in/payment marks are stored in this iPhone's browser storage.
- The app is designed for one operator/device. It does NOT synchronize with the Samsung.

IMPORTANT BEFORE EVENT USE
1. The app must first be hosted on an HTTPS website to install as an iPhone home-screen web app.
2. Open the HTTPS address in Safari on the iPhone.
3. Tap Share -> Add to Home Screen -> Add.
4. Open the new AmCham Check-in icon once while online so the offline app files are cached.
5. Import the FINAL attendee Excel workbook (first worksheet; headers Company, Name, Table Number).
6. Confirm the imported row count and verify table numbers before using it live.
7. Export a JSON backup before the event and periodically during check-in. Export CSV for opening attendance in Excel.

EXCEL IMPORT
- Reads the first worksheet of .xlsx files directly in the browser; no external libraries.
- Also accepts CSV.
- One spreadsheet row becomes one check-in entry. Multiple names in one Name cell stay together as one party entry.
- Blank Company and Table Number cells inherit the previous nonblank value, which supports grouped company rows.
- Import replaces the current list and resets check-in/payment marks after confirmation.
- The supplied working workbook is NOT preloaded; it was intentionally left out because the list is still being adjusted.

DATA LIMITATIONS / SAFETY
- This is local to this iPhone. It does not share changes with another phone.
- Safari website data can be cleared by iOS/user settings. Keep JSON backups in Files/iCloud Drive.
- Do not use the Reset or Import function during the event unless you intend to clear/replace the list.
- The current workbook provided during development has an empty Table Number column; table badges appear once the final workbook contains assignments.

HOSTING
Upload the contents of this folder to a static HTTPS host (for example, a static-site host). Then follow the iPhone installation steps above. HTTPS is required for service-worker/offline installation.
