# 2FA Authenticator Mobile App

Create a sleek, secure mobile app that generates time-based one-time passwords (TOTP) to help users add an extra layer of security to their online accounts. This is your take on apps like [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en)—focus on usability, offline functionality, and a personal touch like custom labels or backup options, all tailored for mobile.

## What Needs to Be Built
Develop a standalone mobile app where users can add accounts (via QR codes or manual entry), view a list of real-time 6-digit codes that refresh every 30 seconds, and keep their 2FA data safe with local encryption. It should work offline and feel intuitive, with optional features to make it uniquely yours.

## Requirements/Features for Mobile App

### Primary features
**Account Setup:** Let users add new accounts by scanning a QR code with the phone's camera (e.g., from a site like Gmail or GitHub) or typing in a secret key manually if they prefer. Let user add an account name for each entry.

**TOTP Display:** Build a home screen that lists all added accounts, each with a live 6-digit code that updates every 30 seconds. Add a countdown timer (like a progress circle) so users know when the code refreshes.

**Offline Functionality:** Make sure the app generates codes locally using the stored keys—no internet required. Store everything securely on the device with encryption to protect the secrets.

**User-Friendly Touches:** Allow users to edit account names (e.g., "Work Gmail" instead of a random string) and maybe add icons or colors for each entry to make it visually pop.


### Additional Features
**Security Lock:** Add a PIN, password, or biometric option (like fingerprint or face unlock) to open the app, so if the phone is lost, the 2FA data stays safe.

**Backup & Restore:** Include a way to export 2FA data as an encrypted file (e.g., to Google Drive or locally) and restore it later—great for switching phones. Keep it simple but secure with a user-set passphrase.

**Extra Flair:** Toss in a dark mode toggle, a quick-copy button to paste codes into other apps, or a search bar if the account list gets long—small wins to make it stand out.


### Learning resource
- [How Google Authenticator Works: System Design Overview](https://medium.com/@YodgorbekKomilo/how-google-authenticator-works-system-design-overview-aa656caad9d6)
- [Building Two-factor Authentication](https://www.gosquared.com/blog/building-two-factor-authentication)
