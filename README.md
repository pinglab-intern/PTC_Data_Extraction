# PTC_Data_Extraction
Extract disease data from PubTator Central for a given query (in this case, 'heart failure'). Link each disease with PMID and MESH ID for use in later projects.

This script does the following:
1. Obtains list of PMIDs from PubMed for a specific search query
2. Converts that list into a format searchable in PubTator Central (PTC)
3. Uses PTC API to get annotated articles (right now just 100 but should be able to do up to 1000) for PMID list. Output is in Pubtator Format.
4. Writes data to csv file, then reads back in and parses into a data frame.

## Requirements



## Running the script

## Credits
Developed by Marlee Zinsser in the Ping Lab at UCLA in Fall 2019.
