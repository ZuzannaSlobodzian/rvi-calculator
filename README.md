# RVI Calculator
## The RVI Calculator developed on the Creodias platform during a Data Science internship

The most popular approach to monitoring vegetation involves analyzing optical data. However, this method has limitations - optical data cannot be used during high cloud cover or nighttime. Fortunately, vegetation analysis is also possible using radar data. For instance, vegetation cover and height can be assessed by calculating the Radar Vegetation Index (RVI). Radar data overcomes issues related to cloud cover and time of day, as radar can capture data regardless of these factors.

The project used radar data from Sentinel-1, with dual VV and VH polarization modes. The data analysing involved creating a graph in SNAP software using the GUI on a virtual machine and then exported to an XML file. Then, the graph was parameterized to allow for the input of different file paths and executed from Python using the subprocess module. Finally, the Radar Vegetation Index was calculated using the formula: RVI = (4 × VH) / (VV + VH).

Quick data processing was enabled due to CREODIAS platform. 
