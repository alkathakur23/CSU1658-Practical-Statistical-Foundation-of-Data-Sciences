#Problem Solution (Theory Explanation)
1️) Percentage of minorities who are tenured professors

To find this, the number of professors who belong to a visible minority and also have tenure is compared with the total number of minority professors.
The result gives the percentage of minorities who are tenured.

Interpretation:
If the percentage of tenured professors among minorities is significantly lower than among non-minorities, it indicates that tenure status differs based on minority status. This may suggest inequality or underrepresentation in tenure positions.

2️) Does average age differ by tenure?

To check this, the mean (average) and standard deviation of age are calculated separately for tenured and untenured professors.

Mean age shows the average age in each group.

Standard deviation shows how spread out the ages are.

Interpretation:
If tenured professors have a noticeably higher mean age, it means that tenure is generally achieved later in one’s career — indicating that experience and age are linked to tenure.

3️) Which graph works better for the age variable?

For the variable age, which is continuous numerical data, the best graphs are:

Histogram: Shows how ages are distributed across different intervals.

Boxplot: Shows the median, quartiles, and any outliers in age distribution.

Conclusion:
A histogram is best for understanding the overall distribution of age, while a boxplot is best for comparing age differences 
between tenured and untenured groups.

4️) Difference between pyplot.bar and pyplot.barh
Function	Description
pyplot.bar()	Used to create vertical bar charts. Each bar stands upright.
pyplot.barh()	Used to create horizontal bar charts. Each bar extends sideways.

Application (Gender Variable):
When visualizing the number of male and female professors:

A bar chart can show gender distribution vertically.

A horizontal bar chart is often clearer when category names are long or there are many categories.

5️) Median evaluation score for tenured professors

The median is the middle value of the evaluation scores of tenured professors.
It divides the data so that half of the professors have higher evaluation scores and half have lower.

Interpretation:
The median evaluation score gives a fair idea of the typical teaching performance among tenured professors. It is less affected by extreme values
(very high or very low evaluations).

#Tech Stack
Category	Tools / Technologies	Purpose
Programming Language	Python	Used for data analysis and visualization
Data Handling Library	Pandas	Used for data manipulation and statistical calculations
Visualization Library	Matplotlib (Pyplot)	Used for creating different types of plots and charts
Development Environment	Jupyter Notebook / Google Colab / VS Code	Used to write and execute Python code
Dataset Used	Student Range Dataset	Contains faculty-related data such as age, tenure, gender, minority status, and evaluation score
