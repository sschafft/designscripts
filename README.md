# Indesign Scripting
---
These scripts are used to make indesign production slightly easier and more manageable. This uses our own flavour of markdown and will eventually be converted to align with HTML and potentially include object styles for indesign templates.

## Install
To install, clone the repo to the following folder (Macintosh OSX)

`git clone git@github.com:biveeco/designscripts.git ~/Library/Preferences/Adobe/Adobe\ Indesign/Version\ 11.0/en_US/`

## Contents
These design scripts include the following functions:

### GREP Query Manager
The query-manager script displays an overview of all GREP queries, showing each query's name, find expression, and change expression. The script aims to address various shortcomings of InDesign's possibilities to manage queries, such as InDesign's inability to chain existing queries and to edit GREP expressions conveniently. The script is a panel, so you can keep it open and work in InDesign.
[Click here](http://www.kahrel.plus.com/indesign/grep_query_manager.html) for documentation on the GREP Query Manager.

### GREP Find-Change Queries
These queries use our own flavour of markdown. 

### Print Settings
We use three different job processes when exporting Indesign files – Print, Web [High Quality], Web [Optimised].

The only setting that changes when exporting files is whether to export as spreads or single pages. **IMPORTANT** cover pages for print are always exported as spreads, and body pages for print are always exported as singles.

To load the print presets, open Indesign and navigate to the following

`File > Adobe PDR Presets > Define`

Then click on `Load` and navigate to the folder containing the print presets and select the export settings to be loaded. These presets will be available when exporting Indesign files to PDF.

### Image Pre-Processing
When managing images for Indesign projects, the preferred format is over 300dpi and in TIFF format. This Photoshop action is loaded by double clicking on the file.

## Future Improvements
+ Modifying the GREP scripts to use traditional HTML
+ Develop object styles to apply to specific elements such as figures and images
