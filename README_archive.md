# CIEE Productivity and Reproducibility Project Archive

**Created by:** Ferne Kotlyar \| **Date created:** September 5, 2025

**Updated by:** Ferne Kotlyar \| **Date stored:** September 25, 2025

This project was completed as part of the CIEE (Canadian Institute of Ecology and Evolution) minicourse: Producitivity and Reproducibility in Ecology and Evolution. This is an archive of the completed assignment. This document will detail what this project contains and where to find that information.

**Folders:**

-   *00_rawdata:* contains all raw data files.
    - README_rawdata.md: short description of the data and methods used.
    - _DATA_DICTIONARY.md: description of each variable/column in the raw data sheet.
    - Kotlyar_PR_Species_Nectar_Dye_Raw.xlsx: raw data. This was initally transcribed in Excel (.xlsx), but the cleaned version was exported in a more universal format (CSV).

-   *01_scripts:* contains all scripts and analysis of the data.
    - README_scripts.md: short description of folder contents.
    - Kotlyar_CIEE_Species_Dye_Data_Cleaning.Rmd: script to clean and export raw data into CSV format and store the cleaned data in the "02_outdata" folder.
    - Kotlyar_CIEE_Species_Dye_Data_Cleaning.html: above script, but in HTML format for shareability.

-   *02_outdata:* contains all cleaned data.
    - README_outdata.md: short description of folder contents.
    - _DATA_DICTIONARY.md: description of each variable/column in the cleaned data CSV (includes original and new columns after data cleaning).
    - Kotlyar_PR_Species_Nectar_Dye_Clean.csv: cleaned data. The data was checked for errors, labels were standardized, and certain columns were almagamated. See "_DATA_DICTIONARY.md" for full description of column content and explanation.

-   *03_figures:* contains all plots and figures of the data.
    - README_figures.md: short description of figures.
    - ND_clean_combined.png: figure displaying the proportion of dye that landed on the anthers and stigma based on the species of hummingbird that was mimicked using different 3D printed bills. Two species of traplining (specialized) hummingbirds were used: green hermits, (*Phaethornis guy*), and violet sabrewings (*Campylopterus hemileucurus*), and two non-specialized (territorial) hummingbirds: rufous-tailed (*Amazilia tzacatl*) and crowned woodnymphs (*Thalurania colombica*).

-   *04_manuscript:* contains all versions of the manuscript and associated citation files.
    - README.md: short description of folder contents.
    - CIEE_Course.bib: list of references exported from Zotero.
    - Nature.csl: description of style for the references (as per Nature journal).
    - Kotlyar_CIEE_Manuscript.Rmd: mock manuscript including the following sections: 
        - Introduction: short introduction of the project.
        - Methods: short description of the methods used (more details can be found in "05_preregistration").
        - Analysis: very quick statistical analysis of the data, which includes display of the contingency tables, a chi-squared analysis, and a fisher exact test. No post-hoc tests were conducted as this was just for a mock manuscript.
        - Results: this section displays the main results. It displays the "ND_clean_combined.png" figure which is saved under "03_figures".
        - Discussion: very quick summary of results.
        - References: reference list of articles cited in the rest of the manuscript.
    - Kotlyar_CIEE_Manuscript.pdf: PDF version of the above.

-   *05_preregistration:* contains all files associated with preregistration.
    - README_preregistraion: short description of folder contents.
    - Kotlyar_CIEE_Preregistration.Rmd: Description of study information, design plan, sampling plan, variables, and analysis plan.
    - Kotlyar_CIEE_Preregistration.pdf: PDF version of the above.
    
-   *renv:* 
    - README_renv.md: short description of folder contents.
    - activate.R: recreates the R environment in which this code was generated (ex. loads correct directy, loads necessary packages, etc.).
    - library: stores necessary packages.
    - settings.json: stored project settings (ex. R version, package dependency fields, etc.).
    - staging: stages project.

**Miscellaneous Files:**

- README.md: description of entire project.
- Kotlyar_Productivity-Reproducibility.Rproj: R project.
- renv.lock: lists all packages necessary to run the code in this project.
