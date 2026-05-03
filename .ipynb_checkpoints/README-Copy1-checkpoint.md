<h1>
  <span class="prefix"></span>
  <span class="headline">Project 2: Exploratory Data Analysis</span>
</h1>

## About
Our first unit in the course covers:
- Basic statistics
- Many Python programming concepts
- Programmatically interacting with files and directories
- Visualizations
- EDA
- Working with Jupyter notebooks for development and reporting

You might wonder if you're ready to start doing data science. While you still have **tons** to learn, there are many aspects of the data science process that you're ready to tackle. This project aims to allow you to practice and demonstrate these skills.

---

## Prerequisites
- Write and run Python code in a Jupyter notebook.
- Create basic Python functions.
- Python programming skills including using modules and libraries.
- Understand what Exploratory Data Analysis is and how to do it uing Python and `pandas`.


---

### Deliverables

All of your projects will comprise of a written technical report and a presentation. As we continue in the course, your technical report will grow in complexity, but for this project it will comprise:
- A Jupyter notebook that describes your data with visualizations & statistical analysis.
- A README markdown file the provides an introduction to and overview of your project.
- Your presentation slideshow rendered as a .pdf file.
**NOTE**: Your entire GitHub repository will be evaluated as your technical report. Make sure that your files and directories are named appropriately, that all necessary files are included, and that no unnecessary or incomplete files are included.

For your presentation, you'll be presenting to a **non-technical** audience. You should prepare a slideshow with appropriately scaled visuals to complement a compelling narrative. **Presentations should be about 5 minutes.**  Time tends to fly when presenting, and doing a dry run for a friend or family member is a great way to practice.

---

### Problem Statement

You will be asked to come up with a data analytics problem. For this project, your problem statement is up to you! Below are some guidelines/things to consider when crafting a problem statement:
> 1. Consider your audience. Who is your project going to help? Who will your presentation be geared towards? Establishing your audience first can help you narrow down your scope.
> 2. Consider the data you will use. Based on the contents of this data, think about some questions you could reasonably answer. These questions should aim to solve some kind of problem.
> 3. Based on these questions, what would bring some kind value to your audience? This can be business insights, increase sales, make decisions, etc.
> 4. Put everything from the above steps together into a few sentences that describe the specific problem you are trying to solve and who it will benefit.

Here are some example prompts if you need inspiration:
> * Climate change will disproportionately affect countries at lower sea levels. In anctipation of sea level rise, you have been hired by a non-profit to identify which countries are most at risk and to report back the top 5 countries where relief and aid should be directed*.
> * You work for a global shipping company. Your higher ups have asked you to identify which countries (and mores specifically which cities) are the best candidates for expansion of port facilities. Your company is interested in countries that are developing quickly, as these ones will soon demand more goods imported via your company's shipping fleet. 
> * *Feel free to be creative with your own prompt!*


---

### Data sets

