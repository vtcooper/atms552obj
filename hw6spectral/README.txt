Homework #6 Cross-Spectral Analysis 2020
 
Get the ‘filename’ HW6Spectral_2020.mat from the class ftp directory
Go to the following link in a web browser:
ftp://eos.atmos.washington.edu/pub/dennis/552_Class/’filename’
or 
wget ftp://eos.atmos.washington.edu/pub/dennis/552_Class/’filename’
from a unix shell.
 
This file contains two arrays that are 16years times 365.25 days long.  They are called x552csp and y552csp.  Rename them x and y.  You are looking for periodicities in these two timeseries and relationships between the two timeseries that will be revealed by cross-spectral analysis.
 
•	Remove the annual cycle from each time series. I suggest regression.
•	Do power spectral analysis to search for significant spectral peaks in both time series. Use red noise as your null hypothesis.  You can try prewhitening, if you wish, or fit the red noise spectrum as your null hypothesis.
•	Do cross-spectral analysis to look for coherence and phase relationships between the two timeseries.
•	Answer the following questions: What are the significant peaks in the power for the two timeseries and at what frequencies do they occur?  Are the two timeseries coherent at any frequencies?  If so, what is the phase relationship between them?
 
In writing up your analysis you need to specify each step in the process, so that someone else could reproduce your analysis.  This is the scientific method, BTW.  Let me know whether you programmed this in Matlab, Python, or something else.

