# ChromTech Series III Plugin

This plugin provides basic control over the ChromTech Series III pump, 
including flow rate control, start and stop commands, and pressure monitoring.
The plugin keeps a log of all data collected in a CSV format for easy analysis
using a spreadsheet program.

## Installation

ChromTech Series III pump drivers are required to communicate with the 
pumps. Download the drivers from 
[here](https://www.github.com/RxnRover/driver_chromtech_series_iii) and extract
the files into your `<labview>/instr.lib` directory, where `<labview>` is the
location of your LabVIEW installation.

Download this plugin by clicking the "Code" button in the top right of its 
GitHub repository and selecting "Download ZIP". Extract the ZIP file into your 
`<documents>/Plugins/ReactorComponents` directory to finish installation. 
Create the `ReactorComponents` subdirectory if it does not already exist.