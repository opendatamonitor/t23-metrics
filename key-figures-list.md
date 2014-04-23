
# Measures over the Aggregate

- **Counts / Averages / Longitudinal**
    - Total number of catalogues
    - Proportion of governmental vs non-governmental catalogues
    - Frequency of use of specific software platforms
    - Mean age of catalogues / rate of appearance of catalogues
    - (Aggregates of all other per-catalogue measures)

- **Rankings**
    - Would multiple "top-n" charts be acceptable?
        - A way to highlight best practice

- **Data Duplication with respect to other catalogues**
    - Download and checksum all the data pointed to
    - Build index of unique datasets

------------------

# Per-Geography Measures

- **Important from a policy-maker's point of view**

- **Catalogues per...**
    - Country (more not always better)
    - Capita / GDP (may tell us nothing, but interesting to see)

- **Time-profile by country**

- **Distribution of catalogues** across
    - Administrative geography (city/region/state/nation)
    - Type of managing institution and sector

- Can we create **"family trees" or dependency graphs of catalogues** within a geography?

------------------

# Per-Catalogue Measures (1/4)

- **Volume**
    - Number of catalogued datasets
    - Total volume
    - Mean dataset size

- **House-keeping**
    - Proportion of catalogued datasets with broken links (zombies)

------------------

# Per-Catalogue Measures (2/4)

- **Formats and Machine-readability**
    - Breakdown of datasets by format
    - Number of 'machine-readable' datasets
        - Look at the continuum of machine-readability (e.g. PDF -> Word -> Excel -> CSV -> JSON -> XML -> RDF)
        - Use [machine-readability criteria tested on data.gov.uk](https://github.com/theodi/R-projects/blob/master/csv-stats/the_status_of_csvs_on_data.gov.uk.md)
    - Change over time in terms of formats used

------------------

# Per-Catalogue Measures (3/4)

- **Licenses**
    - Proportion of datasets with licenses attached
    - Frequency distribution of different licenses
    - License-compatibility within a catalogue

- **Release Cycles, Methods, and Frequencies**
    - Number of datasets up-to-date
        - Average 'age' of datasets?
        - See also measures from the 'Tau of Data'
    - Rate/profile of arrival of data sets
    - New additions vs updates
        - Could be indicative of whether the data is published automatically or not and/or there many or few people contributing updates
    - Use of version control and archiving

------------------

# Per-Catalogue Measures (4/4)

- **Impact**
    - PageRank of the catalogue site
    - Social media as in Twitter stats (over time)

- **Usability**
    - Proportion of APIs vs data dumps
    - 'Quality' of available APIs (how to measure this?)
    - Availability of dataset previews

- **Uptake/Engagement**
    - Number of distinct publishers/contributors (relative to size of the catalogue in terms of datasets)
    - Number of apps developed on the data??

------------------

# Per-Dataset Measures (1/2)

- **Volume**
    - data volume: descriptive stats about dataset sizes
        - not predictive of anything, but interesting to know
    - rate of growth in data size / change in data volume over time

- **Metadata, Standards and Best Practices**
    - Populated metadata fields per dataset
    - Frequency and distribution of vocabularies used per metadata description
    - Open Data Certificate level

------------------

# Per-Dataset Measures (2/2)

- **Machine-readability and Usability**
    - Syntactic validation: errors and warnings from csvlint.io
    - Available extensions to 3rd party software (for working with the data); integration with other software

- **Timeliness**
    - Update frequency (also wrt to data release frequency)














	