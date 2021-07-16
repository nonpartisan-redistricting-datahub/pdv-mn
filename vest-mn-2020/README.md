# vest-mn-2020

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-minnesota-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST MN 2020 file
   - Date accessed: 7/16/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4499011&datasetVersionId=251765
   - File: `mn_2020.zip`
- File: VEST documentation file, 2020
   - Date accessed: 7/16/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4863160&datasetVersionId=251765
   - File: `documentation.txt`
- File: Precinct-level Shapefile, 2020
  - Date accessed: 7/16/2021
  - Link: https://gisdata.mn.gov/dataset/bdry-votingdistricts
  - File: `shp_bdry_votingdistricts.zip`
- File: Precinct-level Election Results, 2020
  - Date accessed: 7/16/2021
  - Link: https://www.sos.state.mn.us/elections-voting/election-results/2020/2020-general-election-results/2020-precinct-results-spreadsheet/
  - Note: select '2020 Precinct Results Spreadsheet' then 'Federal and State Results by Precinct (.xlsx)'. 
  - File: `2020-general-federal-state-results-by-precinct-official.xlsx`

## File processing:

`vest-mn-2020-validation.ipynb` is the script that is the basis of the validation report
