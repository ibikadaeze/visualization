# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

    Python Viz
    > What software did you use to create your data visualization?
    I coded it up using python. The jupyter-notebook with the code is attached.

    > Who is your intended audience? 
    Toronto Government

    > What information or message are you trying to convey with your visualization? 
    Present the distribution of infant room available spaces: The number of available spaces in the infant room of Toronto Child care center are too small for the emerging population. Over 700 daycare centers do not have infant room. This indirectly affects new born parents as some have to resign from work to take care of their little ones since there is no space for them to send the child to the child care centers.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    Type of visualization: I decided on bar plot as the best way to showcase each unique count of IGSPACE. I used ggplot and kind='bar' for this for neater result.
    Color: I used a primary color for accessibility reasons using color='red'
    Labels: I added figure title and axes labels to facilitate understanding of the plot for the reader using ax.set_title(), ax.set_xaxis(), ax.set_yaxis().
    Fig size: I used large figure size for ease of readability using fig, ax = plt.subplots(figsize=(10, 6))
    Text and axis tick fonts: the default was good enough due to the figure size, but ensured that the font sizes are readable for both texts and numbers.
    Annotation to the bars: For accessibility reasons, I added the number count to each bar to reduce cognitive load using ax.bar_label(ax.containers[0], label_type='edge')

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I used jupyter-notebook to code the plot in python. This ensures that the plot can be reproduced at anytime by anybody.
    
    > How did you ensure that your data visualization is accessible?  
    I used bigger fonts, added labels and annotations, used a distinctive color, and a simple to understand plot method (bar plot) to ensure that my data visualization is accessible.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Families with infant children hoping to move to Toronto.
    Government agency incharge of child care centers.
    Employers, hopefully they could allow for remote working while parents are on queue.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I was intrigued by the infant space statistics and thought that it could be a compelling message to present.

    > What ‘underwater labour’ contributed to your final data visualization product?
    I actually did not do anything here.

    Excel Viz
    > What software did you use to create your data visualization? I used Microsoft Excel to generate my visualization.

    > Who is your intended audience? 
    Toronto Government
    Parents
    NGOs who cares

    > What information or message are you trying to convey with your visualization? 
    The pie chart shows a distribution of the total number of spaces available in child care centers in Toronto. Pre-schoolers have the highest space while infant rooms have the lowest available spaces.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Type of visualization: I decided on pie chart as the best way to showcase the sum of each category of classes in teh child care centers. 

    Color: I used distinctive colors for accessibility reasons
    Labels: I added figure title and labels to facilitate understanding of the chart for the reader using the chart format options in excel.
    Text and number fonts: the default was good enough due to the figure size, but ensured that the font sizes are readable for both texts and numbers.
    Annotation to the charts: For accessibility reasons, I added the number count and percentage for each category. I also set it to be outside the chart for easy reability using the chart options in excel.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Excel is a point-click tool. Therefore, the data viz produced with it is not reproducible.
    
    > How did you ensure that your data visualization is accessible?  I added value count and percentage of each category to reduce cognitive load and made sure the labels are outside outside of the pie chart to avoid the colors affecting readability. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Parents
    Toronto Government
    Educators

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    When I saw the 5 different categories which all make up the child care center, I thought that it would be interesting to see the distribution across each category in Toronto child care centers.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    I calculated the total number of spaces for each category first using excel sum() function, and then used that information to make the pie chart using the pie chart function.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09/05/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
