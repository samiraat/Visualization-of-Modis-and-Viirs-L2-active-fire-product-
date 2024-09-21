# Visualization of MODIS and VIIRS Active Fire Products

This repository provides tools for visualizing MODIS (Moderate Resolution Imaging Spectroradiometer) and VIIRS (Visible Infrared Imaging Radiometer Suite) active fire data. These visualizations are based on NASA's active fire product guidelines and are aimed at providing clear, accurate insights into fire activity, land use, and water distribution.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Dataset Information](#dataset-information)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This project aims to help users visualize active fire data from the MODIS and VIIRS satellites. The dataset, provided by NASA, includes information about fire detection, land cover, water bodies, and other related parameters. This repository includes a Jupyter Notebook demonstrating how to use the active fire data for visualization purposes.

## Features
- **Visualization**: Create maps of fire detections, land, and water using MODIS and VIIRS data.
- **Customization**: Users can adjust various visualization parameters, such as map projection, color schemes, and data layers.

## Installation

To use the code, clone the repository and install the required dependencies. You can do this using the following commands:

```bash
git clone https://github.com/yourusername/modis-viirs-fire-visualization.git
pip install -r requirements.txt
```


Ensure that you have Python 3.8+ and Jupyter installed.

## Usage

A Jupyter Notebook is provided to guide users through the steps to load, process, and visualize the MODIS and VIIRS active fire data. Follow the instructions below:

1. **Download the Data**:
   - Download the MODIS and/or VIIRS data from NASA's Fire Information for Resource Management System (FIRMS): [FIRMS Data](https://firms.modaps.eosdis.nasa.gov/)

2. **Run the Notebook**:
   - Launch Jupyter and open the provided notebook (`fire_visualization_notebook.ipynb`).
   - Follow the steps in the notebook to load your data and create visualizations.

## Dataset Information

The MODIS and VIIRS datasets contain the following key features:
- **Fire detection**: Indicates locations where active fires have been detected.
- **Land and water classification**: Defines whether a pixel represents land, water, or other features.
- **FRP (Fire Radiative Power)**: Measures the intensity of the fire.
- **Confidence Levels**: The likelihood that a detected fire is real, with values ranging from low to high.

For more information on the data format, please refer to NASA's official [User Guide](https://modis.gsfc.nasa.gov/data/dataprod/mod14.php).

## Contributing

We welcome contributions! If you'd like to contribute, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
