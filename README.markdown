Jake's MapBasic Toolbar
=======================

A selection of useful tools for MapInfo written in mapBasic.


Requirements
============

These programs have been written in MapBasic 10.5. They *may* work on some older versions but I have no way of testing this. They definitely *don't* compile on v6.5 or earlier. Please let me know if you have tried/succeeded/failed to compile them on an earlier version.


Features
========

__Batch export plans__ 
Export one plan per record in a table with just a few clicks. [Screenshot](http://deviouschimp.co.uk/misc/mapbasicscreenshots/SitePlanExporterScreenshot.png "Screenshot")

* Choose output size and resolution. 
* Override the layer styles
* 13 different output file formats, including PNG, BMP, WMF, JPEG, TIFF, PSD, EMF etc.

__Show overlapping objects__ - Displays objects from a table which overlap other objects in that table. [Screenshot](http://deviouschimp.co.uk/misc/mapbasicscreenshots/OverlapDetector.png "Screenshot")

__Constraints Overlaps__ - Compare one against multiple other tables and find overlaps. Useful for comparing a table of potential sites with tables of constraints such as flood area or areas of scientific interest.

__Update areas__ - Update the area column of a table with the size of the attached objects. [Screenshot](http://deviouschimp.co.uk/misc/mapbasicscreenshots/UpdateAreas.png "Screenshot")

__Export MIF DXF and SHP at once__

__Show unmapped records__

__Save and Recall Mapper Location__ - Save a map window's location and zoom setting for quicker navigation. Similar to the NamedViews program that comes with MapInfo but saves views to a table to be used per-workspace rather than per-installation.

__Window Tool__ - [Screenshot](http://deviouschimp.co.uk/misc/mapbasicscreenshots/WindowTool.png "Screenshot")

* Create basic A4/A3 landscape/portrait layout windows from other windows.
* Rename windows
* Duplicate windows
* Rotate windows (beta)

__Projection Tool__ - Find projection information and other information about tables and windows. [Screenshot](http://deviouschimp.co.uk/misc/mapbasicscreenshots/WindowInfo.png "Screenshot")

__Circle Tool (beta)__ - Draw a circle of a given area/radius/circumference
**Note:** There have been issues with projections when using this tool. It should work correctly now but you might want to double check the size of the generated circle.

__Line Tool (beta)__
 * A simple line tool. Basically a duplicate of MapInfo's built-in line tool.
