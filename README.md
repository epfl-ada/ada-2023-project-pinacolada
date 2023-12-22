# 9/11 and the representation of Arabs in cinema

### Summary
This project aims to explore the portrayal of Arab characters in film, investigating possible changes in their roles before and after the events of 11 September 2001. Our intention is to analyse how these characters have been depicted and to categorise these representations as 'positive' or 'negative'. 
Being more specific, choosing between actor and character ethnicity, we want to extract the second, being it more directly linked to the fictional role. While at the moment it is done filtering the character names if they are of arab origin, we may include the ones not explicitly mentioned in the script, in order to understand the underlying dynamics of representation in film. 
In our study we group the western countries (USA, Canada and Eurpean states) vs the others, to understand if before and after the twin tower attack we notice a change of dynamics in the cinema industry, that influences and influenced by culture.

This [link](https://alexei-erm.github.io) will take you to our datastory.

### Research Questions
- Do arab play more roles in the war and crimes genres in western movies after 9/11?
- How were Arab characters represented in films before and after 9/11?
- Did 9/11 significantly alter the portrayal of Arab characters in films?
  

### Proposed Additional Datasets and their Management
- Analysis of character names and ethnicities using a list of Arabic names from Wikipedia and other databases.
- Imdb reviews dataset for sentiment analysis: we are going to use this dataset to train a pretrained model for sentiment analysis of the plots to see how are the arabic characters represented in comparison to a selection of other ethinities. In addition, this dataset is also going to be used to asses the cultural impact on the society since the reviews are not made by official critics of the movie industry but by common people.

### Methods
- Statistical analysis to compare the frequency and nature of roles assigned to Arab characters before and after 9/11.
- Text filtering to evaluate the presence of arab characters in the character list and if the character is in the plot.
- Observational study to evaluate if arabs characters had more roles in crime and violence genres before and after the twin towers event.
- Natural language processing (NLP) techniques for entity recognition to identify Arabic names and locations in film summaries: specifically enhance our named entity recognition algorithm to be able to recognize not only arabic characters but also locations in the arabic world. This is going to be done either by using a distil bert model (light version of bert) and fine-tuning it on a manually labeled data (might not be feasible due to the lack of time)or by searching for an exhaustive database of arabic names and using it with a similarity function to get the arabic characters from the plot (since the spelling of arabic names/locations may differ especially when translated).
- Sentiment analysis of the movie plots and the imdb movie reviews.

### Proposed Timetable and Objectives
#### Week 1: In-depth Data Analysis
- Analyse in detail the data collected to identify specific trends in the representation of Arab characters.
- Carry out a comparative analysis to distinguish changes before and after 11 September 2001.
- Begin to write the relevant sections of the final report.

#### Weeks 2-3: Development of Entity Recognition Techniques
- Improve NLP techniques for more accurate identification of Arabic names and geographical references in scenarios.
- Integrate the results of this improvement into the overall analysis.
- Update the report with new findings and methodologies.

#### Week 4: Critical Analysis and Review
- Carry out a critical analysis of the results obtained.
- Identify and discuss potential limitations and biases in the study.
- Revise the report based on feedback from team members and course assistants.

#### Week 5: Final Preparation and Submission
- Finalise the report by incorporating all comments and refining the presentation of the results.
- Prepare a succinct presentation of the project for final submission.
- Check that all README and notebook criteria are met before submission.
 
#### Individual Contributions
- Alexei : exploratory analysis, datastory, website
- Filippo :
- Matteo :
- Mohammad : Sentiment analysis, CSS, Double Check DS.
- Yahya : Data cleaning, Named entity recognition, Topic Modeling, Plot summaries analysis



