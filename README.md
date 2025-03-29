# Integrated Project: Video Game Sales Analysis
## Inspiration
This project represents my first integrated data analysis, where I bring together everything I’ve learned so far, ranging from foundational Python syntax to data cleaning, visualization, and statistical analysis. One of the biggest breakthroughs in this project was learning how to use regular expressions (re) to accurately identify and fill in missing ratings, which made the dataset more complete and reliable. That specific skill allowed me to extract valuable data that might otherwise have been ignored. This project marks a milestone in my growth, as I applied tools like pandas, numpy, matplotlib, and scipy with more confidence while tackling real world data.

## Problem Statement
The dataset focuses on global video game sales in 2016. The objective is to help an online store craft a successful 2017 marketing strategy by evaluating platform and genre performance, understanding regional differences, and filling gaps in the dataset to uncover the full story. The project involves:

* Cleaning and preparing the dataset for analysis

* Identifying top-performing platforms and genres

* Filling missing ratings using regular expressions

* Evaluating sales trends by region

* Visualizing insights to guide marketing decisions

## Key Questions Explored
* Are there missing or duplicate entries in the data?

* What genres and platforms dominated the market?

* How do sales differ across North America, Europe, and Japan?

* What can be learned from accurately recovering missing rating data?

* Do outliers influence sales?

## What I Learned from This Project
This was the first time I brought together everything I’ve learned in Python into a complete project. Notable learning milestones included:

* Using re (regular expressions) to identify and impute missing rating values by searching for patterns in the dataset

* Cleaning real-world data by removing duplicates and handling missing values

* Grouping and transforming data to explore sales by genre and region

* Creating visualizations to compare performance across markets

* Applying statistical tools to back business decisions with data

The ability to work with missing values using pattern matching and regex gave me a better understanding of how flexible and powerful Python can be in solving data issues that go beyond simple methods.

## Project Execution
### Setting Up the Environment
To run this project locally, make sure you have the following packages installed:

bash
Copy
Edit
pip install pandas numpy statistics matplotlib scipy seaborn re counter defaultdict
### Data Collection
This project uses a CSV file containing sales data for video games released through 2016. It includes features like name, genre, platform, publisher, regional/global sales, and ESRB ratings.

### Analysis Overview
* Cleaned and inspected the dataset for missing or invalid values

* Used regex (re) to intelligently fill in missing ESRB ratings

* Analyzed game performance by region, genre, and platform

* Created visualizations (histograms, bar charts) to present findings

* Generated insights to help develop a focused 2017 marketing strategy

### How to Run the Project Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/YOUR-USERNAME/Integrated-Video-Game-Analysis.git
cd Integrated-Video-Game-Analysis
Set up a virtual environment and install dependencies:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
Launch the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Integrated_Project_1.ipynb
