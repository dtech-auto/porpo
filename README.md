```
WORK IN PROGRESS
``` 

<p align="center">
  <img src = src/common/images/construct.png width=15% text-align=center />
</p>
  
<p align ="center">
  This repository is a work in progress. Anything and everything is subject to change.
</p>

------

# F1 Data Analysis

<p align="center">
  <img src = src/common/images/icon.png width=45% />
</p>

<p align="center">
  <img src = https://img.shields.io/github/license/dtech-auto/F1DataAnalysis />
    </>
  <img src = https://img.shields.io/github/languages/top/dtech-auto/F1DataAnalysis />
    </>
  <img src = https://img.shields.io/github/v/release/dtech-auto/F1DataAnalysis?display_name=tag&include_prereleases />
    </>
</p>

<p align="center">
  <img src = https://img.shields.io/github/commit-activity/w/dtech-auto/F1DataAnalysis />
    </>
  <img src = https://img.shields.io/github/last-commit/dtech-auto/F1DataAnalysis />
    </>
  <img src = https://img.shields.io/github/issues-raw/dtech-auto/F1DataAnalysis />
</p>

------

## Table of Contents
- [F1 Data Analysis](#f1-data-analysis)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Getting Started](#getting-started)
  - [Usage](#usage)

------

## General Information

This is an application that utilizes the [FastF1](https://github.com/theOehrly/Fast-F1) Python package to easily pull data for specified events, drivers, and sessions and generate visualizations for analysis.

*Note*: [Python3](https://www.python.org/downloads/) (v.3.8 or greater) is required.

## Getting Started

Install Dependencies:

```
pip3 install fastf1
pip3 install PySimpleGUI
```

Currently, there are 2 methods of execution:

`gui.py` to begin using the application with a gui.

`main.py` to begin using the application in CLI.

## Usage

This app can be used to do basic analysis for a specifc lap of an event

![VER_Speed_Bah](/src/examples/images/bah_speed.png)
`Max Verstappen speed on Lap 54 of the 2022 Bahrain GP. We can see he was losing power throughout the lap, up until the moment he completely lost power, and went into the pitlane.`