# Assessment Style Guide

## Have a structural plan for your project repo.

- Having a plan for your project means more than having multiple notebooks. Notebooks should be separated for a reason.
    - A great reason for starting a new notebook is that you have completed the task at hand and are moving on to another, possibly related, task.
    - For example, data collection (i.e. web scraping or querying an API) and storage (saving data to a `.json` or `.csv` file, inserting into a database etc.) could be done in one notebook which is followed by another for data processing and some initial data analysis.
    - It's a good idea to have seperate folders in your repo for things like data files, notebooks, images, reports, etc

## README.md
- Think of your README.md as your landing page for your project. Before a viewer dives into your files, what do you want them to know about your project? Here are some recommendations for your project README.mds:
-   Give a brief overview of what is in each folder in your repo, so a viewer knows how to navigate around.
-   Give a summary of what your project is all about:
    - **Problem Statement:** What question(s) did you aim to answer through your analysis?   
    - **Data:** What data did you use? How did you acquire it?
        - Consider adding a data dictionary that explains what is in each column of your dataset
    - **Data Processing:** What steps did you take to clean and transform your data before more formal analysis
    - **Results/Findings:** What did you find throughout your analysis? This is a great place to add some of your visualizations
    - **Conclusions/Recommendations:** Are there any conclusions or recommendations that can be made based on your analysis?
    - **Next Steps:** If you feel like there is more that could be done with your data to investigate your initial questions, what would you do? Are there other datasets you could add? Other cleaning or tranformation steps?         


## Notebook Comments:
   - It's a good idea to add comments throughout your code notebooks (using markdown cells) so the viewer can easily follow your thought process throughout your analysis. Assume that the reader doesn't know what your doing or why. It's good to address things like:
       - You chose to drop columns or rows - why?
       - You chose to clean or transform your data in a particular way - why?
       - How would you interpret your data visualizations (this part is super important!)
        
## Edit your work.
- It's natural to want to show every bit of hard work you've poured into your project, but at the end of the day, all we need is your final product. If there are notebooks or lines of code that you end up not using, don't keep them in your final repo submission.

