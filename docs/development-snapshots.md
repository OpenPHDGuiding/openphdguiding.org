# PHD2 Development Snapshot Builds

This page contains the latest development builds of PHD2. These builds contain the latest bug fixes and enhancements to PHD2. Although these builds may not be as well tested as the general releases available on the [main Downloads page][1], they have been tested by the developers and are generally stable for imaging use. We would welcome your help testing them out, and if you do encounter any issues, please [let us know][2].

The changes in each snapshot build are summarized below; you can see the detailed changes in the project’s [Git commit log][3]

The online version of the help file for the latest snapshot build is [here][4].

[1]: downloads.md
[2]: getting-help.md
[3]: https://github.com/OpenPHDGuiding/phd2/commits/master
[4]: /man-dev

### 2.6.13dev7

11 January 2025

- Windows: add camera DLL missing from today's 2.6.13dev6 release.
- No other changes in this release. Please see the dev6 changes for what's new.

v2.6.13dev7 | [Windows Download EXE](/phd2-2.6.13dev7-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13dev7-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13dev7-OSX-64.zip)

### 2.6.13dev6

11 January 2025

- Improved display of magnified star in StarProfile
- Improved Guiding Assistant exposure recommendations for encoder mounts
- Improved experience when MultiStar processing and subframes are both enabled
- Better handling of the minimum focal length setting
- Improved experience when the image scale changes
- Better handling of the Saturation ADU setting when camera 8/16 bit mode is changed
- Predictive PEC: fix for possible PHD2 crash when there is an extremely large dither
- Predictive PEC: use the monotonic clock rather than the system wall clock
- server: fix possible problem when imaging app sends multiple overlapping requests
- Improved alert message when Dec guiding is ineffective
- Altair cameras: update to SDK version 20241216_57.27250
- OGMA cameras: update SDK to version 57.26291.20240811
- Player One cameras: native support added using SDK version V3.7.1
- QHY cameras: improved native camera support
- Svbony cameras: update SDK to v1.13.2
- Touptek cameras: update SDK to version 57.27348.20241224
- Updated Czech and Spanish translations
- Help file updates
- Special thanks to our new contributors - see the Help > About window

v2.6.13dev6 | [Windows Download EXE](/phd2-2.6.13dev6-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13dev6-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13dev6-OSX-64.zip)

### 2.6.13dev5

14 July 2024

- Update Windows VC runtime redistributable DLLs to version 14.40.33810.0, 32-bit
- Touptek cameras: update SDK to version 56.25996.20240707
- QHY cameras: update SDK to version 24.03.29
- OGMA cameras: update SDK to version 2024-06-20

v2.6.13dev5 | [Windows Download EXE](/phd2-2.6.13dev5-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13dev5-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13dev5-OSX-64.zip)

### 2.6.13dev4

26 May 2024

- Improved handling of image scale changes
- Improved layout of text labels in the Target window
- Fix a potential error when an imaging app sends a command for a zero-pixel dither
- Touptek cameras: update Touptek SDK lib to version 55.25633.20240519
- Windows: add missing DLL file
- Updated Czech translation

v2.6.13dev4 | [Windows Download EXE](/phd2-2.6.13dev4-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13dev4-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13dev4-OSX-64.zip)

### 2.6.13dev3

21 April 2024

- OGMA cameras: OGMA cameras are now supported in PHD2
- Svbony cameras: SDK updated to version v1.12.6
- opencv cameras: Opencv updated to version 4
- opencv cameras: now available on Mac and Linux
- ask-for-coordinates aux mount is working again
- updated translation: Traditional Chinese
- ra-only guiding: more accurate display of ra error value when RA-only guiding is in effect
- event server: added interfaces to get/set variable delay parameters
- Help file updates

v2.6.13dev3 | [Windows Download EXE](/phd2-2.6.13dev3-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13dev3-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13dev3-OSX-64.zip)

### 2.6.13dev2

23 March 2024

- Mac: Fix crash on Sonoma when a status alert message is displayed
- Windows installer: add missing required dll msvcp140.dll
- Star profile window: improved layout, better font size, and more accurate display of crosshairs
- Performance improvement displaying camera images
- Prevent resizing of rows and columns in stats window grids
- Touptek cameras: update to SDK version 55.24621.20240204
- INDI: Rotator support added
- INDI: Wait for Indi devices to be ready when connecting
- INDI: Better error message for RGB FITS file
- Updated Czech and Spanish translations

v2.6.13dev2 | [Windows Download EXE](/phd2-2.6.13dev2-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13dev2-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13dev2-OSX-64.zip)

### 2.6.13dev1

27 December 2023

- Windows: remove cameras with obsolete SDKs: Fishcamp, Meade-DSI, SAC4-2, SSAG. To use these cameras, stick with an older version of PHD2.
- Mac: no longer building for 32-bit Macs. To use 32-bit Macs, stick with an older version of PHD2.
- INDI: update to INDI 2.0
- Touptek cameras: update SDK lib to version 55.24239.20231224

