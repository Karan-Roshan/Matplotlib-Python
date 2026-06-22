# Matplotlib Python Library
> A comprehensive, hands-on study of the **Matplotlib** data visualization library in Python — covering everything from basic plots to 3D visualizations, documented as a structured Jupyter Notebook.

## Overview
This repository contains a fully documented Jupyter Notebook (`Matplotlib_Python_Library.ipynb`) that covers the **complete Matplotlib library** from the ground up. Each section includes working code examples, explanations, and visual outputs — making it an ideal reference for data science learners, Python developers, and interview preparation.

## Table of Contents
### Getting Started
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Introduction to Matplotlib</td>
      <td>What Matplotlib is and why it matters</td>
    </tr>
    <tr>
      <td>Data Visualization</td>
      <td>Overview of visualization concepts</td>
    </tr>
    <tr>
      <td>Components of a Figure</td>
      <td>Axes, Figure, Canvas, Renderer</td>
    </tr>
    <tr>
      <td>Installing Matplotlib</td>
      <td><code>pip install matplotlib</code> setup guide</td>
    </tr>
    <tr>
      <td>Import Matplotlib</td>
      <td><code>import matplotlib.pyplot as plt</code></td>
    </tr>
    <tr>
      <td>Checking Matplotlib Version</td>
      <td><code>matplotlib.__version__</code></td>
    </tr>
  </tbody>
</table>


### Matplotlib Pyplot
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Matplotlib Pyplot</td>
      <td>Introduction to the <code>pyplot</code> module</td>
    </tr>
    <tr>
      <td>Pyplot API vs Object-Oriented API</td>
      <td>Comparing the two main programming styles</td>
    </tr>
    <tr>
      <td>Pyplot API</td>
      <td>Stateful, function-based interface</td>
    </tr>
    <tr>
      <td>Object-Oriented (OO) API</td>
      <td>Explicit <code>fig, ax = plt.subplots()</code> pattern</td>
    </tr>
  </tbody>
</table>

### Matplotlib Plotting
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Plotting x and y Points</td>
      <td>Core <code>plt.plot(x, y)</code> usage</td>
    </tr>
    <tr>
      <td>Plotting Without Line</td>
      <td>Marker-only plots</td>
    </tr>
    <tr>
      <td>Multiple Points</td>
      <td>Plotting multiple data series</td>
    </tr>
    <tr>
      <td>Default X-Points</td>
      <td>Auto-generated x-axis behavior</td>
    </tr>
  </tbody>
</table>


### Matplotlib Markers
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Markers</td>
      <td>Overview of marker styles</td>
    </tr>
    <tr>
      <td>Marker Reference</td>
      <td>Full marker symbol reference table</td>
    </tr>
    <tr>
      <td>Format Strings <code>fmt</code></td>
      <td>Shorthand format: <code>'b--o'</code> syntax</td>
    </tr>
    <tr>
      <td>Line Reference</td>
      <td>Line style codes</td>
    </tr>
    <tr>
      <td>Color Reference</td>
      <td>Named and hex color usage</td>
    </tr>
    <tr>
      <td>Marker Size</td>
      <td><code>ms</code> / <code>markersize</code> parameter</td>
    </tr>
    <tr>
      <td>Marker Color</td>
      <td><code>mfc</code>, <code>mec</code> (face & edge colors)</td>
    </tr>
  </tbody>
</table>


### Matplotlib Line
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Linestyle</td>
      <td>Solid, dashed, dotted, dashdot</td>
    </tr>
    <tr>
      <td>Shorter Syntax</td>
      <td><code>ls</code>, <code>lw</code>, <code>c</code> shorthand parameters</td>
    </tr>
    <tr>
      <td>Line Styles</td>
      <td>Visual comparison of all line styles</td>
    </tr>
    <tr>
      <td>Line Color</td>
      <td>Applying colors to lines</td>
    </tr>
    <tr>
      <td>Line Width</td>
      <td><code>lw</code> / <code>linewidth</code> customization</td>
    </tr>
    <tr>
      <td>Multiple Lines</td>
      <td>Plotting and distinguishing multiple lines</td>
    </tr>
  </tbody>
</table>


### Matplotlib Labels and Title
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Create Labels for a Plot</td>
      <td><code>xlabel()</code>, <code>ylabel()</code></td>
    </tr>
    <tr>
      <td>Create a Title for a Plot</td>
      <td><code>plt.title()</code></td>
    </tr>
    <tr>
      <td>Set Font Properties</td>
      <td>Font size, family, weight in titles/labels</td>
    </tr>
    <tr>
      <td>Position the Title</td>
      <td><code>loc</code> parameter: left, center, right</td>
    </tr>
  </tbody>
</table>


### Matplotlib Adding Grid Lines
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Add Grid Lines to a Plot</td>
      <td><code>plt.grid(True)</code></td>
    </tr>
    <tr>
      <td>Specify Which Grid Lines</td>
      <td>Controlling major/minor, axis</td>
    </tr>
    <tr>
      <td>Set Line Properties for the Grid</td>
      <td>Color, linestyle, linewidth for grid</td>
    </tr>
  </tbody>
</table>


