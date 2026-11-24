AMCHAM THANKSGIVING DINNER 2026 — CHECK-IN PWA

Event: Tuesday, 24 November 2026
Venue: Hyatt Regency Casablanca

WHAT'S INCLUDED
- 85 preloaded bookings representing 108 tickets.
- Search by company, booking contact, or attendee name.
- Booking-level check-in and individual ticket check-in.
- Individual check-in never checks in the rest of the booking.
- Payment status is separate from arrival/check-in.
- Manual table assignment and attendee-name editing.
- Excel (.xlsx) and CSV import; JSON backup/restore; attendance CSV export.
- Offline PWA support; local data stored on the device.

IMPORTANT DATA MODEL
The source workbook contains booking rows and ticket quantities, not 108 fully identified attendee names. Each booking is preloaded with one attendee slot carrying the supplied Full Name (when present); additional ticket slots are explicitly marked "name needed". These are placeholders, not invented attendee identities. Edit the booking to enter names as they become available.

PAYMENT / ARRIVAL
Payment status does not automatically check in anyone. Use the attendee buttons to check in one person, or "Check in entire booking" for all tickets in that booking.

SEATING
Table numbers are blank and manually editable. No table count or seating plan is assumed.

INSTALLATION
1. Host all files on an HTTPS static host (GitHub Pages works).
2. Open the HTTPS URL in Safari on the iPhone.
3. Share -> Add to Home Screen.
4. Open once while online so the service worker caches the app.
5. Confirm the 85 booking / 108 ticket totals and export a JSON backup.

DATA SAFETY
- Data is stored in this browser on this device only; no multi-device sync.
- Use Export backup regularly and keep the JSON in Files/iCloud Drive.
- Import replaces the current list and resets check-in marks after confirmation.
- Thanksgiving uses its own localStorage key and cache name; it does not overwrite the old Gala app's local data.
