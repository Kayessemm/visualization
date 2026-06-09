# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    Good visualization: https://public.tableau.com/app/profile/energy.markets/viz/Ventescumulativesdevhiculeslectriques/Dashboard1 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      This map of vehicle sales in Canada is a good visualization because it intuitively displays how many gas, hybrid, and electric cars were sold in each province and territory. The title clearly explains what is represented. The total quantity of all vehicles sold is represented both by the size of each pie-chart and the shading of each province/territory. The scale of these size and colour-based attributes is clearly shown in the legend. The pie-charts themselves are also very clear, consisting of no more than three colours that are easy to distinguish from each other, even for viewers with colour-blindness. Furthermore, pie-charts work very well on maps because they take up little space and can be resized to show magnitude/quantity, as in this map. Like most visualizations on Tableau public, specific information is also offered by hovering over most features, and variables can be toggled on/off. 

      The cognitive load (sensu Sibinga and Waldron 2021) of this visualization is quite low, despite the complexity of the information presented. Location, relative share of vehicle sales, and proportions of vehicle types sold in each province are all visible at a glance, and easy to inspect for more details.   

      ```
    - How could this data visualization have been improved?  
      ```
      Given this is a very good visualization, there are few obvious points of improvement. Still, the visualization could be better if it were less redundant in showing the quantity of vehicles sold in each province/territory: both pie-chart size and province/territory colour show total vehicle sale quantity. Perhaps this map would be more informative if the colour gradient were normalized by the population size of each province/territory. That way the colour would represent vehicle sales per capita, while the pie-charts would still represent raw counts.   
      
      Other issues are just minor problems that were probably overlooked by accident. The acronyms of the vehicle types are not clear and should be spelled out: I imagine green represents hybrids, blue electric, and grey gas, but guessing should not be necessary. Finally, the callouts when hovering over the bar-charts seem to be incorrect: they say the total number of vehicles displayed, referring to all of them as "véhicules électriques", regardless of which portion of the chart one selects, and regardless of whether gas vehicles are included.
      
      ```

    Bad visualization: https://public.tableau.com/app/profile/vivien.lee88/viz/Formula1ConstructorsRadialBumpChart/Dashboard1 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      This radial bump chart of Formula 1 team scores/rankings between 2006 and 2025 is not a good visualization because it is overwhelming, it lacks clarity on the units represented, and its colour-scheme is partly inaccessible. Because there are 14 "constructors"/teams, each with their own line that overlaps the others, the chart looks like a tangled mess (i.e., high cognitive load). The cognitive load (sensu Sibinga and Waldron 2021) is also increased by the rarity of the format: bump charts are far less common (and therefore harder to interpret) than line graphs. The units represented in this graph are also unclear on first glance: while the caption says that the lines represent total championship points by year, and points and year are given if one hovers over the line, key info like minimum and maximum points are not obviously indicated. Finally, the design is not very accessible because many colours are close to each other (particularly those in shades of red), and green and red are both used despite being easy to confuse for colour-blind people. Of course, these issues are not as bad in an online, interactive format that tells viewers specific info by hovering, but the initial impression is still overwhelming.     

      ```
    - How could this data visualization have been improved?  
      ```
      Aside from novelty and perhaps some parallel with the subject matter (the visualization resembles a wheel), it is not clear why a radial bump chart was chosen as the format. A simple line chart would communicate this information with just as much clarity and less cognitive load. Even with a line chart, though, each line would appear chaotically tangled with the others. Choosing an accessible colour-scheme would also be difficult with so many data series. So the interactive format that allows viewers to inspect the values of each observation may be necessary. Another interesting format that may better emphasize how well teams did on the long-run would be a cumulative frequency graph. The lines for teams that consistently get more points will get higher than those of teams that perform less well. Not only would this illustrate the best teams overall, but lines would also be less likely to overlap each other as the years progress, minimizing cognitive load. 

      However, if the radial bump chart really is necessary, it can be improved with a couple small fixes. some indiation of scale (e.g., 0, 400, 800 points) would be helpful on the right side of the chart that is empty anyway. The visualization could also be retitled "Yearly score for Formula 1 constructors (2006-2025)" to imediately clarify what units are represented, rather than require viewers to read the caption or hover over specific lines. Finally, the colour-scheme could be made more accessible by removing red or green and defining a colour-scheme with clearer distinctions between teams/constructors. However, this may be difficult, given the number of constructors, and perfectly distinguishable colours are less necessary for an interactive visualization such as this.

      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

References cited: 

Sibinga, E., & Waldron, E. (2021, September 30). Cognitive Load as a Guide: 12 Spectrums to Improve Your Data Visualizations. Nightingale. https://nightingaledvs.com/cognitive-load-as-a-guide-12-spectrums-to-improve-your-data-visualizations/

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [x] Create a branch called `assignment-2`.
- [x] Ensure that the repository is public.
- [x] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [x] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
