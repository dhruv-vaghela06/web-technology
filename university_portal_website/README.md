# Northstar University — Static Website & Split Portal

## Run
Extract the ZIP and open `index.html`, or run the folder with VS Code Live Server.

## Separate workspaces
- `portal.html`: role-selection gateway
- `student-login.html`: student sign-in
- `student-register.html`: validated student registration
- `student-dashboard.html`: student-only dashboard
- `admin-login.html`: administrator sign-in
- `admin-dashboard.html`: administrator-only dashboard

## Demo credentials
- Admin: `admin@college.edu` / `Admin@123`
- Student: `aarav@college.edu` / `Student@123`
- Other seeded students: `diya@college.edu` and `rohan@college.edu`, same demo password.

## Validation and behaviour
Client-side JavaScript validates email, password strength, matching confirmation, Indian mobile number, student ID, required programme/year, duplicate email/ID, and terms acceptance. Registration is saved with Pending status. Admin can approve/suspend records and publish announcements. Student and admin sessions are stored in `sessionStorage`; demo records and announcements use `localStorage` and are shared between browser tabs on the same origin.

## Important limitations
This is a front-end/static demonstration only. Browser storage and client-side checks are not secure authentication or a real database. Do not use real personal information or production credentials. A production deployment needs a server, database, password hashing, authorization checks and HTTPS. External Google Fonts and Unsplash imagery require internet access.
