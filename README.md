# The AOSP  #

# Brought to you by Project team no:6, GEC ,Palakkad #

Members:

Abhina
Haritha
Kavya
Sruthi

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/theaosp/manifest -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX








 
