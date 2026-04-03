# 
Code examples related to the article "Regional atmospheric pattern shifts associated with weather whiplash events in the Upper Yangtze River Basin"

The SOM analysis in this study is implemented using the somoclu library.   
Python Version: 3.10.19. Somoclu Version: 1.7.6.   
For detailed installation guides and usage instructions, please refer to the Official Somoclu Documentation (https://somoclu.readthedocs.io/en/stable/).  

Data (GPH/TP/Temp) anomalies were calculated by subtracting the 44-year mean values for each calendar day on each grid-point.

Below is a brief overview of the core scripts and their functionalities.  
1_SOM_train: SOM model construction, training, and output generation.  
2_feature: Annual/seasonal node occurrences, frequencies, and trend analysis based on SOM outputs.  
3_extreme_events: Statistical analysis of annual/seasonal extreme precipitation and temperature events. Plot Fig.4 and Figs.S5-S8.  
4_pattern_fig: Code for plotting Fig.2.  
5_pattern_link: Code for plotting Figs.3 and 7.  
6_lde_wwe_change_plot: Identify LDE and WWE, and plot Fig.5 and Fig.S9.  
7_wwe_plot: Code for plotting Fig.6.  

This is a preliminary version; further optimizations are possible.  
Questions and suggestions are welcome via: zeycrystal@163.com  
Please cite the relevant papers when using this code. Thank you!