v2.6.13dev1 | [Windows Download EXE](/phd2-2.6.13dev1-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13dev1-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13dev1-OSX-64.zip)

### 2.6.13

22 December 2023

- fix a problem where the camera settings are not displayed properly on some computers

v2.6.13 | [Windows Download EXE](/phd2-2.6.13-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.13-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.13-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.13-OSX.zip)

### 2.6.12

20 November 2023

- Star profile: add option to toggle between raw and interpolated views of the star
- Multistar guiding: better tolerance of passing clouds
- Calibration Assistant: some small improvements to the assessment
- New Profile Wizard: add ability to set saturation ADU based on camera bit depth
- Fix a possible crash after closing the ASCOM Mount properties window
- INDI: compute LST in PHD2 if INDI driver does not provide it
- Altair cameras: update SDK to version 54.23860.20231112
- Touptek cameras: update SDK to version 54.23926.20231119
- ZWO ASI cameras: update SDK to v1.30 (2023-07-18)
- Svbony cameras: update SDK to v1.11.4
- Moravian cameras: update SDK to v4.15
- Updated translations: Spanish, Japanese, Traditional Chinese, Czech

v2.6.12 | [Windows Download EXE](/phd2-2.6.12-installer.exe) | [macOS Sonoma+ ZIP](/PHD2-2.6.12-OSX-64-sonoma+.zip) | [macOS Ventura- ZIP](/PHD2-2.6.12-OSX-64.zip)

### 2.6.11dev6

29 May 2023

- Svbony Cameras: update SDK to version v1.11.2 (2023-04-24)
- Touptek Cameras: update Touptek lib to version 54.22587.20230516
- Calibration Assistant: minor UI tweaks and help file updates
- Updated Japanese translation

v2.6.11dev6 | [Windows Download EXE](/phd2-2.6.11dev6-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.11dev6-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.11dev6-OSX.zip)

### 2.6.11dev5

14 May 2023

- New Calibration Assistant tool
- Multi-star guiding: fix possible loss of secondary stars after a huge dither
- QHY cameras: update to SDK version 2023-05-10
- Touptek cameras: update SDK to version 53.22412.20230409
- Updated Czech, Japanese, Simplified Chinese and Traditional Chinese translations
- PHD2 now compatible with INDI 2.0

v2.6.11dev5 | [Windows Download EXE](/phd2-2.6.11dev5-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.11dev5-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.11dev5-OSX.zip)

### 2.6.11dev4

15 January 2023

- Improved alert messages for camera geometry mismatches
- Fix problem launching PHD2 on some Windows computers (missing vcomp140.dll)
- Updated Czech translation from Stanislav
- Updated Japanese translation from nabePla
- Updated Simplified Chinese translation from Linkage

v2.6.11dev4 | [Windows Download EXE](/phd2-2.6.11dev4-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.11dev4-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.11dev4-OSX.zip)

### 2.6.11dev3

30 December 2022

- Protect against mount drivers that report invalid guide speeds
- Clarify some error messages
- New profile wizard now asks for a Rotator selection (optional)
- Svbony Cameras: update SDK to v1.10.0
- ZWO ASI Cameras: update SDK to version V1.27
- Updated Japanese translation
- Help file updates

v2.6.11dev3 | [Windows Download EXE](/phd2-2.6.11dev3-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.11dev3-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.11dev3-OSX.zip)

### 2.6.11dev2

30 August 2022

- Reduced CPU utilization when rendering the camera image on the screen
- Help content overhaul and restructuring
- INDI Cameras: reduced CPU utilization
- ZWO ASI Cameras: reset colour balance to unity on connection
- ZWO ASI Cameras: update SDK to v1.26
- Moravian cameras: update SDK to version v4.11
- Svbony Cameras: update SDK to v1.9.4
- Svbony Cameras: native support enabled for Linux and Mac
- Svbony Cameras: wait for ST4 guide pulse to complete before starting the next exposure
- Updated Traditional Chinese translation
- Updated Portuguese (Brazilian) translation
- New Czech translation

v2.6.11dev2 | [Windows Download EXE](/phd2-2.6.11dev2-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.11dev2-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.11dev2-OSX.zip)

### 2.6.11dev1

19 April 2022

- New option for variable exposure delays -- helpful for very accurate mounts
- New Profile Wizard and Guiding Assistant: improved for mounts with high precision encoders
- Allow selecting lower values of the minimum HFD setting

v2.6.11dev1 | [Windows Download EXE](/phd2-2.6.11dev1-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.11dev1-OSX-64.zip)

### 2.6.11

22 February 2022

- For new profiles the default is now to enable multi-star guiding and disable star mass checking
- Display centroid coordinates in the star profile window
- Add support for observatory-class focal lengths
- ZWO ASI cameras: update SDK to version v1.20.3
- Svbony Cameras: update SDK to v1.6.4 and fix possible camera hangs when changing binning or ROI

