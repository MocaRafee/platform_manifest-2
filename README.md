WeebProjekt
=======

```bash

# Initialize local repository
repo init -u https://github.com/WeebProjekt/platform_manifest -b cheese

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
