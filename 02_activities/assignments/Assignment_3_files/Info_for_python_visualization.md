Data source: https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/

> What software did you use to create your data visualization?
I used python with matplotlib and seaborn packages, ran in a Jupyter notebook.

> Who is your intended audience? 
This visualization would be most useful for the agency managing public bikeshares in Toronto.

> What information or message are you trying to convey with your visualization? 
My boxplot shows differences in trip duration between casual users of Toronto bikshares and subscription-based members. Although most casual riders (median = 1125 seconds) take longer trips than members (median = 590 seconds), the overlap of either distributions' quartiles 1 and 3 indicate that this difference is not highly significant. Regardless, the casual riders likely longer rides because more of them are probably visitors travelling to different locations, wehereas members probably commute more regularly to nearby locations. In fact, the mean (marked with a "+") being much higher than the median illustrates how irregular the trip durations are for casual riders. 

> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
I aimed to minimize cognitive load, so only one colour was used for the boxes, while everything else was in black or grey on a white background, to increase contrast. Boxplots were also selected for the purpose of evaluating differences in the spread of either variable.
Because the dataset consists of nearly 600,000 observations, I removed markers for outliers ("fliers") that massively cluttered the figure and added virtually no useful information. In stead, the higher mean for the casual riders illustrates how that variable had far more high-value outliers. Again, this diminished cognitive load.  

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
My visualization is reproducible because it is written in python code and only uses open-source packages (Matplotlib; Seaborn) and a public dataset.

> How did you ensure that your data visualization is accessible?  
I used fonts without serifs (to assure accessibility for readers with dyslexia) and colour differences do not communicate information, so my visualization is perfectly legible for people with colour-blindness.

> Who are the individuals and communities who might be impacted by your visualization?  
This visualization would impact riders of Toronto's bikeshare network. Because it illustrates how casual riding habits differ from those of more regular riders wih memberships, fares and station placement may be adjusted according to these demands.

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I decided to exclude outliers because there were too many of them for such a large dataset. If viewers need to know the minimum and maximum durations, then they can refer to the "Statistics" table I created in cell 19. Likewise for the specific mean and median values. It was not necessary to include these values in the visualization itself because the point of the figure is to show that many more long-duration rides occur among casual users of the bikeshare system--the difference between the median bar and the mean "+" communicates this message without complexity. 

> What ‘underwater labour’ contributed to your final data visualization product?

Underwater labour occurred to supply the dataset and create the software I used to create the visualization. Specifically, the software engineers who designed the system for tracking bike use made this dataset possible, as did the municipal employee(s) that uploaded the dataset to the City of Toronto's website. As for the visualization software, because matplotlib and seaborn are open-source, much of this software was programmed and debugged by volunteers. Similarly, when I had issues in trying to program my visualization, I checked multiple fora (namely stack overflow) where programers asked questions and described issues they had, receiving advice from other coders--most of whom were volunteers.