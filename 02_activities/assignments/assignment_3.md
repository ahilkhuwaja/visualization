# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    Used Excel and Python


    > Who is your intended audience? 
    
    My primary audience would be anyone who is interested in understanding the amount of tickets being sold for ferry rides in downtown Toronto. This would be individuals or organizations who are looking to invest into the ferry business in Toronto or who would be interested in investing in secondary businesses around the ferry industry. For example, an individual who wants to open a churros stand or a hot-dog stand would also benefit from analyzing the ticket data.


    > What information or message are you trying to convey with your visualization? 

    Showcase the sales per year in decending order over the 2015-2025 period (Excel)
    Showcase the sales vs redemption comparision per year (Python)
    

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    I took into account the following factors: 
    Which chart to use - to convey the message of the data --> applied them by creating bar charts
    Labels and color usage to ensure that the data was clearly understood and accessible to all the users --> added labels and color to both charts
    Scale - consistent and uniform scale to help understand the data and compare the two charts if needed --> used consisten scale for both charts


    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    Used a random seed in python to ensure reproducability. For Excel, reproducability is tougher to maintain because it is a click and play software. This lack of reproducability might prevent someone from creating the exact same graph but I kept the visualization very basic and converted the data into a pivot table and showcased all of it on the same sheet so that someone else can attempt to recreate the chart with minimum effort.


    > How did you ensure that your data visualization is accessible?  

    Cleaned up noise from the graph (removed extra grid lines and removed legend when not necessary in Excel).
    Used high contrast colors
    Used a clear title which helps the reader understand the data quickly
    Added in ALT text caption
    Used a lot of white space around the chart

    
    > Who are the individuals and communities who might be impacted by your visualization?  

    A variety of individuals and communities, including:
        individuals or organizations who are looking at investing into the ferry or indirect businesses
        governments (municipal and provincial) that support the ferry industry
        individuals who are looking to book a ferry and are interested in understanding how busy the ferry has been over the past years
        individuals who are looking to rent housing near the ferry and are looking to understand how busy the business will be (which might affect their enjoyment of housing) 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    Included the main columns of the dataset and the created column of year. Inclusion was based on the question: is this column required to help readers understand the data. If the answer was no, I didn't include the column. Additionally, I didn't want to overwhlem the user with too many datapoints, so also removed the column unless it was absolutely necessary to understand the data.

    > What ‘underwater labour’ contributed to your final data visualization product?

    Cleaning the dataset to remove any blank or non-value datapoints.
    For Excel: Building out a pivot-table to ensure a distributions can be created on an yearly basis
    For Excel: Removed extra noise of gridlines and other chart elements that don't add value
    For python: writing all the code and testing it to ensure it displays an appropriate graph


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
