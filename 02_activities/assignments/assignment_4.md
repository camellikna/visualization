# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    > 
    > Python and Power BI

    > Who is your intended audience?
    >
    > The intended audience includes policymakers, educational planners, school boards, and stakeholders interested in the state of public education in Ontario. Secondary audiences might include parents, researchers, and community advocates who wish to understand patterns in school locations, types, and accessibility.
    
    > What information or message are you trying to convey with your visualization?
    > 
    > The visualizations aim to provide insights into:
    >The distribution of schools by region and city.
    >Trends in school openings over time.
    >Differences in school types, grade ranges, and languages of instruction.
    >Geographic accessibility of schools across Ontario.
    >The goal is to inform decision-making and promote equitable access to education.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    > 
    > Substantive Principles: Focused on delivering accurate, meaningful data insights. Each visualization directly addresses a key question (e.g., regional distribution or grade ranges).
    > Perceptual Principles: Used clear labels, intuitive color schemes (e.g., blue for geographic data, green for growth), and avoided clutter. Bar charts and line plots were chosen for clarity and simplicity.
    > Aesthetic Principles: Balanced simplicity with visual appeal by applying consistent formatting, professional fonts, and proportional spacing. The pie chart used harmonious colors to distinguish categories.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    > 
    > Reproducibility: Python code was used with libraries such as pandas and matplotlib. The code and dataset URL were provided, ensuring anyone with Python installed can recreate the visualizations.
    > Non-reproducible Tools: Tools like Tableau might not allow full reproducibility unless the project file and dataset are shared. In such cases, Python or open-source tools would be prioritized to ensure transparency and repeatability.
    
    > How did you ensure that your data visualization is accessible?
    > 
    > Accessible Design:
    > Used high-contrast colors for readability.
    > Added clear labels, titles, and legends.
    > Ensured visualizations were compatible with screen readers by including descriptive titles and alternative text when embedding in reports or websites.
    > Alternative Formats: Provided raw data and insights in tabular form for individuals who may not benefit from visual data.
    
    > Who are the individuals and communities who might be impacted by your visualization?
    > 
    > Directly Impacted:
    > School administrators and planners who may use the data to improve resource allocation.
    > Parents and students, especially in underserved or rural areas, who might benefit from insights into school accessibility.
    > Indirectly Impacted:
    > Policymakers shaping education strategies.
    > Researchers analyzing trends in public education infrastructure.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    > Inclusion: Selected features that aligned with the key questions, such as school region, board type, grade range, and opening date, to ensure relevant insights.
    > Exclusion: Columns like fax numbers and postal codes were excluded from visualizations as they provided minimal value for high-level analysis but remain available in the dataset for specific needs.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    > 
    > Data Cleaning: Ensured missing values were handled appropriately (e.g., converting Date Open into a usable format).
    > Exploratory Analysis: Conducted preliminary data exploration to understand patterns and outliers.
    > Tool Selection: Evaluated the best visualization tools (Python and Tableau) based on reproducibility, user familiarity, and project needs.
    > Iteration: Refined visualizations through feedback to ensure clarity and relevance.
    > Documentation: Provided reproducible code and detailed descriptions for transparency.

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
