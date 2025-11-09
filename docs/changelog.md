# Changelog

[//]: # (CHANGELOG)

### v2.6.13

22 December 2023

- fix a problem where the camera settings are not displayed properly on some computers

### v2.6.12

20 November 2023

- New Calibration Assistant tool
- Multi-star guiding improvements: better tolerance to passing clouds or loss of stars after a large dither
- Various enhancements for mounts with high precision encoders
- Reduced CPU utilization when rendering the camera image on the screen
- The star profile can now be viewed without interpolation
- Improved help content and error messages
- Updated camera libraries: ZWO ASI, Moravian, Svbony, QHY, Touptek, Altair
- New/updated translations: Simplified Chinese, Traditional Chinese, Portuguese (Brazilian), Czech, Japanese, Spanish

### v2.6.11

22 February 2022

- Guiding Assistant updates
- Updated defaults for new profiles: HFD checking and multi-star enabled, star mass checking off
- The star profile window now shows the centroid coordinates
- Add support for observatory-class focal lengths
- Updated camera support: Svbony, Touptek, ZWO ASI
- Updated translations: French, Spanish

### v2.6.10

26 June 2021

- New Multi-star guiding option
- Various small UI improvements and minor bug fixes
- Updated camera support for Altair, ASCOM, INDI, QHY, SBIG, ToupTek, WDM, and ZWO ASI cameras
- Added support for Moravian and Svbony cameras
- Updated translations - Catalan, French, Spanish, Traditional Chinese
- Updated Help file

### v2.6.9

4 July 2020

- Updated Help file
- Guiding Assistant: improved dec backlash measurement to better handle some poorly behaving mounts
- Polar Drift Align: add Mirror option for OAG users
- Log uploader: do not display empty logs by default
- Fix background color in the Drift Align window to honor the window manager color theme
- INDI: remove the obsolete driver port selection option
- New Galician translation
- Updated French translation
- Updated Portuguese translation

### v2.6.8

3 May 2020

- No longer display an alert when little South movement is detected after calibration
- Altair cameras: update to SDK version 46.16909.2020.0404 (Windows)
- QHY cameras: fix incorrectly-reported bits-per-pixel value for 16-bit cameras
- Better tolerance of INDI/ASCOM mount drivers that incorrectly report guide speed
- Updated Traditional Chinese translation

### v2.6.7

4 February 2020

- Mac: 64-bit version of PHD2 for macOS Catalina
- PHD2 now produces a single debug and guide log per night rather than a set each time the app is launched
- Added checks for specific mount driver quirks
- Improvements to the log upload tool
- Altair cameras: update to SDK version 38.15031.2019.0706 (Windows)
- iOptrion iGuider camera support added
- Omegon Pro camera selection added
- QHY cameras: update SDK to version V2019.11.15.0 (Linux) and V20191115_0 (Mac)
- ZWO cameras: update SDK to version V1.14.1108 (windows, mac, linux)
- INDI camera improvements
- Workaround for imaging apps which fail to un-pause PHD2: stop button now un-pauses guiding
- Updated French, Korean, Russian, Traditional Chinese translations
- New Japanese translation of the help file
- Automatically update guide settings for changes to binning, pixel size and focal length
- New button on the main toolbar for auto-selecting a star
- New option to enable/disable audible beep for lost star
- Improvements and clarifications of various messages in the application
- Changing the Dec Flip calibration option now triggers a new calibration
- Guiding Assistant: improved guide setting recommendations
- Equipment profile wizard improvements, including specialized settings for mounts with high preceision encoders
- New server methods and notification updates
- Updated Help file
- Debug log and guide log improvements

### v2.6.6

24 March 2019

- Lots of improvements to the Guiding Assistant
- Updated camera support: Altair, QHY, SBIG, SSAG (Mac), ZWO ASI
- New ToupTek camera support for Windows
- New MallinCam SkyRaider camera support for Mac
- INDI SBIG AO support
- Better detection of problems like runaway guiding, excessive backlash, and calibration problems
- Improved backlash compensation
- New Meridian flip calibration tool
- New ZFilter guide algorithm
- Guide algorithm None has been removed
- INDI improvements
- Various minor user interface fixes
- Updated Help file
- Updated translations

### v2.6.5

30 April 2018

- New Static Polar Align tool and Polar Drift tool
- New tool to upload log files for review (Help > Upload Log Files)
- Improved Backlash compensation with additional controls and improved backlash measurement in the Guiding Assistant
- New Profile Wizard improved detection of properties of connected gear
- Improved handling of camera binning and mount guide speed changes
- Dither settling now ignores dec distance when dec guide mode is None
- Some minor UI tweaks like more explicitly labeling pixels vs arc-seconds units, showing help info in status bar as menu items are highlighted, and layout fixes for high resolution displays
- Remove modal dialog boxes from most camera connections
- Allow star auto-selection to select stars closer to the edge of the frame
- Altair Cameras: update SDK to version 20_12_2017
- Atik Cameras: binning support added
- ZWO Cameras: updated Windows SDK to V1.13.1.9
- Guide log enhancements (additional logging)
- INDI fixes
- Server API additional methods
- Updated translations - French, German, Russian, Traditional Chinese

### v2.6.4

25 September 2017

- New Predictive PEC Guide algorithm for RA
- INDI support added for Windows and Mac
- Updated native camera support for QHY, ZWO, SX, and Altair cameras
- Improved detection of low-SNR stars by more accurate background calculation
- PHD2 now checks for PHD2 updates
- AO: better stability when large bumps are required
- Various UI improvements, such as allowing arbitrary camera exposure durations
- New option for avoiding hot pixels: minimum star HFD threshold
- New option for star saturation detection: max ADU threshold
- New image logging options based on trigger events like star lost or large offset
- Comet tracking improvements
- Server API: addition of new API methods
- Diagnostic improvements including log file enhancements and more info in fits headers for saved images
- Updated translations including a new Portuguese (Brazilian) translation
- Help file updates

### v2.6.3

12 February 2017

- Reliability improvements and SDK updates for various cameras: ZWO, SX, Altair, SBIG, and WDM webcams
- Comet tool fixes
- Display improvements for small screens and high-DPI screens
- New star-cross test tool
- Stats window now displays image size and guider FOV
- AO enhancements: display RA and Dec directions on the AO graph, automatically increase bump step size when dither settling
- Allow Dec dither when Dec guide mode is north or south by temporarily switching to bi-directional dec guiding until dither settles
- Star mass change detection now works when exposure is Auto
- OSX: disable AppNap on OSX versions >= 10.9
- Server API: various new functions added
- Various logging and diagnostic improvements
- Updated translations
- Updated help documentation
