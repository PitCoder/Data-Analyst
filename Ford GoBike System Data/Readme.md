# Communicate-Data-Findings
Udacity's Data Analyst Nanodegree - Project 5

![Ford GoBike Picture](/Ford_GoBikes.png)

### Motivation
Data visualization is an important skill that is used in many parts of the data analysis process. 
> *Exploratory* data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. 

> *Explanatory* data visualization techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

### Project Details
1. Dataset: [Ford GoBike](https://s3.amazonaws.com/baywheels-data/index.html)
2. Explore the data: Exploration of the data both visually and programatically.
3. Document the story: People love stories, they are perfect to convey findings and communicate ideas.
4. Communicate the findings: A slide deck ready to communicate the work done here through an amazing pitch.

### Project Findings
In general this project have a lot benefits for both the city goverment, and the people who live in the San Francisco area:

- It provides not only an alternative transportation system, but also it integrates and complements with other transporation systems like (Caltrain, Ferry and Bart).

- It has an excellent system that allow people with low resources use this service. Eventhough there are not too many people that have this membership, it is wonderful that this option exists.

- Complements the tourism in San Francisco, since people can enjoy rides with sight of the most enigmatic places: The San Franscisco Bridge, Alcatraz Island, The Bay, and of course the famous Pier 39.

- It is technologically attractive, since most of the users prefer to rent their bicycles by using the app, which is of course is more practical than carrying electronic cards or cash. Nevertheless it doesn't discard these options.

However there are also some points in this system that can be better, because of the overwhelming gap in the gender, it must be take into consideration how to encourage women to use more this service.

Renting a bike from the Ford GoBike System is an excellent option than helps you to be more healthy while being environmentally friendly while you move around the city, it is useful for both entertainment and work. Also data suggest that these bikes were designed to not travel very long distances but they are fast enough so you can be on time.


### Files
	- src/ : Folder with the datasets in csv files.
	- Readme.md - This markdown file contains information about the project: title, motivation, details, findings and folder structure.
    - Communicate-Data-Findings.ipynb: This Jupyter Notebook contains the exploration process of this dataset, starting from gathering, asessing and cleaning up to univariate, bivariate and multivariate visualizations.
	- Communicate-Data-Findings.html: The file above but in html format.
	- Communicate-Data-Findings-Pitch-Deck.ipynb: This Jupyter Notebook contains the documentation of the story, polished visuals and narrative are shown here.
	- Communicate-Data-Findings-Pitch-Deck.html: Final slide deck, this document shows a pitch deck of the story.
    - output_toggle.tpl: This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project).