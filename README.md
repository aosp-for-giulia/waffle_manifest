# Stuff needed to build for giulia/giuliac

### Init Your ROM's Manifest. For example:

```
repo init -u https://github.com/Lunaris-AOSP/android -b 16.2 --git-lfs
```

### Clone Repository

```
git clone https://github.com/aosp-for-giulia/waffle_manifest.git -b lunaris .repo/local_manifests
```

### Start Sync 

```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --current-branch -j$(nproc --all)
```
