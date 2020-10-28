# Bay Wheels Data Exploration Project

## Talal Al-Dawudi

### The Dataset

- This project aims to analyze data from Bay Wheels (previously Ford GoBike), San Francisco's premier bike sharing service, in hopes of uncovering useful insights about the company's operations.


- The dataset used for this project was obtained from the [Bay Wheels site](https://www.lyft.com/bikes/bay-wheels/system-data). The project focused specifically on rides that occurred between January 1st to December 31st in 2019.


![Bay%20Wheels.jpg](attachment:Bay%20Wheels.jpg)
_Image from https://www.sfmta.com/blog/bike-share-update-bringing-back-reliable-service_

### Findings 

The data provided by Bay Wheels offers no opportunity to analyze customer demographics. For this reason, the project revolved around the analysis of monthly, weekly and hourly usage of the bike sharing service to gain a better understanding of rental behavioral patterns. This analysis revealed the following findings:

- Subscribers are most likely to use the service for daily commuting needs (to and from work during rush-hour).

- Subscribers are less likely to use the service for leisure, as shown by the dramatic decline in subscriber usage on weekends, and during holidays.

- Customer (casual users of the service) demand is also strongest during work-day rush-hours, indicating that a large proportion of customers use the service for work-related commuting.

- Customers differ from subscribers in that their demand is consistent during the week, and does not drop off as significantly outside of rush-hours (7AM-9AM and 4PM-6PM).

- January, February and May are some of the slowest periods for both customers and subscribers, which suggests that these months could particularly benefit from promotions, advertising and incentives.

- Subscribers ride, on average, for half the amount of time that customers ride the bikes for. While the service definitely benefits from high and fast turnover (as this makes bikes more frequently available for new riders), it could implement a strategy to promote bike usage for purposes other than short distance commuting, including exercise. This could be done through integrations with health software to track statistics including trip duration, elevation and calorie burn, which might attract a new kind of subscriber to the service.

Overall, Bay Wheels provides an excellent green alternative to commuting by car, subway or bus. It is extremely accessible and provides a great framework for other cities to follow in the pursuit of of low carbon emmissions and transport relief.

The visualizations I have chosen to present in the slide deck are the ones that give a well-rounded idea of rider-behavior and usage. The rental behavior on a weekly, hourly and monthly basis for both customers and subscribers will be the main focus, so the graphs that provide us with the most meaningful insights about this data are the ones that are outlined.

### Feedback

The feedback I obtained from friends and family were extremely useful, and helped influence the final visualizations shown in my explanatory analysis. The main takeaways were as follows:

- Univariate Exploration: bar plots and pie charts I chose were familiar to my friends and family, and were easily processed. Everybody found the graphs simple and insightful, with no complaints about the general look or color scheme.

- Bivariate Exploration: I was told that my graphs would be more impactful if plotted side-by-side, in order to highlight the difference in ride duration between customers and subscribers. I made the changes accordingly.

- Multivariate Exploration: I was told that my heatmaps would look better with warmer colors that intensified in hue as traffic increased, so I made the change from seaborn's 'coolwarm' to 'YlOrBr'. I also plotted the heatmaps side-by-side at the request of my friends, and decided to exclude any additional data that would make the graphs seem "junky". 

### Project Files

- **readme.md**: Covers the general findings of my exploration, the dataset used, and any resources that I used to better my analysis and slide deck.


- **exploratory_data_analysis.ipynb**: the workbook that documents the entire process of obtaining the data and undergoing my exploratory analysis. This file also highlights many insights that I chose not to include in the slide deck.


- **baywheels_slide_deck**: the slide deck that includes the most meaningful visualizations and insights, as well as a brief explanation of the project and a summary of my findings.

### References

- [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers)

- [Seaborn Color Palettes](https://seaborn.pydata.org/tutorial/color_palettes.html)

- [Seaborn Heat Map Documentation](https://likegeeks.com/seaborn-heatmap-tutorial/)

- [Pandas List Sorting Assistance](https://stackoverflow.com/questions/23482668/sorting-by-a-custom-list-in-pandas)

- [Bar Plot Sorting Assistance](https://stackoverflow.com/questions/22635110/sorting-the-order-of-bars-in-pandas-matplotlib-bar-plots)

- [Matplotlib Pie Chart](https://matplotlib.org/3.1.1/gallery/pie_and_polar_charts/pie_features.html)

- [Seaborn Violin Plot Document](https://seaborn.pydata.org/generated/seaborn.violinplot.html)

- [Embedding an Image](https://stackoverflow.com/questions/32370281/how-to-embed-image-or-picture-in-jupyter-notebook-either-from-a-local-machine-o#:~:text=You%20can%20insert%20the%20image,image%20separately%20in%20the%20folder.&text=From%20menu%20bar%2C%20Cell%20%3E%20Cell%20Type%20%3E%20Markdown.)

- [Bay Wheels Data](https://www.lyft.com/bikes/bay-wheels/system-data)

- [Hide Code in Slideshow](https://www.markroepke.me/posts/2019/06/05/tips-for-slideshows-in-jupyter.html)

- [Presentation Assistance](https://www.youtube.com/watch?v=utNl9f3gqYQ)


```python

```
