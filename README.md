---
output:
  html_document: default
  pdf_document: default
editor_options: 
  chunk_output_type: inline
---
# Test_work
A repository for exploring testing work on various settings
This is a complete preview of the week 4 of the coursera project work

library(dplyr)
library(reshape2)
library(tidyr)
download.file("https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip",destfile = "Master.zip")
filelist <- unzip("Master.zip")
filelist
