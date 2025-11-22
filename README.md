# LIBSYNC App

LIBSYNC is an Android app (APK) distributed in this repository for easy download and installation.

**Download**
- APK file: `Libsync app.apk` (stored with Git LFS in the repo root).
- Recommended: download from the repository web UI Releases page if available, or clone with Git LFS enabled.

**Requirements**
- Android device (Android 6.0+ recommended).
- If cloning the repository: `git` and `git-lfs` installed on your machine. Run `git lfs install` and `git lfs pull` after cloning.

**Installation (on device)**
1. Transfer the APK to your device (USB, cloud, or direct download on device).
2. On the device, enable Install from Unknown Sources (or Allow this source) in Settings  Security.
3. Using a file manager, tap the APK `Libsync app.apk` and follow the installer prompts.
4. After installation, you can revoke Unknown Sources permission if desired.

**Installation (adb)**
- If you have `adb` installed and the device connected with USB debugging enabled:

```
adb install -r "Libsync app.apk"
```

**Notes**
- The APK in this repository is tracked via Git LFS. To fetch the actual binary when cloning:

```
git clone https://github.com/Vaibhavp809/LIBSYNC-APP-.git
cd LIBSYNC-APP-
# ensure LFS is set up
git lfs install
git lfs pull
```

- If you prefer not to use Git LFS, download the APK from the Releases page (recommended for end-users).

**Support**
- If you need installation help or run into errors, open an issue on the repository.
