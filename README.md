# Research Compendium Title
Description of the Research Compedium and its purpose. This Research Compendium has been created after creating a new project based on Github repo 
and defining it as a research compendium through `rrtools::use_compendium("../NameProjectNoUnderscores/", open = FALSE)`

For any question about the code or data, [please contact me](mailto:camille.magneville@gmail.com)

# How to cite
Please cite this compendium as: ...

## Project Information
**Project lead / contact:**  
**Associated researchers**
**Affiliation:**  
**Funding source(s):**  

## Repository Structure
This project follows the folder structure:

```
ResearchCompendium/
├── make.R 🪄 # A R script to run the analysis workflow
├── DESCRIPTION 📚 # Created when creating the research compendium through rrtools
├── README_researchcompendium.md 📚
├── raw_data/ 📦 # Input datasets (never modified)
  ├── subfolders if needed/ 
  ├── README_raw_data.md 📚 # Listing the raw data information (cf README_raw_data.md)
├── transformed_data/ 📦 
  ├── subfolders if needed/ 
    ├── README_transformed_data.md 📚 # List and short explanation of each transformed data saved (cf README_raw_data.md)
├── analyses/ 🍳 # Analysis code
├── R/ 🪛 # Functions coded for use in the Analysis folder
└── output/ 🎨 # Figures, tables, model results

```

## Software & Reproducibility
**Main language(s):** R

## How to Run the Analysis
Run the `make.R` file.

**Add notes if HPC or external resources are required:** ...

## Acknowledgements
(Optional) Funding, collaborators, field or lab support, etc.
