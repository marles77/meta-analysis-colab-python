# Meta-analysis with Colab and Python
Perform meta-analysis in Google Colab using Python &amp; R via rpy2 package.

## Aim
Creating a meta-analysis template in Python, including generating a forest plot and a funnel plot to assess publication bias.

## Problem
Python lacks a stable, mature package for meta-analysis, and the existing API from [statsmodels](https://www.statsmodels.org/stable/stats.html#module-statsmodels.stats.meta_analysis) is still in experimental version. R, on the other hand, provides well-designed and tested packages, like [metafor](https://wviechtb.github.io/metafor/) which remains a standard in scientific publications. However, some people (such as myself) choose Python as their preferred programming language for data analysis and visualization. If we want to keep our code neat, consistent and easily accessible it turns out that we do not have a good optin here.

## Solution
R provides excellent code for reliable meta-analysis. Python + Numpy + Pandas + Matplotlib enable flexible and readable code and visualizations. Thanks to [rpy2 package](https://rpy2.github.io/) binding both technologies is really easy. rpy2 provides an interface to R that converts R objects to Python objects. Since both interpreters are installed in Google Colab by default, we can use and exchange data between R and Python in one notebook. 

## Usage
Open the notebook in Google Colab. Provide data, modify the code to customize plots etc.

## Features
The notebook allows to upload data, perform a meta-analysis and generate graphs ready for publication.

## Limitations and known issues
No issues reported so far.
