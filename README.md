<h2><p align=center> Oahu Weather Analysis </p> </h2>

<h3><p> Background </p></h3>
The 'Surf & Shake' shop idea needs a solid foundation of weather analysis as the business is highly dependent on the weather at that location. This analysis builds a solid foundation to back up the business plan and answers a few questions for the investor of the project.


<h3><p> Purpose </p></h3>
The main purpose of the analysis is to analyze the weather on the Oahu island using the dataset and tools listed below. The outcomes of the analysis will help make a decision about the success of the upcoming 'Surf & Shake' shop on the Oahu island.

<h3><p> Resources: </p></h3>

Data Source: hawaii.sqlite

Software: SQLAlchemy, Flask, Python 3.7.10

IDE: Jupyter notebook, Visual Studio Code 1.60.0

<h3><p> Analysis Overview: </p></h3>

The hawaii.sqlite dataset contains the Oahu island weather data for 8 years. The dataset is analyzed using python and SQLAlchemy. The focus of the analysis is on the statistical analysis of temperature data over past 8 years. Analysis consists of two parts, first part is statistical summary of temperatures on Oahu island in the months of June. Second part takes account of the statistical summary of temperatures in the month of December. Let us take a look at both the parts in the following sections:

<h4> PART I : Summary Statistics for June </h4>

- After importing the dependencies, the data from sqlite files is reflected into tables and the table references are saved into Measurement and Stations tables for querying purposes.
- The summary statistics for June are determined querying and filtering the temperature data from Measurement table for only the month of June.
- It is then converted into a dataframe to get the summary statistics using the .describe() method in Padas.


<h4> </h4>

<kbd>
  <img width="770" alt="Screen Shot 2021-12-18 at 10 30 10 PM" src="https://user-images.githubusercontent.com/90424752/146666175-ddfa7cc1-7d15-4a81-af69-d96014cbae1e.png">

</kbd>

<h4> PART II : Summary Statistics for December </h4>

- The summary statistics for the month of December are calculated in the same manner, by filtering all temperatures for the month of December from Measurement table.
- The attached image shows the summary results for December temperatures on Oahu island, Hawaii.

<kbd>
  <img width="792" alt="Screen Shot 2021-12-18 at 10 31 06 PM" src="https://user-images.githubusercontent.com/90424752/146666198-19b35319-e3c6-48af-9841-5b521ca70e0e.png">

</kbd>

<h3><p> Results </p></h3>

- The statistical summary of 8 years of temperature observation data for the month of June indicates:
    1. Median temperature is 75 F which is close to average temperature 74.94 F with standard deviation of 3.25 F.
    2. While min. temperature is 64 F, the max. temperature recorded is 85 F
-  The statistical summary of 8 years of temperature observation data for the month of December indicates:
    1. Median temperature is 71 F which is close to average temperature 71.04 F with standard deviation of 3.75 F.
    2. While min. temperature is 56 F, the max. temperature recorded is 83 F
-  We have slightly more data for the month of June (1700 recordings) than that for December (1517 recordings).
-  The minimum temperature for month of June is 64 F while for December it is 56 F.
-  The average temperatures also differ for both months. The average temperature for for June being almost 75 F and that for December is 71 F.

<h2><p align=center> Summary </p></h2>

- Statistically, the temperatures for the month of June seem favorable for the 'Surf & Shake' shop idea lying in the range of 64 F to 85 F with the mean of about 75 F.
- The month of December also seems to be temperate and in fact a great winter getaway for surfers, with temperatures going as high as 83 F and averaging 71 F.
- However, the precipitation is also an important factor to be considered along with the temperatures. 
- The additional analysis and summary for precipitation for months of June and December is added in a section below.

   
   
<h4><p align=left> Precipitation Analysis </p></h4>

The following image shows the **precipitation summary analysis** for the month of **June**.

- The average precipitation is 0.136 with minimum of 0 and maximum of 4.43.
- It is observed that overall the month of June has very low chances of precipitation.
- Hence it could be a good season for the business idea in consideration.

<kbd>
  <img width="844" alt="Screen Shot 2021-12-18 at 11 46 06 PM" src="https://user-images.githubusercontent.com/90424752/146667634-d07d181d-3a1c-42a2-bc6a-ea10630b5e39.png">

</kbd>

<p> 

</p>


The image below displays the **precipitation summary** for month of **December**.

- Month of December, with mean precipitation of 0.21 has minimum of 0 and maximum precipitation of 6.42.
- Hence, statistically there is low chance of precipitation in the month of December on Oahu island.
- This could make it a popular destination for winter getaway for surfers.


<kbd>

<img width="861" alt="Screen Shot 2021-12-18 at 11 47 21 PM" src="https://user-images.githubusercontent.com/90424752/146667670-1b91b21c-c061-4a92-ade5-6a9f6be4fb07.png">


</kbd>

