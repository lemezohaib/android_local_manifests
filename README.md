# Local manifest for my projects

### Clone Repository

```
git clone https://github.com/lemezohaib/android_local_manifests.git .repo/local_manifests
```

### Start Sync 

```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