v2.6.11 | [Windows Download EXE](/phd2-2.6.11-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.11-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.11-OSX.zip)

### 2.6.10dev3

28 November 2021

- Minor adjustments to Guiding Assistant, minMove floor, SNR checking
- Enable Min HFD checking by default
- Svbony cameras: update to SDK v1.6.1
- Updated Spanish translation

v2.6.10dev3 | [Windows Download EXE](/phd2-2.6.10dev3-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.10dev3-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.10dev3-OSX.zip)

### 2.6.10dev2

19 September 2021

- ZWO ASI cameras: update SDK to version V1.20 - Windows, Mac, and Linux
- Linux: update launcher icon to work better with Ubuntu/Gnome
- Svbony cameras: update SDK to version 1.4.4
- Svbony cameras: add support for SV305M PRO and other monochrome cameras

v2.6.10dev2 | [Windows Download EXE](/phd2-2.6.10dev2-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.10dev2-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.10dev2-OSX.zip)

### 2.6.10dev1

22 August 2021

- Svbony cameras: update SDK to version 1.4.2
- Touptek cameras: fix problem on MacOS locating the SDK dylib
- Updated French translation

v2.6.10dev1 | [Windows Download EXE](/phd2-2.6.10dev1-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.10dev1-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.10dev1-OSX.zip)

### 2.6.10

26 June 2021

- Svbony cameras: update SDK to version 1.3.7
- ToupTek cameras: update SDK to version 48.18081.2020.1205
- ZWO ASI cameras: update SDK to version 1.19
- Updated Spanish and Traditional Chinese translations

v2.6.10 | [Windows Download EXE](/phd2-2.6.10-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.10-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.10-OSX.zip)

### 2.6.9dev5

1 May 2021

- QHY cameras: update to SDK version 20210313_17 (Windows)
- Altair cameras: add an option to discard initial camera frames
- ASCOM cameras: fix an error from some cameras about invalid frame size after disconnecting and re-connecting the camera
- INDI cameras: fix a problem where the INDI server's binning value could override PHD2's binning setting
- Stats window - restore the size and position when PHD2 is restarted
- event server API: add star info to the LoopingExposures event
- Updated Catalan and Spanish translations
- Tool-tip and status bar message updates
- Help file updates

v2.6.9dev5 | [Windows Download EXE](/phd2-2.6.9dev5-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.9dev5-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.9dev5-OSX.zip)

### 2.6.9dev4

8 February 2021

- Windows installer: fix 32-bit Windows incompatible version of vcruntime140.dll added in v2.6.9dev3
- Multi-star: change display when primary star is lost
- Multi-star: reduce aggressiveness of dropping lost secondary stars
- Guide stats: fix incorrect max deflection calculation
- ZWO cameras: update SDK to V1.16.3 (Windows, Mac, Linux)
- New Catalan translation
- Updated Traditional Chinese translation
- Updated Help file

v2.6.9dev4 | [Windows Download EXE](/phd2-2.6.9dev4-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.9dev4-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.9dev4-OSX.zip)

### 2.6.9dev3

3 January 2021

- Altair cameras: update SDK to version 2020.1223
- Graph stats: exclude dither recovery frames from stats
- Multi-star: correctly report guide star distance to imaging apps
- Multi-star: do not automatically reset the Use MultiStar option in the UI
- WDM cameras: fix divide-by-zero crash when camera driver does not report AvgTimePerFrame
- Windows installer: include vcruntime140.dll
- Help file updates: add info about star-saturation controls and camera cooler
- Updated French translation

v2.6.9dev3 | [Windows Download EXE](/phd2-2.6.9dev3-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.9dev3-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.9dev3-OSX.zip)

### 2.6.9dev2

2 December 2020

- New: Multi-star guiding
- New: Moravian camera support
- Bug fix: ensure Dec comp is applied when meridian flip is accompanied by a Dec slew
- ZWO: update ZWO ASI SDK to version 1.16 - Windows, Linux, and Mac
- SBIG cameras: remember choice of whether to use the tracking CCD
- ZWO / INDI / ASCOM cameras: use binned frame size reported by camera
- ZWO camera: fix possible crash when changing binning
- INDI cameras: discard stale video frames when switching binning
- INDI cameras: improved verbose INDI logging
- Fix crash when cancelling AO port selection
- Fix crash when new profile created with mount set to None
- Fix incorrect pixel size change warning when new profile is created
- Updated French, Polish and Traditional Chinese translations

v2.6.9dev2 | [Windows Download EXE](/phd2-2.6.9dev2-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.9dev2-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.9dev2-OSX.zip)

### 2.6.9dev1

31 August 2020

