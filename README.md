# homework_1_excel
module 1 - excel analysis


Given the data provided in the exercise:

•	Three conclusions that we can draw about the crowdfunding campaigns are:
o	Theater, music, film & video are the most popular crowdsourced projects on the platform. They account for approximately 70% of the total combined project volume on this crowdfunding platform. Plays are by far the largest sub-category with 34% of the total project volume. The next closest sub-category is rock music with 9% of the total volume.  
o	Seasonality does not have a strong effect on the success of projects, but June and July have above average success counts. August and September have the lowest relative success when analyzed on a 12-month cycle. 
o	Parent category sample sizes vary but technology and games have the largest variance of percent funded. Photography and publishing have the lowest variances (journalism does not have enough samples to be relevant). The variance of percent funded can viewed as a proxy for risk. 

•	Limitations of the dataset include:
o	The dataset is heavily weighted toward the arts. Other crowdfunding platforms may have greater focuses on technology, food, games, etc. This can mean a cause several biases (people looking to this platform to fund art projects, donors do not associate the platform with industries outside of the arts, etc.). Without more information about the platform and how it’s marketed, it’s difficult to know what is driving the focus on arts. 
o	The dataset does not provide any insight into why the projects failed. There does not appear to be a strong relationship to live campaign time and total funding. Without more information it’s hard to know specific success drivers beyond the category breakdown. 

•	Other tables:
o	The module asks for analysis around success/failure rates but does not address the total funding above the success threshold. The average funding to goal is 200% but some projects exceeded their goals by well over 10X. Viewing the data by the % funded metric can give a more nuanced analysis vs. the binary analysis (success/failed). 
o	Staff picks generally underperformed against projects that were not picked by the staff when you analyze the percent funded (185% to 201%, respectively). Spotlight projects were flat (outcome and funding percentage). 
o	The number of backers may also give insight into the relative success of a campaign. 

•	Notes:
o	Required sheets (tabs) in the workbook are formatted green across the bottom of the workbook. Extra analysis is formatted in blue. 
o	For the Goal Analysis, I created 2 new columns. One for the max value in the row, one for the min value. The point of this was to avoid hard coding the value into the formula. I hid the columns B & C to keep with the format of the table. 
o	For the Statistical Analysis:
	Statistics are based on this population. I did not interpret this dataset as a sample of all crowdfunding campaigns in a larger population. 
	The data is right skewed, so the median summarizes the data better, in both cases. 
	There is more variability with the successful campaigns. This makes sense because successful campaigns had higher counts of outliers, while unsuccessful campaigns generally had lower numbers of backers. 
