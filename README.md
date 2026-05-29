<img width="776" height="392" alt="51c19032-c5e7-457c-8dcd-abb173186409" src="https://github.com/user-attachments/assets/000c1d3f-419c-46b0-acd0-0f59559d5469" />

### Credits go to PipaDB and ymdzq

# About OrangeFox Recovery

It's essentially a roided version of TWRP ~ Check [Releases](https://github.com/ruik3z/OrangeFox-Recovery-For-Pipa/releases)

## Main Recovery Operations

ADB & Sideload: Full command line communication and remote zip flashing.

Decryption: Built in support to read encrypted data partitions.

Display & Touch: Fully operational UI with display driver support.

Fastbootd: User space fastboot mode for advanced partition flashing.

Flashing & MTP: Seamless zip installation and computer to phone file transfers.

USB-OTG: Storage expansion via external flash drives and mice.

## Root & Security Management

Magisk & APatch: Native injection and management for root solutions.

KernelSU Support: Built in modules manager for modern kernel level root.

Passcode Reset: Special scripts to bypass forgotten lock screen pins.

Recovery Lock: PIN or password protection to secure the recovery itself.

## Automation & OTA Features

ROM OTA Survival: Supports incremental, block based manufacturer updates.

Auto-Recovery Injection: Prevents custom ROMs from overwriting OrangeFox.

OpenRecoveryScript: Executes automated, multi file flashing sequences.

## Interface & System Tools

Material Design 2: Modern visual interface with gesture navigation.

Hardware Controls: Button navigation backup if the touchscreen fails.

Visual Themes: Native customization for fonts, colors, and splash screens.

File Editor & Terminal: Built in tools to modify text files and run shell commands.

Automated Logging: Compresses error logs into zip files for easy troubleshooting.

# Download It

OrangeFox RECOVERY.img can be found in [Releases](https://github.com/ruik3z/OrangeFox-Recovery-For-Pipa/releases)

# General Advice
Run 'fastboot boot RECOVERY-FILE.img' during flash to test whether decryption, touch, and filesystem is all clear.

If everything looks good, flash OrangeFox permanently within menu. It should show up again upon reboot.

# Build Info
This build is made for Android 13, so approach cautiously or hit me up with a reply on xdaforums to request a custom build in case you're dabbling in custom ROMs (up to A16 supported).

UPDATE: You can now build it yourself using the [OrangeFox-Recovery-Full-Guide](https://github.com/ruik3z/Orange-Fox-Recovery-Build-Full-Guide)

# I'm Not Responsible For
Thermonuclear war, or whether you got fired because your alarm misbehaved. If you're gonna modify your device in any way, then be sure to understand that anything you do may come with the risk of a full software/hardware brick and/or future complications.

Flash responsibly.
