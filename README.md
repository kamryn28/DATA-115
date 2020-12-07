# Adoption of Genetically Engineered Crops in the U.S.

## Motivation
Over the last twenty years, biotechnology has drastically improved and the capabilities of genomics has expanded greatly. I am pursuing a degree in Agricultural Biotechnology so I was interested in looking at how the use of genetically engineered crops has changed over time. The three main genetically engineered crops in the U.S. include corn, soybean and upland cotton. Although there are other types of genetically engineered crops grown and sold in the U.S., I was only able to discover data involving the three most commonly grown GMO crops from the <a href="https://www.usda.gov/content/usda-open-data-catalog">USDA Open Data Catalog</a>.  Other GMO's grown in the U.S. are less significant since they are grown in relatively small numbers.

## Data Source
The USDA collected data from 2000-2020 regarding the use of insect-resistant, herbicide-tolerant or stacked gene varieties of corn, soybean and cotton. The <a href="https://www.ers.usda.gov/data-products/adoption-of-genetically-engineered-crops-in-the-us.aspx">Adoption of Genetically Engineered Crops in the U.S.</a> dataset helped me to answer some questions I had about GMO use.  The data was collected by USDA's National Agricultural Statistics Service (NASS). The raw data is included above as alltablesGECrops_raw.csv.

## Processing Steps
There was not much processing that needed to go into preparing the data for analysis.  The dataset was already very clean and even sorted by the "Table" column, which describes which crop species it is.  Some entries in the percentage column contained a period or an asterisk.  It was not clear whether these inputs mean zero or no data, so those entries were left alone and are not included in the visualizations.  However, for construction of the boxplots it was necessary to alter these entries so rather than taking the data out I changed them to zero.  The only other changes made to this dataset was eliminating unnecessary spaces in some of the entries.

## Visualization

All visualizations created were bar graphs due to the data containing all categorical values except the percentage column.  To start, I created bar graphs of the percentage of Genetically Engineered crops planted by year separated by species of the crop, displayed in the first image. These graphs clearly show that the amount of GMO use increases from 2000-2005 then remains relatively constant in the 15 years following for each species of crop.  The graph also displays differences in which crops have more GMO varieties. There are more corn and cotton GMO's used than soybean.

As displayed in the second graph, I also graphed the percentage of GMO crops by the variety of the GMO. From this graph it provides the ability to distinguish between the types of GMO's used.  It is clear that insect-resistant cultivars have been used at a decently constant rate from 2000-2020.  The stacked gene varieties (which is a combination of insect-resistant and herbicide-tolerant) increased slightly every year, going from less than 5% in 2000 then continuing up to a peak of 80% in the last 5 years.  Herbicide tolerant cultivar usage was low in 2000 then increases until 2005 where it then remains constant for the remaining years.  It also shows that stacked gene varieties are used more in recent years than insecticide-resistant only or herbicide-resistant only.  When combining all of the varieties it appears the use has remained relatively constant throughout all years displayed.

<img width="383" alt="Year_by_Crop" src="https://user-images.githubusercontent.com/71746406/101296954-3a468e00-37db-11eb-8771-736aa610c273.png"> <img width="378" alt="Year_by_Variety" src="https://user-images.githubusercontent.com/71746406/101296958-403c6f00-37db-11eb-869a-4baef637d7a9.png">

## Analysis

To further analyze the bar graphs above, I graphed them as boxplots.  This way I was able to identify outliers and understand the distribution of the data represented in the bar graph visuals.  We are able to see Tukey's 5 number summary as a visual.  In the first graph it is clear there are outliers in the soybean cultivar.  In the second graph it is apparent that outliers exist in the herbicide-tolerant varieties as well.  These two graphs are also where the most increase of percentage planted overtime is demonstrated.  The outliers were not removed because they are significant in portraying the change in the adoption of the species or variety of crop overtime.

<img width="327" alt="boxplot_crop" src="https://user-images.githubusercontent.com/71746406/101310493-de442f80-3803-11eb-992b-cb6fde5484cc.png"> <img width="341" alt="boxplot_variety" src="https://user-images.githubusercontent.com/71746406/101310510-e7cd9780-3803-11eb-94b8-be2a7bab53f3.png">

## Descriptions of Codes and Materials
The raw data that was downloaded from the <a href="https://www.usda.gov/content/usda-open-data-catalog">USDA Open Data Catalog</a> is uploaded in .csv form as alltablesGEcrops_raw.  The notebooks created to complete processing of the data and producing plots are uploaded as PP1.ipynb, PP2.ipynb and PP3.ipynb.
