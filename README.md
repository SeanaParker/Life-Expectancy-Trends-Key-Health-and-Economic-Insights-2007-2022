# Global-Life-Expectancy-Analysis-2007-2022
Table of Contents

	Project Background

	Data Structure & Initial Checks

	Executive Summary

	Insights Deep Dive

		Global Life Expectancy Trends

		Countries with the Largest Increases in Life Expectancy

		GDP and Life Expectancy Correlation

		Developed vs. Developing Countries

		BMI and Life Expectancy Analysis

		Adult Mortality Trends and Regional Disparities

	Recommendations

	Assumptions and Caveats



Project Background

Life expectancy is a key indicator of health and economic conditions worldwide. This project analyzes data from the Global Health Observatory (GHO) under the World Health Organization (WHO) and economic indicators from the United Nations, covering 193 countries from 2007 to 2022. Using SQL, I explored trends, examined disparities in life expectancy, and assessed the relationship between GDP and healthcare access. The findings offer data-driven insights to inform public health strategies and resource allocation.



Insights and Recommendations

Key areas analyzed include:





Trends in Global Life Expectancy



Countries with the Largest Increases in Life Expectancy



Relationship Between GDP and Life Expectancy



Impact of Economic Status (Developed vs. Developing Countries)



BMI and Life Expectancy Correlations



Adult Mortality Trends and Regional Disparities



The SQL queries used to inspect and clean the data for this analysis can be found here.

Targeted SQL queries used for exploratory analysis can be found here.

Raw datasets in Excel format can be found here.



Data Structure & Initial Checks

The dataset consists of two main tables: World_Life_Expectancy and World_Life_Expectancy_Continents, with a total row count of 3187 rows. 





World_Life_Expectancy: This table contains life expectancy data for 193 countries over a 15-year period (2007–2022), along with key health and economic indicators.



World_Life_Expectancy_Continents: This table serves as a reference table that categorizes each country by its corresponding region and sub-region data.



To ensure data integrity, the following cleaning steps were taken:





Removed duplicate entries based on 'Country' and 'Year'.



Addressed missing values by filling blank 'Status' values with the most frequent classification for each country.



Imputed missing 'Lifeexpectancy' values using the average from adjacent years for the same country.
