# Researching Changes in Perception of Academic Support

*A Study on Framing Effects in Information Presentation*

## Overview

This project examines how differently framed information affects individuals' perception of academic support. The research utilizes survey data to analyze the impact of various framing techniques on responses.

## Project Structure

- **Survey_Data.csv** – The raw survey dataset used for analysis.
- **Survey_Final_Project.qmd** – The Quarto document containing the research report, methodology, and analysis.
- **Survey_Final_Project.html** – The rendered output of the Quarto document for easy viewing.

## Methodology

The study involved distributing surveys with varying framing techniques and analyzing the collected responses to identify trends in perception shifts. The analysis includes statistical comparisons and data visualizations.

## Requirements

To reproduce the analysis, ensure you have:

- R and RStudio installed
- Quarto installed (`quarto install`)
- Required R packages:
  ```r
  install.packages(c("tidyverse", "ggplot2", "dplyr"))
  ```

## Running the Project

1. Open `Survey_Final_Project.qmd` in RStudio.
2. Render the document using Quarto:
   ```sh
   quarto render Survey_Final_Project.qmd
   ```
3. View the `Survey_Final_Project.html` for the results.

## Authors

- **Dana Childs**

## License

This project is open-source and available under the [MIT License](LICENSE).
