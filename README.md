# Automobile-Dataset
I was presented with a data set for automobiles.  The data consisted of make, wheel-drive, ect.
The purpose of this project was to clean the data and do visualizations.

##Data that was analysed
The data set that was analysed was a .txt file named automobile(https://github.com/Rhyno87/Automobile-Dataset/blob/master/automobile.txt).
The data set consisted of 26 columns and 206 rows.
**Columns**
The columns ranged from symbolizing, make, body style, engine size to name a few.
**Rows*
The rows contained the information of makes of automobiles.

##How data was analysed
I used jupyter note book to do the coding(https://github.com/Rhyno87/Automobile-Dataset/blob/master/automobile.ipynb)
The script was Phyton.  I observed that some of the data points were indicated by a question mark '?', and replaced them with a NaN value,
using .replace().
I also checked each column to determine how many missing values each had.  I also pulled the percentage of the missing data so see if the data 
was sufficient to work with.  Lastly I pulled a matix to visualize the missing data points.

##Main Findings
I compieled an EDA report(https://github.com/Rhyno87/Automobile-Dataset/blob/master/EDA.docx) to put all my findings in.
I did a box plot to show tthe comparison of the different drive-wheels to the price to see how the tyoe of prive influences the price of the automobile.
I also did a count plot to show the amount of automobiles per make in the data set.
Further I did a scatter plot to show how the engine -size of the automobile dictates the price of the automobile.
Lastly I did a pivot table and a heat map to show the average price as per the drive-wheel and body-style of the automobiles
