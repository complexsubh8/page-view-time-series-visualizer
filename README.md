# Page View Time Series Visualizer

This project is part of the freeCodeCamp Data Analysis with Python certification.

## Project Overview

The goal of this project is to visualize time series data from the freeCodeCamp forum using:

* Pandas
* Matplotlib
* Seaborn

The dataset contains daily page view counts from May 2016 through December 2019.

## Features

### Data Cleaning

* Removed the top 2.5% outliers
* Removed the bottom 2.5% outliers

### Visualizations

#### Line Plot

Shows daily forum page views over time.

#### Bar Plot

Displays average monthly page views grouped by year.

#### Box Plots

* Year-wise Box Plot (Trend)
* Month-wise Box Plot (Seasonality)

## Installation

```bash
pip install pandas matplotlib seaborn
```

## Usage

```bash
python main.py
```

Generated files:

* line_plot.png
* bar_plot.png
* box_plot.png

## Project Structure

```text
page-view-time-series-visualizer/
│
├── fcc-forum-pageviews.csv
├── time_series_visualizer.py
├── main.py
├── line_plot.png
├── bar_plot.png
├── box_plot.png
└── README.md
```

## Author

Subham Sarkar

## Certification

freeCodeCamp - Data Analysis with Python
