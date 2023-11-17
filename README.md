# ada-2023-project-pinacolada 
## Project Title: Representation of Arabs in Cinema Before and After September 11

### Summary
This project aims to explore the portrayal of Arab characters in film, investigating possible changes in their roles before and after the events of 11 September 2001. Our intention is to analyse how these characters have been depicted and to categorise these representations as 'positive' or 'negative'. 
Being more specific, choosing between actor and character ethnicity, we want to extract the second, being it more directly linked to the fictional role. While at the moment it is done filtering the character names if they are of arab origin, we may include the ones not explicitly mentioned in the script, in order to understand the underlying dynamics of representation in film. 
In our study we group the wester countries (USA, Canada and Eurpean states) vs the others, to undestrand if before and after the twin tower attack we notice a change dynamics in the cinema industry, that is influenced and influences the culture. In this sense, we want aslo to mesure how much films that depict arabs in a negative way have a cultural impact and may bring to a "domino efffect".

### Research Questions
- Assessment of the presence and roles of Arab characters in films, focusing on those released in the US and other Western countries.
- Do arab play more roles in the war and crimes genres in western movies after 9/11?
- What are the common categories of 'positive' and 'negative' portrayal, and where do Arab characters typically fall within these categories?
- How were Arab characters represented in films before and after 9/11?
- Did 9/11 significantly alter the portrayal of Arab characters in films?
- Did movies where arabs are negative depicted have a cultural impact on the society, using the relevancy score?
  

### Proposed Additional Datasets and their Management
- Web scrapring of actors ethnicities using the wikidata API.
- Analysis of character names and ethnicities using a list of Arabic names from Wikipedia and other databases.
- *We will use publicly available IMDb datasets to populate our dataset with, for example, rating scores*
- Imdb reviews dataset for sentiment analysis: we are going to use this dataset to train a pretrained model for sentiment analysis of the plots to see how are the arabic characters represented in comparison to a selection of other ethinities. In addition, this dataset is also going to be used to asses the cultural impact on the society since the reviews are not made by official critics of the movie industry but by common people.

### Methods
- Statistical analysis to compare the frequency and nature of roles assigned to Arab characters before and after 9/11.
- Text filtering to evaluate the presence of arab characters in the character list and if the character is in the plot.
- Observational study to evaluate if arabs characters had more roles in crime and violence genres before and after the twin towers event.
- Natural language processing (NLP) techniques for entity recognition to identify Arabic names and locations in film summaries: specifically enhance our named entity recognition algorithm to be able to recognize not only arabic characters but also locations in the arabic world. This is going to be done either by using a distil bert model (light version of bert) and fine-tuning it on a manually labeled data (might not be feasible due to the lack of time)or by searching for an exhaustive database of arabic names and using it with a similarity function to get the arabic characters from the plot (since the spelling of arabic names/locations may differ especially when translated).
- Sentiment analysis of the movie plots and the imdb movie reviews.
- *Developping a weighting of datapoints with a "relevancy score" (ie a measure of a movie's relevancy) which will be comprised of ratings, box offcie, obtained prizes, etc...*

### Proposed Timetable and Objectives
#### Week 1 (17.11-24.11): In-depth Data Analysis
- Analyse in detail the data collected to identify specific trends in the representation of Arab characters.
- Carry out a comparative analysis to distinguish changes before and after 11 September 2001.
- Begin to write the relevant sections of the final report.

*Deadline Homework 2 01.12.2023*

#### Weeks 3 (02.12-09.12): Development of Entity Recognition Techniques
- Improve NLP techniques for more accurate identification of Arabic names and geographical references in scenarios.
- Integrate the results of this improvement into the overall analysis.
- Update the report with new findings and methodologies.

#### Week 4 (09.12-16.12): Critical Analysis and Review
- Carry out a critical analysis of the results obtained.
- Identify and discuss potential limitations and biases in the study.
- Revise the report based on feedback from team members and course assistants.

#### Week 5 (17.12-22.12) : Final Preparation and Submission
- Finalise the report by incorporating all comments and refining the presentation of the results.
- Prepare a succinct presentation of the project for final submission.
- Check that all README and notebook criteria are met before submission.

### Questions for Course Assistants (Optional)
- Do you have any suggestions for improving our entity recognition approach for Arabic names?
- Recommendations for effectively comparing the representation of Arab characters before and after September 11?
