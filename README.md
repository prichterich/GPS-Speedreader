# GPS-Speedreader
GPS Speedreader is a program to analyze GPS tracks from modern GPS
units. The program was specifically developed for the GPS Team
Challenge, in close collaboration with GPSTC advisors.

GPS Speedreader is free to use, and supplied without any warranties.

The current GPS Speedreader version is 3.0.4 released August 31, 2025. 
Version 3.04 added options to change misclassified turns, for example jibes to tacks; added an option to change text size when exporting to Google Earth; and fixed bugs in the calculation of turn diameters and minimum speed.

## Downloads

The links below are ZIP files that contain the applications for MacOS
and Windows, and an executable jar file for Linux.  

To run GPSSpeedreader, Java must be installed on your computer (version 8 or
newer). If Java is not installed on your computer, you can download it
for free from <https://www.java.com/en/download/> or
<https://adoptium.net/temurin/releases/>.

### MacOS

[Download the ZIP archive with the Mac application](https://github.com/prichterich/GPS-Speedreader/raw/main/download/GPSSpeedreader_Mac.zip)  and unpack the ZIP
archive. Requires MacOS 10.9 or newer.

After downloading and unzipping, move the application to your
application folder (or a folder of your choice). When you start GPS
Speedreader the first time, you will probably see a warning dialog "GPS
Speedreader can't be opened because it is from an unidentified
developer". To open the application anyway, you can right-click on the
GPS Speedreader icon, which will show a slightly different dialog that
gives you an option to open the application.

### Windows

[Download the ZIP archive with the Windows executable](https://github.com/prichterich/GPS-Speedreader/raw/main/download/GPSSpeedreader_Windows.zip) and unpack the ZIP
archive.

After downloading and unzipping, move the application to a folder of
your choice. When downloading or running GPS Speedreader the first time,
you may see one or more warning dialogs from Windows and/or your
antivirus software that you have to click through.

### Linux

[Download the ZIP archive with the jar file](https://github.com/prichterich/GPS-Speedreader/raw/main/download/GPSSpeedreader.jar.zip)
and unpack the ZIP archive.

After downloading and unzipping, move the GPSSpeedreader.jar file to a
folder of your choice. If Java is correctly installed on your system,
you should be able to start GPS Speedreader by double-clicking on the
GPSSpeedreader.jar file.

## Recent Changes

### Version 3.0.2

- Interpolate (and list) repeated points; fixed parsing float COG in FIT files
- Added "Draw/Hide positional speeds" to popup menus (if "Show expert menu items and columns" is selected in the preferences)
- Multiple bug fixes, including drawing alpha circles correctly and tracking GNSS settings on Garmin watches correctly

For additional details and changes in older versions, please read the [change log](CHANGELOG.md)
