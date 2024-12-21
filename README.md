# BST2602024FallFinalProject
This repo was made for the final project of BST 260 2024 Fall, contributed by Arthur Zeng, Irisa Jin, and Alexandra Han

To reproduce this report as well as all data:

###Preparation 1###
Run intall.r file to install all package before running all question qmd file
###Preparation 2###
Your own census key is required to be put into census_key.r file.

###1###
Run main.qmd file in code folder

###2###
#You can dismiss this step since the data had been outputed into data file#
Run code/Time_Series.qmd file which may take 20-40 min, this step creates an estimated mortality data for 2020-2023.

###3###
Run code/q1.qmd, code/q2.qmd, code/q3.qmd, code/q4.qmd, code/q5.qmd to reproduce all figures and tables based on their comments.
##You have to choose RUN ALL
##Dont restart R nor clean your wd until you finish all steps
All files have to run in question number order (q1 first, then q2, then q3...).

###4###
The raw data of estimated population has been downloaded and was stored into raw-data folder
The processed data and estimated mortality data were stored into data folder
The images were outputted into doc folder

###5###
Render report.qmd to generate final report.pdf in code folder. A report.pdf has been made in case you want to look at the results first.


###Author###
Arthur Zeng, Irisa Jin, Alexandra Han

###Special Thanks###
Special thanks to Bruce Zhou for his help on fixing the git merge issue on our repo.