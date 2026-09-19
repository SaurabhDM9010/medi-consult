# Medi Consult

Android app for online self-consultation, built so people can check on their health from home instead of waiting for a doctor's appointment. A user enters their symptoms and gets a list of possible diseases with basic information and a link to learn more, can locate nearby hospitals, and can place an emergency call — usable from any remote location, which helps with early detection (so a condition doesn't spread further) and can matter when someone can't reach a hospital themselves.

<!-- Add 2-3 screenshots here, e.g.: -->
<!-- ![Home Screen](screenshots/2_Home%20Screen.jpg) -->

## Objective
- Diagnose the disease based on entered symptoms
- Get more information about a particular disease, including precautions and causes
- Find nearby hospitals
- Reach emergency help quickly

## Features
- Symptom-based disease search
- Nearby hospital locator using Google Maps API
- One-tap SOS/emergency call
- Contact page with call, mail, and location

## Tech stack
- Android (Java)
- Google Maps API
- Gradle

## My role
Built solo as an academic project.

## Setup
1. Clone the repo
2. Open in Android Studio
3. Add your own Google Maps API key in `app/src/main/AndroidManifest.xml` / `app/src/release/res/values/google_maps_api.xml`
4. Run on an emulator or device (min SDK as configured in `app/build.gradle`)

## Screenshots
See the `screenshots/` folder for the full set (splash, home, symptoms, disease list, nearby hospitals, emergency call, contact, share).

## License
See [LICENSE](LICENSE).
