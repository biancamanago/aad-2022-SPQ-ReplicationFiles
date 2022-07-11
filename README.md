# aad-2022-SPQ-ReplicationFiles
Replication files for 2022 Social Psychology Quarterly Paper entitled "Mapping the Content of Asian Stereotypes in the United States: Intersections with ethnicity, gender, income, and birthplace"


README for Benard, Manago, Russian, and Cha. 
SPQ Replication files.
Created by:
Bianca Manago, Vanderbilt University
bianca.manago@vanderbilt.edu

----------------------------------------------------
FILE LIST

- _aad-spq-primary.do
- _aad-spq-packages.do

- aad-spq-data05-4-exclusions.dta
- aad-spq-data05-4-full.dta
- aad-spq-do00-demographics.do
- aad-spq-do01-coefplots.do
- aad-spq-do02-reg.do
- aad-spq-do03-scatter.do
- aad-spq-do04-tables.do
- aad-spq-do05-factorAnalysis.do

All script files are explained in _aad-spq-primary.do

------------------------------------------------------
FILE INFORMATION

To recreate all results, tables, and figures:

- Step 1. Download Stata (we use version 14.1 for all files - 
          newer versions can run version 14.1).
- Step 2. Download the zip with all files and folders to your desktop. 
          The files reference subfolders within the main folder, 
          so without downloading all, you cannot run the files.
- Step 3. Run _aad-spq-packages.do to install all necessary 
          user-written packages.
- Step 4. Set your working directory to "-workSCS" 
- Step 5. Run the do file(s) of interest or re-run ALL analyses 
          by running the file _aad-spq-primary.do.

Notes: The do-files will load the relevant .dta files when 
       needed to run the analyses. Files can be run in any order.

Study instruments are provided in docx format as well as qsf (Qualtrics) format.

---------------------------------------
DATA-SPECIFIC INFORMATION

The dta files only contain variables needed to reproduce the results. Additional
variables from the survey instrument are being reported in other publications and are 
available upon request.

------------------------------------------------------
CHANGELOG

1. The posted files are to be considered final versions which reproduce the published 
manuscript.

------------------------------------------------------
COPYRIGHT & LICENSING INFORMATION
Source data was created by Bianca Manago.

Interested parties should contact the authors if they want more information.

------------------------------------------------------
LIMITATIONS

N/A
