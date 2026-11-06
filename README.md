# All Mail — Android starter project

This is a buildable Gmail-inspired Android UI starter. It currently displays sample messages and navigation only.

## Important
This is **not yet a working email client**: Gmail/Yahoo/iCloud sign-in, inbox sync, sending, attachments, push notifications, and account storage are not implemented. Do not enter real email passwords into this starter. A production client needs provider-approved OAuth flows where available, secure token storage, and carefully configured IMAP/SMTP or provider APIs. Gmail access in particular requires Google OAuth consent/configuration; iCloud and Yahoo have their own authentication requirements.

## Build an APK using only an Android phone
1. Download and extract `AllMailAndroid.zip` on your phone.
2. Create a GitHub account (if you do not have one) and a new **public or private repository** named `AllMail`.
3. Upload the extracted project files and folders to the repository. Make sure `.github/workflows/build-apk.yml` is included.
4. Open the repository on GitHub in Chrome. Go to **Actions** → **Build All Mail APK** → **Run workflow**.
5. Wait for the workflow to finish. Open the completed run and download the **All-Mail-debug** artifact.
6. Extract the downloaded artifact ZIP. Tap `app-debug.apk` to install. Android may ask you to allow installs from Chrome or Files.

## Next development phase
Implement secure sign-in and sync one provider at a time, beginning with Gmail OAuth. Then add Yahoo/iCloud/Outlook account adapters, unified inbox, compose/send, attachments, search, folders, and notifications. Never collect or store users' raw email passwords.
