# Project
A simple demo of a safe, local teacher email login flow.

## What this does
- Simulates a login form for a test account (`teacher@example.com`, PIN `1234`).
- Shows a dummy inbox on successful login.
- Includes a password-change screen with validation and localStorage persistence.
- No real Gmail connection, no external authentication, no phishing.

## Run locally
1. Open `index.html` in a web browser.
2. Use email `teacher@example.com` and PIN `1234`.
3. Login, then click `Change Password` to test password update flow.

## Project files
- `index.html`: full UI + logic for this demo.

## Security/naming note
This is an educational mockup. Do not use it in production or for any unauthorized account access. In real applications, use Google OAuth and the Gmail API with proper consent and security controls.

