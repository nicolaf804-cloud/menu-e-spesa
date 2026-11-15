# Menù e spesa

Weekly meal planner and shopping list (Italian / English), shared between two Android phones via Firebase.

## Get the app
Open **Releases → Latest** on the phone and tap `menu-e-spesa.apk`.
Install it over the existing app (do not uninstall): data stays.

## Change the app
Edit `www/index.html` and commit to `main`. GitHub Actions builds a new APK
(about 5 minutes) and publishes it as a new release.

The signing key is stored as the repository secret `DEBUG_KEYSTORE_B64`.
Do not delete it: without the same key, updates will not install over the old app.
