# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    I used Python Matplot package. I really like the simplicity of the plots. 

    > Who is your intended audience? 

    The intended audience is the planners and decisionmakers in City of Toronto. 
    
    > What information or message are you trying to convey with your visualization? 

    The future looks catastrophic for Toronto. The current desicion makers hold our future in their hands. I want to highlight the dramatic rise in mean temperature. I also wanted to evaluate the uncertainty of the future. This is why I plot box plots and show the model spread. Especially through the end-of-century the model agremment weakens. I want to persuade the planners acting urgently for mid-century! We should avoid ambitious targets or unrealistic actions. We should assess these models not pessimisticly but rather search for the best feasible adaptation options.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    I compared medium emission (ssp2-45) and high emission (ssp5-85) scenario. These global scenaios define how humanity choose about mitigation of emissions. And even in medium emission scenario the future looks different than today. I want to persudae the audience by rational appeal.

    The time series evaluation of climate change highlights how dramatic the future could be! 

    I added the datasource as alt text below. These information is generally missing in presentation and it is essential to know the source of the dataset. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    I used pyhton to increase the reproducibility of the code. But because my data selection relies on the columns and the rows of the data table, if future work would use the same data storiang apporach my code works efficiently .But if they change the storgae scheme, one can need some data transformation. 
    
    > How did you ensure that your data visualization is accessible?  

    I checked the colorblind colors goes well together. 
    I avoid sophisticated visulaizations and keep everything simple. 
    Texts are legitimative. 
    Basically the emission scenarios are similar in theory so similar visulaziton works well but I differentiated the color to highlight the variance
    
    > Who are the individuals and communities who might be impacted by your visualization? 

    I targeted the technical stuff that plane the city now!! The mid century is ahead and we have limited time. I want to show this!
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    The dataset inludes a bunch of climate variables. I visulaize only annual mean temperature which is a simple climate indicator that everyone can relate. Because code is reproducible any variable on the dataset can be visualize by only chnaging selection.  
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data cleaning and selection: Filtering the dataset to keep only relevant columns such as Climate Scenario, Time Horizon, and Annual Mean Temperature.

    Formatting values: Ensuring temperature values were numeric and removing rows with missing or non-numeric data.

    Structuring the data: Grouping the data by scenario and time horizon so that it could be plotted correctly in box plots.

    Choosing visualization type: Testing line and box plots to decide which best represented both median and percentile information clearly.

    Annotation and clarity: Adding labels, axis titles, and descriptive alt text to make the visualization understandable without extra explanation.

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
* Submission Due Date: `23:59 - 11/02/2025`
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
