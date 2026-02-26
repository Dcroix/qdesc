# 📈  QDesc : Quick and Easy Descriptive Analysis
![Package Version](https://img.shields.io/badge/version-1.1.1-pink)
![Downloads](https://pepy.tech/badge/qdesc)
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
[![Socket Badge](https://badge.socket.dev/pypi/package/qdesc/1.0.9.5?artifact_id=tar-gz)](https://badge.socket.dev/pypi/package/qdesc/1.0.9.5?artifact_id=tar-gz)
[![DOI](https://zenodo.org/badge/990715642.svg)](https://doi.org/10.5281/zenodo.15834554)
![License: GPL v3.0](https://img.shields.io/badge/license-GPL%20v3.0-pink)

## <font face = 'Calibri' color = '#274472' >  Installation via Anaconda Prompt </font>
```sh
pip install qdesc
```

## <font face = 'Calibri' color = '#274472' >  Update to recent version (for existing users) via Anaconda Prompt </font>
```sh
pip install --upgrade qdesc
```

## <font face = 'Calibri' color = '#274472' >  Overview </font>
Qdesc is a package for quick and easy descriptive analysis. It is a powerful Python package designed for quick and easy descriptive analysis of quantitative data. It provides essential statistics like mean and standard deviation for normal distribution and median and raw median absolute deviation for skewed data. With built-in functions for frequency distributions, users can effortlessly analyze categorical variables and export results to a spreadsheet. The package also includes a normality check dashboard, featuring Anderson-Darling statistics and visualizations like histograms and Q-Q plots. The recent version includes functions that simplifies creating purposive data visualizations using Python. It scored 100/100 on Socket.dev for security, quality, maintenance, and licensing. Whether you're handling structured datasets or exploring statistical trends, qdesc streamlines the process with efficiency and clarity. 

### Recent Updates:  
**Version 1.1.1:**
- Fixed the following: qd.purvis_bar function to return fig, ax for easy image save.  
- Fixed the QDesc ReadMe file.

**Version 1.1.0:**
- Introduced two new functions, purvis_rose and purvis_bubble, to create purposive rose charts and bubble charts respectively.  
- Updated the docstring and provided specific details on the Return section for purposive data visualization functions.  
- Updated data visualization functions to return fig, ax for easy image save using: fig.savefig("datavis.png", dpi=300).  
- Provided a link to available QDesc Color Palettes in said section of this Read Me.

**Version 1.0.9.9:**
- Updated dependency versions to ensure compatibility and prevent import errors with recent scipy releases.

## <font face = 'Calibri' color = '#274472' > QDesc Function Demonstrations </font>
* [QDesc Descriptive Functions and Normality Testing Sample One](https://github.com/Dcroix/qdesc/blob/main/Qdesc%20Demo%20Notebook%20One.ipynb) *(right-click → Open in new tab)*
* [QDesc Descriptive Functions and Normality Testing Sample Two](https://github.com/Dcroix/qdesc/blob/main/Qdesc%20Demo%20Notebook%20Two.ipynb) *(right-click → Open in new tab)*
* [QDesc Purposive Data Visualization Samples](https://github.com/Dcroix/qdesc/blob/main/Qdesc%20Demo%20Notebook%20Three.ipynb) *(right-click → Open in new tab)*

### Version 1.1.1 works with the following libraries:
- pandas>=3.0.0  
- numpy>=2.4.2  
- scipy>=1.17  
- seaborn>=0.13.2  
- matplotlib>=3.10.8  
- statsmodels>=0.14.6
  
[Read More Here](https://pypi.org/project/qdesc/#description)

  
