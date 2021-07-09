# vest-il-2016

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-illinois-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST IL 2016 file
   - Date accessed: 7/1/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4749661&datasetVersionId=251374
   - File: `il_2016.zip`
- File: VEST documentation file, 2016
   - Date accessed: 7/1/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4863153&datasetVersionId=251374
   - File: `documentation.txt`
- File: U.S. Census Bureau's 2020 Redistricting Data Program final release
    - Date accessed: 7/8/2021
    - Link: https://www.census.gov/geo/partnerships/pvs/partnership20v2/st17_il.html
    - Note: not downloading the files for the election results validation, as they are available from the Census.
- File: Precinct Level Election results, 2016
    - Date accessed: 7/8/2021
    - Link: https://www.elections.il.gov/ElectionOperations/ElectionVoteTotalsPrecinct.aspx?ID=KaiJHIgaAjo%3d&T=637614259551200776
    - Files: 
        - `51-120-PRESIDENT AND VICE PRESIDENT-2016GE.csv`
        - `51-160-UNITED STATES SENATOR-2016GE.csv`
        - `51-210-COMPTROLLER-2016GE.csv`
    - Note: selected `Precinct` then `Precinct Downloads by Office` then the 5 offices on the VEST file
- File: DuPage County Precinct Shapefile
    - Date accessed: 7/9/2021
    - Link: https://gisdata-dupage.opendata.arcgis.com/datasets/election-precincts
    - File: `Dupage_Election_Precincts.zip`
    - Note: it is unclear if these were the precincts at the time of the 2016 election. 


### Inaccessible files:
- File: Kane County Precinct Shapefile
    - Date accessed: 7/9/2021
    - Link: https://www.kanecountyclerk.org/Elections/Pages/Maps.aspx
    - Note: there is an interactive GIS portal but the shapefile is not available to download. Otherwise, there are pdf images of every precinct by township. 
- File: Kendall County Precinct Shapefile
    - Date accessed: 7/9/2021
    - Link: https://maps.co.kendall.il.us/mapviewer/?page=page_3
    - Note: there is an interactive GIS portal but the shapefile is not available to download.
- File: Will County Precinct Shapefile 
    - Date accessed: 7/9/2021
    - Link: https://gisapp.willcountyillinois.com/Html5Viewer/Index.html?viewer=Data_Viewer
    - Note: there is an interactive GIS portal but the shapefile is not available to download.

## File processing:

`vest-il-2016-validation.ipynb` is the script that is the basis of the validation report
