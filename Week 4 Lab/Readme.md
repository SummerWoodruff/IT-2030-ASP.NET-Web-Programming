
Issues found:
1-	MealCost variable in the tipcalculator.cs file was  missing data type declaration. Added “double?” before the variable name to declare it as a double type fixing the syntax error
2-	The return statement was missing a semicolon, in the CalculateTip method. Added semicolon to end of line
3-	Range attribute in the MealCost variable, minimum value was set to 0.0 which allowed users to enter 0 as the cost of the meal, causing an incorrect tip amount to be calculated, changed minimum value to 0.01 to fix
4-	Label element in the site.css file, width of label element was set to 10em, causing labels to not display correctly. Fixed by changing to 20em. and correcting widht to width
