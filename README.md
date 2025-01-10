# Project Retail_Sales

**Project Retail_Sales** Project Retail_Sales is a beginner-friendly data analysis project designed to explore and visualize retail sales data. This project identifies trends and insights using Python and simple data visualization techniques.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* This project uses three datasets:

1. Stores.csv

Details about each store, including store type and size.

2. Features.csv

Information such as markdown promotions, holiday flags, and fuel prices.

3. Sales.csv

Weekly sales data for various stores and departments.


## Business Requirements
*The objective of this project is to analyze retail sales data and provide actionable insights by identifying patterns such as:

* Weekly sales trends.
* The impact of holidays and promotions on sales.
* How store type and size influence sales.


## Hypothesis and how to validate?

* Hypotheses:

* Sales peak during holiday weeks.
* Store Type A generates the highest total sales.
* Larger stores tend to have higher weekly sales.

Validation Methods:

* Analyse weekly sales data during holiday and non-holiday periods.
* Compare total sales by store type (A, B, C).
* Correlate store size with total weekly sales.

Key Findings:

* Sales peaked during holiday weeks.
* Store Type A had the highest total sales.
* Larger stores consistently showed higher sales.

## Project Plan
The method to plan the project was a Kanban board, a link link to it can be found her https://github.com/users/juliancolling/projects/2/views/1

## The rationale to map the business requirements to the Data Visualisations

Holiday Impact:

 *Use bar charts to compare weekly sales during holidays and non-holidays.

Store Type Performance:

* Grouped bar charts to compare total sales by store type.

Store Size Correlation:

* Line plots to show sales trends by store size.

## Analysis techniques used

ETL (Extract, Transform, Load):

Extract: Read data from CSV files.

Transform: Handle missing values, create new columns (e.g., holiday sales), and clean the data.

Load: Organize the data into Pandas DataFrames for analysis.

Visualisation:

Bar charts to compare sales across categories.
Line plots for trend analysis.

Heatmaps to visualise sales distribution by store.

## Ethical considerations

Privacy: The dataset used is publicly available and does not contain personal information.

## Unfixed Bugs
* The one issue i had with this project was plotly express chart issue and it kept crashing the laptop, the only quick fix for this was to stop the hover function and set it "None" this solved the problem and and chart was able to be viewed 
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 



## Acknowledgements (optional)
* Thank the people who provided support through this project.
