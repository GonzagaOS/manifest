# Javanese OS #
<div align="center">
<a href="https://github.com/Javanese-OS">
<img src="https://github.com/Javanese-OS/GreatDocs/blob/main/assets/header.png?raw=true" alt="Javanese OS"> 
</a>
</p>

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/GonzagaOS/manifest.git -b 12

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch javanese_$device-userdebug

# Build the code
$ make java -jX
```
---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**POSP**](https://github.com/PotatoProject)
 * [**Nusantara**](https://github.com/Nusantara-ROM)
 * [**LegionOS**](https://github.com/Project-LegionOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**BiancaProject**](https://github.com/BiancaProject)

---------------------------------------------------------------------------------------
