# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    ''' 
    I have used Python and Tableau Public
    Here are the links for the visualizations created in Tableau Public:
    [Top10 Neighbourhoods with High Volume of Crimes in Total](https://public.tableau.com/app/profile/inna.semenykhina/viz/Top10NeighbourhoodswithHighVolumeofCrimesinTotal/Sheet1?publish=yes)
    [Top10 Neighbourhoods with High Volume of Crimes in Total (rate per 100,000 population)](https://public.tableau.com/app/profile/inna.semenykhina/viz/Top10NeighbourhoodswithHighVolumeofCrimesinTotalrateper100000population/Sheet1?publish=yes)
    [Crime Volume Trend Over the Time in Top 3 Neighbourhoods](https://public.tableau.com/app/profile/inna.semenykhina/viz/CrimeVolumeTrendOvertheTimeinTop3Neighbourhoods/Sheet2?publish=yes)
    [Crime Volume Trend Over the Time in Top 3 Neighbourhoods (rate per 100,000 population)](https://public.tableau.com/app/profile/inna.semenykhina/viz/CrimeVolumeTrendOvertheTimeinTop3Neighbourhoodsrateper100000population/Sheet3?publish=yes) 
    '''
    > Who is your intended audience? 
    '''
    My intended audience is a leadership of the Police of Toronto, who has right to change budget for different police departments in terms to reduce amount of crimes.
    '''
    > What information or message are you trying to convey with your visualization? 
    '''
    I have a few messages to vocalize:
    1. The geography of the high rate of crimes in total for the last 11 years with detailing top 10 areas.
    2. The trend of different reported type of crimes over 11 years for top 3 areas with high volume of crimes.
    Each data is shown in raw numbers (counts) and as rate of each type of crime per 100,000 population pear each year.
    '''
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    '''
    I can considered the following aspects:
    1. Aesthetic - to make my visualization nice to look at. It has clean and nice style, white grid for the background, different colours which are great for differentiation for either colour-blind and non-colourblind people. I have also rotated x-axis labels for readability and increased font sizes in the figure title for better readability.
    2. Substantiveness - to make sure my visualization presents the accurate data. The visualization has different scale to present clear visual of data in each cases. 
    3. Perception - to make sure the visualizations’ message is clear for understanding. Each visualization has titles, subtitles, labels for x and y axis and legend. 
    '''
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    '''
    1. I created all visualizations using fully code-driven libraries from seaborn and matplotlib in Python. That means each chart can be regenerated the same way from the script without any manual edits.
    2. I also used Pandas library from Python to process and reshape the dataset. Which means all filtering, grouping, and formatting steps were processed in code avoiding any manual work and can be reproduced by anyone else using this code. 
    3. I have also commented all essential steps for the future reproducibility both by someone else and me
    '''
    > How did you ensure that your data visualization is accessible?  
    '''
    1. I made sure to make the layout clear and intuitive, with straightforward labels, titles and detentions.
    2. I have used different colours for each graphic after reassuring that these colours are recognizable by colour-blind people as well.
    3. I have used readable font and its style.
    4. I also added legends for clarity.
    '''
    > Who are the individuals and communities who might be impacted by your visualization?  
    '''
    The police workers and people, who live in GTA could be impacted by my visualization.
    '''
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    '''
    I have tested a few types of visualizations to ensure that all data is represented clearly. Thus, I decided to show lollipop style of visualization for representing data for top 10 neighbourhoods with highest crime volume to show the comparison between each neighbourhoods. I have also decided to use lines plot with detailization for each type of crime over 11 years for the top 3 neighbourhoods with the highest volume of the crimes. So it would be easier to compare trend for each type of crime for these neighbourhoods and decide what measures are required for each neighbourhood and how the situation was improved over the years.
    '''
    > What ‘underwater labour’ contributed to your final data visualization product?
    '''
    1. Sampling the data by data scientists, who published these dataset in the Internet.
    2. Data cleaning and reshaping: I have melted some values in order to split the year and type of crime for better filtering and visualization.
    3. Filtering and aggregation: data was grouped by areas and years and sorted by max value in the visualizations.
    4. Ensuring accessibility while checking the colouring and styles for the layout.
    '''
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
* Submission Due Date: `23:59 - 13/07/2025`
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
