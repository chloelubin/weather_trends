### Weather Trends

In this weather trends project, I explore the correlation between local and global average temperatures by 
comparing weather trends in San Francisco against global average temperatures. In this analysis, I am looking 
to answer the following question: how indicative global estimates are of local temperature averages? I decided 
to limit my universe of elements to a specific city, San Francisco, for the sake of time.

**I performed the following operations:**
1. Queried the data for San Francisco and global average temperatures using SQL
2. Computed a 4-year moving average of San Francisco and global average temperatures in Excel
4. Built a pivot table and a line chart for the four variables (San Francisco avg_temp, San Francisco MA_temp,
global avg_temp, global MA_temp) in Excel
5. Computed the correlation coefficient between the San Francisco MA_temp and the global MA_temp

**Here's the summary of my conclusions:**
* the temperatures in San Francisco are consistently higher that the global estimates, about 69% higher on average.
* A big difference we also note is the fact that local and global temperatures increase at a different rate. While 
temperatures in San Francisco, measured by the moving average, only increase by approximately 8% between 1849 and 2013, 
global temperatures increase much more rapidly, at 19% for the same time period.
* In this case, the coefficient of San Francisco and global temperature moving averages is approximately 0.71.
The coefficient seems to indicate here a relatively strong positive correlation, observed by occasional synchronic 
movement of both lines.
