rydberg_experiment_tools
======

Collection of various tools in running the Rydberg experiment.


make_analysis_folders
------
Joe's script to automatically generate Raw_Data and Analysis folders and pull the latest version of Rydberg's analysis code [rydberg_analysis](https://github.com/KillianRice/rydberg_analysis) from GitHub. 


custom_scan_generator
------
Code to generate scans with varying linear point densities.

The idea is to be able to have a "low" density of data points (i.e., take big steps) where there are no atomic lines and a "high" density of data points (i.e., take small steps) where there are atomic lines.