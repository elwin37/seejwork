# seejwork
Work for SW on his proposal

10/01/2019: First draft upload.
Jupyter notebook for data analysis: SEEJwork_meta.ipynb
Edited rosat archive positions file to remove carriage return issue: rosarchive_final_fix_carraige_return.pos
The TESS transit crossing events TCE files for regions 1 and 2:  tess_tce_sector[1,2]
The TCE files are all the candidate planet crossings detected by the current TESS reduction pipeline. Way better than what I can do on short notice! :) 
ROSAT has a positional accuracy of 10-20" and a resolution of ~60"

RESULTS:
There are no matches between the TCE sources and the ROSAT sources in the archive within 60".
Closest is ~200"

Will continue with the XMM Slew Survey and Chandra archives to see if there is anything there.

Chandra: 
Returning 45 field matches within 10 arcmin to TCE 1.  Would need to actually go to observations and perform source extraction to see if any of the TCE objects are detected... Too time consuming for me! 
But upper limits would be available at least. 

XMM-Newton:
About 150 of the 550 in the first half of the TCE 1 file have coverage within 30 arcmin (most likely from the Slew Survey). 
Returns a list of OBSIDs for further investigation, so likely some detections or upper limits in there too..


