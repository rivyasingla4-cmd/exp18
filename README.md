Experiment 18

Exploring Statistical and Specialized Data Visualization Techniques

Name: Rivya Singla
Roll Number: 25070123091

⸻

Aim

The aim of this experiment is to understand and implement different statistical and specialized data visualization techniques using Python libraries like Matplotlib, Seaborn, Pandas, and NumPy. The goal is to represent data in graphical form to make analysis easier and more meaningful.

⸻

Theory

Data visualization is the graphical representation of data to help understand patterns, trends, and relationships. It is widely used in data analysis and decision making.

Matplotlib is a basic plotting library in Python used for creating simple graphs such as line plots, bar charts, and area plots.

Seaborn is built on top of Matplotlib and provides more advanced and visually appealing statistical plots like heatmaps, boxplots, and enhanced scatter plots.

Pandas is used for handling and analyzing structured data, while NumPy helps in numerical operations and generating random data.

Different types of plots used in this experiment

Area plot
Used to show the magnitude of values over categories

Pie chart
Represents data as proportions of a whole

Donut chart
A variation of a pie chart with a hole in the center

Box plot
Shows the distribution of data including median and outliers

Heatmap
Displays correlation between variables using colors

Bubble plot
A scatter plot where the size of points represents another variable

⸻

Code and Explanation

1. Import Libraries and Create Dataset

The required libraries are imported. A dataset is created using Pandas with random values generated using NumPy.

Explanation
NumPy is used to generate random sales and profit values
Pandas is used to store the data in tabular form

⸻

2. Area Plot

Code creates an area plot using fill_between function.

Explanation
fill_between fills the area under the curve
Categories are shown on x axis and values on y axis
Color and transparency are adjusted using parameters

⸻

3. Area Plot with Seaborn Style

Seaborn style is applied to improve the appearance of the graph.

Explanation
Two areas are plotted for sales and profit
Legend is added to distinguish between them
Transparency helps to compare overlapping areas

⸻

4. Pie Chart

A pie chart is created using the VALUE column.

Explanation
Each slice represents a category
autopct shows percentage values
Labels indicate category names

⸻

5. Donut Chart

A donut chart is created by adding a white circle in the center of a pie chart.

Explanation
The circle removes the center part of the pie chart
This improves visual appearance and readability

⸻

6. Box Plot

A boxplot is created using Seaborn.

Explanation
Displays spread of data
Shows minimum, maximum, median, and possible outliers

⸻

7. Heatmap

A heatmap is created using correlation values.

Explanation
Correlation shows relationship between variables
Values close to 1 indicate strong positive relation
Values close to negative 1 indicate strong negative relation
Colors represent strength of relationship

⸻

8. Bubble Plot using Matplotlib

A scatter plot is created where bubble size represents VALUE.

Explanation
X axis shows sales
Y axis shows profit
Size of bubble represents value column

⸻

9. Bubble Plot using Seaborn

Seaborn scatterplot is used to enhance visualization.

Explanation
Size and color both represent VALUE
Palette improves visual clarity
Helps compare three variables at once

⸻

Conclusion

In this experiment, various statistical and specialized visualization techniques were implemented successfully. Different types of plots such as area plot, pie chart, donut chart, boxplot, heatmap, and bubble plot were created using Matplotlib and Seaborn.

These visualizations helped in understanding relationships between data variables such as sales, profit, and value. The experiment demonstrated how graphical representation makes data analysis more intuitive and effective.

Overall, this experiment improved understanding of data visualization techniques and their practical applications in data analysis.
