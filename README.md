# LabView-Controls-AMS
LabView Controls for the AMS beam line as of April 21, 2016

Many of these files were initially written by Daniel Robertson, then edited by Matthew Bowers, and then edited by Karen Ostdiek. 
Briefly the file CriticalComponents.vi handles things like vacuum readings, gate values, and the Wien Filter (things that rely on the vacuum being good). DetectorOnly.vi handles changing the voltage on the PGAC and IC. ShieldOnly.vi handles the moving of the shield. SCOnly.vi handles things in the scattering chamber (the target ladder and the silicon detector). WriteGlobalVariables.vi handles writing some values to a text file. If you save the text file in Dropbox, for example, you can access this information away from the computer/campus.
