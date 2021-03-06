# documentation

# Structure
* Path for pictures: src/Images/. Each picture should be stored in a folder with the same name as the documentation section.
* Path for MD files: src/md/src/. Each section is located in the folder of the same name.
In the section there is a main file (index.md) and files of subsections.

>**Note**
The first level header can only be contained in the main file(index.md) in a single instance.
Subsections files can have headers of the second and higher level.

# Guide

## Block image
To display the picture, use the following syntax:
```$xslt
[ ![ImageName](tumbImagePatch) ](imageOrYoutubePath)
```
* ImageName - the name of the image that will be displayed if there are errors during the download.

* tumbImagePath - the address of the picture that will be displayed when the documentation is displayed. 
There should be certain sizes of 1000x768.
For example: 'Images/userGuide/manageLaunches/MergeScheme.png'

* imageOrYoutubePath - the name of the image or link to youtube which will be shown when clicking on the picture.
For example 'Images/userGuide/manageLaunches/MergeScheme.png' or 'https://youtu.be/7PZIowd9III'

## Block note
To display the block 'Note', use the following syntax:
```$xslt
>**Note:**
yout note text
```