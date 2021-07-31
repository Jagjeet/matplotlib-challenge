# matplotlib-challenge

This project analyzes the data from the Pymaceutical study of various drugs in mice including Pymaceutacal's own Capomulin. Overall, Capomulin appears worthy of further research. For more information see the analysis in the `pymaceuticals_analysis.ipynb` Jupyter Notebook. A final analysis including observations (3) can be found in the top cell of the notebook.

## Prerequisites

To run this project the following tools are needed:

* Python (tested with v3.85, earlier versions may work as well, but have not been tested)
* Jupyter Notebooks and/or Jupyter Labs
* Anaconda is recommended though library dependencies can be installed individually as well.

## Usage

Clone the respository and open and run the `pymaceuticals_analysis.ipynb` from Jupyter Notebook or Jupyter Labs.

Analysis can be viewed in the individual cells.

## Known Issues

* In some cases data from previous Jupyter cells are used to calculate values in the current cell. As such make sure to run all above cells to obtain the correct output

## References

The Pymaceutical analysis made use of the following concepts and links in addition to the Pandas/Plotly documentation.

### Matplotlib Markers

* https://matplotlib.org/stable/api/markers_api.html

### Boxplot Reference

https://towardsdatascience.com/create-and-customize-boxplots-with-pythons-matplotlib-to-get-lots-of-insights-from-your-data-d561c9883643

### Avoiding NANs in Pandas Dataframes After Merging

https://stackoverflow.com/questions/46754398/pandas-merge-returns-nan
