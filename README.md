# Theta burst analyzer for Le et al

System requirements: 
Numpy 
matplotlib 
csv 
xlwt

To run, install Python3, then open file and hit play (or run through standard Python methods). Enter directory and output directory. Should take 2s per file.

Sample output provided in "output" sample input in "input".

Outputs explained- png of file name is a photo of what was counted (up till where there is no data). Purple dots indicate burst heights with baseline correction. Red lines are start of the theta burst area measure. Green line is the end of the area measure. Blue lines are fixed width stop relative to the start of each area measure. Green is adaptive baseline (used in this paper). The 'art' graph is the area with artifacts removed (used in this paper).

There are lots of sheets in the data_report. The relevant tab is 'art adapt Auc' which is artifact-removed, baseline-adapted code measuring the area under the curve, and 'burst_heights' which measures the amplitude of each pulse within a burst.
