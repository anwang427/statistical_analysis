# LLM Augmentation Study
This project conducts exploratory data analysis and statistical tests on a dataset to investigate whether access to a large language model (LLM) augments users across various metrics, including accuracy, completeness, time spent, perceived difficulty, innovativeness, and more.

# Dataset
The dataset used in this study contains user responses and performance data from a controlled experiment where participants were randomly assigned to either have access to an LLM or not. The dataset includes the following variables:

id: Unique identifier for each participant

stage: The stage of the task (e.g., ideation, acquisition, magnification, formulation, release)

accuracy: Score measuring the accuracy of the response (on a 0-10 scale)

completeness: Score measuring the completeness of the response

innovation: Score measuring the innovativeness of the response

difficulty: Self-reported perceived difficulty of the task (on a 1-10 scale)

n_user_messages: Number of messages sent by the user

n_internet_resources: Number of internet resources accessed

time_to_complete_sec: Time taken to complete the task (in seconds)

cohort: Whether the participant is a student or an expert

assignment: Whether the participant had access to an LLM, internet only, or both

llm_experience: How much past experience they had

The original dataset and associated study can be found here: https://openai.com/research/building-an-early-warning-system-for-llm-aided-biological-threat-creation

# Analysis
The analysis pipeline includes the following steps:

Data Cleaning and Preprocessing: Handle missing values, remove outliers, and perform any necessary data transformations.

Exploratory Data Analysis (EDA): Visualize the data, investigate distributions, and identify potential patterns or relationships.

Statistical Testing: Conduct appropriate statistical tests (e.g., t-tests, Barnard's exact test, determining correlation coefficients, Mann-Whitney U test, and more) to evaluate the impact of LLM access on the various metrics of interest. It also includes interpretations of the statistical findings and draws conclusions about the effect of LLM augmentation on user performance and experience.

# Dependencies
The analysis is performed using Python.

Clone the repository: git clone https://github.com/anwang427/statistical_analysis.git
Install the required dependencies: pip install -r requirements.txt
Run StatisticalAnalysis.ipynb

This will execute the complete analysis pipeline and generate visualizations and statistical reports.