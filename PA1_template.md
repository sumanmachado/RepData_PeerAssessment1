---
title: "Reproducible Research - Assignment 1"
author: "Suman Machado"
date: "Saturday, July 18, 2015"
output: html_document
---

This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.

### Data

The variables included in this dataset are:

steps: Number of steps taking in a 5-minute interval (missing values are coded as NA)

date: The date on which the measurement was taken in YYYY-MM-DD format

interval: Identifier for the 5-minute interval in which measurement was taken

The dataset is stored in a comma-separated-value (CSV) file and there are a total of 17,568 observations in this dataset.



### What is mean total number of steps taken per day?

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png) 

Note: The mean is a red line and the median is an orange line.

## What is the average daily activity pattern?

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3-1.png) 

The 5-minute interval that contains the maximum number of steps


```
## [1] 835
```

## Imputing missing values

The total number of missing values in the dataset are:


```
## [1] 2304
```

The strategy used for imputation is to fill in the missing NA values with the average steps for the given interval.

![plot of chunk unnamed-chunk-6](figure/unnamed-chunk-6-1.png) 

Note: The mean is a red line and the median is an orange line.

The impact of imputing missing data on the estimates of the total daily number of steps is that the data has a wider distribution and the mean and median are the same.

## Are there differences in activity patterns between weekdays and weekends?

![plot of chunk unnamed-chunk-7](figure/unnamed-chunk-7-1.png) 
