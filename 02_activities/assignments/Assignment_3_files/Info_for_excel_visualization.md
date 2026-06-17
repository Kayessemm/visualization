Data source: https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/

> What software did you use to create your data visualization?
I used excel to create a bar chart that compared two data-series. I tried to use google sheets (because it doesn't require a subscription) but the huge spreadsheet (nearly 600,000 observations) made it crash often.

> Who is your intended audience? 
This visualization would be most useful for the agency managing public bikeshares in Toronto.

> What information or message are you trying to convey with your visualization? 
My bar chart compares how many trips bikeshare members and casual riders took every month in quarters 3-4 of 2016. It demonstrates how members ride more consistently even in the cooler months (like November and December) whereas casual riders overwhelmingly ride during the summer, probably for leisure. 

> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
As with my boxplot, I wanted to minimize cognitive load, so I only used two shades of grey for the bars, while everything else was in black on a white background, to increase contrast. 

Unfortunately, excel insists on adding far too many labels for gridlines. To decrease cognitive load further, I'd remove about half of these labels in graphic design software so that viewers can focus on how the bars compare, not a wall of text on the left of the chart.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
My visualization is difficult to reproduce perfectly because it was made on excel. Regardless, the bars represent a small table that contain counts (using the COUNTIFS() function) for all pairings of month and member/casual, and it would be easy to make a similar bar-chart based on this table. Furthermore, it is possible to make a "chart template" on excel that could be shared between users. Regardless, this is still not as easily reproducible as the lines of code I used in Python for the boxplot.

> How did you ensure that your data visualization is accessible?  
I used fonts without serifs (to assure accessibility for readers with dyslexia) and I only used distinct shades of grey to differentiate between data series, so my visualization is perfectly legible for people with colour-blindness.

> Who are the individuals and communities who might be impacted by your visualization?  
This visualization would impact riders of Toronto's bikeshare network. It shows differences in riding habits between members and casual riders depending on the time of year, so it may impact decisions on where to allocate bikes (e.g., more bikes in commuter heavy areas during the fall), or perhaps encourage the introduction of promotions to encourage more casual users during the fall. 

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
The original dataset only had dates and times for when bikes were borrowed/returned. But this information was far too detailed to visualize coherently. Also, the date notation differed between quarters (m-d-y in Q3; d-m-y in Q4). So I had to manually enter a column where I specified nothing but the month (using data filters). This allowed for the visualization of distinct changes over time, organized by month. Based on my boxplot, I also new that there were substantial differences between the habits of member and casual riders, so the bar chart further demonstrates how these changed over time.

> What ‘underwater labour’ contributed to your final data visualization product?

As with my boxplot, underwater labour occurred to supply the dataset and create the software I used to create the visualization. Employees of the city of Toronto (or organizations subcontracted by the city) designed the data intake system and uploaded the dataset to the city's website. As for the visualization software, this was designed by Microsoft employees, but it was also debugged based on the input of thousands (possibly millions) of users over the years.