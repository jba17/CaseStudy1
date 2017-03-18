#CaseStudy1
##Instructions for Setup

    Clone the repo (or pull new changes):
    Using RStudio Build Menu Item (Build All) or (Clean and Build)

##Files and folders

    .paper/Makefile - build the project and renders the CaseStudy1.html and Casestudy1.md
    .paper/CaseStudy1.Rmd - RMarkdown file that turns the analyses into high quality html and markdown document
    source - a folder containing all scripts used for downloading, cleaning data and question steps
    source/download.R - a script used for downloading and reading GDP and Education CSV data.
    source/cleanData.R - a script used for cleaning the gdp data
        cleans data from gdp.csv and creates a tidy gdp_tidy.csv file
    source/clean_income_groups.R - a script used for cleaning the clean_income_groups data
        cleans data from income_groups.csv and creates a tidy income_groups_tidy.csv file
    source/merge.R - a script used for merging the two datasets
        merges the data from gdp_tidy.csv and income_groups_tidy.csv files and creates merged_data.csv