### Matplotlib Subplot
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Display Multiple Plots</td>
      <td><code>plt.subplot()</code> and <code>plt.subplots()</code></td>
    </tr>
    <tr>
      <td>Super Title</td>
      <td><code>plt.suptitle()</code> for overall figure title</td>
    </tr>
  </tbody>
</table>

### Matplotlib Histograms
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Histogram</td>
      <td>What histograms represent</td>
    </tr>
    <tr>
      <td>Create Histogram</td>
      <td><code>plt.hist()</code> basic usage</td>
    </tr>
    <tr>
      <td>Specify Number of Bins</td>
      <td><code>bins</code> parameter</td>
    </tr>
    <tr>
      <td>Histogram with Labels</td>
      <td>Adding axis labels and title</td>
    </tr>
    <tr>
      <td>Change Color & Add Border</td>
      <td><code>color</code>, <code>edgecolor</code> parameters</td>
    </tr>
  </tbody>
</table>


### Matplotlib Box Plot
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Structure of a Box Plot</td>
      <td>Median, Q1, Q3, whiskers, outliers</td>
    </tr>
    <tr>
      <td>Horizontal Box Plot</td>
      <td><code>vert=False</code> orientation</td>
    </tr>
    <tr>
      <td>Multiple Box Plots</td>
      <td>Comparing distributions side-by-side</td>
    </tr>
  </tbody>
</table>


### Matplotlib Pie Charts
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Creating Pie Charts</td>
      <td><code>plt.pie()</code> fundamentals</td>
    </tr>
    <tr>
      <td>Labels</td>
      <td>Adding segment labels</td>
    </tr>
    <tr>
      <td>Start Angle</td>
      <td>Rotating the starting position</td>
    </tr>
    <tr>
      <td>Explode</td>
      <td>Highlighting a slice with <code>explode</code></td>
    </tr>
    <tr>
      <td>Shadow</td>
      <td>Adding depth with <code>shadow=True</code></td>
    </tr>
    <tr>
      <td>Legend</td>
      <td><code>plt.legend()</code> for pie charts</td>
    </tr>
    <tr>
      <td>Legend With Header</td>
      <td>Adding a title to the legend</td>
    </tr>
  </tbody>
</table>


### Count Plot in Matplotlib
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Count Plot</td>
      <td>Frequency-based bar chart (Seaborn-style in Matplotlib)</td>
    </tr>
  </tbody>
</table>

### Bivariate Analysis
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bivariate Analysis</td>
      <td>Exploring relationships between two variables</td>
    </tr>
  </tbody>
</table>

### Matplotlib Scatter
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Creating Scatter Plots</td>
      <td><code>plt.scatter()</code> basics</td>
    </tr>
    <tr>
      <td>Compare Plots</td>
      <td>Overlaying multiple scatter series</td>
    </tr>
    <tr>
      <td>Colors</td>
      <td>Color mapping per data point</td>
    </tr>
    <tr>
      <td>Size</td>
      <td>Marker size variation (<code>s</code> parameter)</td>
    </tr>
    <tr>
      <td>Alpha</td>
      <td>Transparency with <code>alpha</code> parameter</td>
    </tr>
  </tbody>
</table>


### 3D Plot in Matplotlib
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Import 3D Module</td>
      <td><code>from mpl_toolkits.mplot3d import Axes3D</code></td>
    </tr>
    <tr>
      <td>3D Scatter Plot</td>
      <td><code>ax.scatter3D()</code> for 3D scatter</td>
    </tr>
    <tr>
      <td>3D Line Plot</td>
      <td><code>ax.plot3D()</code> for 3D line charts</td>
    </tr>
  </tbody>
</table>


### Univariate Variable
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Univariate Variable</td>
      <td>Single-variable distribution analysis</td>
    </tr>
  </tbody>
</table>

## Tech Stack
<table>
  <thead>
    <tr>
      <th>Tool</th>
      <th>Version</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Python</td>
      <td>3.x</td>
    </tr>
    <tr>
      <td>Matplotlib</td>
      <td>3.x</td>
    </tr>
    <tr>
      <td>Jupyter Notebook</td>
      <td>Latest</td>
    </tr>
    <tr>
      <td>NumPy</td>
      <td>Latest</td>
    </tr>
    <tr>
      <td>Pandas</td>
      <td>Latest</td>
    </tr>
  </tbody>
</table>


## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/matplotlib-python-library.git
cd matplotlib-python-library
```

### 2. Install Dependencies
```bash
pip install matplotlib numpy pandas jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook Matplotlib_Python_Library.ipynb
```

## Key Concepts Covered
- **Pyplot vs Object-Oriented API** — understanding when to use each style
- Customization** — colors, markers, line styles, sizes, and transparency
- **Statistical Charts** — histograms, box plots, pie charts, count plots
- **Multivariate Visualization** — scatter plots, bivariate analysis
- **3D Visualization** — 3D scatter and line plots using `mpl_toolkits`
- **Subplots** — displaying multiple plots in a single figure
- **Grid, Labels, Titles** — making plots publication-ready


## Who Is This For?
- Students learning Python data visualization
- Professionals preparing for data science interviews
- Developers exploring Matplotlib for the first time
- Anyone building a portfolio in data analysis