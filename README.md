# Survey of India Multi-State Station Data Analysis

A Python-based data processing and validation project developed for
analyzing Survey of India station-based file data across multiple
states and regions.

The project focuses on organizing file-level information, validating
file naming patterns, checking station and date information, identifying
data quality issues, and generating station-wise and daily-wise reports.

---

## 📌 Project Overview

This project provides a structured workflow for processing Survey of
India station data using Python and Pandas.

The workflow works with file metadata and station information to perform
date-based filtering, station identification, state-wise filtering,
file validation, file-size analysis, Julian-date validation, and
daily/station-wise reporting.

The original source dataset is confidential/restricted and is therefore
not included in this repository.

---

## 🎯 Objectives

The main objectives of this project are:

- Process station-based file information efficiently
- Filter data according to a specified date range
- Extract dates from file paths
- Extract station codes from file names
- Map station information with states/regions
- Validate file naming patterns
- Identify invalid or non-matching files
- Identify files with unusually low file sizes
- Check duplicate/file-level information
- Validate Julian date codes
- Analyze daily file distribution
- Perform station-wise analysis
- Generate summary reports for further analysis

---

## 🔄 Project Workflow

The overall workflow follows these steps:

```text
Raw File Metadata
       ↓
Data Loading
       ↓
Date Filtering
       ↓
Date Extraction from File Paths
       ↓
Station Code Extraction
       ↓
State/Region Filtering
       ↓
File Extension Identification
       ↓
File Name Pattern Validation
       ↓
Valid / Invalid File Analysis
       ↓
File Size Analysis
       ↓
Julian Date Validation
       ↓
Daily File Distribution
       ↓
Station-wise Analysis
       ↓
Summary Reports
