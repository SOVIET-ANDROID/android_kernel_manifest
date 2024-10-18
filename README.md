## Repo Init ##
```bash
repo init -u https://github.com/SOVIET-ANDROID/android_kernel_manifest.git -b raphael
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
