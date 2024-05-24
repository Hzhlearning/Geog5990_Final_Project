# Analysis of Disability Rates and PPFI Correlation
## Background and Context
This project is dedicated to exploring the correlation between the Priority Places for Food Index (PPFI) and disability rates in Leeds, and to further understanding the distribution patterns of disability rates in different urban areas through cluster analysis.PPFI, as a measure of the distribution and accessibility of food resources in a city, is strongly correlated with the quality of life of disability groups. By analysing the relationship between PPFI and disability rates, we can identify possible inequalities in urban planning, thus providing a basis for more equitable and effective urban food policies.

In addition to this, the application of cluster analysis allows us to group different areas in the city based on similarities in disability rates, which not only helps us to identify areas with similar characteristics, but also provides a deeper understanding of the differences between areas and their possible causes. The introduction of this methodology deepens the insight into the deeper relationships behind the data and provides a new perspective and analytical tool for urban policy makers to better meet the needs of people with disabilities, especially in terms of the distribution and accessibility of food resources.

Through the analyses in this project, it is hoped that it will contribute to the discussion on the improvement of the living environment of urban groups of persons with disabilities, as well as to the formulation and implementation of relevant policies to enhance their quality of life and social participation.
## Repository contents
<ul>
<li><strong>A Jupyter Notebook File(201787097_Project.ipynb)</strong></li>
contains the entire process of data processing and analysis, from data cleaning and exploratory data analysis to cluster analysis and correlation testing. The notebook details the code and comments for each step so that users can follow the steps to understand the logic and results of the analysis. And the internal Markdown cell highlights why the current visual analytics and models were adopted.
<li><strong>Data Files</strong></li>
  This example applies to a total of 3 data, which are <strong>Leeds LSOA geographic data</strong>: Leeds.geojson (Source: [Open Geography portal of ONS](https://geoportal.statistics.gov.uk/))<br>
  <strong>ppfi_index_v2_nov2023.csv: </strong> Priority Places for Food Index Version 2 (Source: [CDRC](https://data.cdrc.ac.uk/dataset/priority-places-food-index-version-2)) <br>
  <strong>Disable_per.csv: </strong>Disability rates (Source: [Census data](https://www.nomisweb.co.uk))
</ul>

## Guidelines for use
<ol>
<li>Environment preparation: Make sure that Python and the necessary Python libraries such as numpy, pandas, matplotlib, etc. are installed. For specific libraries, please refer to the applicable list in the notebook.</li>
<li>Data preparation: Download the required data files and make sure that the file path in Jupyter notebook matches the local storage path.</li>
<li>Run Notebook: open Jupyter notebook and execute each cell in order, taking care to read the comments at each step to better understand the analysis process.</li>
</ol>