- New Svbony camera support
- Altair cameras: update to SDK 46.17427.2020.0704
- ZWO cameras: update SDK to version V1.15.0617
- Disable Dec guide param controls if Dec guide mode is None
- Updated dark subtraction method fixing a problem with pedestals being set too high
- Shift-click on the auto-select button now de-selects the guide star
- Updated Help
- Updated Traditional Chinese translation

v2.6.9dev1 | [Windows Download EXE](/phd2-2.6.9dev1-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.9dev1-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.9dev1-OSX.zip)

### 2.6.9

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

v2.6.9 | [Windows Download EXE](/phd2-2.6.9-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.9dev5-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.9dev5-OSX.zip)

### 2.6.8

3 May 2020

- No longer display an alert when little South movement is detected after calibration
- Altair cameras: update to SDK version 46.16909.2020.0404 (Windows)
- Updated Traditional Chinese translation

v2.6.8 | [Windows Download EXE](/phd2-2.6.8-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.8-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.8-OSX.zip)

### 2.6.7dev1

30 March 2020

- Altair cameras: update SDK to 39.15529.2019.0906 (Windows)
- Guiding Assistant: display guide pulse duration on the backlash test graph
- QHY cameras: fix incorrectly-reported bits-per-pixel value for 16-bit cameras
- QHY cameras: fix problem with camera going unresponsive after the stop button is clicked
- Better tolerance of INDI/ASCOM drivers that incorrectly report guide speed

v2.6.7dev1 | [Windows Download EXE](/phd2-2.6.7dev1-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.7dev1-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.7dev1-OSX.zip)

### 2.6.7

4 February 2020

- Linux/Mac: save PHD2 settings after significant changes, like after calibration completes
- Mac: no longer need to restart PHD2 when first run to disable AppNap
- server: added option to specify a region of interest for star auto-selection
- Help file updates
- logging enhancements
- Updated Korean, Russian and Traditional Chinese translations

v2.6.7 | [Windows Download EXE](/phd2-2.6.7-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.7-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.7-OSX.zip)

### 2.6.6dev4

6 January 2020

- PHD2 now produces a single debug log and guide log per night rather than a set each time the app is launched
- Saturation detection by max ADU value is now the default setting for new equipment profiles
- Guiding Assistant: slightly more aggressive RA min-move recommendation
- Log upload tool improvements
- Guide log now includes the orthogonality error value and the RA guide rate normalized to Dec 0
- Improved handling of guide speed and image scale changes
- EQMOD ASCOM: display EQMOD-specific instructions in the new profile wizard
- iOptron iGuider camera support (Windows)
- QHY cameras: Linux/Mac: remove unnecessary debug messages when run from command-line
- QHY cameras: Linux: updated SDK to V2019.11.15.0
- Add check for problematic AP ASCOM driver synchronous guide pulse mode
- Bug fix: do not repeatedly show alert about dark file mismatch when disconnected camera reconnects
- Bug fix: do not display pulse guide limit reach alert after a long Guiding Assistant run
- Linux: show the translated language names (as we already do on macOS and Windows)
- Display the "you must restart phd2 for the language change to take effect" message translated
- cfitsio package updated to version 3.47
- Fixed flicker of controls in graph window
- Updated Korean and Russian translations, plus a new Japanese translation of the Help file
- Help file updates
- event server: add an optional ROI argument to find_star and guide methods
- event server: add LockPositionShiftLimitReached event notification
- event server: add option to get_lock_shift_params method to ask for x/y shift rate
- debug log improvements

v2.6.6dev4 | [Windows Download EXE](/phd2-2.6.6dev4-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.6dev4-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.6dev4-OSX.zip)

### 2.6.6dev3

7 December 2019

- Mac: 64-bit version of PHD2 for macOS Catalina
- QHY cameras: update macOS SDK to version V20191115_0 (32-bit and 64-bit)
- QHY cameras: log the QHY SDK version in the debug log
- ZWO cameras: update to SDK version V1.14.1108 (windows, mac, linux)
- Workaround for imaging apps which fail to un-pause PHD2: stop button un-pauses guiding
- Updated French translation
- Updated Traditional Chinese translation
- Fix potential crash when AO graph is updated by a thread other than the main UI thread
- Fix unlikely crash if imaging app tells phd2 to start guiding just as user closes app
- Extend auto-adjustment of guiding params for changes to pixel size, binning, or focal length

v2.6.6dev3 | [Windows Download EXE](/phd2-2.6.6dev3-installer.exe) | [macOS Ventura- ZIP](/PHD2-2.6.6dev3-OSX-64.zip) | [macOS 32-bit ZIP](/PHD2-2.6.6dev3-OSX.zip)

### 2.6.6dev2

10 September 2019

