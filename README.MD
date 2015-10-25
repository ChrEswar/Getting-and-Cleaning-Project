Description

Downloading Data

I have already downloaded the data to my   D://Dataset_getclean



File Preparation

Using the package data.table 
read the both the files into two variables
using rbind merged the two files 


Extract Mean & Standard Deviation Measurements

for the features text , found out the mean and std. found around 80+ features have been found.


Tidy Data Output

I used melt and merge to trim the data down and then summarize. I then output the file as a txt with headers.


