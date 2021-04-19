# Frecuency-plot-package

This is a project to learn how to create Python packages and upload them to PyPi.org. I have created the Countplot class, which is used to visualize in a bar plot the frecuency of occurrence of a unique value list contained in an list-like column
    
    Attributes:
        - Color (string): the color of the bars in the plot
        - N_bars (int): number of top values that appear in the plot
        - Size (float array 2x1): size of the visualization
        - Title (string): title of the plot
        - Sep_type: separator between values in the original column
        - data: a list-like column
        

## Files

- frecuency_plot.py: Code that makes up the package
-  __init__.py: Constructor of the package
- license.txt: Terms of distribution of this package
- setup.cfg: Ini file that contains option defaults for setup.py commands. 
- setup.py: It’s the file where the package is configured and the command line interface for running commands that relate to packaging. 


## Insatallation
You can install this package as usual with pip or conda.

You can download the package from  [pypi.org](https://pypi.org/project/frecuency-plot/0.3/)