download the `.zip` file for your topic from the datasets folder
| No. | Topic                      | Info                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-----|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1** | **World Development Statistics** | There are 3 data sets included in the [`data`](./data/) folder for this project. You are required to pick **at least two** of these to complete your analysis. Feel free to use more than two if you would like, or add other relevant datasets you find online.<br>We're going to take a look at World Development Statistics from [Gapminder](https://www.gapminder.org/about/), an independent Swedish foundation that aims to make data about the world more accessible and reliable. A good introduction on Gapminder is this [Ted Talk](https://www.ted.com/talks/hans_rosling_the_best_stats_you_ve_ever_seen) from Hans Rosling, which also shows how effective data visualization can be for your audience.<br>**Hint:** _The Gapminder website has way more datasets_ |
| **2** | **Olympics**               | This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.<br>Scraped from [sports-reference](http://www.sports-reference.com) in May 2018.<br>Note that the Winter and Summer Games were held in the same year up until 1992. After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on. A common mistake people make when analyzing this data is to assume that the Summer and Winter Games have always been staggered.                          |
| **3** | **Kickstarter**            | Kickstarter is a funding platform that helps creatives get their ideas, that otherwise may not be able to have a chance, on their feet. Kickstarter is driven by two main groups; creators and backers. Creators will come forward with a creative idea and backers fund the ideas. [For more info](https://www.hatchwise.com/resources/what-is-kickstarter-and-how-does-it-work)                                                                                                                                                                                                                       |
| **4** | **Bahrain Imports**        | This dataset, sourced from the Bahrain Open Data Portal, offers a detailed overview of the Kingdom's international trade activities from 2021 to 2024. It contains monthly transaction-level records of imports, providing valuable insights into trade patterns, commodity flows, and economic relationships. Each entry includes information such as partner country, commodity type, transaction value, weight (in kilograms), quantity, and unit of measure.<br>For further reference, [Bahrain Customs Affairs](https://www.customs.gov.bh/en) serves as the primary source of this information.       |
| **5** | **Wind Turbines**          | Main file (wind-turbines.csv): Data on wind turbines in the U.S. (location, which plant they are in, how much power they generate, etc.). It is from the [U.S. Wind Turbine Database](https://eerscmap.usgs.gov/uswtdb/), and includes information on 70,808 turbines covering 44 states (plus Guam and Puerto Rico). The data are used by government agencies, scientists, private companies, and citizens for a variety of analyses.<br>Secondary file (wind-operators.csv): Data on operators within the U.S. energy space. Data is from [EIA-923](https://www.eia.gov/electricity/data/eia923/) (2022: EIA-923 January 2022 zip file). |
| **6** | **Cosmetic Chemicals**     | The data is from the California Safe Cosmetics Program (CSCP) in the California Department of Public Health. The primary purpose of the CSCP is to collect information on hazardous and potentially hazardous ingredients in cosmetic products sold in California and to make this information available to the public.<br>Many different chemicals are used in making cosmetics. Consumer and worker advocacy groups are concerned because some cosmetic products contain chemicals known or suspected to cause cancer, birth defects, or damage to the reproductive system. Those who work with cosmetics — including barbers, hair stylists, and skin care, body care and nail salon workers — may be more vulnerable to the adverse health effects posed by these products. |

#### Additional Data
You are welcome to add any other data sources you find online to support your analysis, but this is **not required**.

---

### Technical Report Template

Future projects will require you to decide on the entire structure of your technical report. Here, we provide you with a simple EDA template (inside the .zip file) in a Jupyter notebook that will help to guide your data exploration and analysis. **If you choose to edit the core structure of this notebook, make sure you don't exclude any of the requested operations**.

---

### Style Guide and Suggested Resources

[Project Overview Guidelines](./project-overview-guidelines.md) have been included for you in this repository. Some 
recommendations are geared toward future projects (which will include modeling and span multiple notebooks), but generally these are great recommendations.

In addition, the [Problem Statement](#problem-statement)  section provides examples and advice for writing a problem statement and structuring your readme file. 

__Note:__ in order for your readme to automatically display in github, it must be named `README.md`. So, before submitting, make sure to delete this one and replace it with your own!

Here's a link on [how to give a good lightning talk](https://www.semrush.com/blog/16-ways-to-prepare-for-a-lightning-talk/), which provides some good recommendations for short presentations.

[Here's a great summary](https://towardsdatascience.com/storytelling-with-data-a-data-visualization-guide-for-business-professionals-97d50512b407) of the main points of the book _Storytelling with Data_, which I can't recommend enough. [Here's a blog post](http://www.storytellingwithdata.com/blog/2017/8/9/my-guiding-principles) by the author about his guiding principles for visualizations.

---

### Submission

**Materials must be submitted by the date and in the method outlined by your instructor.**

Your technical report will be hosted on your GitHub. Make sure it includes:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis (renamed to describe your project)
- Data files
- Presentation slides
- Any other necessary files (images, etc.)

**Please fork the project, download or clone to your local machine, and submit a link to your GitHub repo as per guidelines from your instructor.**

---

### Presentation Structure

**You must be ready to present your findings by the start of class on the date set by your instructor.**

- **Must be within time limit - not more than 5-7 minutes.**
- Use Google Slides or some other visual aid (Keynote, Powerpoint, etc).
- Consider the audience. Assume you are presenting to a non-technical audience.
- Start with the **data analytics problem**.
- Use visuals that are appropriately scaled and interpretable.
- Talk about your procedure/methodology (high level, **CODE IS ALWAYS INAPPROPRIATE FOR A NON-TECHNICAL AUDIENCE**).
- Talk about your primary findings.
- Make sure you provide **clear recommendations** that follow logically from your analyses and narrative and answer your data analytics problem.

Be sure to rehearse and time your presentation before class.

---

### Rubric
Your instructors will evaluate your project (for the most part) using the following criteria.  You should make sure that you consider and/or follow most if not all of the considerations/recommendations outlined below **while** working through your project.

**Scores will be out of 21 points based on the 7 items in the rubric.** <br>
*3 points per section*<br>

| Score | Interpretation |
| --- | --- |
| **0** | *Project fails to meet the minimum requirements for this item.* |
| **1** | *Project meets the minimum requirements for this item, but falls significantly short of portfolio-ready expectations.* |
| **2** | *Project exceeds the minimum requirements for this item, but falls short of portfolio-ready expectations.* |
| **3** | *Project meets or exceeds portfolio-ready expectations; demonstrates a thorough understanding of every outlined consideration.* |

**Project Organization**
- Are modules imported correctly (using appropriate aliases)?
- Are data imported/saved using relative paths?
- Does the README provide a good executive summary of the project?
- Is markdown formatting used appropriately to structure notebooks?
- Are there an appropriate amount of comments to support the code?
- Are files & directories organized correctly?
- Are there unnecessary files included?
- Do files and directories have well-structured, appropriate, consistent names?

**Clarity of Message**
- Is the problem statement clearly presented?
- Does a strong narrative run through the project?
- Does the student provide appropriate context to connect individual steps back to the overall project?
- Is it clear how the final recommendations were reached?
- Are the conclusions/recommendations clearly stated?

**Python Syntax and Control Flow**
- Is care taken to write human readable code?
- Is the code syntactically correct (no runtime errors)?
- Does the code generate desired results (logically correct)?
- Does the code follows general best practices and style guidelines?
- Are Pandas functions used appropriately?
- Does the student demonstrate mastery masking in Pandas?
- Does the student demonstrate mastery sorting in Pandas?

**Data Cleaning and EDA**
- Does the student fix data entry issues?
- Are data appropriately labeled?
- Are data appropriately typed?
- Are datasets combined correctly?
- Are appropriate summary statistics provided?
- Are steps taken during data cleaning and EDA framed appropriately?

**Visualizations**
- Are the requested visualizations provided?
- Do plots accurately demonstrate valid relationships?
- Are plots labeled properly?
- Plots interpreted appropriately?
- Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report?

**Research and Conceptual Understanding**
- Were useful insights gathered from outside sources?
- Are sources clearly identified?
- Does the student provide appropriate interpretation with regards to descriptive and inferential statistics?

**Presentation**
- Is the problem statement clearly presented?
- Does a strong narrative run through the presentation building toward a final conclusion?
- Are the conclusions/recommendations clearly stated?
- Is the level of technicality appropriate for the intended audience?
- Is the student substantially over or under time?
- Does the student appropriately pace their presentation?
- Does the student deliver their message with clarity and volume?
- Are appropriate visualizations generated for the intended audience?
- Are visualizations necessary and useful for supporting conclusions/explaining findings?

In order to pass the project, students must earn a minimum score of 1 for each category.
- Earning below a 1 in one or more of the above categories would result in a failing project.
- While a minimum of 1 in each category is the required threshold for graduation, students should aim to earn at least an average of 1.5 across each category. An average score below 1.5, while it may be passing, means students may want to solicit specific feedback in order to significantly improve the project before showcasing it as part of a portfolio or the job search.

### REMEMBER:

This is a learning environment and you are encouraged to try new things, even if they don't work out as well as you planned! While this rubric outlines what we look for in a _good_ project, it is up to you to go above and beyond to create a _great_ project. **Learn from your failures and you'll be prepared to succeed in the workforce**.


---

## Important note
Please ignore the `_layouts` folder and the `config.yml` file in the root of this repo.  They are needed to make sure the repo renders well; please don't change them or delete them and your repo will work fine :)

---
