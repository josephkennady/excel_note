Here is an example of an Excel formula to calculate age based on a given birthdate and categorize the age into different ranges:

=IF(DATEDIF(B2,TODAY(),"Y")<18,"Under 18",IF(DATEDIF(B2,TODAY(),"Y")<30,"18-29",IF(DATEDIF(B2,TODAY(),"Y")<40,"30-39",IF(DATEDIF(B2,TODAY(),"Y")<50,"40-49",IF(DATEDIF(B2,TODAY(),"Y")<60,"50-59","60 or Above")))))

In this formula, "B2" is the cell that contains the birthdate and "TODAY()" returns the current date. The "DATEDIF" function calculates the difference between two dates and returns the result as a string in years. The "IF" function is used to categorize the age into different ranges based on the calculated difference.

=IF(DATEDIF(B2,TODAY(),"Y")<18,"Under 18",IF(DATEDIF(B2,TODAY(),"Y")<30,"18-29",IF(DATEDIF(B2,TODAY(),"Y")<40,"30-39",IF(DATEDIF(B2,TODAY(),"Y")<50,"40-49",IF(DATEDIF(B2,TODAY(),"Y")<60,"50-59","60 or Above")))))
