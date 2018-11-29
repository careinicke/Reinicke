# Analysis of Student Loans CFPB data set — 2011 to 2018

This repository contains data, analytic code, and findings that support portions of the article, “She joined the Army National Guard to get her degree for free. She didn’t expect to graduate with $60,000 of student loan debt" TKTK published Month Date, Year TK. Please read that article, which contains important context and details, before proceeding.

## Data

This analysis uses the following spreadsheets.

The spreadsheets come from the following sources:

- Name of source:
  - `Student_Loan_Complaints_CFPB': Raw data of complaints submitted by student loan borrowers to the Consumer Finance Protection Bureau

Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

- `Sub-product` — What kind of loan the complaint is in reference to
- 'Issue' - Category of complaint 
- `Sub-Issue` — Specific complaint
- 'Tags' - indicates that the borrower who submitted the complaint self-identified as a servicemember 


## Methodology

##### Part 1: Download and clean 

- I downloaded the data I needed from the CFPB's socrata site. I used the site to do some basic filtering, instead of downloading all available complaints. I filtered so that I only downloaded complaints related to student loans. 
- I cleaned the data for gaps, missing fields, etc. so that I could do my own analysis.


##### Part 2: Pivot

- I used a pivot table to view complaints by count
- I also filtered complaints by issue and sub-issue and count, to see which were the most prevalent. 
- I cleaned answers to account for duplicates (there were many) and used the final data to make visualizations. 


## Outputs

This spreadsheet contains the outputs of my analysis 'Student_Loan_Complaints_Outputs.csv'.

## Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). The data file in the output/ directory is available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?

Contact Carmen Reinicke at careinicke@gmail.com 