- New button on the main toolbar for auto-selecting a star
- New option to enable/disable audible beep for lost star
- Soften wording of some calibration alert messages to be more advisory in nature
- Fix various problems running the Guiding Assistant with an AO unit
- Changing the Dec Flip calibration option now triggers a new calibration
- Guiding Assistant: better recommendation for polar alignment
- Guiding Assistant: rework min-move recommendations to handle long G.A. runs
- Guiding Assistant: fix incorrect display of +/- symbol
- New profile Wizard: added an option for auto-restoring calibration
- Polar drift: allow window to be resized; save size and position across sessions
- Altair cameras: update to SDK version 38.15031.2019.0706 (Windows)
- INDI cameras: new option to suppress fallback to streaming mode
- INDI cameras: do not start exposure until prior exposure has completed
- INDI: ensure device names always include "INDI"
- ASCOM cameras: fix crash attempting to set cooler after camera is disconnected
- Server: add star HFD to guide step event
- Server: new ConfigurationChange event
- Server: allow clients to send multiple overlapped requests
- Updated French translation
- Updated Traditional Chinese translation
- Updated Help content

v2.6.6dev2 | [Windows Download EXE](/phd2-2.6.6dev2-installer.exe) | [macOS 32-bit ZIP](/PHD2-2.6.6dev2-OSX.zip)

### 2.6.6dev1

23 May 2019

- Equipment profile wizard and Guiding Assistant now recommend Lowpass2 Dec guiding for mounts with high-res encoders or near-zero backlash
- Calibration is now automatically cleared if the camera selection is changed
- Predictive PEC: enable the model retaining option by default for new profiles
- ZWO cameras: update to SDK version 1.14.0227 (Windows, Mac, and Linux)
- New Omegon Pro camera selection
- INDI mounts: fix incorrect LST fallback calculation for mount drivers that do not provide LST
- Guide log: ensure monotonically increasing timestamps regardless of changes to the system clock
- Minor debug log cleanup
- Camera simulator: fix crash when no mount or AO is selected
- Fix crash in connect equipment or advanced dialog when AO is selected but mount is None
- Updated French translation

v2.6.6dev1 | [Windows Download EXE](/phd2-2.6.6dev1-installer.exe) | [macOS 32-bit ZIP](/PHD2-2.6.6dev1-OSX.zip)

### 2.6.6

24 March 2019

- Mac: MallinCam SkyRaider camera support
- INDI SBIG AO support
- Drift Align tool: auto-select a new star if star was lost in the Adjust phase
- Fix Advanced Settings window problem where typing invalid characters in the focal length field could set it to zero
- Minor UI updates: improve some tool tips; re-enable the camera selection button after the camera is disconnected
- Server API: include calibration declination in get_calibration_data message
- Added command-line options for saving and loading the full set of config settings to/from a file
- Additional logging in the debug log
- Updated French and Traditional Chinese translations

v2.6.6 | [Windows Download EXE](/phd2-2.6.6-installer.exe) | [macOS 32-bit ZIP](/PHD2-2.6.6-OSX.zip)

### 2.6.5dev7

29 January 2019

- Guiding Assistant: new feature to review prior G.A. run results
- Guiding Assistant: avoid too large min-move recommendations
- Guiding Assistant: check for poor camera focus
- Guiding Assistant: recommend binning when image scale is too low
- Calibration review: show calibration side of pier
- Add menu items for toolbar button functions
- Backlash compensation: better resiliency against stiction
- Dark libraries: fix problem loading the wrong dark frame for exposures below 0.02s
- Connect gear: only enable camera selection button when camera driver supports multiple cameras
- ASCOM scopes: better handling for ASCOM drivers that terminate outside of PHD2
- Altair cameras: update to SDK version 30.13270.2018.1102
- ToupTek cameras: update to SDK version 33.13814.2019.0120
- ZWO cameras: use snap mode for USB cameras USB2 mini cameras - fixes various guiding stability problems caused by video mode
- Linux: add Touptek camera support
- Linux: fix a potential crash related to INDI text properties
- Fix long-standing possible crash when Manual Guide tool is run with On-camera mount
- Updated French and Traditional Chinese translations

v2.6.5dev7 | [Windows Download EXE](/phd2-2.6.5dev7-installer.exe)

### 2.6.5dev6

25 October 2018

- New Meridian flip calibration tool
- New: ToupTek camera support for Windows; using ToupTek SDK version 30.13059.2018.1003
- Guiding Assistant: improved min-move recommendations
- Guide camera pixel scale is now shown in the new profile wizard and the stats window
- Added a button to reset camera gain to camera's default value
- Altair cameras: update to SDK version 30.13010.2018.0926
- Altair cameras: new option to use older SDK for 2015/2016 era cameras
- Altair cameras: prevent connecting to the wrong camera when reconnecting after a disconnect
- Lowpass2: insure guide pulse never goes in the wrong direction; more debug logging
- Fix glitchy display when changing profiles by clearing the displayed image
- New profile wizard: center the dialog on the screen, not on the gear dialog
- Windows: fix PHD2 crash when opening the mount setup dialog after the RPC server has been terminated
- Fix bug in ProfileWiz - camera properties were being displayed on AuxMount tab if camera was Simulator
- Ensure backlash compensation is enabled only when Dec guide mode is Auto
- INDI: fix problem connecting Aux Mount that does not provide guiding properties
- Event server: send calibration step events
- Updated Traditional Chinese Translation
- Help file: add help for too-little east/south moves in calibration; fix broken link re focusing with Star Profile tool

