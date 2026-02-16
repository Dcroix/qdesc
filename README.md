# 📈  QSesc : Quick and Easy Descriptive Analysis
![Package Version](https://img.shields.io/badge/version-1.0.9.7-pink)
![Downloads](https://pepy.tech/badge/qdesc)
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
[![Socket Badge](https://badge.socket.dev/pypi/package/qdesc/1.0.9.5?artifact_id=tar-gz)](https://badge.socket.dev/pypi/package/qdesc/1.0.9.5?artifact_id=tar-gz)
[![DOI](https://zenodo.org/badge/990715642.svg)](https://doi.org/10.5281/zenodo.15834554)
![License: GPL v3.0](https://img.shields.io/badge/license-GPL%20v3.0-pink)

## <font face = 'Calibri' color = '#274472' >  Installation via Anaconda Prompt </font>
```sh
pip install qdesc
```

## <font face = 'Calibri' color = '#274472' >  Overview </font>
Qdesc is a package for quick and easy descriptive analysis. It is a powerful Python package designed for quick and easy descriptive analysis of quantitative data. It provides essential statistics like mean and standard deviation for normal distribution and median and raw median absolute deviation for skewed data. With built-in functions for frequency distributions, users can effortlessly analyze categorical variables and export results to a spreadsheet. The package also includes a normality check dashboard, featuring Anderson-Darling statistics and visualizations like histograms and Q-Q plots. The recent version includes functions that simplifies creating purposive data visualizations using Python. It scored 100/100 on Socket.dev for security, quality, maintenance, and licensing. Whether you're handling structured datasets or exploring statistical trends, qdesc streamlines the process with efficiency and clarity. 

Recent Updates:  
**Version 1.0.9.7:** Updated the README to reflect the changes in the outputs of qd.desc(), qd.grp_desc(), and qd.normcheck_dashboard() functions.  
**Version 1.0.9.6:** Updated the qd.desc(), qd.grp_desc(), and qd.normcheck_dashboard() function to use the SciPy "interpolate" method for Anderson-Darling p-value calculation, ensuring compatibility with SciPy => 1.17. Users no longer need to manually compare Anderson-Darling statistics with critical values; p-value is now returned directly.  
**Version 1.0.9.5:** Updated the Readme file.  
**Version 1.0.9.4:** Introduced docstrings for purposive data visualizations.  
**Version 1.0.9.1:** Provided docstrings for descriptive statistics functions. See them via function? (i.e., qd.desc?)  
**Version 1.0.8.8:** QDesc introduces three new visualization functions designed to make column, bar, and line charts more intentional and expressive.  


[Read More Here](https://pypi.org/project/qdesc/#description)

  
