## Master Thesis: Analysis and Implementation of EM Algorithm for GAMs

This repository contains all the materials related to my Master's thesis, which focuses on the implementation and analysis of the Expectation-Maximization (EM) algorithm, particularly a Generalized EM (GEM) algorithm, applied to Generalized Additive Models (GAMs).

## Repository Structure

- `data/`: This directory contains both the raw and processed data used in the thesis. The raw data represents the initial dataset, while the processed data includes transformations and modifications done as part of the analysis.
- `EM_algorithm_for_GAM.ipynb`: A Jupyter Notebook that includes the main functions and the code for the analysis of the primary model used in the thesis. It provides an in-depth exploration of the EM algorithm applied to GAMs.
- `Master_thesis.pdf`: The complete PDF document of my Master's thesis, which includes a comprehensive explanation of the research, methodology, results, and conclusions.
- `Master_thesis_poster.pdf`: A poster of my Master's thesis, which serves as a summary.

## Introduction to problematic

The Jupyter Notebook `EM_algorithm_for_GAM.ipynb` serves as a practical guide and detailed analysis of the EM algorithm in the context of GAMs. The central objective of this study is to tackle the intricate challenge of parameter estimation in two distinct GAMs, one representing the signal and the other representing the background. This task is particularly complex due to the nature of the data: we only have access to the aggregated sum of these two components, making the separation and analysis of the individual components a sophisticated problem.

## Libraries Used

The analysis and implementation make use of the following R libraries:

- `mgcv`: For modeling and smoothing in GAMs.
- `ggplot2`: For creating elegant and complex graphics.
- `RColorBrewer`: For a rich palette of colors used in plotting.
- `dplyr`: For data manipulation and transformation.

Ensure these libraries are installed and loaded in your R environment to replicate the analysis.

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `EM_algorithm_for_GAM.ipynb` in Jupyter Notebook or Jupyter Lab to view and run the analysis.
3. Explore the `data` directory to understand the dataset used in this research.
4. Read the `Master_thesis.pdf` for a comprehensive understanding of the theoretical background, methodology, and results of this research.

## Contact

For any queries or discussions related to this research, feel free to contact Dalil Koheeallee at dalil.koheeallee@epfl.ch.