v2.6.5dev6 | [Windows Download EXE](/phd2-2.6.5dev6-installer.exe)

### 2.6.5dev5

9 September 2018

- ZWO Cameras: fix a bug in 2.6.5dev4 that could prevent camera from connecting

v2.6.5dev5 | [Windows Download EXE](/phd2-2.6.5dev5-installer.exe)

### 2.6.5dev4

4 September 2018

- Simplified Z filter settings interface
- Bookmarks are now persistent across PHD2 sessions
- ZWO cameras: update SDK to version v1.13.0821 (Window, Linux, Mac)
- ZWO cameras: provide an option to operate camera in 8-bit or 16-bit mode
- ZWO cameras: use camera model name to decide which camera to connect to
- SBIG cameras: do not rely on camera name to distinguish color vs mono
- More detailed tooltip for status bar calibration indicator
- Update the Flip Calibration menu item and tooltip to make it more explicit that it flips the calibration immediately
- Server interface: return an error response for an invalid JSON RPC request
- Server interface: fix invalid JSON message output for alert messages with embedded newline characters
- Windows: better Windows version reporting in the debug log
- Better handling of errors that occur during application startup
- INDI Aux Mount selection no longer excludes mounts that do not have the GUIDER interface
- New Profile Wizard: use an 'on-camera' mount if camera = 'simulator'; add warning dialog if selected gear has no pointing info
- Remove the None guide algorithm (aka Identity guide algorithm) selection
- Updated Traditional Chinese translation

v2.6.5dev4 | [Windows Download EXE](/phd2-2.6.5dev4-installer.exe)

### 2.6.5dev3

23 July 2018

- Updated calibration settings window
- Calibration distance is now configurable
- New option to display mount corrections to scale on the graph
- New low-pass ZFilter guide algorithm (experimental)
- ZWO Cameras: use default gain setting reported by the driver (default gain was way too high)
- Guiding Assistant: fix problem with invalid min-move recommendations when GA is stopped and re-started
- Guiding Assistant: enforce minimum sampling time for making recommendations
- Remove unwanted check on guide rates when dec compensation is disabled
- Fix incorrect range checks on aggressiveness for Hysteresis and Resist Switch guide algorithms
- Log uploader: fix problem with log timestamps being garbled in some time zones
- Fix display of calibration graphs on Linux
- Fix problem with star profile not being displayed when search region is less than 15 pixels and star is close to the edge of the frame
- INDI: fix phd2 crash when another app sets the camera or mount Connected property to false
- event server: remove excessive debug log output when client is calling get_star_image
- Updated Traditional Chinese translation
- Help file updates

v2.6.5dev3 | [Windows Download EXE](/phd2-2.6.5dev3-installer.exe)

### 2.6.5dev2

2 July 2018

- ZWO ASI Cameras: update SDK to v1.13.0523 (Windows) and v0.7.0503 (Linux & Mac)
- SBIG cameras: fix problem not recognizing multiple SBIG cameras
- SSAG cameras (Mac): fix possible crash after connecting camera and allow entering arbitrary USB VID/PID values for cameras with corrupted firmware
- PPEC: allow stopping/starting guiding without resetting the model
- Guiding Assistant: fix handling of very large backlash to always show recommendations
- Updated Traditional Chinese, French, and Russian translations
- Debug log improvements

v2.6.5dev2 | [Windows Download EXE](/phd2-2.6.5dev2-installer.exe)

### 2.6.5dev1

23 May 2018

- More informative alert messages when runaway guiding is detected and for failed calibrations
- QHY cameras: update Windows SDK to V20180502_0 from QHY
- AO: remove irrelevant guide algo choices
- Update to wxWidgets 3.0.4
- Fix layout bug in BLC controls
- Minor debug logging improvements
- Lots of INDI improvements
- INDI cameras: automatically de-bayer color cameras
- do not allow overlapping RA and Dec guide pulses (overlaps can trigger a bug in some INDI drivers)
- better logging including a verbose logging option
- display the selected INDI devices in the Connect Equipment window
- only show camera drivers in the camera selection list and mount drivers in the mount selection list
- much better resilience to dropped connections from the INDI server
- cancellable progress window for INDI device connection
- fix INDI GUI excessive window updates by displaying the GUI after properties have been received from the server
- A bunch of help file updates
- Various improved tool-tip messages
- Updated Korean and Russian translations

v2.6.5dev1 | [Windows Download EXE](/phd2-2.6.5dev1-installer.exe)

### 2.6.5

30 April 2018

