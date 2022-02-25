Overview:
Creates data visualizations based on COVID-19 case data to look for trends. Note that this was a personal project and was never meant to be a finalized product. 

Notes:
Must run data_analysis.Rmd first. This downloads all of the covid-19 case data (Source: Johns Hopkins University, https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data), analyzes it, and puts it in the format required by the data visualizations. To change the dates of the data that are grabbed by the script, change to_date and start_date for county data (lines 29 and 30) and to_date_state and start_date_state for state data (lines 51 and 52). Exports 4 files to be read in by the data visualizations (state_data_final3_test33.csv, county_data_final4_test30.csv, US_data_final2_test15.csv, country_data_final2_test10.csv). WARNING: This process is time consuming, computationally intensive, and can output large files.

To run the data visualization, run viz.Rmd. This might take a little bit to import all of the data exported by data_analysis.Rmd. To change dates of analysis, change lines 25 and 26 (to_date, start_date).
