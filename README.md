# ERPAY Android Demo

Premium mobile-first ERPAY UI prototype packaged as an Android WebView project.

## Important
- Demo prototype only; no real payments, UPI, UTR verification, banking integration, OTP, or production authentication.
- Dashboard values are simulated. Do not use it to collect real financial information or represent demo balances as real funds.
- Local demo sign-in is not secure production authentication.

## Build APK using GitHub Actions
1. Create a new GitHub repository and upload all files in this folder (including the hidden `.github` directory).
2. Open the repository's **Actions** tab.
3. Select **Build ERPAY Demo APK** and choose **Run workflow** (or push a commit after enabling Actions).
4. When the workflow succeeds, open the run and download the `ERPAY-debug-APK` artifact.
5. Extract the downloaded artifact ZIP to get `app-debug.apk`.

The APK is not precompiled in this archive. The workflow compiles it on GitHub's runner where Android SDK and Gradle can be downloaded.
