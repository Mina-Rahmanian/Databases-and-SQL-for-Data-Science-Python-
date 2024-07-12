# Chicago Datasets Analysis with SQLite & Python

## Introduction

This repository contains a Python Jupyter Notebook designed for the graded assessment involving analysis of three key datasets from Chicago. Using SQLite and Python, you will load these datasets, execute SQL queries, and derive insights based on the data.

## Setup Instructions

### Requirements
- Python 3.x
- Jupyter Notebook# Chicago Datasets Analysis

## Introduction

This repository contains a Python notebook for analyzing three key datasets from the city of Chicago: socioeconomic indicators, public schools data, and crime data. The notebook uses SQLite for data manipulation and SQL queries to answer assignment questions.

## Datasets Used

### 1. Socioeconomic Indicators in Chicago

- Dataset description: This dataset includes six socioeconomic indicators and a hardship index for each community area in Chicago from 2008-2012.
- [Original Dataset Link](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)

### 2. Chicago Public Schools

- Dataset description: Provides school-level performance data for the 2011-2012 school year.
- [Original Dataset Link](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)

### 3. Chicago Crime Data

- Dataset description: Reports crime incidents in Chicago from 2001 to present (excluding the last seven days).
- [Original Dataset Link](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

## Setup

### Loading Data into SQLite Database

To facilitate analysis, the datasets were loaded into SQLite tables:
- `CENSUS_DATA`
- `CHICAGO_PUBLIC_SCHOOLS`
- `CHICAGO_CRIME_DATA`

The notebook establishes connections to `FinalDB.db` and populates these tables using Pandas.

## Running the Notebook

To run the notebook:
1. Ensure you have Python, Pandas, SQLite, and Jupyter installed.
2. Clone this repository.
3. Open the notebook and execute cells to load data, perform analysis, and answer assignment questions.

## Assignment Problems

The notebook addresses several assignment questions using SQL queries. You could find the answer here.








