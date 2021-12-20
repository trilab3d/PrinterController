- [Controller Version 1.1.4](#controller-version-114)
- [Controller Version 1.1.3](#controller-version-113)
- [Controller Version 1.1.2](#controller-version-112)
- [Controller Version 1.1.1](#controller-version-111)
- [Controller Version 1.1.0](#controller-version-110)

Controller Version 1.1.4
====================

Bug fixes:
- Fixed heater fault protection tolerance

New features:
- Added connection to Google Drive - print files directly from Drive

Improved:
- Updated PrusaSlicer to version 2.3.3
- Added tolerance to Z-Probe offset change to run full calibration
- Changed AzteQ Industrial Load, Unload, Purge filament temperature to 250 degrees

Controller Version 1.1.3
====================

Bug fixes:
- Temporarily disabled Mosaic Canvas due to communication interface change
- Confirm reading the change log on the close button
- Modified temperature presets
- Fixed default Printhead configuration file
- Fixed chamber temperature tolerance for cooling

New features:
- Updated PrusaSlicer to version 2.3.2

Improved:
- Added filament specific chamber temperature to PrusaSlicer for AzteQ Industrial

Controller Version 1.1.2
====================

Bug fixes:
- Z-Probe calibration limits
- Fix dropdown chamber temperatures
- Filament change during printing and pause
- Fix external USB camera issue
- Fix internal SD card update error
- Fix SD card update error

New features:
- Waiting for the printhead to cool before printing
- Notification of possible updates of the Delta Control mobile app

Improved:
- Deactivated macro execution during printing
- Allowed gcode file upload when printer busy
- Onboard camera temporarily disabled during file upload, increases file upload speed

Controller Version 1.1.1
====================

Bug fixes:
- Fixed incorrect height of the first layer after full calibration(3 round)
- Fixed G1/G2/G3 intermediate position outside machine limits error
- Fixed sorting of TWC log entries on MacOS
- Fixed DeltaControl app no filament dialog

New features:
- Added CRC checksum check when uploading file from web interface
- Dialog what's new after the update
- Added slicer profiles for PrusaSlicer 2.3.0
- Added slicer profiles for CANVAS

Improved:
- Updated KISSlicer printing profiles
- Fixed text wrapping of the current offset value

Controller Version 1.1.0
====================

