Oxid-Docset
===========

Full Oxid documentation in apple docset format, to use with Dash

Importing into Dash
==========
After downloading the docset from this repo, open Dash and open the preferences.
If you see the _preferences_ window, go to the _docset_ tab and click on __+__ at the left bottom of the _en_ tab and navigate to the downloaded docset file.
Thats it, now you can browse the documentation of OXID.

Notes
=========
Actuall this is only a test, so it is a old version of OXID, because i didn't have a newer one locally.


How to generate your own docset?
=========
Dash is a realy cool tool, it have so many documentations delivered, but where it goes to the max is, when you can browse the full documentation, and even search throw it.
That's impossible, false, it is possible, you can use your own docsets with Dash.

All you need is [Doxygen](http://www.stack.nl/~dimitri/doxygen/), which can parse your project documentation.
Download it, start it and go to the HTML Preferences in List, which have a entry _GENERATE_DOCSET_, only availeable in expert mode, and some related configuration options which can be set to generate the makefile for generating the docset.
Don't forgett to set all other option, like output directory, project name, etc.
Now you can run Doxygen by clicking the _Run doxygen_ button under the _run_ tab.
After doxygen is finished, you can got to the output folder and call the _Makefile_ in the _html_ subfolder.
This takes a little time and afterward you have a docset inside the _html_ folder, which you can import into Dash.
Thats it, now you can have so much fun with your project documentation, even if you are not connected, e.g.: on a long trip ;)

