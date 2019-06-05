# ProFit

INSTRUCTIONS FOR INPUT FILE GENERATION

First row: Concentration of receptor in competitive experiment (0 if there is no competitive experiment) (in uM)
Second row: 0 or 1 for Normal or forced fit during 'Fit two files'
After second row, tabulated
First column: Concentration of direct experiment (in uM)
Second, third, fourth column: data points for direct experiments
Fifth column:  Concentration of competitive experiment (in uM)
Sixth, seventh, eighth column: data points for competitive experiments


The name of the input file:

title_of_the_direct_experiment.title_of_the_competitive_experiment.x_axis_in_direct_experiment.x_axis_in_competitive_experiment.txt


In the tutorial folder, you will find all the experimental data for the TRPM4 measurements, including the already processed report sheets and figures. You can simply copy all the files from the RAW folder of the tutorial to the RAW folder of the working directory to re-run the analysis. Due to the Monte Carlo approach, you should expect some variations in the results. (It is recommended to increase the number of cycles to at least 250-1000, depending on the data quality.)
