# NHTSA_Complaint_Text_Mining

## Data Source
The original FLAT_CMPL.txt file can be downloaded from [NHTSA's website](https://static.nhtsa.gov/odi/ffdd/cmpl/Import_Instructions_Excel_All.pdf).

## Notebooks Description
- **Dataset_Cleaning.ipynb**: Processes the original txt file to create a parquet file containing only data from 2015 onwards.
- **Spacy_Preprocessing.ipynb**: Performs time-consuming NLP tasks including lemmatization and entity recognition.
- **Main_Analysis.ipynb**: Contains the main analysis. Requires `complaints_with_entities.parquet` as input.