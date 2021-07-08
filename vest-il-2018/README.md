# vest-il-2018

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-illinois-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST IL 2018 file
   - Date accessed: 7/1/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4773520&datasetVersionId=251384
   - File: `il_2018.zip`
- File: VEST documentation file, 2018
   - Date accessed: 7/1/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4863187&datasetVersionId=251384
   - File: `documentation.txt`
- File: U.S. Census Bureau's 2020 Redistricting Data Program final release
    - Date accessed: 7/8/2021
    - Link: https://www.census.gov/geo/partnerships/pvs/partnership20v2/st17_il.html
    - Note: not downloading the files for the election results validation, as they are available from the Census.
- File: Precinct Level Election results, 2018
    - Date accessed: 7/8/2021
    - Link: https://www.elections.il.gov/ElectionOperations/ElectionVoteTotalsPrecinct.aspx?ID=8ehQy1Itjqo%3d&T=637607567723378235
    - Files: 
        - `54-180-GOVERNOR AND LIEUTENANT GOVERNOR-2018GE.csv`
        - `54-190-ATTORNEY GENERAL-2018GE.csv`
        - `54-200-SECRETARY OF STATE-2018GE.csv`
        - `54-210-COMPTROLLER-2018GE.csv`
        - `54-220-TREASURER-2018GE.csv`
    - Note: selected `Precinct` then `Precinct Downloads by Office` then the 5 offices on the VEST file

## File processing:

`vest-il-2018-validation.ipynb` is the script that is the basis of the validation report
