

## Data Entry Analysis

This document describes the proposed solutions to the problems identified in the data provided for the data entry analysis assignment.

## List of Files
•	https://github.com/spathala/Data2Decisions/blob/master/Data%20Entry%20Analysis/pond2010.xlsx
•	https://github.com/spathala/Data2Decisions/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp-main.xlsx
•	https://github.com/spathala/Data2Decisions/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp.xlsx

## Authors

**Shravya Shruthi Pathala** - *Initial work* - [Shravya Shruthi Pathala](https://github.com/spathala)

See also the list of [contributors]( https://github.com/spathala/Data2Decisions/graphs/contributors) who participated in this project.

### Summary of The Files

The 3 excel files added to the folder “Data Entry Analysis” belong to the same research performed to examine the day-night distribution of 2 species of zooplankton across multiple years. The type of zooplankton they studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual rotifers stick together in colonies. The scientists plan to repeat this study for several more years as per the description provided in the assignment

### Task 1

# Problems identified in the data files provided

1.	Units for certain columns are not specified. 
•	In all 3 files, Temp field doesn’t specify whether noted in Fahrenheit or Celsius.
•	Density in “pond2010.xlsx”
•	Chla (Chrolophylla) 

2.	Column names may not be understood by the user of zoop-temp.xlsx since it does not have the names tab unlike the zoop-temp-main.xlsx. Also, in pond2010.xlsx column “Z” does not indicate which data is collected (attribute) clearly.

3.	Data for the same attributes is collected and maintained in two different files.

4.	Since there is no time of sample collection is noted for zooplankton data maintained in both files (zoop-temp-main and zoop-temp), it creates ambiguity to the user to perform analysis of the day and night distribution.


5.	Labels and units for the axes are not mentioned in the graph

6.	Since the data of ponds and zooplanktons is collected in different time-period, the purpose of the study to compare may not be fulfilled. The pond data is collected in 2010, while the zoop data is collected in 2011

7.	No yellow notebook provided for the map and details 

8.	 Incorrect values are entered in the file failing domain integrity. Negative values cannot be possible for the number of cuni/chippo per liter

9.	Some of the column names are not clear/ understandable to layman. For example, column “z” in pond2010.xlsx file

10.	The reason for color coding is not clearly mentioned to the user. Certain values in the provided data files are in red/yellow

11.	In zoop-temp.xlsx, 
•	The term “secchi” is neither explained nor used.
•	The purpose for the small table to the right is not clearly understood (7th,9th, chippo, cuni)

### Task 2

# Suggestions for a new system for organization

1.	A more advanced method of saving data can be used like MS Access. But since we are using excel, we can combine all 3 files to a single file and use filters to easily look up data.
2.	Single file for zooplankton data should be maintained with proper time being noted for samples under a new column “Time” and “Station”. Which in turn eases the analyses for day and night distribution at respective stations.
3.	Column names should be clearly written following the standard naming conventions.
4.	The units of measurement for columns should be specified.
5.	Domain integrity needs to be enforced to eliminate the risk of incorrect values being stored.
6.	Unnecessary color coding of the data can be removed.
7.	Any graphs or interpretations made, should have clear labels.

### Proposed Table  

| Time | Date | Species | Species #/L | Species Colony Size(millimeter) | Depth(meters) | Chlorophylla | Station | Density (Kg/cubic meter) | Temperature(Degree Fahrenheit) |
|-----------|------|----------|------------------------------|---------|---------------|------------|--------------------------------|---------------|---------|


