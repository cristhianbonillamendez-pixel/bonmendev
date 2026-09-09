# My Loan Privacy Policy

Effective date: September 9, 2026.

My Loan is a BonMenDev app for calculating and managing personal loans. It does
not provide financial advice.

## Data and local storage

Loan amounts, rates, terms, names, payments, notes, fees, reminders, and
preferences entered by the user are processed and stored locally on the device
using SQLite. No account is created, and BonMenDev operates no server that
receives this information.

Uninstalling the app or clearing its data may remove this information. Users can
create a local `.miprestamo` backup; it can contain entered financial data and is
not encrypted.

## Reports, backups, and external apps

My Loan can generate PDF reports and backups locally. They only leave the device
when the user chooses to save, print, or share them through Android's picker or
share sheet. The destination app or service processes the file under its own
policies. My Loan performs no automatic cloud sync or cloud backup.

## Reminders and permissions

Reminders are scheduled locally. On Android 13 or later, the app requests
`POST_NOTIFICATIONS` only when the user attempts to enable this feature. It
declares `RECEIVE_BOOT_COMPLETED` to restore reminders after a reboot or app
update; the notification plugin also declares `VIBRATE`. It does not request
exact-alarm access.

The app does not use the camera, microphone, location, contacts, SMS, call logs,
or broad storage permissions.

## Third parties and tracking

My Loan Pro is offered as a one-time purchase processed by Google Play. Google
may process information needed to complete, restore, and manage the transaction
under its own policies. My Loan queries Google Play for the product, localized
price, and purchase status; BonMenDev does not receive or store full payment card
numbers or other payment credentials.

No advertising, analytics, telemetry, tracking, authentication, or proprietary
cloud service is integrated. PDF, sharing, file, notification, and purchase
libraries are reviewed against the final artifact before release.

## Children and changes

The app is not specifically directed at children and does not knowingly collect
children's personal information. This policy will be updated if practices,
permissions, or integrations change.

## Contact

Developer/brand: **BonMenDev**.

Contact: **bonmendev.apps@gmail.com**.

Public Google Play URL:
**https://cristhianbonillamendez-pixel.github.io/bonmendev/mi-prestamo/privacy-policy/**.
