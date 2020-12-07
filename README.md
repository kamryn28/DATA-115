# Adoption of Genetically Engineered Crops in the U.S.

## Motivation
Over the last twenty years, biotechnology has drastically improved and the capabilities of genomics has expanded greatly. I am pursuing a degree in Agricultural Biotechnology so I was interested in looking at how the use of genetically engineered crops has changed over time. The three main genetically engineered crops in the U.S. include corn, soybean and upland cotton. Although there are other types of genetically engineered crops grown and sold in the U.S., I was only able to discover data involving the three most commonly grown GMO crops from the <a href="https://www.usda.gov/content/usda-open-data-catalog">USDA Open Data Catalog</a>.  Other GMO's grown in the U.S. are less significant since they are grown in relatively small numbers.

## Data Source
The USDA collected data from 2000-2020 about the use of insect-resistant, herbicide-tolerant or stacked gene varieties of corn, soybean and cotton. The <a href="https://www.ers.usda.gov/data-products/adoption-of-genetically-engineered-crops-in-the-us.aspx">Adoption of Genetically Engineered Crops in the U.S.</a> dataset helped me to answer some questions I had about GMO use.  The data was collected by USDA's National Agricultural Statistics Service (NASS).

## Processing Steps
There was not much processing that needed to go into preparing the data for analysis.  The dataset was already very clean and even sorted by the "Table" column, which describes which crop species it is.  Some entries in the percentage column contained a period or an asterisk.  It was not clear whether these inputs mean zero or no data, so those entries were left alone and are not included in the visualizations.  However, for construction of the boxplots it was necessary to alter these entries so rather than taking the data out I changed them to zero.  The only other changes made to this dataset was eliminating unnecessary spaces in some of the entries.

## Visualization

All visualizations created were bar graphs due to the data containing all categorical values except the percentage column.  To start, I created bar graphs of the percentage of Genetically Engineered crops planted by year separated by species of the crop, displayed in the first image.
As shown in the second graph, I also graphed the percentage of GMO crops by the variety of the GMO.  

<img width="383" alt="Year_by_Crop" src="https://user-images.githubusercontent.com/71746406/101296954-3a468e00-37db-11eb-8771-736aa610c273.png"> <img width="378" alt="Year_by_Variety" src="https://user-images.githubusercontent.com/71746406/101296958-403c6f00-37db-11eb-869a-4baef637d7a9.png">

## Analysis

<img width="327" alt="boxplot_crop" src="https://user-images.githubusercontent.com/71746406/101310493-de442f80-3803-11eb-992b-cb6fde5484cc.png"> <img width="341" alt="boxplot_variety" src="https://user-images.githubusercontent.com/71746406/101310510-e7cd9780-3803-11eb-94b8-be2a7bab53f3.png">

## Descriptions of Codes and Materials
