# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 


[Dataset chosen]
https://open.toronto.ca/dataset/library-branch-programs-and-events-feed/

[Excel Visualization]

What software did you use to create your data visualization?
Microsoft Excel.

Who is your intended audience?
Toronto Public Library (TPL) decision-makers, for example: branch administrators, program coordinators, and policymakers. This visualization is intended to help them understand which branches have most events planned for the near future (May to September 2025). 

What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
Since Excel has more limited visualization capabilities, I tried to make the bars in the barplot look like book spines to match the theme. I also only focused on the top 10 branches to avoid cognitive overload. But eventually when speaking to TPL stakeholders we could adjust visualization to their needs, for example Top 10 in one region or specialized in a age group audience.

How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
Using standard Excel package and straigthforward calculation of events per branch.

How did you ensure that your data visualization is accessible?
I took into consideration the choice of high-contrast colors, labels were placed horizontally, sufficiently large font sizes (minimum 14 point) and ample space between components to ensure good readability. A supporting data table provides numerical values as an alternative data format. Title and subtitles used plain language.

Who are the individuals and communities who might be impacted by your visualization?
Other than TPl stakeholders who need to make informed decisions, hopefully local communities can identify branches with most events offered and potentially journalists to use as a data source.

How did you choose which features of your chosen dataset to include or exclude from your visualization?
I deliberately limited the visualization to the top 10 branches for clarity, avoiding cognitive overload. I also excluded more granular details like event types, target demographics to maintain simplicity.

What ‘underwater labour’ contributed to your final data visualization product?

[Python Visualization]
    > What software did you use to create your data visualization?
    Python in Jypyter Notebooks.

    > Who is your intended audience? 
    Toronto Public Library decision-makers, for example: branch administrators, program coordinators, and policymakers. This visualization is intended to help identify how the top 10 library branches specialize in specific event types. This should help them understand where there is overlap or gaps in event types and make informed decisions about resource allocation. For example, both Toronto Reference Library and Bloor/Gladstone show strong specialization in "Book Clubs & Writers Groups", is the overlap useful to the communities served? Additionally, there seems to be a gap in "Storytelling" events since only Albert Campbell specializes in it.

    > What information or message are you trying to convey with your visualization? 
    This second visualization is meant as a companion to the previous one made on Excel, to complement. It shows where there is overlap or gap in event type offerings. Note the visualization also focuses only on the same top 10 branches with most events, but eventually it would also be possible to use the same type of analysis and visualization to group branches per audience type or geographical location.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    My main concern here was with cognitive overload: how to communicate the information without being overwhelming. Some of the initial attempts had too many colours, or were using colours that were not accessible. I also tried barplots first but it was way too much to look at.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Adhering to FAIR principles, I used open-source Python libraries, meaning the code is reproducible using the same libraries.
    
    > How did you ensure that your data visualization is accessible? 
    I intentionally played around with colour schemes to avoid conveying information using colour only. Since the heatmap also had enough space to add the numerical values, it would not be a total blocker for colourblind people, but still I wanted to make sure. I also tried adding textures but that was way too much cognitive overload, so I removed in the end. Also I was careful with descriptive titles and labels to make sure the content was easy to understand.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    My hope would be community members using the TPL system would benefit from more diverse event types offered. But also the administrators at TPL and branch managers can also make more informed decisions about events they want to organize or discontinue.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    I focused only on the same top 10 libraries from the Excel Visualizationand top 10 event types to prevent cognitive overload. The proposed Specialization Index helped by normalizing the dataset for branch size differences, allowing for clearer comparison. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

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
