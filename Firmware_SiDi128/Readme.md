For uddate your SiDi128 copy firmware_xxxxxx.upg to root sd card and rename it to firmware.upg, start yor SiDi128 and select in OSD upgrade firmware.


## Firmware 240922
------------------
- Use QSPI on Minimig for CDROM data transfer
- Load boot art files from the current directory for Minimig
- USB/HID fixes by Eugene Lozovoy (UzixLS)
- Detect ROM type for SNES carts

## Firmware 240505
------------------
- Fix PSC CD TOC sent to core (Wipeout, CD audio in some games)
- Increase the max. supported number of HD file fragments to 2048 for indexing
- Fallback to root directory when RBFNAME from ARC file is not found