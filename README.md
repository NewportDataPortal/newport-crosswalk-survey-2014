# Newport Crosswalk Safety Survey (2014)

This dataset contains anonymous results from the Newport Bicycle and Pedestrian Advisory Commission survey conducted in 2014.  This repository contains the survey questions, a partial dataset containing the responses for specific intersections, and a shapefile with the location of the crosswalks, numbered corresponding to the survey results.



### bpac_survey_2014.geojson

This file is a processed dataset.  The following steps were used to generate it:

1. Link survey responses in`Newport Pedestrian Safety Survey - May 2014 cleaned.csv`  to corresponding location in `pedestrian-safety-2014.shp`
2. Compute total "Safe", "Unsafe", and "I don't know." responses in for each crosswalk location
3. Calculate score as `score = safe/(safe+unsafe)`

