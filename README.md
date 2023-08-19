# US-University-and-College-Ancestry-Visualization
The project aims to create visualizations to understand the evolutions of different universities and colleges in the United States from 1973 till 2021 based on the 10 updates of the Carnegie Classification of Institutions of Higher Education. The visualizations include the Table Visualization, Sankey Diagram, Bar Chart and Decomposition Tree. 

# Visualizations:

* Tracking the evolution of institutions over time within CCIHE is very challenging. This problem was solved using table visualizations
which helps in providing a clear and concise way of presenting this information. The visualization is structured as a table which includes name of institution, sub-category label and category label as shown in the Figure below. This allows viewers to easily track the evolution of each institution and see how changes in institution name correspond with changes in classification.

![Intitution Evolution over time](https://github.com/Mansisarda1999/US-University-and-College-Ancestry-Visualization/assets/60294261/bb79126f-56b5-4c18-b5c0-e1e77a72efb9)

Examining the table can reveal patterns in institution name changes and expansions of academic curriculum over time. For example, some institutions may change their names more frequently than others, or there may be certain periods of time when name changes are more common. Analyzing the table can also provide insights into the reasons behind institutional name changes. Institutions may change their names to better reflect their academic programs or to distance themselves from controversial histories, among other reasons. There also might be cases where the names have not evolved for a specific year but the institutes upgraded to include higher education domains and levels such Master’s or Doctoral programs. Changes in institutional names may correspond with changes in classification within the CCIHE framework. For example, an institution may change its name as part of an effort to improve its classification. Name changes can have a significant impact on an institution's identity and brand. Analyzing the table can provide insights into how institutions have navigated these changes over time. Finally, analyzing the table can reveal geographic and demographic trends in institutional changes. For example, certain regions or types of institutions may be more likely to change their names than others.

* Evolution of university category wise
Sankey diagrams are a type of data visualization that show the flow of data or information through a system. In the context of institutional evolution, a Sankey diagram could be used to show how institutions have changed over time in terms of their classification within the Carnegie framework as shown in the below Figure.

![Sankey Diagram](https://github.com/Mansisarda1999/US-University-and-College-Ancestry-Visualization/assets/60294261/5a6721a5-9dab-403e-ab06-5aef1d1014bf)

The diagram shows the flow of institutions from one classification to another over time, highlighting which categories saw the most movement. The diagram covered the 10 updates from 1973 with the most recent update as in 2021 according to the Carnegie framework. This provided a comprehensive overview of the evolution of universities in this timeframe. The diagram included all the categories from the data including two new categories labeled “Inactive” and “Not Yet Born”. The diagram helps analyze how institutions moved over a time period as institutions may remain in the same category or become part of a different classification. The width of the links are determined on the basis of weights which are summed up for every update of the university. The nodes for specific years are colored to identify the change over time more easily. For example, the diagram could show that many institutions moved from a "Master's Colleges and Universities" classification to a "Doctoral/Professional Universities" classification over the past decade, while relatively few moved out of the "Doctoral" category. This provides insight into how the landscape of higher education is changing, and which category types of institutions are growing or declining. The visualization also helps to understand when some institutions were established and if any institutions were shut down over the years and labeled as Inactive.

*  Name Change over the years
The Bar graph visualization is used to track the count of institutional name changes over time within the Carnegie Classification of Institutions of Higher Education (CCHIE) as shown in the below Figure.

![Bar Graph](https://github.com/Mansisarda1999/US-University-and-College-Ancestry-Visualization/assets/60294261/081cf57d-f0c6-4ebc-8ca9-f3ece3d02262)

The x-axis represents the year in which the name was updated as compared to previous year, while the y-axis represents the number of institutions which underwent the name changes as well as the count of universities which didn’t have any name change. By analyzing the bar graph, stakeholders can identify trends and patterns in institutional name changes over time. For example, the graph could reveal whether there are certain periods when name changes were more common, or if there are specific years when many institutions underwent name changes. Comparing the number of name changes to other institutional changes, such as changes in classification or status, can also provide insights into how name changes fit into broader institutional trends. For example we can interpret that the maximum number of changes occurred from 1973 to 1976. And the count of changes decreased in the next year and after that displayed a gradual increase trend until 2021. The bar graph can also be used to identify outliers or unique patterns. For instance, if there is a year with an unusually high number of name changes, it may be worth investigating the reasons behind this trend. Overall, a bar graph visualization can provide a clear and
concise way of analyzing trends in institutional naming over time within the CCIHE framework, and can help researchers gain insights into the factors driving these changes.

*  Distribution of Institutions

The Decomposition Tree visualization is used to display the distribution of institutions across different classifications of the Carnegie Framework and locations for each year as shown in the below figure. This allows the comparison between the number and type of each institution within each state and city for all the years. 

![Decomposition Tree](https://github.com/Mansisarda1999/US-University-and-College-Ancestry-Visualization/assets/60294261/00e58da0-edac-42b2-9263-0852b0aee650)

For example, the tree shows that California has the maximum number of institutions in the year 2015 in Los Angeles and has a max number of institutions in the "SF: 4yr Colleges and Universities" classification, while New York has a greater number of institutions in the "SF: 4yr Colleges and Universities" classification. Over time, the tree could reveal shifts in the distribution of institutions within each state, indicating changes in the higher education landscape.

To design this visualization, the tree is organized by this specific ordering to show major groups higher in the hierarchy. Hence the Year is represented first followed by State and City columns for geographic analysis. Then for each the count is shown for each category and sub category of Carnegie Framework.

The tree includes all the categories from the Carnegie framework. This gives a detailed analysis of how each state has moved from different types of classification. This also helps in determining which institutes have been growing or diminishing over time.  Also gives insight as to which state shows significant allocation of resources to education and academic variety.

# Challenges
* Data accuracy and completeness: The quality of the data used in the visualization can significantly impact its effectiveness. We have incomplete and duplicate data that can lead to incorrect or misleading conclusions. 
To resolve this issue, we have restructured and cleaned the data. For instance, the universities which were under the “Unclassified” label are now categorized in “Not yet born” and “Inactive”.  
We have also reported some of the inaccuracy issues to our client so that they can rectify at their level. 
* Visual clarity and user-friendliness: The tool's interface and visual representation of data must be clear and easy to understand to ensure that users can effectively interpret and analyze the information presented. Our previous Sankey diagrams showed the course's evolution over the time frame of total universities. However, we were not able to show the information of a particular university.

# Conclusion
The use of the above visualizations can provide valuable insights into the evolution of institutional names and classifications within the Carnegie Classification of Institutions of Higher Education (CCIHE) framework. These visualizations allow researchers to track patterns and trends in institutional name changes and understand how institutions have navigated changes in classification and location over time.

The Table visualization which is the primary deliverable for the stakeholders provides a clear and concise way of presenting the evolution of institutional names and classifications over time. It allows viewers to easily track the changes in the name of institutions, sub-category label and category label. By analyzing this visualization, stakeholders can gain insights into the reasons behind institutional changes, how they correspond with changes in classification, and geographic and demographic trends in institutional name changes.

A Sankey diagram is particularly useful for showing the flow of institutions from one classification to another over time. This visualization allows researchers to identify which categories saw the most movement and gain insights into how the landscape of higher education is changing.

Bar Chart visualizations can help researchers identify trends and patterns in institutional name changes over time. By comparing the number of name changes to other institutional changes, such as changes in classification or status, researchers can gain a deeper understanding of the factors driving these changes.

Finally, the Decomposition Tree helps in understanding the university distribution patterns based on location, year and classification. This will help policy makers to design the education curriculum accordingly which will vary state-to-state and assign resources to states which have lesser number of institutions and lack of academic domains coverage.


