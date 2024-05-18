# GPS-Speedreader
GPS Speedreader is a program to analyze GPS tracks from modern GPS
units. The program was specifically developed for the GPS Team
Challenge, in close collaboration with GPSTC advisors.

GPS Speedreader is free to use, and supplied without any warranties.

The current GPS Speedreader version is 2.2.3 released March 19, 2024.

## Downloads

The links below are ZIP files that contain the applications for MacOS
and Windows, and an executable jar file for Linux. _Downloads will be converted
to Github in the near future_.  
To run GPS
Speedreader, Java must be installed on your computer (version 8 or
newer). If Java is not installed on your computer, you can download it
for free from <https://www.java.com/en/download/> or
<https://adoptium.net/temurin/releases/>.

### MacOS

[Download the ZIP archive with the Mac application](https://github.com/prichterich/GPS-Speedreader/raw/e1a3d014a891efda722881944d5b52d49e5197f5/download/GPSSpeedreader2.2.3_Mac.zip)  and unpack the ZIP
archive. Requires MacOS 10.9 or newer.

After downloading and unzipping, move the application to your
application folder (or a folder of your choice). When you start GPS
Speedreader the first time, you will probably see a warning dialog "GPS
Speedreader can't be opened because it is from an unidentified
developer". To open the application anyway, you can right-click on the
GPS Speedreader icon, which will show a slightly different dialog that
gives you an option to open the application.

### Windows

[Download the ZIP archive with the Windows executable](https://github.com/prichterich/GPS-Speedreader/raw/e1a3d014a891efda722881944d5b52d49e5197f5/download/GPSSpeedreader2.2.3_Windows.exe.zip) and unpack the ZIP
archive.

After downloading and unzipping, move the application to a folder of
your choice. When downloading or running GPS Speedreader the first time,
you may see one or more warning dialogs from Windows and/or your
antivirus software that you have to click through.

### Linux

[Download the ZIP archive with the jar file](https://github.com/prichterich/GPS-Speedreader/raw/e1a3d014a891efda722881944d5b52d49e5197f5/download/GPSSpeedreader2.2.3.jar.zip)
and unpack the ZIP archive.

After downloading and unzipping, move the GPSSpeedreader.jar file to a
folder of your choice. If Java is correctly installed on your system,
you should be able to start GPS Speedreader by double-clicking on the
GPSSpeedreader.jar file.

## Recent Changes

### Version 2.2.3

-   New ability to save and import defined background maps
-   Polar plot improvements
-   Improved support for files that do not have doppler speed data
-   Multiple bug fixes

### Version 2.2.2

-   Accuracy improvements in turn analysis
-   Several improvements for 1 Hz data
-   Fixed a bug reading GPX files with time stamps containing second
    fractions

### Version 2.2.1

-   New turn analysis window with option to analyze jibes, tacks, or
    both
-   New "Sorted Speeds" window
-   Fixed a problem with viewing results in browser for file names with
    unusual (non-ascii) characters

### Version 2.1.4

-   Fixed a bug that sometimes caused the date to be off by one day when
    posting to GPSTC
-   Remove filtered trackpoints when erasing filtered speeds
-   Require identical data rates and similar file sizes to build
    "intelligent average" tracks

### Version 2.1.2

-   Fixed bugs that caused time for data from .gpy files to be shown
    incorrectly, and wrong times saved when exporting to .gpy files
-   Added a workaround for .gpy files which contain records with invalid
    time stamps

### Version 2.1.1

-   Support for reading files in .gpx format and speed calculations when
    "doppler" speeds are missing
-   Support for reading and exporting files in the new "compact GNSS"
    (.gpy) format
-   The default format when exporting tracks is now .gpy. To export in
    .sbp format, change the file extension to .sbp when exporting.
-   When comparing two files using the "Compare Files" function and the
    two files have the same number of points, and either different
    extensions or nearly identical file names, a point-by-point
    comparison of all data items is done (intended for testing reading
    and writing in new file formats like .gpy)

### Version 2.0.1

-   Support for "intelligent averaging" (intented for DIY loggers
    mounted to both sides of the boom)
-   Open dialogs now allow.the selection of multiple files
-   Separate and lower accuracy filter thresholds for files from u-blox
    GPS units (Motion, DIY loggers)
-   Read FIT files from Garmin, Coros, and other watches
-   Alphas can now partially (for up to half of the points) overlap with
    faster alphas
-   When comparing files, very small differences are not highlighted in
    the results table any more (up to 0.04 knots for speeds, and 0.2%
    differences in distance)

### Version 1.4.3

-   Fixed an issue where exported SBP files sometimes contained wrong
    dates
-   Better handling of very large files on Windows with some older
    (32-bit) Java versions

### Version 1.4.2

-   Fixed a problem reading .sbp files with non-Locosys headers
-   Additional speed improvements for alpha calculation if files have
    large stationary periods

### Version 1.4.1

-   New "Angle to wind" column
-   Polar plot improvements
-   Added ability to compare files from different dates

### Version 1.4.0

-   Added "Export" to save tracks to files in SBP format; bug fixes

### Version 1.3.8

-   Support zooming in the tracks and speed panels using keyboard
    shortcuts; bug fixes

### Version 1.3.7

-   Added "Forget map.." to "View" menu to remove outdated background
    maps

### Version 1.3.6

-   Support for background maps
-   Distance measurements in the tracks panel by alt-dragging (Linux
    users may need to press alt+shift while dragging)
-   Alphas with 60 and 70 m gate widths are now also shown in the
    results table
-   Sliders for zooming in the tracks and speed panels
-   New options to highlight the selected regions by color, and to set
    the line width for the selection
-   Faster calculation of alphas for files with long stationary periods
-   New latitude and longitude column options for the trackpoint table

### Version 1.3.4

-   Better handling of Motion .oao files with corrupt records
-   Support .sbp files that contain older sessions after newer sessions

### Version 1.3.3

-   Changed posting to GPSTC to use the same window and https to get
    around problems that some browsers showed recently

### Version 1.3.3

-   Changed posting to GPSTC to use the same window and https to get
    around problems that some browsers showed recently

### Version 1.3.2

-   Fixed a bug reading UBX files from 2020

### Version 1.3.1

-   Fixed a problem where export to Google Earth produced incorrect
    files on computers using languages other than English
-   New "Combine files" function

### Version 1.3.0

-   If files contain multiple sessions, users can choose which session
    to analyze
-   New "Remove filtered points" and "Remove selection" menu items
-   Turn analysis (experimental) shows turns with the highest minimum
    speed in the speed results table. The second column shows the
    "score" - the percent of the maximum entry speed (looking back 50
    meters from the turn center) kept.

### Version 1.2.9

-   Handle time rollbacks (leap second adjustments) in files correctly
-   Fixed a minor bug in results table (number of results not changed
    correctly when filters change)

### Version 1.2.8

-   Support .sbn files (from GT-31)
-   Option to define highlight colors when exporting to Google Earth
-   Bug fixes

### Version 1.2.7

-   Export for Google Earth
-   Show speed as tooltips in speed panels

### Version 1.2.5

-   Better highlighting of selection regions in tracks (thicker lines,
    crosshair is at first selected point)
-   Popup menu in tracks panel to allow easy switching between drawing
    full and partial tracks

### Version 1.2.4

First public release.
