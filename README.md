# Python-Day-48-Data-visualization-with-matplotlib-and-seaborn
This project explains about the Data visualization with matplotlib and seaborn using python
#Example: Bar plot using matplotlib:
import matplotlib.pyplot as plt 
# Data 
categories = ['A', 'B', 'C', 'D’] 
values = [10, 20, 15, 30] 
# Create a bar plot 
plt.bar(categories, values) 

# Add title and labels
 plt.title("Simple Bar Plot") 
plt.xlabel("Categories") 
plt.ylabel("Values") 

# Show the plot 
plt.show()
#Example: scatter plot using seaborn:
import seaborn as sns 
import matplotlib.pyplot as plt

# Example dataset 
tips = sns.load_dataset("tips")

# Box plot to show the distribution of tips by day 
sns.boxplot(x="day", y="tip", data=tips)

# Show the plot 
plt.show()
