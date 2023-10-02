# Lineage OS
https://wiki.lineageos.org/

Path in Lineage OS : `/lineage/kernel/xiaomi/chime/`

## manifest

`/lineage/.repo/local_manifests/roomservice.xml`  
```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <remote name="githubrepo"
          fetch="https://github.com/Oros42"
          revision="lineage-20.0" />

  <remote name="pixel-devices-blobs"
          fetch="https://gitlab.pixelexperience.org/android/vendor-blobs"
          revision="thirteen" />

  <project path="device/xiaomi/lime" remote="githubrepo" name="device_xiaomi_lime" revision="lineage-20.0" />
  <project path="device/xiaomi/chime" remote="githubrepo" name="device_xiaomi_chime" revision="lineage-20.0" />
  <project path="hardware/xiaomi" remote="githubrepo" name="hardware_xiaomi" revision="lineage-20.0" />
  <project path="kernel/xiaomi/chime" remote="githubrepo" name="kernel_xiaomi_chime" revision="lineage-20.0" />

  <project path="vendor/xiaomi/lime" remote="pixel-devices-blobs" name="vendor_xiaomi_lime" revision="thirteen" />
  <project path="vendor/xiaomi/chime" remote="pixel-devices-blobs" name="vendor_xiaomi_chime" revision="thirteen" />
  <project path="vendor/xiaomi/chime-perf" remote="pixel-devices-blobs" name="vendor_xiaomi_chime-perf" revision="thirteen" />
</manifest>
```

## How to use it
https://ecirtam.net/wiki/doku.php?id=wiki:android:lineageos:redmi9tlime