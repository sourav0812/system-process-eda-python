# System Process Exploratory Data Analysis (EDA)

## Overview
A Python-based exploratory data analysis project that cleans, 
aggregates, merges, and filters real system performance data 
across CPU, Disk, and Memory datasets using Pandas.

## Skills & Tools
- Python, Pandas, NumPy
- Data cleaning & type conversion
- GroupBy aggregation, pivot tables
- DataFrame merging (inner joins)
- Boolean filtering & conditional logic

## What This Project Does
1. Loads and extracts relevant columns from three system datasets 
   (cpu.csv, disk.csv, memory.csv)
2. Cleans column headers dynamically using a reusable function
3. Cleans and converts numeric columns (removes commas, drops 
   invalid rows, casts to int)
4. Aggregates data by process image name (sum + count)
5. Merges all three datasets into a single unified DataFrame
6. Filters processes by memory usage, thread count, and I/O activity

## Datasets
- `cpu.csv` — Process CPU usage and thread counts
- `disk.csv` — Process disk read/write activity
- `memory.csv` — Process memory (working set) usage
