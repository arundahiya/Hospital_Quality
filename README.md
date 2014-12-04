Hospital_Quality
================

#Functions mining a government health data set.
Deriving metrics to classify the quality of care of various U.S. hospitals from the Hospital Compare web site (http://hospitalcompare.hhs.gov) run by the U.S. Department of Health and Human Services.

##Best
This function takes two arguments: the 2-character abbreviated name of a state and an outcome name. The function reads the outcome-of-care-measures.csvfile and returns a character vector with the name of the hospital that has the best (i.e. lowest) 30-day mortality for the specified outcome in that state.
