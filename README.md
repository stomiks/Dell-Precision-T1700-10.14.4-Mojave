# Dell Precision T1700 hackintosh
macOS Mojave (10.14.4)

- CPU: Intel Core i7 4770/4790
- GPU: Intel HD 4600
- LAN: Intel 82579
- HDA: Realtek ALC269Q 

## Issues
No known issues 

## Instructions

- Update BIOS to the newest version
- Make a bootable installer with UniBeast/TINU, use the latest Clover (r4920 at the time of the build)
- Use the usual drivers, fix with OsxAptioFix2Drv
- Graphics works OOB
- Use the freshest IntelMausiEthernet to patch LAN
- Use the freshest AppleALC to patch audio (inject "15", tick ResetHDA)

Bootup **config.plist** included
