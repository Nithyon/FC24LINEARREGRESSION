# FIFA 24 Linear Regression Analysis

This project uses FIFA 24 player data for linear regression analysis, aiming to uncover patterns and predict ratings or attributes based on various player statistics. The analysis is conducted in a Jupyter notebook that leverages data exploration, visualization, and regression modeling techniques.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project analyzes FIFA 24 player data from EA Sports to examine relationships among various player attributes, using linear regression to model and predict specific aspects like player ratings or performance metrics. The insights generated could benefit player scouting, comparison, or deeper statistical analysis.

## Dataset

The project includes the FIFA 24 player dataset as a CSV file:

- **File Path**: `data/fc-24-players-database-and-stats.csv`
- **Attributes**:
  - **Player Info**: Name, Age, Nationality, Club, Position
  - **Ratings**: Overall rating, potential, skill-based ratings
  - **Physical and Skill Attributes**: Attributes such as dribbling, passing, acceleration, and strength

## Project Structure

```plaintext
├── data
│   └── fc-24-players-database-and-stats.csv  # Dataset file (CSV format)
├── notebooks
│   └── fc24linearregreesion.ipynb            # Linear regression analysis notebook
├── README.md                                 # Project README file
└── requirements.txt                          # List of dependencies
