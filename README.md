# Inni Care Android App

Native Android starter project for Inni Care. Built with Kotlin and standard Android views (no extra UI libraries).

## Included
- Purple/pink branded UI, vector app icon and native splash/theme background
- Home, product catalogue, cart quantity controls, customer order form, wholesale enquiry
- Device-local order history, WhatsApp share/contact, website, About and More screens
- GitHub Actions workflow to build a debug APK

## Product pricing
- 7 Pads Pack: ₹40
- 15 Pads Pack: ₹179

## Build APK on GitHub
1. Create a new GitHub repository and upload the contents of this folder (not the folder itself).
2. Ensure the default branch is `main`.
3. Open Actions and run `Build Inni Care APK`, or push a commit.
4. Open the completed workflow run and download the `Inni-Care-APK` artifact. Extract the ZIP to get `app-debug.apk`.

## Important limitations
Orders and history are stored only on the current device; there is no shared admin dashboard or online database. Status stays `Received` unless the app is extended. No payment gateway is connected. Verify real payment independently before confirming any order. This is a starter project and has not been built/tested on a physical device in this environment.