- Backlash compensation improvements
- Updated Russian and Traditional Chinese translations
- Updated Russian Help File
- Server API enhancements (fix a potential crash when the client instructs PHD2 to shutdown; add methods for setting and allow clients to get the name of the current guide algorithm on each axis.)
- Improved logging of events in the Guide Log, like exposure duration changed and PPEC parameter changes

v2.6.5 | [Windows Download EXE](/phd2-2.6.5-installer.exe)

### 2.6.4dev10

31 March 2018

- improved backlash compensation dynamic adjustment
- add additional control options for backlash compensation
- apply backlash comp for "fast recovery" moves after dithering
- apply backlash comp for AO mount bumps in declination
- simulator: fix lag in response to manual guide motions during long exposures
- Updated Traditional Chinese translation
- Updated Russian translation
- Updated Russian help file
- Windows: fix problem with log file uploader not seeing the full contents of the current session's logs
- log file uploader: fix layout of grid for non-English translations
- Polar drift tool: status line fix
- Polar drift tool: restore guiding on close

v2.6.4dev10 | [Windows Download EXE](/phd2-2.6.4dev10-installer.exe)

### 2.6.4dev9

1 March 2018

- Add some new options for better control of backlash compensation
- fix a problem that prevented some cameras from automatically re-connecting after a disconnect
- ZWO cameras: update SDK versions to V0.7.0118 (Linux/Mac) and V1.13.1.12 (Windows)
- Updated Traditional Chinese translation
- Polar drift tool: re-enable guiding when done
- min motion controls allow changing with finer increments
- server: fix problem with receiving empty commands from some clients
- fix problem with graph sometimes displaying the correction incorrectly when the Predictive PEC guide algorithm is in use
- simulator minor improvements for changing settings on the fly

v2.6.4dev9 | [Windows Download EXE](/phd2-2.6.4dev9-installer.exe)

### 2.6.4dev8

12 February 2018

- New tool to upload log files to openphdguiding.org
- Guiding Assistant: improved backlash test
- Altair cameras: updated SDK to version 20_12_2017
- Updated French translation
- Updated Help

v2.6.4dev8 | [Windows Download EXE](/phd2-2.6.4dev8-installer.exe)

### 2.6.4dev7

17 January 2018

- fix bug introuced in 2.6.4dev6 causing a new equipment profile to replace an existing profile
- updated help file
- updated French translation
- fixed spacing in polar drift align window
- Guiding Assistant: correct for dec drift and show an uncertainty estimate

v2.6.4dev7 | [Windows Download EXE](/phd2-2.6.4dev7-installer.exe)

### 2.6.4dev6

19 December 2017

- ZWO Cameras: update Windows SDK to V1.13.1.9
- SX Camera: fix pixel size value being reported incorrectly when square pixels option is enabled
- Updated Traditional Chinese translation
- Updated French translation
- Updated German translation
- Dither settling now ignores dec distance when dec guide mode is None
- Show help info in status bar as menu items are highlighted
- Drift align tool: fix problem with alignment circle sometimes following the guide star in Adjust mode when it is supposed to remain stationary
- Fix bug when guiding is initiated at the pole

v2.6.4dev6 | [Windows Download EXE](/phd2-2.6.4dev6-installer.exe)

### 2.6.4dev5

30 Nov 2017

- New Polar drift tool - drift alignment using a star field near the pole
- Static Polar Align tool updates
- Better detection and handling of changes to mount guide speed and camera binning
- Improvements to New Profile Wizard
- INDI fixes
- Updated French and Traditional Chinese translations
- Updated help file

v2.6.4dev5 | [Windows Download EXE](/phd2-2.6.4dev5-installer.exe)

### 2.6.4dev4

20 Oct 2017

- Star auto-selection no longer has 40-pixel edge distance restriction
- More explicit labeling of pixels vs arc-seconds units in graph window and stats window
- Remove modal dialog boxes from most camera connect functions
- Updated Traditional Chinese translation
- Updated French translation
- Static Polar Align tool improvements
- Add RA to guide log guide section heading

v2.6.4dev4 | [Windows Download EXE](/phd2-2.6.4dev4-installer.exe)

### 2.6.4dev3

8 October 2017

- Static Polar Alignment tool improvements
- Atik cameras: binning support added
- Server API: new methods for sensor temperature and cooler status

v2.6.4dev3 | [Windows Download EXE](/phd2-2.6.4dev3-installer.exe)

### 2.6.4dev2

3 October 2017

- Static Polar Align tool updates
- Add Static Polar Align and Drift Align tutorials to the Help file
- High resolution (4K) screen UI layout fixes
- Updated Traditional Chinese translation

v2.6.4dev2 | [Windows Download EXE](/phd2-2.6.4dev2-installer.exe)

### 2.6.4dev1

27 September 2017

- New Static Polar Align tool that uses the center of rotation of a polar field to align on the pole.

