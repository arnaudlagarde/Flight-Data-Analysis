# Flight Data Analysis

## Overview

This repository contains code and resources for analyzing flight data using Apache Spark and MySQL. It includes Docker configurations to set up a development environment with MySQL and Spark, as well as Jupyter Notebooks for data analysis.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/your-username/flight-data-analysis.git
   ```
Set up Docker to run MySQL and Spark containers by following the instructions in the docker-compose.yml file.

Create a virtual environment (optional) and install the required Python packages:
```bash
cd flight-data-analysis
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt



Start Jupyter Notebook:
```bash
jupyter notebook
```

Open and run the Jupyter Notebooks in the notebooks directory to perform various analyses.


```
Usage
Split CSV Data
The flight data is split into multiple parts to manage large files. You can download these parts from the following links:

Part 1
Part 2
Part 3
Part 4
Part 5
Part 6
Part 7
Part 8
Part 9
Part 10
Part 11
Part 12
Download the necessary parts based on your analysis requirements.

Combining Split Data

To combine the split data parts into a single CSV file for analysis, you can use the following Python script:

# Flight Data Analysis

## Overview

This repository contains code and resources for analyzing flight data using Apache Spark and MySQL. It includes Docker configurations to set up a development environment with MySQL and Spark, as well as Jupyter Notebooks for data analysis.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/your-username/flight-data-analysis.git
Set up Docker to run MySQL and Spark containers by following the instructions in the docker-compose.yml file.

Create a virtual environment (optional) and install the required Python packages:

shell
Copy code
cd flight-data-analysis
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt


```bash
python combine_csv.py
```

This script will merge the split data parts into a single CSV file named flights_combined.csv.

You can then use flights_combined.csv for your analysis in the Jupyter Notebooks.

Contributing
Contributions to this project are welcome. If you have any ideas, improvements, or bug fixes, feel free to submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
