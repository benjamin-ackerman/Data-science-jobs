This repository contains all files related to my project for the first term of Advanced Data Science at JHSPH, in which I explore trends in data science job listings on Stack Overflow.  Due to data privacy issues, the data are stored separately, and are only accessible with permission from their owner.

Here is some helpful information to locate relevant files and code:

- My original ideas for this project are located in the file titled **projectplan.Rmd**; however, these plans are outdated and do not reflect my final plans, data sources, or analyses.
- Prior to obtaining data directly from Stack Overflow, I attempted to scrape data from the web from two job boards: Datajobs.com and Stack Overflow.  All relevant code for creating those data frames and creating exploratory plots are located in the file titled **finalproject.Rmd**; however, this code was not used to create the final report.
- The final code used to read in and clean the data and to create figures and tables is located in the file titled **writeup.Rmd**, and the written report is titled **writeup.pdf**.  If you have obtained the data for this project, please keep the following in mind when running this `.RMD` file:

     1. The very first chunk of code contains the names of all `R` packages used.  Please run the first chunk prior to knitting the document, so that all required packages are installed and loaded on your system.
     2. The third chunk of code contains all of the code used to clean the data obtained directly from Stack Overflow.  If you have the raw data from Stack Overflow, please run this code before compiling the document, so that the cleaned data are saved to your system. If you already have the cleaned data, please disregard this chunk, and keep it hidden as it currently is.
     3. Again, please keep these data private.  I am thankful to have access to them for the purpose of this project, and wish to respect the requests of their owner.
