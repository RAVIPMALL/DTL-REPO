# DTL Connect v0.8 — Interactive UAT Prototype

This version turns the v0.7 UI preview into an interactive prototype using synthetic local data.

## Demo accounts
Employee: `demo.employee` / `DTL@Demo2026`
Admin: `demo.admin` / `DTL@Admin2026`

These are UI/UAT credentials only. Disable Demo Mode before production.

## Android
Open `android/` in Android Studio and run the app. Choose Demo Employee or Admin Preview. Interactive areas include salary details, leave application, document search/filter, notification read state, APAR editing/submission, and admin approval/publishing actions.

## Web admin
From `admin/`: `npm install` then `npm run dev`.

## Production boundary
Real DTL identity/MFA, employee/payroll/leave/APAR/e-office integrations, employee-scoped authorization, secure document storage, audit/SIEM, rate limiting, session/device revocation, UAT and security testing are still required.
