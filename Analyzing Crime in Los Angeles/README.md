

## How to approach the project

    1. Finding the frequencies of crimes by the hour of occurrence

    2. Identifying the area with the most night crime

    3. Crimes by age group

## Finding the frequencies of crimes by the hour of occurrence
    You can extract the hours from the relevant column, convert it to integer data type, and plot the frequencies.


    Extracting the hours
    Plotting the frequencies
    Storing the hour as a variable

## Identifying the area with the most night crime
    You'll need to filter the data for the relevant hours and count the number of crimes by area.

    Subsetting for night hours
    Counting crime by area

## Crimes by age group
    Bin and label victim age into the provided groups, then produce a pandas Series detailing how many crimes were committed against each age group.


    Creating bins and labels
    Adding a new column to the crimes DataFrame containing binned age bracket values
    Counting crimes by victim age group