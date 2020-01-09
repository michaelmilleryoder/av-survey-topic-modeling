# av-survey-topic-modeling
Topic modeling results of an survey on autonomous vehicles collected by the non-profit bike and pedestrian advocacy organization [BikePGH](https://www.bikepgh.org/) in 2017 and 2019.

## Contents
Jupyter Notebooks are included for both Python and R environments.

Slides: `nlp_workshop_slides.pdf`. Slides 1-26 give brief introductions to NLP, topic modeling, and the context of the data. Slide 27 starts with instructions that accompany these.

Data: Survey data is in `bikepgh_av_survey.csv`. The survey questions for each year that correspond to each column can be found in `column_mappings.csv`. The process for normalizing this data can be found in `av_comment_data.ipynb`.

Notebooks: `av_survey_topic_modeling_python.ipynb` for Python, `av_survey_topic_modeling_r.ipynb`.


## Instructions
Step-by-step instructions are included in the notebooks. At a high level, you will choose a column with a text field, tokenize the text, extract unigram (bag-of-word) features, run LDA, and interpret topics. You can also correlate these learned topics with categorical and numerical (structured) data columns. Have fun!


## Packages
For the Python notebook, you'll want to install the following Python packages:
* pandas
* gensim
* matplotlib

For the R notebook, you'll need:
* tidytext
* dplyr
* topicmodels
