# Guided Lab 386.6.1 – Creating Scatter Plots with Matplotlib

## Overview

This lab introduces scatter plots using Matplotlib to visualize relationships between variables. It demonstrates how to customize marker size, color, transparency, and colormaps to create more informative and visually appealing data visualizations.

## Objectives

* Create scatter plots using Matplotlib
* Visualize relationships between two variables
* Customize marker size, color, and transparency
* Apply colormaps to represent additional data dimensions
* Analyze real-world datasets using scatter plots

## Technologies Used

* Python 3
* Matplotlib
* NumPy
* Pandas
* Google Colab / Jupyter Notebook

## Methods & Concepts

* `plt.scatter()` – Create scatter plots
* `plt.colorbar()` – Display the color scale used in the plot
* `plt.figure()` – Create and size a new figure
* `plt.title()` – Add a chart title
* `plt.xlabel()` / `plt.ylabel()` – Label the axes
* `plt.legend()` – Display a plot legend
* `np.random.randint()` / `np.random.randn()` – Generate random data for visualization
* `pd.read_csv()` – Load a real-world dataset into a DataFrame

## Key Scatter Plot Parameters

| Parameter | Purpose                                 |
| --------- | --------------------------------------- |
| `x`       | X-axis values                           |
| `y`       | Y-axis values                           |
| `s`       | Marker size                             |
| `c`       | Marker color or values mapped to colors |
| `marker`  | Marker shape                            |
| `cmap`    | Colormap used for color mapping         |
| `alpha`   | Marker transparency                     |

## Topics Covered

* Creating basic scatter plots
* Customizing marker size
* Changing marker colors
* Adjusting marker transparency
* Applying colormaps
* Displaying colorbars
* Comparing multiple scatter plots
* Visualizing randomly generated datasets
* Analyzing real-world housing data using scatter plots
* Representing multiple variables through marker size and color

## Dataset

* Randomly generated NumPy datasets
* California Housing dataset (loaded with `pd.read_csv()`)

## Learning Outcome

By completing this lab, I gained hands-on experience creating and customizing scatter plots with Matplotlib, using marker size, color, transparency, and colormaps to visualize relationships and represent multiple variables within a single chart.
