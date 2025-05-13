# Occupancy modeling of the Sonoran desert toad and mud turtle

##### CalebMilford_DataWrangling

## Summary

This repository includes data sets and code looking at the encounter history of Sonoran desert toad (in the code marked as BUAL) and Sonoran mud turtles (in the code marked as KISO) over the course of 3 years. These are presence/ absence studies that also record different landscape and site covariate data. The code is designed to help determine what are detection level covariates for these two species.

Under the Geospacial section of the project I also started working with data from the other half of my thesis. The data is the field site locations where Rio Grande Leopard frogs have been found and where I will continue doing collections. I was simply taking this opportunity to practicing making maps and it is something that will be very useful for me to have later.

In the Final_Project_Script.Rmd (found in the scripts folder), you will find headings before cod chunks outlining which week it is covering primarily. There are some code chunks that have some overlap between weeks in order to complete an overarching task.

## Structure

-   data_raw - starting data

    -   The data I am using primarily is in the "Combined_Frog" CSV file
    -   The RMD files were already cleaned versions of the raw data. I did not end up using them. I only used them as a reference on how I could clean my own data better. These can be ignored
    -   The RABE_SiteQuery_HerpsDB.csv is a completely seperate part of my thesis but I am using this opportunity to practice doing some geospacial data manipulation with it

-   data_clean - data that has been restructures and/or cleaned

    -   BUAL_EH - The encounter history of the desert toad
    -   BUAL_monthly_det - The number of times per month per year the desert toads were detected
    -   KISO_EH - The encounter history of the mud turtle
    -   KISO_monthly_det - The number of times per month per year the mud turtles were detected
    -   master_df - the clean, organized and final data frame that has all the pertanent information i need going forward to continue analyzing my thesis data
    -   RABE_sites - the locality data of the Rio Grande leopard frog sites
    -   survey_data - the data set that holds all the vegitation, climate, survey level covariate data
    -   survey_year_summary - shows the number of times each site was surveyed each year

-   scripts - different code chunks

    -   Final_Project_Script.Rmd - This is the main script for my final project
    -   Planning doc - just for me to help think about all the objectives I need to accomplish both between this class and what would be useful for my thesis. This mostly can be ignore unless you want to see how my weird brain works

-   output - plots, graphs and tables

    -   KISO_BUAL_site_map - an interactive map that shows all the survey site locations for the desert toad and mud turtle study

    -   prop_detec_plot - ggplot showing the proportion of detections for each species per month per year

    -   RABE_sites_map - an interactive map that shows all the survey site locations for Rio Grande leopard frogs
