## this is a test repo for testing segmentation for activities

### categorized_data are activities data, with categorizing by person and activity.

### the segmentation file does following
    * shuffle the categorized data
    * combine files after shuffling, do normalization
    * build evaluation funciton, give out false positive percentage, and positive true percentage
    * test with 1 second, 3 seconds, 5 seconds, with overlaping as N.A, 1 second, 3 seconds