v2.6.4dev1 | [Windows Download EXE](/phd2-2.6.4dev1-installer.exe)

### 2.6.4

25 September 2017

- Fix bugs in calibration review and calibration sanity check when Dec guiding is disabled
- Update to latest ZWO ASI SDK

v2.6.4 | [Windows Download EXE](/phd2-2.6.4-installer.exe)

### 2.6.3dev8

2 September 2017

- Altair cameras: update to new SDK version (2017-09-01)
- Updated French translation from Cyril
- Guide log: only show gain value when PHD2 is controlling the gain
- AO: better handling of step failures: show an alert and suggest new AO travel limit setting
- AO: fix bump instability when guide star is far from lock position
- AO: make sure calibration covers full travel range
- INDI fixes
- Updated Windows INDI client libs
- Do not allow invalid hysteresis setting (100%)
- Fix problem with server sometimes not restarting when PHD2 is restarted
- Allow cam simulator to simulate async ST4 guiding
- Do not tie up main UI thread for GPxxx and INDI mounts and AO moves
- Include milliseconds in FITS header timestamps
- Help file updates
- Debug log enhancements

v2.6.3dev8 | [Windows Download EXE](/phd2-2.6.3dev8-installer.exe)

### 2.6.3dev7

18 July 2017

- Enable INDI support on Mac and Windows
- Disable Auto-select star when calibrating or guiding
- Updated French, Spanish and Traditional Chinese translations
- Help file updates
- Reset graph when gear profiles changes
- Event server: send a SettleBegin event when settling starts; added a new method to expose a single camera frame
- Windows: prevent windows firewall warning message after installing PHD2

v2.6.3dev7 | [Windows Download EXE](/phd2-2.6.3dev7-installer.exe)

### 2.6.3dev6

13 June 2017

- QHY cameras: fix incorrect guide directions when using On-camera (ST4) guiding
- Restart PHD2 automatically when language changes or when the Reset Configuration option is selected
- Help file updates
- New option to automatically check for software updates

v2.6.3dev6 | [Windows Download EXE](/phd2-2.6.3dev6-installer.exe)

### 2.6.3dev5

31 May 2017

- Updated Portuguese translation
- Windows installer - do not run the VC++ redistributable installer
- Fix text truncation with some translations in spctrograph slit position window
- Mac: fix crash when disconnecting GPUSB
- Adjust guiding parameters automatically when camera binning is changed
- PPEC: fix problem with min-move parameter not being honored
- Make sure not to retain calibration unless auto-load calibration is selected
- Display AO correction rate in AO graph window
- Help file updates
- Guard against too-small aggressiveness or hysteresis settings being entered
- Allow custom camera exposure duration selection

v2.6.3dev5 | [Windows Download EXE](/phd2-2.6.3dev5-installer.exe)

### 2.6.3dev4

29 April 2017

- fix RA/Dec overlay when AO is in use
- server API additions to get calibration information and send guide pulses to scope
- improve Guiding Assistant text layout for some translations
- additional debug log output for the PPEC guide algorithm
- A new Portuguese (Brazilian) translation
- Default Gain for QHY cameras is now 40
- update QHY camera SDK to V7.4.16.4
- Update Altair SDK to latest 1.1.4 version to support new camera models
- fix crash when stats window is updated and Camera = None
- update ZWO Linux/Mac SDK to V0.6.0328
- don't allow Predictive PEC period value to be disrupted when the guiding assitant is run
- updated French translation

v2.6.3dev4 | [Windows Download EXE](/phd2-2.6.3dev4-installer.exe)

### 2.6.3dev3

10 April 2017

- updated translations
- more strict protection against windows being placed off-screen after screen resolution changes
- Predictive PEC settings UI improvements in Advanced Dialog
- Predictive PEC key settings added to Graph window
- additional information saved to FITS headers when saving an image
- QHY cameras: we now use an up-to-date QHY camera SDK for native support of QHY cameras on Windows, Mac, and Linux

v2.6.3dev3 | [Windows Download EXE](/phd2-2.6.3dev3-installer.exe)

### 2.6.3dev2

28 March 2017

- New Predictive PEC guide algorithm!
- Mac: fix problem with SX camera not being found
- camera gain setting should not allow value 0
- comet tracking: adjust RA shift rate for scope declination

v2.6.3dev2 | [Windows Download EXE](/phd2-2.6.3dev2-installer.exe)

### 2.6.3dev1

20 March 2017

- New image logging options based on trigger events, like star lost or large error offset
- Option to determine star saturation based on ADU value rather than star profile
- Improved detection of low-snr stars by more accurate background calculation
- Improved star mass change detection
- New option to reject stars below a minimum size (HFD)
- AO: fix bug with AO bump continuing after server received Pause command
- add more info to fits headers when saving images
- event server: add get_settling method

v2.6.3dev1 | [Windows Download EXE](/phd2-2.6.3dev1-installer.exe)
