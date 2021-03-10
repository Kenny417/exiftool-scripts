# exiftool-scripts
This is a collection of scripts I've written to automate a few things with ExifTool. 

## What is exiftool?
ExifTool is a command-line application created by Phil Harvey for reading, writing and editing meta information in a wide variety of image and video files. You can find more information and download instruction on [the official website](https://exiftool.org/). 

## My scripts
- `RenameFileToCreateDate.bat` is a simple batch file that renames every NEF, JPG, MOV, TIF, and .DNG in the directory to the date and time it was created (YYYY-MM-DD_hhmmss). This allows for easy sorting and avoids the problem of having files with names like `DSC_5474-1.jpg`. It's also nice when you have photos printed and the shop has an option to include the filename on the back. (so you always know when the photo was taken!)