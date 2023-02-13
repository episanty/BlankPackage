BlankPackage: a Mathematica package template 
====

This notebook is a template to start Mathematica packages. 


How to use
----------
To use, basically, replace "BlankPackage" with your package name (and any descriptions with the descriptions for your package) on all the relevant places:
 - Most importantly, open the notebook file, BlankPackage.nb, on a text editor, and search-and-replace the string 'BlankPackage' for your chosen package name.
 - Update the package description and homepage on the initialization cell at the end of the Readme section of the notebook file, which prints out a brief description onto the .m package (after which you can collapse the cell and forget about it).
 - Update the headers on File > Printing Settings > Headers and Footers.
 - Update the Readme cell with your own package description.
 - Update the Licensing section below with your chosen license.
 - Start writing! This is probably best done where the SampleFunction definition is.


Features
--------
After all that, you will have created a notebook master from which Mathematica will automatically create a package .m file every time you save the notebook. Why use this template?
 - The package privacy options have been set correctly: the Track Notebook History option has been turned off (ensuring that this notebook file can play reasonably well with source-control software), and FileOutlineCache has been set to False.
 - You get a number of handy commands for dealing with the package infrastructure, including a version number that includes the timestamp at which the notebook file was last saved, and an interface with git.
 


Licensing
---------
This template is © Emilio Pisanty 2023 and it is licensed under the MIT License. If you distribute it unchanged or in the form of an edited template file, then please abide by the conditions of that license (which essentially mean, retain the copyright notice). That said, if you use this template to create a new package, then please feel free to remove all of the BlankPackage copyright information and deal with your package files as you see fit.
