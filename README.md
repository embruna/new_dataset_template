TEMPLATE: NEW DATASET CLEANUP AND MANAGEMENT

This is the structure of the template. After setting it up, replace the text in the README with informartion specific to your dfata cleanup project.
A sample README can be found at https://github.com/BrunaLab/HeliconiaSurveys  


new_dataset_template  

|- code/                # Folder for R code    
|  +- data_cleaner.R    # R script for loading, cleaning, and organizing dataset  
|   
|- data/                #   
|  +- data_clean/       # folder for clean data files in open formats such as TXT, CSV, TSV, etc.     
|  +- data_raw/         # folder for raw data not changed once created    
|      +- my_data.csv   # data files in open formats such as TXT, CSV, TSV, etc. Do not change these files directly    
|   
|- docs/                #  
|  +- docs.md           # documentation for the R files   
|  
|- CODE_OF_CONDUCT.md    # code of conduct for collaborators and contributors  
|- CONTRIBUTING.md       # information on how to suggest improvements to the code  
|- LICENSE.md            # specifies the conditions of use and reuse of the code, data & text  
|- NEWS.md               # details updates, version status, and other milestones  
|- README.md             # top-level description of content and guide to users  
|- makefile.R            # file to execute the cleaning and organizing of data using scripts in the `code` folder  



#### TO ADD:

- Github actions: 
  - data validation with pointblank
  - automatic versioning after corrections & saving txt file of `clean_data ` with version no. 

- More advanced, likely overkill:
    - `Renv` for package versions
    - `targets` to manage project workflow.
