# Airline-Membership-Segmentation
Airline membership segmentation, for marketing purposed

<p align="center">
  <img src="https://user-images.githubusercontent.com/113813929/208122429-4fd53745-02c3-43c6-a018-d835769d9cb6.png">
</p>

In this project, we will try to analyze the characteristics of airline member, based on various category and segmenting the members. The result from this analysis, will help identify the right marketing steps for each segment. An airline can be defined as a company that offers regular services for transporting passengers or goods via the air. These companies are said to make up the airline industry, which is also regarded as a sub-sector of the aviation sector and the wider travel industry. 

For the dataset, we use [flight.csv](https://www.kaggle.com/datasets/felixign/airline-customer), and using **KMeans Clustering** method to help clustering the dataset. K-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean.

[source](https://www.revfine.com/airline-industry/#:~:text=An%20airline%20can%20be%20defined,and%20the%20wider%20travel%20industry.)
[source](https://en.wikipedia.org/wiki/K-means_clustering)

## Dataset Explanation
`MEMBER_NO` : ID Member <br>
`FFP_DATE` : Frequent Flyer Program Join Date <br>
`FIRST_FLIGHT_DATE` : First flight date <br>
`GENDER` : Member's gender <br>
`FFP_TIER` : Tier of Frequent Flyer Program <br>
`WORK_CITY` : Member's Hometown <br>
`WORK_PROVINCE` : Member's Hometown province <br> 
`WORK_COUNTRY` : Member's home country <br>
`AGE` : Member's age <br>
`LOAD_TIME` : Times when data collected <br>
`FLIGHT_COUNT` : Amount of flight taken <br>
`BP_SUM` : Travel plan <br>
`SUM_YR_1` : Fare Revenue <br>
`SUM_YR_2` : Votes Prices <br>
`SEG_KM_SUM` : Total miles <br>
`LAST_FLIGHT_DATE` : Last flight date <br>
`LAST_TO_END` : Distance between latest flight with last flight <br>
`AVG_INTERVAL` : Average time distance <br>
`MAX_INTERVAL` : Maximum time distance <br>
`EXCHANGE_COUNT` : Point exchange <br>
`avg_discount` : Member's average discount <br> 	
`Points_Sum` : Member's point amount 	<br>
`Point_NotFlight` : Unused point <br>


## Used Library
Python, numpy, pandas, sklearn, seaborn and matplotlib
