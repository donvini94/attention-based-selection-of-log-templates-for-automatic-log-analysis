# Attention Based Selection of Log Templates for Automatic Log Analysis

## Overview
This Bachelor's thesis presents novel research on improving automated log analysis through attention-based selection of log templates. The research extends prior work on attention mechanisms to enhance log parsing accuracy and explores impact of structural metadata like timestamps on prediction quality.

## Key Contributions
- Evaluated attention-based template selection with multiple state-of-the-art log parsing algorithms (Drain, Spell, NuLog)
- Discovered and quantified significant impact of timestamp removal on prediction accuracy
- Assessed generalizability across multiple real-world log datasets (Huawei, HDFS, Thunderbird)
- Demonstrated improved robustness of log template selection through attention mechanisms

## Technical Implementation
- Extended existing DomainML framework to support multiple log parsing algorithms
- Conducted extensive experiments comparing parsing algorithms and parameter configurations
- Analyzed impact of dataset size and timestamp information on prediction quality

## Key Findings
- Attention mechanism improved template selection for specific algorithms and datasets
- Timestamp removal significantly enhanced prediction accuracy, especially for smaller datasets
- Identified optimal combinations of parsing algorithms and attention mechanisms
- Provided practical recommendations for preprocessing steps in log analysis pipelines

## Technologies & Concepts
- Attention Mechanisms
- Log Parsing Algorithms 
- Machine Learning
- Data Preprocessing
- Python
- DomainML Framework

This research was conducted at the Institute for Program Structures and Data Organization (IPD) at Karlsruhe Institute of Technology (KIT) under the supervision of Prof. Dr.-Ing. Klemens Böhm.
