# Homeless Comparison: Oklahoma City and Seattle

# Readme

This dataset is focused on the race/ethinic homeless composition of the cities of Seattle and Oklahoma City. The breakdown, pulled from annual municipal reports and the Census, turns its gaze to the total population and percentage of White, Black/African-American, and Native American in these two respective cities. Also, the dataset is then broken down into the same demographics for the homeless population. Included is the sheltered and unsheltered homeless population.

## Contents

- [Naming](#naming) 
- [Normalization](#normalization)
- [Data Dictionary](#datadictionary)
- [Metadata](#metadata)
- [Security](#security)
- [Contact](#contact) 

## Naming

The File Naming Convention used for this dataset is .csv with purpose to ensure the creation of dataset supported by nearly all data interfaces. This faciliates the movement of importing and exporting data from one interface to the other. 

Should this project continue, city_homelesspopulation could be used if a single city or multiple cities are compared as spatial datasets. year_city_homelesspopulation could be used if a temporal element was implemented to compare cities over time.

## Normalization

Normalization was created by taking the Seattle/King County data and calculating the data that is specifically for Seattle. For both cities, all unsheltered data was calculated by eliminating calculations for those not in emergency shelters, transitional housing, etc. By focusing on raceand ethnicity, standards used by the Census were implemented into the data findings for both reports, and thus the set.


## Data Dictionary


| **Variable** | **Readable Variable Name** | **Measurement Unit** | **Allowed Values** | **Definition** |
| --- | --- | --- | --- | --- |
| **cityName** | City Name | String | US city names | Name of Cities in the United States |
| **#totalPopulation** | Total population  | Numerical | Integers greater than 0 | Total population of cities in dataset|
| **%White** | White population   | Numerical | Numbers between 0-100 (percentage) | Percentage identified as White in total city population |
| **%Black/African-American** | Black or African-American population  | Numerical | Numbers between 0-100 (percentage) | Percentage identified as Black/African-American in total city population |
| **%NativeAmerican** | Native American population  | Numerical | Numbers between 0-100 (percentage) | Percentage identified as Native-American in total city population. Includes American Indian, or First Nations |
| **%OtherRace/Ethinicity** | Other population  | Numerical | Numbers between 0-100 (percentage) | Percentage not identified as White, Black, or Native |
| **#totalHomelessPopulation** | Total homeless  | Numerical | Integers greater than 0 | Total homeless population of cities in dataset|
| **%WhiteHomeless** | White homeless  | Numerical | Numbers between 0-100 (percentage) | Percentage of homeless population idenfied as White in city population  |
| **%Black/African-AmericanHomeless** | Black or African-American homeless  | Numerical | Numbers between 0-100 (percentage) | Percentage of homeless population idenfied as Black/African-American in city population |
| **%NativeAmericanHomeless** | Native American homeless  | Numerical | Numbers between 0-100 (percentage) | Percentage of homeless population idenfied as Native in city population |
| **%OtherRace/EthnicityHomeless** | Other homeless  | Numerical | Numbers between 0-100 (percentage) | Percentage of homeless population not identified as White, Black, or Native |
| **#totalSheltered** | Total in shelter | Numerical | Integers greater than 0 | Total number of homeless population in a shelter |
| **#totalUnsheltered** | Total not in shelter | Numerical | Integers greater than 0 | Total number of homeless population not living in a shelter |

## Metadata
Schema Used: Dublin Core Metadata Initiative Project

| **Attribute** | **Value** |
| --- | --- |
| accessRights | Public |
| audience | Policy Makers |
| coverage | Oklahoma City |
| coverage | Seattle |
| date | 2020 |
| description | The resource is a comparison of homeless demographics of two U.S. cities of similar population, Seattle and Oklahoma City, respectively. These cities were chosen for this dataset because of size but also because they have divergent politics. This dataset is intended to be valuable to policy makers.|
| creator | Seth Kurke |
| format | CSV |
| identifier | [https://github.com/skurke1/okc-seattle-homeless](https://github.com/skurke1/okc-seattle-homeless)
| issued | 2021-03-08 |
| language | en-us |
| rights |Public |
| subject | &quot;homelessness&quot;, &quot;racial disparities&quot;, &quot;seattle&quot;, &quot;oklahoma city&quot;|
| title | Homeless Comparison: Oklahoma City and Seattle |
| type | Dataset |

## Security

This data repostitory is open to the public.

## Contact
Seth Kurke
skurke1@uw.edu


