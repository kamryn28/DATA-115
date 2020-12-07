# Adoption of Genetically Engineered Crops in the U.S.

## Motivation
Over the last twenty years, biotechnology has drastically improved and the capabilities of genomics has expanded greatly. I am pursuing a degree in Agricultural Biotechnology so I was interested in looking at how the use of genetically engineered crops has changed over time. The three main genetically engineered crops in the U.S. include corn, soybean and upland cotton. Although there are other types of genetically engineered crops grown and sold in the U.S., I was only able to discover data involving the three most commonly grown GMO crops from the <a href="https://www.usda.gov/content/usda-open-data-catalog">USDA Open Data Catalog</a>.  Other GMO's grown in the U.S. are less significant since they are grown in relatively small numbers.

## Data Source
The USDA collected data from 2000-2020 about the use of insect-resistant and herbicide-tolerant varieties of corn, soybean and cotton. The <a href="https://www.ers.usda.gov/data-products/adoption-of-genetically-engineered-crops-in-the-us.aspx">Adoption of Genetically Engineered Crops in the U.S.</a> dataset helped me to answer some questions I had about GMO use.  The data was collected by USDA's National Agricultural Statistics Service (NASS).

## Processing Steps
There was not much processing that needed to go into preparing the data for analysis.  The dataset was already very clean and even sorted by the "Variety" column, which described what type of GMO the crop was.  Some entries in the percentage column contained a period or an asterisk.  It was not clear whether these inputs mean zero or no data, so those entries were left alone and are not included in the visualizations.  The only changes made to this dataset was eliminating unnecessary spaces in some of the entries.

## Visualization

All visualizations created were bar graphs due to the data containing all categorical values except the percentage column.  To start, I created a bar graph of the percentage of all Genetically Engineered crops planted by Year.  The graph displays that when viewing all varieties and all species (corn, soybean, cotton), the amount of use increased from 2000 to 2005 but has generally remained constant in the years after 2005.  This visualization displays that there was an increase in the planting of GMO crops in regards to these three most common crops.
I also graphed the percentage of GMO crops by the state instead of the year, to see if there was any states that stood out.  The graph showed that Ohio and California have less GMO crops planted out of the three cultivars being analyzed, while Georgia and Missouri appear to have the most.

<img width="383" alt="Year_by_Crop" src="https://user-images.githubusercontent.com/71746406/101296954-3a468e00-37db-11eb-8771-736aa610c273.png">

<img width="378" alt="Year_by_Variety" src="https://user-images.githubusercontent.com/71746406/101296958-403c6f00-37db-11eb-869a-4baef637d7a9.png">

## Analysis

In order to further understand what was going on in the previous graphs, I broke down the genetically engineered crops by year graph into three graphs separated by the species of crop planted.  You can see in the graph below the differences in planting of specific crops.



Along with that, I broke down the genetically engineered crops by year graph again into 

<img width="327" alt="boxplot_crop" src="https://user-images.githubusercontent.com/71746406/101310493-de442f80-3803-11eb-992b-cb6fde5484cc.png">

<img width="341" alt="boxplot_variety" src="https://user-images.githubusercontent.com/71746406/101310510-e7cd9780-3803-11eb-94b8-be2a7bab53f3.png">

## Descriptions of Codes and Materials
