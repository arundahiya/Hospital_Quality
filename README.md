Hospital_Quality
================

#Functions mining a government health data set.
Deriving metrics to classify the quality of care of various U.S. hospitals from the Hospital Compare web site (http://hospitalcompare.hhs.gov) run by the U.S. Department of Health and Human Services.

##Best
This function takes two arguments: the 2-character abbreviated name of a state and an outcome name. The function reads the outcome-of-care-measures.csvfile and returns a character vector with the name of the hospital that has the best (i.e. lowest) 30-day mortality for the specified outcome in that state.

##Rankhospital
This function called "rankhospital" takes three arguments: the 2-character abbreviated name of a state (state), an outcome (outcome), and the ranking of a hospital in that state for that outcome (num). The function reads the "outcome-of-care-measures.csv" file and returns a character vector with the name of the hospital that has the ranking specified by the num argument.

##Rankall
This function called "rankall" takes two arguments: an outcome name (outcome) and a hospital ranking (num). The function reads the outcome-of-care-measures.csv file and returns a 2-column data frame containing the hospital in each state that has the ranking specified in num.
