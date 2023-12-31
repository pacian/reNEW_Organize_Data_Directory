## reNEW Organize Data Directory

<img src="https://raw.githubusercontent.com/elixir-europe/rdmkit/master/assets/img/RDMkit_logo.svg" alt="RDMkit logo" width="450"/>     

<!-- <img src="https://data-champions.renew-platforms.dk/renew-data-champions/rdm-infographic-series/research-data-life-cycle.jpg" alt="RDM Life Cycle logo" width="450"/> -->

### Each scientific area (Genomics, Microscopy, Tissue Culture, Flow Cytometry) has its directory in this structure. Within each area are directories for different Projects, each with folders for 
### Raw_Data, Processed_Data, and Reports. Additionally, each scientific site has directories for Protocols, Tools, and Resources relevant to that area.

### Regarding the naming conventions:

### For Projects, you could use a descriptive name followed by the start date in the format YYYYMMDD—for example, GeneSequencing_20230617.

### For files, use descriptive names indicating the project, the nature of the file, and the date in the format YYYYMMDD—for example, GeneSequencing_RawData_20230617.fastq or 
### Microscopy_Report_20230617.pdf.

#### Avoid using spaces, special characters, and long filenames. Use underscores _ to separate words in a file name.

### Keep file versions if necessary, e.g., GeneSequencing_Report_V1_20230617.pdf, GeneSequencing_Report_V2_20230617.pdf.

### Maintain a 'Readme' file in each project directory to explain what each file is and other pertinent details.

### Remember, creating an intuitive system that works for the reNEW Group's needs is the most important thing. The exact folder structure and naming convention need to be adjusted accordingly.


# reNEW_Group/                                     
##   ├── Genomics/
### │   ├── Projects/
### │   │   ├── Project_A/
### │   │   │   ├── Raw_Data/
### │   │   │   ├── Processed_Data/
### │   │   │   └── Reports/
### │   │   ├── Project_B/
### │   │   │   ├── Raw_Data/
### │   │   │   ├── Processed_Data/
### │   │   │   └── Reports/
### │   ├── Protocols/
### │   ├── Tools/
### │   └── Resources/
##   ├── Microscopy/
### │   ├── Projects/
### │   │   ├── Project_A/
### │   │   │   ├── Raw_Data/
### │   │   │   ├── Processed_Data/
### │   │   │   └── Reports/
### │   │   ├── Project_B/
### │   │   │   ├── Raw_Data/
### │   │   │   ├── Processed_Data/
### │   │   │   └── Reports/
### │   ├── Protocols/
### │   ├── Tools/
### │   └── Resources/
##   ├── Tissue_Culture/
### │   ├── Projects/
### │   │   ├── Project_A/
### │   │   │   ├── Raw_Data/
### │   │   │   ├── Processed_Data/
### │   │   │   └── Reports/
### │   │   ├── Project_B/
### │   │   │   ├── Raw_Data/
### │   │   │   ├── Processed_Data/
### │   │   │   └── Reports/
### │   ├── Protocols/
### │   ├── Tools/
### │   └── Resources/
##   └── Flow_Cytometry/
###  ├── Projects/
###  │   ├── Project_A/
###  │   │   ├── Processed_Data/
###  │   │   └── Reports/
###  │   ├── Project_B/
###  │   │   ├── Raw_Data/
###  │   │   ├── Processed_Data/
###  │   │   └── Reports/
###  ├── Protocols/
###  ├── Tools/
###  └── Resources/

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Richard Dennis has waived all copyright and related or neighboring rights to this work.
