import matplotlib.pyplot as plt
import seaborn as sns
sns.set_style('darkgrid')   
x = [2014, 2015, 2016, 2017, 2018, 2019]
y = [1800, 17000, 600, 14560, 8550, 11420]
colors = ['orange', 'blue', 'green', 'red', 'purple', 'brown']
plt.barh(x, y, color=colors)
plt.title(' horizntal Barplot')        
plt.xlabel('year')
plt.ylabel('gross amount')
plt.show()
